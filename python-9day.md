## Comprehension

>List


1. List Comprehension  
	파이썬의 유용한 도구  
	예1 [ i*i for i in range(1,11) ] # [ 계산식 for문 ]  
	예2 [ i*i for i in range(1,11) if i % 2 == 0 ] # [ 계산식 for문 조건문 ]  
	예3 [ ( x, y ) for x in range(15) for y in range(15) ] # [ 계산식 for문 for문 ]  
	
2. Dictionary
	Dictionary Comprehension  
	파이썬의 유용한 도구  
	
	예시
		{ "{}번".format(number):name for number, name in enumerate(students) } # [ 형식 for문 ]  
		{student:score for student, score in zip(students, scores)}  
		


> 날짜와 시간


1. datetime  

	datetime 모듈  
	날짜와 시간을 사용하게 해주는 라이브러리  
	
2. timedelta  

	timedelta 클래스  
	시간의 연산을 가능하게 해주는 클래스  
	

	

	
