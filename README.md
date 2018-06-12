# :heart_eyes:npm 명령어 정리


1. npm init //npm 초기설정
2. npm init --yes //초기설정, 입력없이
3. npm list --depth=0 //설치된 패키지 보기
4. npm install //깃헙에서 처음 불러왔다면
5. npm view mongoose dependencies // 패키지 의존성 보기
6. npm view mongoose versions //패키지 모든 버전 보기
7. npm install mongoose@2.4.2 //패키지 버전 바꾸기(다운그레이드, 업그레이드)
8. npm outdated //패키지 업그레이드 확인
9. npm update //모든 패키지 wanted버전으로 업그레이드
10. npm install -g npm-check-updates<br>
npm-check-updates<br>
npm install<br> //모든 패키지 최신버전으로 업그레이드
13. npm install jshint --save-dev //개발할때만 사용하는 패키지 설정
14. npm un mongoose //패키지 삭제

패키지 출판하기
=============
1. npm adduser //npm에 회원가입
2. npm login //npm에 로그인
3. npm publish //패키지 출판
4. npm version major<br>
npm version minor<br>
npm version patch<br>
//버전업그레이드 patch는 버그수정
