##title 조건문

>if문

1. if에는 조건식이 참이라면 아래에 적힌 print 문을 하게되고 아니라면 다른코드로 넘어간다.  
	ex) apple=30 으로 지정하였는데 if apple < 50 이렇게 된다면 조건문을 실행하는것이다.

>조건식

1. 숫자비교
	클경우 0<10 10>11  
	크거나 같다 3<=10 15>=10  
	같다 5 == 5  
	같지 않다 5 != 10  
	부등호의 순서가 바뀌면 오류가난다.  
2. boolean 연산
	and 연산  
		두 조건이 모두 참인지를 체크  
	or 연산  
		두 조건 중 하나라도 참이다  
	not 연산  
		true/false를 뒤집기 위해 사용

>블럭

1. 함께 실행되는 하나의 코드 덩어리
2. 들여쓰기로 블럭을 구분한다.
3. 들여쓰리가 어긋나면 오류가 발생한다.
4. 블럭 안에 다른 블럭이 들어갈 수 있다.
5. 내부의 블럭은 외부의 블럭에 종속적
6. 파이썬 코드 전체를 하나의 블럭으로 볼 수 있다.

>if else

1. else  
	if mine == yesrs:  
		result = DRAW  
	else:  
		result = '이기거나 지거나'  

	이런식으로 else는 반드시 if뒤에 나와야 하고  
	if의 조건이 맞지 않은 경우 항상 실행
2. elif  
	if mine == SCISSOR:  
		result = '가위'  
	elif mine == ROCK:  
		result = '바위'  
	else:  
		result = '나머지'  
	이런식으로 else와 if의 결합으로 조건이 맞지 않는 경우 다른 경우를 검사  
	기느의 차이가 아닌 보이는 것의 차이 이다.
	
>함수

1. 함수는 코드 덩어리에 이름을 붙인 것이다.
2. 새 함수를 정의할 수 있다.
3. print는 미리 만들어진 함수이다.
4. 함수를 한번 만들고 나면, 그 안은 잊어버려도 좋다.

	def function(): ## 함수의 정의  
		print ('안녕, 함수!')  
	print('첫줄 실행')  
	function()  
	print('끝줄 실행')  

>매개변수

1. 매개변수 : 함수를 정의할 때 사용하는 이름
2. 실행 인자 : 함수를 실행할 때 넘기는 변수,값
3. 매개변수와 실행인자 : 
	매개변수와 실행 인자의 개수는 동일해야 한다.
	여러 개일 경우 쉼표로 구분
	
	def print_round(number):  
		rounded = round(number)  
		print(rounded)  
	
	print_round(4.6)  
	print_rount(2.2)  
	
> 함수의 값

1. 함수  

	return을 이용해 값을 돌려줄 수 있다.
	
	def add_10(value):
		result = value + 10
		return result
	
	n = add_10(5)
	print(n)
	
2. 여러 값 반환  

	return 뒤에 여러값을 쉼표로 구분해서 값을 보내고, 받을 때도 쉼표로 구분하여 받는다.