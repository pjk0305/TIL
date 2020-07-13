##while문과 반복 제어

> while문 쓰기

1. while문 쓰기
	while문  
	조건이 참인 경우 계속 실행하는 반복문  

	ex) while selected not in ['가위', '바위', '보']:  
		selected = input('가위, 바위, 보 중에 선택하세요>')  

	for 반복문으로 작성한 코드는 while 반복문으로 작성 할 수 있다.  


2. break,continue  

	break, continue  
	
	break  
	반복문을 종료시키는 기능  
	
	continue  
	반복문의 나머지 부분을 보지 않고, 반복문의 처음으로 돌아가는 기능  
	
>try except

1. try except  
	예외 처리  
	try:
		# 에러가 발생할 가능성이 있는 코드  
		
		
	except Exception: # 에러 종류
		#에러가 발생 했을 경우 처리할 코드  
	경우에 따라 예외 처리 대신 if else를 사용 할 수 있다.  
	
	
2. 예외의 이름을 모를 때

	예외 이름을 모르는 경우 처리 방법  
	ex) try:  
		# 에러가 발생할 가능성이 있는 코드  
		except Exception as ex: # 에러 종류  
			print('에러가 발생 했습니다', ex) # ex는 발생한 에러의 이름을 받아오는 변수  


3. raise

	예외 발생한  
	
	사용자가 직접 에러를 발생시키는 기능  
	raise Exception # 에러 종류  
	많이 사용하면 코드를 읽기 어려워진다.  
	
