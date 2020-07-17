##title : Hello World!
>Hello World! 

1. notepad 에서 print('Hello, World') 를 입력후 Ctrl+S 를 눌러 저장
2. Window+R 키에서 powershell 창에서 test.py 파일을 실행
3. powershell 에서 잘 출력되었나 확인

>변수

1. notepad 에서 변수 identtity 지정
2. identity = '한국인'
	number_of_legs = 2
	print('안녕! 나는', identity, '이야, 나는 다리가', number_of_legs, '개 있어.')
3. powershell 에서 출력되었나 확인

> 주석

1. 주석은 코드의 오른쪽이나 왼쪽에 추가하여 적당한 메모를 남길 수 있다.
2. 주석은 *** 세개를 추가하여 ***으로 닫아 그사이의 것들을 한꺼번에 주석처리 할 수 있다.
3. #print('Hello World') <-- 출력안됨
4. powershell 에서 출력이 안되어야 함

> 숫자와 문자열

1. 숫자는 수학연산이 가능 +,-,*,/,%,** 			# ** 은 거듭제곱을 뜻함
2. 문야열 화면이 그대로 출력 가능 따옴표로 둘러싸서 표시함.

>REPL

1. REPL 이란 Read,Eval,Print,Loop로 읽어서 평가하고 출력하는 루프 라는 뜻을 가졌다.

>Shell

1. pwd : 현재 진행중인 디렉토리 경로를 출력하라
2. ls : 현재 폴더 내용물을 출력하라
3. cd : cd <폴더명> 다른폴더로 이동한다 cd.. 란 상위폴더로 이동하는것이다.
4. cp : cp <복사할것>. <복사할파일이름> 한다면 복사를 한다.
5. rm : 파일을 삭제
6. 쉘에는 그래픽 셸과 명령줄 셸 둘으로 나뉜다.

>fotter :

powershell 에서 잘못하고 python 만 입력한 경우 exit<>로 종료하여 나올  수 있음