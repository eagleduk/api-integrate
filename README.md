# API 연동

1. 개발 환경 설정
- axios 설치
** react-api 관련 문서 https://meetup.toast.com/posts/92
** api 조회 사이트 https://jsonplaceholder.typicode.com/

2. useState 를 이용한 api 요청

3. useReducer 를 이용한 api 요청
- 요청 관리에 대한 코드를 파일로 작성하여 재사용 가능

3. custom hook 으로 reducer 만들기
- callback 함수로 custom hook 을 재사용 가능하다

4. react-async 로 요청 상태 관리하기
- react-async 설치 (yarn add react-async)
** react-async 관련 문서 https://github.com/async-library/react-async

5. Context 에서 비동기작업 상태 관리
- 처음 랜더링시 함수를 실행하려면 useEffect 를 사용...