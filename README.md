# 2019-1-OSSP2-DataStructure-9
 
 ## CANE (Co-Assistant system for Neighbor’s Eye)
 
 ### tensorflow를 활용한 시각장애인 통행 보조 어플리케이션
 
 ### 개발환경
 
- 개발 언어 : Java

- 개발 프로그램 : Android studio

- 사용 API :  Tensorflow Object Detection API 

### 팀원
  
- 컴퓨터공학과 2015112082 김현도   (팀장) 개발 및 아이디어 종합, 보고서 작성  
- 컴퓨터공학과 2015112149 연정민   개발 총괄 및 아이디어 종합, 보고서 작성
- 컴퓨터공학과 2015112150 최연호   PPT작성, 디자인 및 개발, 보고서 작성
- 컴퓨터공학과 2015112104 이정우   발표 및 개발, 보고서 작성

### 프로젝트 설명

- 내용 : 시각장애인들의 현실적인 문제를 해결하고자 실제 보행상황에서 위협이 될만한 물체들에 대한 경고음 발생을 통해 보행에 편리함을 더해주기 위한 안드로이드 어플리케이션이다. COCO data set에 대해 교육된 MobileNet SSD 모델을 사용하여 Android 기기의 후면 카메라를 통해 물체들을 인식하고 상대적인 거리안에 위험물체가 있다고 판단되는 경우 경고음을 발생시켜준다. 또한 어플리케이션 설치후에 사용자가 긴급시 연락할 번호를 입력하고 사용도중 화면을 더블 탭 하는 경우 전화가 바로 걸리게 된다. 

- 사용대상 : 사용 대상은 평소 보호자 또는 안내견의 도움 없이 케인을 사용하여 보행을 해야하는 시각장애인이다. 사용자는 케인(지팡이)를 수반한 상태에서 어플리케이션을 사용한다.

### 실행방법 
1. 프로젝트 설치가 아닌 apk파일을 통해 바로 어플로 실행시킬 경우

<pre><code> https://github.com/CSID-DGU/2019-1-OSSP2-DataStructure-9/blob/master/app-debug.apk </code></pre>
- 위의 링크에서 cane.apk 를 Android 기기에 설치하고 실행시키면 된다.

2. 프로젝트 설치후 실행 하는 경우 
<pre><code> https://github.com/CSID-DGU/2019-1-OSSP2-DataStructure-9/blob/master/CANE%20app.zip </code></pre> 
- 위의 링크에서 CANE app.zip파일을 다운 받고 압축을 풀어주십시오.
- Android Studio가 설치되있는 경우 Android Studio를 실행시켜서 Open an existing Android Studio project를 선택한뒤 압축을 푼 파일의 경로를 입력한 뒤 OK버튼을 눌러 파일을 실행시켜줍니다.
- Android Studio에 파일이 옮겨 졌으면 Android기기를 컴퓨터와 연결하고 권한을 허용해준 뒤에 Android Studio 상단에 Play 버튼을 눌러줍니다.
- Select Deployment Target이라는 창이 뜨면 연결된 핸드폰을 select하고 OK버튼을 눌러주면 빌드가 성공되고 어플이 휴대폰에 깔리게 됩니다.
- 휴대폰에 어플이 깔리면 CANE 어플을 실행시켜 초기의 번호를 입력해준 뒤 사용하면 됩니다.

[선행 조건]
- 만약 Android Studio를 아직 설치하지 않은 경우 [Androidstudio](https://developer.android.com/studio/index.html) 의 지침에 따라 설치하십시오. (Android Studio 3.2 이상)

[실행 시 주의사항]
- 프로젝트를 build 하는 경우 기기의 후면 카메라가 있어야지만 어플이 정상적으로 작동하므로 Android 기기와 연결이 되어진 상태로 빌드되어야 합니다. 

### 실행화면
<어플 실행시 default 전화번호> 
<center><img src="https://github.com/CSID-DGU/2019-1-OSSP2-DataStructure-9/blob/master/defaultnumber.jpg?raw=true" width="200" height="450">

<어플 사용자가 전화번호 설정>
<center><img src="https://github.com/CSID-DGU/2019-1-OSSP2-DataStructure-9/blob/master/changenumber.jpg?raw=true" width="200" height="450">

<더블 탭하여 전화>
<center><img src="https://github.com/CSID-DGU/2019-1-OSSP2-DataStructure-9/blob/master/calling.jpg?raw=true" width="200" height="450">

<어플리케이션을 통한 오토바이 인식>
<center><img src="https://github.com/CSID-DGU/2019-1-OSSP2-DataStructure-9/blob/master/moterbicycle.jpg?raw=true" width="200" height="400">

<어플리케이션을 통한 트럭 인식>
<center><img src="https://github.com/CSID-DGU/2019-1-OSSP2-DataStructure-9/blob/master/truck.jpg?raw=true" width="200" height="400">

<어플리케이션을 통한 자동차 인식>
<center><img src="https://github.com/CSID-DGU/2019-1-OSSP2-DataStructure-9/blob/master/car.jpg?raw=true" width="200" height="400">

### 문의사항

- 김현도 (kk090303@naver.com)
- 연정민 (jryoun1@naver.com)
- 최연호 (dusgh4321@naver.com)
- 이정우 (dwd4798@gmail.com)

### 사용오픈소스

-Tensorflow object detection API

-Link: [TensorflowLite object detection demo](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/android)



