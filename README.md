Busanbus for Android 2.2.4
========
[![Analytics](https://ga-beacon.appspot.com/UA-51734472-2/BusanBus/readme)](https://github.com/kmshack/busanbus-android)


@Deprecated 

부산버스 안드로이드 앱 ( http://play.google.com/store/apps/details?id=com.kmshack.BusanBus ) 
오픈소스

![busanbus screens](screens.png)

필요한 라이브러리
-----

- Google Play Services
- ActionBarSherlock  
- Sherlock Navigation Drawer
- DragSort ListView


데이터 정보
-----

- 정류소 데이터 http://121.174.75.12/02/021.html_ok.asp?m=2&m1=2&bstopnm=

- 실시간 도착 데이터 http://121.174.75.12/01/011.html.asp?m=1&m1=1&bstop_id=172690101&linenm=186&line_id=5200186000

- 기타 추가적인 정보 http://bus.busan.go.kr


주의점 및 참고사항
-----

 - 구글 지도 V2는 Android Manifest의 meta-data에 Key를 발급 받은 후 등록 하셔야 합니다.

 - 버스와 노선 관련 데이터파일과 수집 방법에 대한 방법은 database를 참고 하시면 됩니다.

 - database/BusData.kms 데이터파일은 sqlite파일이며 2012년 12월을 최신으로 작성된 데이터입니다. 데이터수집 및 작성방법은 database/busanbus_data.xlsx을 확인바랍니다.

 - 데이터파일은 앱내에 저장되어 있으며 안드로이드 특성상 데이터를 분할 하여 앱 실행시 다시 합치는 방식으로 앱 분할 방법은 database/datacut 프로젝트를 참고하시기 바랍니다.


추가 문의사항은 이슈게시판 또는 개발자 블로그( http://www.kmshack.kr )에 글을 남겨 주기시 바랍니다.

