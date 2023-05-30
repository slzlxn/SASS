# SASS  사용 거의 안함. SCSS를 사용한다 SCSS--> 싸쓰라고 읽음

![image](https://github.com/slzlxn/SASS/assets/105650300/b65e5b3f-e8e3-48d9-b4ba-e709383c0c79) 

# scss 컴파일

![image](https://github.com/slzlxn/SASS/assets/105650300/a4b03f08-8cff-408c-b73d-d238bd4a7dd3)

# css 위치 변경
![image](https://github.com/slzlxn/SASS/assets/105650300/b51c96e4-e9f3-4221-828d-869148853152)
# savePath:null 이면 scss파일과 같은 위치에 style.css가 생긴다
![image](https://github.com/slzlxn/SASS/assets/105650300/0d64ef5e-5e68-440c-a71a-096a9216dc0e)

# savePath:~/css 이면 style.scss과 같은 위치에 style.css가 생긴다
![image](https://github.com/slzlxn/SASS/assets/105650300/1a5c8b90-14b5-4725-8a5d-9d14996c8062)

# savePath:~/../css 이면 scss파일이 있는 폴더의 상위폴더에 생성
![image](https://github.com/slzlxn/SASS/assets/105650300/97556ca7-9bf2-4af9-b0fd-9dd161dbb998)

# 주석처리방법
# //주석처리방법은 css로 컴파일되지 않는다
# /* */ 주석처리방법은  css로 컴파일 된다 
![image](https://github.com/slzlxn/SASS/assets/105650300/059a375a-a156-4b39-ba7e-a48a0d541ef2)

# 변수만들기 --> $로 시작함,(영문, 숫자, -, _)만 사용할 수 있음. 숫자로 시작할 수 없음
![image](https://github.com/slzlxn/SASS/assets/105650300/b14994ee-7424-46af-aec6-20b1804c0ba5)

# .wrap{ & h1{} } = .wrap h1 {}  --> &하위요소   &::after ->.wrap::after
![image](https://github.com/slzlxn/SASS/assets/105650300/7087ed85-db9a-4cc1-a9ed-fca821bef066)

# partials(파샬)
 --관련된 것끼리 묶어서 분리/ 소스에 반복되는 부분들을 분리 부산시켜서 모듈화 시키는 기능
 
  * Partials의 파밍명은 _로 시작하며 
  * 불러들일때는 @import '파일명' 이때 파일명에 _는 포함시키지 않고, 확장명도 포함시키지 않는다

   Scss는 _로 시작하는 파일은 컴파일하지 않는다.
   ![image](https://github.com/slzlxn/SASS/assets/105650300/60280c72-cf24-4c92-bea2-1df4c25fe734)
