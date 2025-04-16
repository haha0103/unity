#unity
File save as에다가 Scene있는데 거기에 저장을 해줘야함
object를 클릭하면 밑에 Add component가 있는데 맨밑에 있는 new뭐시기를 해줘야함
일시정지나 실행중에 저장을 하면 저장이 안됨
확인하기!!
저장을 할때는 pc에 프로젝트 파일을 압축해서 저장하느 다음 열때는 압축풀고

C# 코드
C#이 꼴받게 글자가 안뜰 때
→Edit>밑에 있는 pre뭐시기
Start 한번만 실행 
(초기 설정 같은거 넣는거임)
Application.targetFrameRate = 60; 프레임 수

Update 매 프레임 마다 실행
transform.Rotate(0, 0, 10);<-(X축,Y축,Z축)
2D이니 Z축으로 돌리기

 if(Input.GetMouseButtonDown(0))
 if 0(좌클릭 1은 우클릭임)이 되면 간다
 float는 소수점 포함 상수형 그래서 값 뒤에 F,f를 붙여줘야함

 this.car=GameObject.Find("car");
 this.flag=GameObject.Find("flag");//car라는 Object를 찾아서 넣는다
