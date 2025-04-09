# unity
File save as에다가 Scene있는데 거기에 저장을 해줘야함
object를 클릭하면 밑에 Add component가 있는데 맨밑에 있는 new뭐시기를 해줘야함
일시정지나 실행중에 저장을 하면 저장이 안됨
확인하기!!

C# 코드
Start 한번만 실행 
(초기 설정 같은거 넣는거임)
Application.targetFrameRate = 60; 프레임 수

Update 매 프레임 마다 실행
transform.Rotate(0, 0, 10);<-(X축,Y축,Z축)
2D이니 Z축으로 돌리기
