# BTB - frontend

## 0. Logs  & references

### 1) Logs

* 0525

```
1. 원하는 page를 페이지가 넘어가지 않으면서 자연스럽게 불러오는 방법

해결 : react-router-dom 을 이용해 해당 페이지를 router 형식으로 불러온다 

2. router-dom 의 경로를 switch로 묶어 줬지만 원하지 않은 경우에도 첫번째 경로의 component가 자동적으로 불러와져 원하는 배치 형태가 안되는 문제

해결 :  app에서 해당 component를 불러오지 않고 component를 불러올 페이지를 하나 만든다. 해당 페이지에서 component를 불러오는 방식을 사용
```



* 0526 

```
1. password / email / phone 정보에 대한 validation문제

2. signup 페이지 정보 추가

3. 비밀번호 변경 페이지 완성

4. user 페이지 구조작업
```

* 0527

```
1. todo
	1) 비밀번호 변경 페이지 구성
	2) validation check
	3) http 통신
		(1) login page
		(2) signup page
	4) main page css
	5) log-in 상태 유지
	
2. progress

3. complete
```

* 0528

```
1. todo
	1) http 통신
	2) main page css
	3) log-in 상태 유지
2. progress
	1) validation check 중 gender, checkbox value 변경 문제
3. complete
	1) validation check
```

* 0529

```
1. todo
	1) main page css
	2) log-in 상태 유지
2. progress
	1) validation check 중 gender, checkbox value 변경 문제
	2) http 통신

3. complete
```

* 0530

```
1. todo

2. progress

3. complete
```

* 0601

```
1. todo
	1) userexam page 구현
	2) userexamresult page 구현
	3) user css

2. progress
	1) userprofile page 구현
	2) router 구현

3. compolete
```

* 0602

```
1. todo
	1) userexamresult page 구현
2. progress
	1) router 구현
	2) userexam page 구현
3. compolete
	1) userprofile page 구현
```





### 2) references

* [Redux 개념]([https://medium.com/@ljs0705/redux%EB%A5%BC-%EC%9D%B4%ED%95%B4%ED%95%98%EC%9E%90-7c9e8de0ab7f](https://medium.com/@ljs0705/redux를-이해하자-7c9e8de0ab7f))
* [React와 Redux 개념](https://d2.naver.com/helloworld/1848131)
* [login 및 sign up 기능 구현]([https://medium.com/@yms0214/2%EC%A3%BC-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EB%A1%9C%EA%B7%B8%EC%9D%B8-%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85-%EA%B8%B0%EB%8A%A5-bfbbfa1e9ccc](https://medium.com/@yms0214/2주-프로젝트-로그인-회원가입-기능-bfbbfa1e9ccc))
* [login 관련 인증처리](https://pro-self-studier.tistory.com/118)





## 1 . Main

### 1) main page

### 2) Login

* error 처리

```
1. 기존 domain

https://signinssl.gmarket.co.kr/login/login?url=https://www.gmarket.co.kr/

2. 에러 domain

https://signinssl.gmarket.co.kr/LogIn/LogIn?member_type=MEM&failCheck=1&type=&url=http://www.gmarket.co.kr/
```



### 3) 회원 가입

### 4) 정보 찾기



## 2. Student



## 3. Teacher



## 4. Admin





