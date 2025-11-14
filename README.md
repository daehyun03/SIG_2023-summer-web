# 오늘의 뉴스
## 개요
### 시스템의 목표
오늘의 뉴스는 간결하고 빠른 정보 전달을 위해, 기존 기사를 후처리하여 제공하는 뉴스 플랫폼입니다.
본 시스템은 대한민국 10대 중앙 종합 일간지(경향신문, 국민일보, 동아일보, 문화일보, 서울신문, 세계일보, 조선일보, 중앙일보, 한겨레, 한국일보)의 뉴스들을 대상으로, 뉴스 클러스터링, 클러스터 단위 요약, 연관 클러스터 식별 기능을 제공합니다.

기존 뉴스 플랫폼들은 성장에 따라 사용자에게 많은 기능을 제공하고 있습니다. 하지만 사용자 경험을 해칠 정도의 많은 기능이 존재하여 복잡한 인터페이스를 제공하기도 합니다. 따라서 본 시스템에서는 가볍게 뉴스 플랫폼을 이용하는 사용자에 초점을 맞추어, 사용자 경험을 추구하는 기능을 제공하고자 하였습니다. 본 시스템에서는 아래의 개선점들을 제공합니다.

- 중복된 정보는 모아서 보여준다.
- 한 페이지에서 다양한 정보를 얻을 수 있다.
- 기사 원문을 읽지 않고도 정보를 얻을 수 있다.

## UI
### 메인 화면
![image](https://github.com/user-attachments/assets/204408ef-c04f-4c2d-9929-0ad7ef81b33e)

- 클러스터링된 토픽중 크기가 큰 토픽들을 핫토픽으로 선정하여 버블차트 형태로 제공합니다.

### 섹션 조회 화면
![image](https://github.com/user-attachments/assets/352f856a-85ae-4d6c-801a-805de6c16660)

- 섹션별로 클러스터링된 토픽들을 요약문과 함께 제공합니다.

### 핫토픽 조회 및 채팅
<img width="567" height="522" alt="image" src="https://github.com/user-attachments/assets/f6a88a77-5bb0-4707-a6c0-8c2c4ae0e628" />

- 클러스터링 된 기사들의 요약문과 관련 기사들을 확인할 수 있습니다.
- 핫토픽으로 선정된 클러스터에서는 채팅을 할 수 있습니다.

## 프로젝트 구조
![오늘의 뉴스 프로젝트 구조](https://github.com/user-attachments/assets/7f06d27b-d37f-4ad7-b09d-2eb2cecb2244)

## 🛠 기술스택
| 구분 | 내용 |
| :-- | :-- |
| **Frontend**   | ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=Sass&logoColor=white)|
| **Chat**       | ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)|
| **인증**       | ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)|
| **상태관리**   | ![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=zod&logoColor=white)|
