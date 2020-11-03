# Ⅰ. **개요**
*   개발 기간 : 2019.04.08 ~ 2020.06.03
*   개발 목적 : 사용자를 차별화 하여 동일한 공간 내에서 특정 사용자에 맞는 서비스를 제공
*   대한전기학회 워크샵 150-151
  
# Ⅱ. **동작 구성도**
<img src="https://user-images.githubusercontent.com/73852272/98046531-b7de4d80-1e6d-11eb-9ecb-7832ccef9f18.jpg" width="400" hieght="400">

# Ⅲ. **개발환경**
*    Languege &nbsp;&nbsp;: Python
*    FrameWork :&nbsp; Caffe
*    HardWare &nbsp;&nbsp;: &nbsp;RaspberryPI

# Ⅳ. **주요기능**
*    Face Recognition을 통해 등록 되어진 사람을 구분한다.
*    인증 되어진 사용자의 현재 위치를 파악한다.
*    해당 장소에서 사용자에게 맞는 서비스를 제공한다.

# Ⅴ. 사용자 인증
<img src="https://user-images.githubusercontent.com/73852272/98048638-764fa180-1e71-11eb-99c3-3126844c0192.png" width="200" hieght="200">
<img src="https://user-images.githubusercontent.com/73852272/98048641-7780ce80-1e71-11eb-9ea4-fe4203b6a684.jpg" width="200" hieght="200">
<img src="https://user-images.githubusercontent.com/73852272/98048642-7780ce80-1e71-11eb-9729-cc486df5de08.png" width="200" hieght="200">

*    FaceDetection을 이용하여 데이터베이스에 학습되어진 얼굴의 경우
     Label을 표기


# Ⅵ. 장소 특정

<img src="https://user-images.githubusercontent.com/73852272/98048952-19a0b680-1e72-11eb-9064-2c3bfa51c225.png" width="200" hieght="200">

<img src="https://user-images.githubusercontent.com/73852272/98048951-186f8980-1e72-11eb-81a9-02fbe5868fc9.png" width="200" hieght="200">

*   장소 특정은 크게 주방, 화장실, 거실로 구분하여 해당 장소에서 대표적인 가구를
    <br>여섯 가지씩 학습시켜 같은 부류의 가구가 세 가지 이상 동시에 검출 될 시
    <br>해당 장소를 앞서 정의한 주방, 화장실, 거실 중의 한 곳으로 특정한다. 

*   '사람' 객체와 세 가지의 동일 부류 가구가 동시에 검출 될 시<br>
    현재 사람이 해당 장소에 있음으로 간주하여 지정된 서비스를 제공한다.
 
 # Ⅶ. 구현 영상
 *    Link : 
