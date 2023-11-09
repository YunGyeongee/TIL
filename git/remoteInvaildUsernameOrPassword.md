# remote: Invalid username or password.

- git 로그인이 풀린 문제
- 기존에 생성된 토큰이 있다면 그대로 사용하면 되지만, 없다면 발급해줘야함 [링크]()

1. 설정 초기화
```
git init
```
2. git 정보 등록
```
git remote add origin [나의 git 주소]
```
```
예) git remote add origin https://github.com/YunGyeongee
```
3. repositories 복제 후 설정
```
git clone [복제할 프로젝트 주소]

// clone 한 이후
Username for 'https://github.com': 

// 라고 코드가 생성될 것. 
// 이름 입력 (git 이름과 동일하지 않아도 됨)

Password for 'https://rachel@github.com':
// token 을 입력한다.
```
