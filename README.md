# Andong_Nation_University
Winui3 카페를 참고하여 펜데이터 저장과 읽어오기 부분을 기반으로 파일에서 서브메뉴(New File과 Save, Load, Exit)를 추가하였습니다. 글씨를 쓰고 save를 누르면 저장이 되고 New File을 클릭하면
파일이 새 파일이 됩니다. 다시 LOAD를 클릭하면 저장된 글씨가 나타나게 되고 Exit를 클릭하면 화면이 사라집니다.
그리고 write버튼과 저장된 텍스트나 그림을 불러올 수 있는 Read, 지울 수 있는 Clear 버튼을 만들었습니다. 또한 슬라이더를 통해서 펜의 굵기를 정할 수 있고
컬러 픽커를 이용해 원하는 색상을 지정 할 수 있습니다. 그리고 추가 기능으로 버튼을 이용해 클릭했을 때 컬러픽커를 보이게하거나 숨기게 할 수 있습니다.

# Andong_Nation_University Window 제목설정

## xaml.cpp


![image](https://user-images.githubusercontent.com/105805974/207750530-b2d94311-d2ff-4ac7-8fe1-5859b1ffb9a7.png)

Window화면 창 크기를 각각 210, 210, 1051, 700으로 크기를 지정하였고 윈도우 화면 창 제목을 Andong_Nation_University로 설정하였습니다.


# 실행결과화면
![image](https://user-images.githubusercontent.com/105805974/207751038-6adb6963-ced7-4f92-a508-118f52941a93.png)



# 컬러픽커 Disable, Enable xaml.cpp
![image](https://user-images.githubusercontent.com/105805974/207751568-1bdc44a3-8f9c-4631-86ac-5aea8d24add6.png)

if와 else문을 이용해 클릭했을때 각각 컬러픽커를 숨기게하거나 보이게 할 수 있습니다.

# 컬러픽커 숨기기 결과화면
## 컬러픽커 기능이 보일 때
![image](https://user-images.githubusercontent.com/105805974/207752226-8a79dac5-6aeb-4f99-855b-85037e4a421f.png)

## 컬러픽커 기능이 보이지 않을때 
![image](https://user-images.githubusercontent.com/105805974/207752383-2f0e1bfe-f304-47a3-81ee-4c6768799d32.png)

# 최종결과화면

## 굵기 조절 및 컬러픽커 색상조절
![image](https://user-images.githubusercontent.com/105805974/207752661-bba10fca-7bb1-458a-8b20-c8c194729180.png)


## NewFile클릭 화면
![image](https://user-images.githubusercontent.com/105805974/207752861-a3264665-14ab-455a-bb5e-d0e3e0560324.png)

## save 클릭 화면
![image](https://user-images.githubusercontent.com/105805974/207753148-82c55a6b-a0c2-4377-8adc-079fb31e6d5c.png)

## load로 불러오기
![image](https://user-images.githubusercontent.com/105805974/207753339-57df4ab8-eb31-469e-be98-eb46de06559c.png)

## write클릭
![image](https://user-images.githubusercontent.com/105805974/207753509-7e264e1d-7de6-4ca9-a263-6771e97af07a.png)

## Clear 클릭
![image](https://user-images.githubusercontent.com/105805974/207753607-1cfa20df-c7f5-4911-9b17-b21199a8d891.png)

## read로 불러오기
![image](https://user-images.githubusercontent.com/105805974/207753898-96693ce0-0b16-4567-b3c5-0631edc84c70.png)


참고문헌: https://cafe.naver.com/whatisc, WinUI3gallery
유튜브 링크: https://www.youtube.com/watch?v=Yu9B4a52jTk







