# 2022 React Webgame

## 1-1. 리액트를 왜 쓰는가?

- 웹 애플리케이션은 전통적인 웹사이트들에 비해서 데이터가 많다.
- 데이터를 바꾸면 화면이 바뀐다. 예) 엑셀
- 프론트에서 데이터를 가지고 있고, 데이터를 바꾸면 화면도 알아서 바뀐다.
- 페이스북은 MVC 패턴의 웹사이트를 버리고 리액트로 데이터와 화면 불일치 문제를 해결했다.
- 뷰나 스벨트가 사용하기는 훨씬 편하다. 그러나 한국에서 대세는 리액트이다.
- 리액트를 사용하는 이유는 복잡한 웹앱에서 화면 불일치 문제를 쉽게 풀어준다.
- 전통적인 웹, 문서 같은 페이지들은 리액트로 할 필요가 없다.

### 장단점

- 데이터와 화면 일치 문제를 해결하기는 쉽지만, 검색 엔진 노출에 어려움이 있을 수 있다.
- 검색 엔진 노출 때문에 리액트로 안 만드는 경우도 있다.
- 네이버나 다음 같은 경우는 리액트로만 이루어진 웹사이트 분석을 잘 못한다.

### 주의할 점

- 스코프와 실행 컨텍스트를 잘 익혀야 한다.
- JS를 못하면 리액트도 못한다.


## 1-3. 첫 리액트 컴포넌트

- 리액트는 JS이다. JS이기에 JS 기본기가 탄탄해야 한다.
- 실무에서는 제로초도 CRA를 사용한다.
- 이제는 최신 문법이랄 것이 없다. IE도 완전히 서비스 중단이 된다.
- 클래스는 99% 사용하지 않는다. 하지만 1% ErrorBoundary에서 사용한다.

- 컴포넌트는 데이터와 화면을 하나로 묶어둔 덩어리이다.
- 데이터는 state, 화면은 render 함수의 return 부분
- 화면의 바뀔 부분들을 state로 만든다.


## 참고 링크

- [강좌 저장소](https://github.com/ZeroCho/react-webgame)
- [듣던 강좌 1-4](https://youtu.be/Rf73Ibj-Lbk)