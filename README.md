# 정규표현식 (Regular Expression)
- 일정한 규칙을 가진 문자열을 표현하는 방법
- 문자열에서 특정 내용을 찾거나 대체 또는 발췌하는데 사용

# 장점
- 일반적인 조건문으로 복잡할 수 있지만, 정규표현식 이용 시 매우 간단하게 표현 가능

# 단점
- 주석이나 공백을 허용하지 않고, 여러 기호를 혼합하여 사용하기에 가독성이 떨어짐

# 구성

![image](https://github.com/chelling2/RegularExpression_JS/assets/114050357/70db1aab-e886-48db-892d-3165d56d8a42)

  /패턴(pattern)/플래그(flag)
- 슬래시 문자 두개 사이로 정규식 기호가 들어가는 형태

# 정규 표현식 만드는 방법
![image](https://github.com/chelling2/RegularExpression_JS/assets/114050357/a6ac863c-7f35-4dcc-9ae1-8b1af63660e3)       
정규 표현식 리터럴은 스크립트를 불러올 때 컴파일되므로, 바뀔 일이 없는 경우 리터럴을 사용해 성능 향상 가능        

![image](https://github.com/chelling2/RegularExpression_JS/assets/114050357/0916c6ee-505f-4675-86ad-4dfd652ffd2b)    
생성자 함수를 사용하면 정규 표현식이 런타임에 컴파일 되므로, 바뀔 수 있는 패턴이나 사용자 입력 등 외부 출처에서 가져오는 패턴에서 사용하기에 용이함    

# 정규식 메소드
![image](https://github.com/chelling2/RegularExpression_JS/assets/114050357/67b6200f-cf96-43db-9e7d-4c29c224f090)    
- Javascript 에서 지원하는 정규표현식 메소드
- 정규표현식을 가지고 이메일이나 전화번호 매칭 필터링을 하기 위해 메소드를 이용하여 패턴을 검사하고, 매칭되는 문자열을 추출, 변환

# 정규식 플래그
![image](https://github.com/chelling2/RegularExpression_JS/assets/114050357/04bf2099-2f98-4b40-a72f-83ea3cb3e374)     
- g 전역검색    
전역 검색 플래그가 없는 경우 최초 검색 결과 한번만 반환하는 반면 전역 검색 플래그가 있는 경우 모든 검색 결과를 배열로 반환
- m 줄바꿈 검색
여러 줄의 문자열에서 필터링 해야 될때 사용     
입력 시작(^)앱커는 전체 문자열이 아닌 각 줄 별로 대응되게 만들어졌기 때문에 여러줄을 검색해야 한다면 m플래그를 사용
- i 대소문자 구분 없음
정규식은 기본적으로 대소문자를 구분    
대신 i 플래그를 통해 대소문자를 구분하지 않을 수 있음

# 정규식 특정 문자 숫자 매칭 패턴
![image](https://github.com/chelling2/RegularExpression_JS/assets/114050357/2cc996ef-99e8-4fd9-b12f-41cdb8790acc)

# 정규식 검색 기준 패턴
![image](https://github.com/chelling2/RegularExpression_JS/assets/114050357/c4e4d1ac-825f-4718-b5d0-a5f69d0edf56)










  







   







  
