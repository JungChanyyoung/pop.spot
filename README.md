# 🏠  POP,SPOT <br>(팝업스토어 정보, 웨이팅, 사전예약을 통합으로 이용하는 서비스)

<img src="https://blog.kakaocdn.net/dn/7qhOr/btsIbpoR2RP/XKsBQWmqm1h9TwXTAK3Fm1/img.gif" width="600">

<br>

## 프로젝트 소개
- 서울의 팝업스토어 정보를 한곳에서 확인할 수 있습니다.
- 사용자들은 사전예약 및 현장대기 서비스를 통해 대기 시간을 줄이고 편리하게 이용할 수 있습니다.
- 팝업스토어 업체 관리자가 사전예약 및 현장대기 현황을 쉽게 관리할 수 있습니다.
## 프로젝트 기획
- 플로우차트 : 구상한 기능을 페이지별로 나누고 유저의 사용자 경험을 따라 플로우차트를 작성
- 아키텍처 : next.js를 사용해보자
- 와이어프레임 : 기획을 바탕으로 구체적인 페이지의 와이어 프레임을 피그마로 작성

<img src="https://blog.kakaocdn.net/dn/lrbGL/btsNiDpWvEi/CdjznRq1G71uXEKm8rcv8K/img.png" width="300">   <img src="https://blog.kakaocdn.net/dn/bhzX3m/btsNjDxrDGw/6IoPzK4kWAhMLnxTbmbo4k/img.png" width="300" height="220">   <img src="https://blog.kakaocdn.net/dn/bMDwFV/btsNlggeBLX/nDbOtPn47VrWjHoA8mk6t0/img.png" width="300" height="220">

<br>

## 프로젝트 기간 & 인원
- 프로젝트 기간 : 2023.11.13 ~ 2023.12.01
- 개발 인원 : 풀스택 6명
  
<br>

## 사용 기술

- **FrontEnd**
  : Next.js / React / SCSS / Prettier / Eslint <br>

- **BackEnd** :
  Node.js / express.js / MongoDB / Mongoose <br>

- **협업** : Git & Git lab / Figma / Postman / Gather / Notion <br>

<br>

## 담당 페이지 구현 및 기능
### 업체 관리자 페이지 개발
- 헤더
- 사이드바
- 웨이팅, 사전예약 전체 리스트 조회
- 웨이팅, 사전예약 현황 조회
- 정렬(이름, 날짜, 총인원)
- 업체관리자 전용 페이지의 접근 권한 검증 기능
- 반응형
  
<br>

## 페이지별 기능
### 1. 전체 목록 페이지(관리자 메인 페이지)
- 로그인 시 업체 관리자만 특정 페이지에 접근할 수 있도록 기능 권한을 설정하였습니다.
- 로그인 시 관리자는 팝업스토어 이름과 브랜드명별로 목록을 조회할 수 있습니다.
- 필터 기능을 통해 웨이팅 리스트와 사전예약 리스트를 구분하여 확인할 수 있습니다.


<img src="https://blog.kakaocdn.net/dn/cMfpXy/btsH8VpNWN4/je7iPj8Ciu8UF0dklroIC0/img.png" width="400"> <img src="https://blog.kakaocdn.net/dn/bMZBAd/btsH9XUq1SF/gq76ZknGuvHfdW2zfEKi2K/img.png" width="400">


<br>

### 2. 웨이팅,사전예약 페이지
- 이름, 날짜, 총인원별로 현황 리스트를 정렬하여 확인할 수 있습니다.
- 웨이팅과 사전예약 사용자의 실시간 현황을 모니터링할 수 있습니다.
- 사용자가 현장에 도착하면 관리자가 완료 버튼을 누르면 완료 상태로 변경되어 완료 페이지에 자동으로 정리됩니다.

  
<img src="https://blog.kakaocdn.net/dn/RdoD6/btsH9tsBE4B/jCqQaxtm0kzekDGpdDcUtK/img.png" width="400"> <img src="https://blog.kakaocdn.net/dn/oHusH/btsH97o3bGX/7TS9ZdVwGlbrNBbTMnbTik/img.png" width="400">

### 3. 반응형
- @media 미디어 쿼리를 사용하여 화면 너비에 따라 다른 스타일을 적용합니다.
- flex-direction: column;을 사용하여 작은 화면에서 세로 방향으로 요소를 배치하도록 레이아웃을 조정하였습니다.
- 버튼 등의 UI 요소는 다양한 미디어 쿼리에서 스타일이 달라질 수 있습니다.
- 아이콘을 통한 토글 기능으로 화면 크기에 따라 사이드바가 자동으로 조정됩니다. 데스크탑 환경에서는 항상 표시되며, 모바일 환경에서는 아이콘을 클릭하면 나타납니다.

  
<img src="https://blog.kakaocdn.net/dn/C6MJx/btsIaTxl7T3/xzzQmobv54t3qxFcPPNMHk/img.gif" width="400"> <img src="https://blog.kakaocdn.net/dn/ckctoh/btsIbpbsMKB/CVr2q4FjHc4JIgB5OX7GT1/img.gif" height="209" width="160">
