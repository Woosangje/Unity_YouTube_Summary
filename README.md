# Unity_YouTube_Summary
01/04 하스스톤강좌 챕터1, 복습하니 이해도가고 주석달기도 편해짐<br/>
~01/21 3match퍼즐 공부하고있는데 강좌의 int useDotUse가 직관적이지않아 마음에 안들지만  막상 내가 이름을 수정하는것도 참 어려운거같다.<br/>
02/01 4match 관련 코드<br/>
02/17 Part 25 카메라 board오브젝트의 면적으로 카메라 스케일 조절,<br/>
다른 게임에서도 응용할수있을듯<br/>
02/20 Part 28 스테이지 컨텐츠<br/>
02/23 Part 30 힌트 이펙트<br/>
02/25 Part 32,33 score UI, background Tile<br/>
03/08 Part 42 UI
03/13 Part 43부터 Combat포폴은 별도로 작업 
03/14 Part 47 ui설정 
03/18 Part 50 Board.cs와 매칭 코드들이 뒤집어지는 시점 문제가 해결안될시 Part49스크립트로 돌아가면됨<br/>
03/20 Part 5252.1 concrete 관련 강좌<br/>
03/21 Part 53,54  53의 슬라임강좌는 미완성된 강좌, 댓글 참조해야하고 댓글참조해도 슬라임 늘어날시 엉망임<br/>
03/24 만약 모바일에서 랙걸리면 애니매이션 루프확인해볼것 퍼즐 가끔씩 파괴가 안되서 오류 해결 중,,,<br/>
03/25 오류해결 </br>
03/26 테스트시 속도 빨라지는 법 <br/>
Edit -> Project Settings -> Editor -> Enter Play Mode Options의 토글 On으로 하면됨<br/>
TextMeshPro-Text사용시 레이어가 안보이면 Extra Settings에 레이어 설정 옵션 확인할 것 </br>
오브젝트이름?. 또는 ?[]은 오브젝트나 null이 아닐 경우만 <br/>
03/28포폴 로스터 UI 1페이지완성 ScrollRect, ContentSizeFitter <br/>
03/29 히어로 UI배치하는데 10시간 소비,<br/>

03/30 RTS 카메라 https://www.youtube.com/watch?v=cfjLQrMGEb4 모바일은 볼필요없음
04/01 화면 이동시 
Input.GetMouseButtonDown(0),Input.GetMouseButton(0) 만 사용하면 UI 영역에서 마우스클릭해도 클릭된다. UI에서 적용안되게 할려면<br/>
using UnityEngine.EventSystems;
if (Input.GetMouseButtonDown(0) && !EventSystem.current.IsPointerOverGameObject()),
if (Input.GetMouseButton(0) && !EventSystem.current.IsPointerOverGameObject())  선언해주자<br/>
