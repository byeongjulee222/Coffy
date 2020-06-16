# :coffee: Coffy <img src="https://img.shields.io/badge/public_ver-1.0-blue">

<br>

## :one: Overview

- 주니어 프론트엔드 엔지니어를 위한 코드 공유 서비스

- `Code를 Copy`해서 사용하는 `Coffee` 처럼 중독성 있는 프론트엔드 코드 공유 서비스(made by `SSAFY` Project 'SangleSangle' Team)

<br>

## :two: Project Schedule

![Image Pasted at 2020-6-9 12-13](https://user-images.githubusercontent.com/52685250/84102212-c6edda80-aa4a-11ea-99b7-59ab07241420.png)

<br>

## :three: Tech Stack & Architecture

![Image Pasted at 2020-6-9 11-25](https://user-images.githubusercontent.com/52685250/84101997-3b744980-aa4a-11ea-9c8d-3da42683caf3.png)

:round_pushpin: <b>Frontend</b> : `Vue.js`

:round_pushpin: <b>Backend</b> : `Spring Boot`

:round_pushpin: <b>Database</b> : `MySQL`

:round_pushpin: <b>Deploy</b> : `docker`, `Jenkins`

:round_pushpin: <b>Development Enviornment</b> : Windows 10, Node.js 12 or higher, Vue CLI 4 or higher, Apache 2.0

:round_pushpin: <b>Using Editor</b> : Visual Studio Code

<br>

## :four: Quick Start

:heavy_check_mark: <b>Requirement</b>

- `Node.js` : 12 or higher
- `Vue CLI` : 4.0 or higher

:heavy_check_mark: <b>Installation</b>

```bash
$ cd front
$ npm install
```

:heavy_check_mark: <b>Usage</b>

```bash
$ npm run serve
```

:heavy_check_mark: <b>Deploy URL</b>

- https://k02b2021.p.ssafy.io/ 주소로 접속해서 볼 수 있습니다.

<br>

## :five: Homepage Configuration

### (1) 메인 페이지

![image](https://user-images.githubusercontent.com/52685247/84480618-cca82200-accf-11ea-863e-f6ac04db69b7.png)

- 간단한 서비스 소개 + 좋아요 순으로 Best Template 제공
- 로그인 시 `Dashboard` 에서 자신이 작성한 템플릿와 찜한 템플릿을 볼 수 있습니다.
- dark <-> white 기능으로 테마 색상을 변경할 수 있습니다.
- 하단의 `Show More` 버튼을 클릭하면 코드 목록 페이지로 이동해 더 많은 코드들을 볼 수 있습니다.

<br>

### (2) 코드 작성

![01](https://user-images.githubusercontent.com/52685250/84101845-e59fa180-aa49-11ea-97e1-17e4b4fb7cc7.JPG)

- Sidebar의 `try it!` 탭 클릭 시 이동할 수 있습니다.
- HTML, CSS, Javascript 언어를 사용해서 만든 템플릿을 실시간으로 미리 볼 수 있습니다.
- 저장 기능을 통해 자신이 작성한 코드를 보관할 수 있습니다.

<br>

### (3) 코드 목록

![image](https://user-images.githubusercontent.com/52685247/84480183-1d6b4b00-accf-11ea-9b22-f480001ac966.png)

- Sidebar의 `Code` 탭 클릭 시 이동할 수 있습니다.
- 다른 사람들이 공유한 코드를 볼 수 있습니다.
- 제목, 내용을 기반으로 검색이 가능하도록 구현하였습니다.

<br>

### (4) 게임으로 익히는 CSS 지식

![image](https://user-images.githubusercontent.com/52685247/84482479-c8313880-acd2-11ea-8073-09b3e039b5c4.png)

- Sidebar의 `Game` 탭 클릭 시 이동할 수 있습니다.
- CSS 관련 지식들을 간단한 게임을 통해 재미있게 학습할 수 있습니다.
- :coffee:<b>Coffy</b> 서비스에서 제작한 게임의 CSS 테마는 `flex`, `text`, `grid`, `transition`이 있으며 추후 새로운 컨텐츠를 추가할 계획입니다.
- 해당 게임 서비스는 로그인을 해야 이용 가능하며 차례대로 해결해야 다음 문제를 풀 수 있습니다. 그리고 해결한 문제는 문제 버튼이 파란색으로 바뀌게 됩니다.

![image](https://user-images.githubusercontent.com/52685247/84482391-991ac700-acd2-11ea-9a62-1d4ee8284b0a.png)

- 소개와 힌트를 제공하여 게임을 진행하는데에 도움을 주었습니다.

![02](https://user-images.githubusercontent.com/52685250/84101858-ea645580-aa49-11ea-9acc-0fc9fe355914.JPG)

- 해결한 문제에 접속하면 상단에 `Solved`로, 해결하지 못한 문제는 `Unsolved`로 표시됩니다.
- 문제를 풀다가 헷갈리거나 어려운 경우 `힌트보러가기` 버튼을 누르면 해당 문제와 관련된 힌트를 보실 수 있습니다.

<br>

### (5) 클랜 기능

![image](https://user-images.githubusercontent.com/52685247/84482572-f4e55000-acd2-11ea-9389-734ffcc53f21.png)

- Sidebar의 `Clan` 탭 클릭 시 이동할 수 있습니다.
- 전체 클랜 목록을 제공하여 원하는 클랜에 지원할 수 있도록 하였습니다.

![03](https://user-images.githubusercontent.com/52685250/84101860-eb958280-aa49-11ea-8f32-654b4934fc89.JPG)

- 관심사가 비슷한 사람들끼리 클랜을 이뤄서 지식을 공유할 수 있습니다.
- 클랜 기능도 로그인을 해야 이용 가능하며 유저당 클랜은 하나만 가입 가능합니다.

<br>

### (6) Introduction

![image](https://user-images.githubusercontent.com/52685247/84480901-3a544e00-acd0-11ea-97fa-9ed44124b8ca.png)

- 좌측 메뉴에서 `About` 탭을 누르면 :coffee: <b>Coffy</b> 서비스에서 제공하는 컨텐츠의 간략한 설명과 서비스를 만든 `SangleSangle`팀의 간략한 프로필을 볼 수 있습니다.
- 서비스를 사용하시다가 궁금한 점이 있으시면 이 페이지에 있는 저희 팀 멤버들에게 문의해주세요!

<br>

## :six: etc

- 프로젝트와 관련된 기타 자세한 사항들은 notion에 기록되어 있습니다.
  - https://www.notion.so/sanglesangle