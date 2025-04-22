# ATOMIX

![메인 페이지](https://github.com/user-attachments/assets/440c2fca-864a-46dd-a28b-4ba25f3bf582)

---
### ATOMIX 웹/앱 프로젝트

### 2025 STDev-Hackathon-Team10 출전 작품
주제 : 호기심을 풀어내는 과학 관련 서비스

기간: 2025.4.19 - 2025.4.20 

---
## 개발팀 소개 (DEv.JIN)
|이나영|이재희|문준원|홍준표|
|--|--|--|--|
|@lnylnylnylny|@ij5|@moonjun1|@hongjunpyo123|
|PM & FE| FE | BE | BE |

---
## 개발 환경
|Frontend|Backend|
|---|---|
|<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white">![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=for-the-badge&logo=bun&logoColor=white)![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)|dd|

---
## 문제 인식 및 선정 배경
**교육** &rarr; 초/중/고등학생들의 디지털화 수업과 지역별 교육 격차를 해소 


**호기심** &rarr; 원소끼리 섞으면 어떤 화합물이 나올 지에 대한 궁금증 해소

---
## 프로젝트명
ATOM + MIX 

원소를 조합해 다양한 화합물을 제작하고 결과를 통해 과학 지식을 탐구하는 시뮬레이션 기반 교육 서비스

---
## 프로젝트 설명
### 1. Single Play
- 기본 원소들을 선택하여 화합물을 제작할 수 있습니다.
- 기본 원소들은 H,C,N,O,S 총 5개로 이뤄져 있으며 다양한 조합을 통해 화합물을 발견할 수 있습니다.
- 화합물을 발견하면 도감이 채워지며 도감으로 이동되는 모달창이 함께 보여집니다.

#### Dictionary System
- 여태까지 찾은 화합물을 확인할 수 있습니다.
- 화합물을 클릭하면 화합물에 대한 정보와 설명이 들어 있어 학습효과를 줍니다.

#### Ranking System
- 개인 랭킹 : 가장 많은 화합물을 제작한 유저의 닉네임과 화합물 개수를 보여줍니다.
- 그룹 랭킹 : 설정한 학교에 맞춰 학교 별 랭킹을 보여줍니다.

#### Store System
- 포인트를 통하여 기본 원소 외의 원소들을 구매할 수 있습니다.
- 포인트 얻는 방법은 아래와 같습니다.
  1) 새 화합물 발견시
  2) 멀티 플레이에서 우승 시
  3) 광고를 보았을 때


### 2. Multi Play
- 실시간 접속을 통한 랜덤 매칭이 이뤄집니다.
- 1:1 대결을 통하여 화합물 대결이 진행되며, 30초 이내에 최대한 많은 체력을 깎는게 우선입니다.
- 기본 체력 500이 주어지며, 화합물 별 능력치가 설정되어 있어 상대의 체력을 감소시킬 수 있습니다.
- 하지만 중복 화합물 제작시 공격이 되지 않습니다.
- 최대한 많은 화학식을 암기하여 멀티 플레이에서 우승하세요

---
## 프로젝트 설치 및 실행방법

#### Frontend

To run:
```bash
bun run dev
```

#### realtime (웹 소켓)

To install dependencies:
```bash
bun install
```
To run:
```bash
bun run index.ts
```
This project was created using bun init in bun v1.1.42. Bun is a fast all-in-one JavaScript runtime.

#### Backend
