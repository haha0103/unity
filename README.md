#unity
File save as에다가 Scene있는데 거기에 저장을 해줘야함
object를 클릭하면 밑에 Add component가 있는데 맨밑에 있는 new뭐시기를 해줘야함
일시정지나 실행중에 저장을 하면 저장이 안됨
확인하기!!
저장을 할때는 pc에 프로젝트 파일을 압축해서 저장하느 다음 열때는 압축풀고

C# 코드

//첫날
【【Start 한번만 실행 
(초기 설정 같은거 넣는거임)
Application.targetFrameRate = 60; 프레임 수

Update 매 프레임 마다 실행
transform.Rotate(0, 0, 10);<-(X축,Y축,Z축)
2D이니 Z축으로 돌리기

 if(Input.GetMouseButtonDown(0))//마우스 누룰 때
 if 0(좌클릭 1은 우클릭임)이 되면 간다
 float는 소수점 포함 상수형 그래서 값 뒤에 F,f를 붙여줘야함】】

 //둘쨋날
 【【C#이 꼴받게 글자가 안뜰 때
→Edit>밑에 있는 pre뭐시기> EX뭐시기 Tool이 있는데 거기서 마이크로소프트 비쥬얼 스튜디오로 바꿔 주면됨^^b

 this.car=GameObject.Find("car");//car라는 Object를 찾아서 넣는다
 this.flag=GameObject.Find("flag");;//flag라는 Object를 찾아서 넣는다

 float lengt = this.flag.transform.position.x - this.car.transform.position.x;
  //flag의 x값-car의 x값
//using TMPro;이거 추가해야 ↓오류 안뜸
 this.distance.GetComponent<TextMeshProUGUI>().text = "Distance:" + lengt.ToString("F2") + "M";
                                         //Distance:lengt(flag의 x값-car의 x값).소수점두째자리까지M
Vector2 starpos;
//2차원 변수이름 (x,y값을 넣을 수 있음 {3차원은 Vector3})
(Input.GetMouseButtonUp(0))//마우스를 때는 순간
GetComponent<AudioSource>().Play();】】
