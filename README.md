# Python - django framework project 

[목적]
- django framework로 helloworld 출력 
- 대용량 데이터 시각화 진행 ( 통계청 데이터 끌어와서 진행할 예정 ) 

[장점] 
- 유저, 인증, 뷰, 템플릿, URL, static files 등 이미 framework 안에 기능들이 다 있다. 
- CRUD 할 경우 최적화 되어있다. 블로그 인스타그램 유튜브 등 

[python django 사용에 적절하지 않은 기술]
- 우버등과 같이 CRUD 이외 리얼타임이 필요할 경우 적절하지 않다. ( node js를 추천 ) 
- 넷플리스의 경우도 CRUD 이외에 스트리밍이라던가 리얼타임을 자주 하기 때문에 django framework 사용에 적절하지 않다. 


[프레임워크 설치 및 진행 관련 도움말] 
- 아래 프레임 워크 참고함
- 프레임워크 관련 주소 : https://godrjsmgl.tistory.com/32 

- 아키텍처 및 app 구성도 정보 
- http://pythonstudy.xyz/python/article/305-Django-App

- 내 블로그 정보 : blog.naver.com/superukie ( python 관련 기초적인 내용 및 설치 관련 정보 ) 


[에러 처리 관련 정보] 
1. 로컬 저장소와 원격저장소 연결이 지속적으로 안됐었음 
> refusing to merge unrelated histories
원인 : 로컬저장소와 원격저장소간 차이가 많이 날 경우 발생함 
해결방법 : 
1. master branch에서 작업하지 말고 create new branch로 새 작업 
2. 원격 저장소와 연결 : git branch --set-upstream-to=origin/master junyahn/python/1
3. 강제로 원격저장소 pull 처리 : git pull --allow-unrelated-histories


