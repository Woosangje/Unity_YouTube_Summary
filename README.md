# Unity_YouTube_Summary

03/13 Part 43부터 Combat포폴은 별도로 작업 
03/18 Part 50 Board.cs와 매칭 코드들이 뒤집어지는 시점 문제가 해결안될시 Part49스크립트로 돌아가면됨<br/>
03/21 Part 53,54  53의 슬라임강좌는 미완성된 강좌, 댓글 참조해야하고 댓글참조해도 슬라임 늘어날시 엉망임<br/>
03/24 만약 모바일에서 랙걸리면 애니매이션 루프확인해볼것 퍼즐 가끔씩 파괴가 안되서 오류 해결 중,,,<br/>
03/26 테스트시 속도 빨라지는 법 <br/>
Edit -> Project Settings -> Editor -> Enter Play Mode Options의 토글 On으로 하면됨<br/>

TextMeshPro-Text사용시 레이어가 안보이면 Extra Settings에 레이어 설정 옵션 확인할 것 </br>
오브젝트이름?. 또는 ?[]은 오브젝트나 null이 아닐 경우만 <br/>
03/28포폴 로스터 UI 1페이지완성 ScrollRect, ContentSizeFitter <br/>

03/29 히어로 UI배치하는데 10시간 소비,<br/>

03/30 RTS 카메라 https://www.youtube.com/watch?v=cfjLQrMGEb4 모바일은 볼필요없음<br/><br/>

04/01 화면 이동시 <br/>
Input.GetMouseButtonDown(0),Input.GetMouseButton(0) 만 사용하면 UI 영역에서 마우스클릭해도 클릭된다. UI에서 적용안되게 할려면<br/>
using UnityEngine.EventSystems;<br/>
if (Input.GetMouseButtonDown(0) && !EventSystem.current.IsPointerOverGameObject()),<br/>
if (Input.GetMouseButton(0) && !EventSystem.current.IsPointerOverGameObject())  선언해주자<br/>
<br/>
#region 이름<br/>
#endregion 이름<br/>
일종의 주석 같은건데, 숨김 기능이 있는 주석 기능<br/>

C#파일 입출력 <br/>
https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=joymrk&logNo=140034196937<br/>

● TLS Allocator ALLOC_TEMP_THREAD, underlying allocator ALLOC_TEMP_THREAD has unfreed allocations, size 102 오류<br/>
오류뜨면 일단 유니티 한번 닫았다 열어보자<br/>

keyTool 경로 
https://foxtrotin.tistory.com/521

23/01/23 모듈화 공부
