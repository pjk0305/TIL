## 논리연산과 if문 더 알아보기

>논리연산

1. 논리연산 더 알아보기

	단락평가  
	논리연산에서 코드의 앞만 보고 값을 정할 수 있는 경우 뒤는 보지 않고 값을 결정  
	복잡한 코드를 단순하게 하는 방식  
	
2. bool 값과 논리연산과  
	
	true, false  
	숫자 0을 제외한 모든 수 - true  
	빈 딕셔너리, 빈 리스트를 제외한 모든 딕셔너리, 리스트 - true  
	아무 값도 없다는 의미인 None - false  
	빈문자열을 제외한 모든 문자열 - true  
	

>list의 다양한 기능

1. list의 기능  

	list.index( value ) : 값을 이용하여 위치를 찾는 기능  
	list.extend( [value1, value2] ) : 리스트 뒤에 값을 추가  
	list.insert( index, value ) : 원하는 위치에 값을 추가  
	list.sort( ) : 값을 순서대로 정렬  
	list.reverse( ) : 값을 역순으로 정렬  
	
2. list와 문자열  
	
	리스트와 문자열은 유사하다.  
	서로 변환이 가능하다.  
	list = str.split( ) : 문자열에서 리스트로  
	" ".join( list ) : 리스트에서 문자열으로  
  
> Slice

1. slicing

	리스트나 문자열에서 값을 여러개 가져오는 기능  
	ex) text = "hello world"  
		text = text[ 1:5 ]  

		list = [ 0, 1, 2, 3, 4, 5 ]  
		list = list[ 1:3 ]  
		slice를 하면 해당하는 부분의 리스트나 문자열을 새로 만들어 준다.  

	시작과 끝부분을 얻어 오는 방법  

	ex) list[ 2: ] : 2번째부터 끝까지 반환  
		list[ : 2 ] : 처음부터 2번째 까지 반환  
		list[ : ] : 처음부터 끝까지 전부 반환  
		
		
2. slice의 step

	step  
	slice한 값의 범위에서 step 값을 주어 그 값만큼 건너뛰어 가져오는 기능  
	list[ 시작값:끝값:step ]  
	
3. slice로 리스트 수정하기  

	slice 활용  
	
	삭제  
	
	ex) del list[ :5 ] : 처음부터 5번째까지 삭제  
	수정  
	 
	ex) list[ 1:3 ] = [ 77, 88 ]  
		list[ 1:3 ] = [ 77, 88 ,99 ] : 더 많은 개수로 변환  
		ist[ 1:4 ] = [ 8 ] : 더 적은 개수로 변환  
	

	