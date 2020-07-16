##클래스와 객체지향 프로그래밍

> 자료형 다루기

1. 자료형  

	type( a ) # type( 변수명 ) : 자료형  
	isinstance( 42, int ) # isinstance( 값, 자료형 ) : 자료형 검사  
	
2. 인스턴스 이해  

	클래스  
	함수나 변수들을 모아 놓은 집합체  
	
	인스턴스  
	클래스에 의해 생성된 객체  
	인스턴스 각자 자신의 값을 가지고 있다.  
	
3. 클래스 만들기

	클래스 선언  
	ex) class Human():  
		'''사람'''  
	
	인스턴스 생성  
	ex) person1 = Human( )  
		person2 = Human( )  
	
	클래스와 인스턴스를 이용하면 데이터와 코드를 사람이 이해하기 쉽게 포장할 수 있다.
	
4.  모델링

	모델링  
	클래스로 현실의 개념을 표현하는 것  
	
5. 메소드 이해하기

	메소드(Method)  
	
	메소드는 함수와 비슷하다.  
	클래스에 묶여서 클래스의 인스턴스와 관계되는 일을 하는 함수  
	
	클래스 내부에 함수를 포합시킨 예  
	.  
	.  
	.  
		class Human( ):  
		'''인간'''  
		def create( name, weight ): # 다음 강의에서 자세히 설명  
			person = Human()  
			person.name = name  
			person.weight = weight  
			return person  

		def eat( self ):  
			self.weight += 0.1  
			print("{}가 먹어서 {}kg이 되었습니다".format(self.name, self.weight))  

		def walk( self ):  
			self.weight -= 0.1  
			print("{}가 걸어서 {}kg이 되었습니다".format(self.name, self.weight))  

		person = Human.create("철수", 60.5)  
		person.eat()  

	self  
	
	메소드의 첫번째 인자  
	인스턴스의 매개변수를 전달 할때는 self 매개변수는 생략하고 전달  
	
6. 
	
	
	
		
	
	