# Parasite(가제)
  ### [2021.03 ~ 2021.07]
  - 2021.03 ~ 2021.05 : 스토리 구상 및 게임 컨셉 설정
  - 2021.04 ~ 2021.06 : 캐릭터, 아이템 컨셉 설정
  - 2021.05 : 컨셉아트 제작
  - 2021.07 ~ : 프로토타입 개발
 
 # 프로토타입 개발 화면
  <p align="center"><img src = "https://user-images.githubusercontent.com/57585303/150061198-a6dbeab5-f8c4-4c95-8c85-4859fd10adf1.gif"></p>

  - **카메라**
  
    카메라가 플레이어를 추적하도록
    
  - **점프 시스템**

    벨트스크롤 장르의 특성상 2D이지만 가상의 z축(높이)이 존재하므로 캐릭터의 발 아래에 Shadow 오브젝트를 위치시키고 콜라이더를 설정한다. 물리 효과들이 정상적으로 작동하도록 Rigidbody를 Dynamic 타입으로 두어야 하기 때문에 중력 대신에 Translate 함수를 이용한 점프 시스템을 구현해 아바타가 가라앉는 것을 방지하였다.
    
    
