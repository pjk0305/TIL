##for 반복문

> for in list

1. for in 반복문  
	코드를 필요한만큼 반복해서 실행  
	
	ex) for pattern in patterns:  
		print (pattern)  
		
	1)리스트 patterns의 값을 하나씩 꺼내 pattern으로 전달  
	2)리스트의 길이만큼 print (pattern) 실행

2. fot in range 반복문

	range 함수  
	필요한 만큼의 숫자를 만들어내는 유용한 기능  
	ex) for i in range(5):  
		print(i)  
	
	리스트가 있는 경우 순서와 리스트의 값을 전달하는 기능  
	ex) names = ['철수','영희','영수']  
		for i, name in enumerate(names):  
			print('{}번: {}' .format(i + 1, name))

> 모듈

1. 모듈 사용하기  

	미리 만들어진 코드를 가져와 쓰는 방법  
	import 모듈이름  
	사용 방법: 모듈이름,모듈안의 구성요소  
	
	ex) math.pi  
		random.choice()
		
	모듈의 예  
	
		import math  
		수학과 관련된 기능  
		import random  
		무작위와 관련된 기능  
		import urllib.request  
		인터넷의 내용을 가져오는 기능  
		
2. 모듈 만들기

	1) 사용할 함수, 메소드 코드를 작성한 모듈파일을 생성  
	2) 모듈이 쓰일 파일에 import를 사용하여 모듈을 호출  
	3) 사용 방법은 기존의 모듈과 동일  
	4) 주의할 점은 사용자가 만든 모듈과 모듈을 쓸 파일이 같은 폴더에 있어야 한다.  
	

	
	