<h1>:snake:SNAKE GAME:snake:</h1>
<hr>
<h3>스네이크 게임이란:question:</h3>
:one:화면에 뱀이 표시되고 플레이어는 방향키로 뱀을 조작할 수 있다.<br>
:two:맵의 랜덤한 위치에 음식(보통 사과)가 등장하고 획득하면 점수와 뱀의 길이가 1씩 증가한다.<br>
:three:뱀은 자신의 몸과 충돌하면 게임오버다.
<hr>
<h3>제작한 게임에 대한 설명</h3>

* <h6>게임 메인화면</h6>
<img src = https://user-images.githubusercontent.com/113351553/205493734-eec2c947-ee51-44c1-9cb1-303198e5dbfe.png alt = "메인화면">
   게임의 제목과 뱀 이미지 파일, 그리고 게임의 조작법에 대한 설명을 출력한다.<br>
   별다른 키보드 입력이 있을 때 까지 계속해서 화면을 출력한다.<br>
   키보드 입력이 있으면 게임을 시작한다.<br><br>
   
* <h6>게임 플레이화면</h6>
<img src = https://user-images.githubusercontent.com/113351553/205492356-96ada2a9-7725-43ff-a2e0-988642f76388.png alt = "게임화면">
  게임이 시작되면 bgm이 시작된다.<br>
  bgm의 재생 여부는 오른쪽 아래 아이콘으로 표시된다.<br>
  m 버튼을 누르면 음악이 꺼졌다는 것을 표시하는 아이콘으로 변경된다.<br><br>

* <h6>게임의 소리를 껐을 때 게임 플레이화면</h6>
<img src = https://user-images.githubusercontent.com/113351553/205493529-4ae39486-8e88-4c58-a413-cb0bc74f84ee.png alt = "소리꺼짐">
  <br>
  뱀의 위치와 뱀의 방향, 음식의 위치는 전부 랜덤으로 결정된다.<br>
  뱀이 음식을 획득하면 점수가 1 증가하고 뱀의 길이도 1 증가하며 속도도 0.25 증가한다.<br>
  음식은 획득과 동시에 사라지며 다시 맵의 랜덤한 위치에 음식을 생성한다.<br>
  
* <h6>음식을 획득한 후 게임 플레이화면</h6>
<img src = https://user-images.githubusercontent.com/113351553/205494198-11c468ee-335b-4ecb-a533-6200a0c52ab7.png alt = "음식 획득한 후">

* <h6>뱀이 맵의 끝을 통과했을 때</h6>
