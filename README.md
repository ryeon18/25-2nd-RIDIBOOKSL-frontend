# RIDIBOOKSL 2nd PROJECT
<img width="1660" alt="스크린샷 2021-10-31 오후 3 38 04" src="https://user-images.githubusercontent.com/81367886/139572236-777383f0-dfa0-4c6f-aa20-1e49056b26aa.png">

## Introduction
[리디북스](https://ridibooks.com/) 를 모티브로 한 팀 프로젝트<br>
웹툰/웹소설, 전자책, 만화까지 취향에 딱 맞는 다양한 컨텐츠를 제안하고 제공하는 웹사이트
- 기간 : 2021. 10. 18. ~ 2021. 10. 29.
- [Backend GitHub](https://github.com/wecode-bootcamp-korea/25-2nd-RIDIBOOKSL-backend)
- [프로젝트 시연 영상](https://youtu.be/AiPwNHyOqH4)
- 초기 세팅부터 직접 구현하였으며, 모든 데이터는 프론트와 백의 통신으로 받아왔습니다.

## Members
- **Frontend**: 김수민, 김용현, 박세연, 이나영
- **Backend**: 이기용, 이정아


## Technology
- **Frontend**: `HTML/CSS` `JSX` `React(CRA)` `Styled-components` (Library: `React-router-DOM`, `React-slick`)
- **Common**: 버전관리 `Git & GitHub`, 소통 `Slack`,  일정관리 [Trello](https://trello.com/b/zSVgJt0Z/%EB%A6%AC%EB%94%94%EB%B6%81%EC%8A%AC%EB%B6%81%EC%8A%ACridibooksl)

## 담당 기능

**메인페이지 구현**
</br>**1. 각 항목에 따른 데이터 `광고이미지`, `책리스트`를 슬라이더로 구현**
</br>  - Library `React-slick` 을 이용. 작업물에 맞게 스타일을 `styled-component`로 수정.</br>

**2. 베스트셀러, 많이 읽고 있는 책 리스트**
</br>  - `grid`를 이용하여 책 리스트들을 맵함수를 통해 데이터를 가져옴으로써 반복된 코드를 줄이고, 원하는 갯수까지만 나오도록 구현.</br>

**3. 컴포넌트 재사용**
</br>  - 백엔드로부터 받는 데이터에 따라 화면에 렌더되도록 컴포넌트 재사용 함으로써 반복을 줄임.</br>

**4. 옵셔널체이닝**
</br>  - `lifecycle`로 인하여 데이터가 들어오기 전에는 화면에 에러가 뜨기 때문에 데이터가 있는 경우에 화면이 렌더되도록 옵셔널체이닝 사용

**푸터 구현**
1. `onClick`으로 사업자정보가 나오도록 &&연산자를 통해 구현

**구현 영상**

![구현 영상](https://user-images.githubusercontent.com/62207127/145957666-794d1e38-eed2-4ff1-be61-1999c912063d.gif)

