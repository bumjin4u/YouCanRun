# YOU CAN' RUN
- 단순한 레이싱 게임은 이제 식상하시죠? 상대방을 방해하면서 게임을 즐겨보세요!

## 소개 및 시연 영상

## 개요
친구들과 함께 즐기는 '메타버스 레이싱'! 친구들을 방해하며 먼저 결승점에 도달하세요
 - 스타크래프트 유즈맵 혈압마라톤, 폴가이즈, 테일즈러너에서 영감을 받아, 기본적은 게임 구조는 선착순 결승점 도달이지만, 중간중간 사용자들끼리 방해할 수 있는 요소를 집어넣어 색다른 재미를 줄 수 있는 게임입니다.

## Why?
다른 사람들과 상호작용 할 수 있는 메타버스와 게임으로써 승부욕을 불러 일으키는 레이싱을 접목했습니다.

## 주요 서비스 화면

### 로그인 화면
![회원가입](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85.gif)
![로그인](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%EB%A1%9C%EA%B7%B8%EC%9D%B8.gif)
### 메인 UI
![코스튬](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%EC%BD%94%EC%8A%A4%ED%8A%AC.gif)
![도감](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%EB%8F%84%EA%B0%90.gif)
![랭킹](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%EB%9E%AD%ED%82%B9.gif)
![튜토리얼](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%ED%8A%9C%ED%86%A0%EB%A6%AC%EC%96%BC.gif)
### 로비
![로비](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%EB%A1%9C%EB%B9%84.gif)
### 게임 입장 화면
![게임리스트입장](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%EA%B2%8C%EC%9E%84%EB%A6%AC%EC%8A%A4%ED%8A%B8%EC%9E%85%EC%9E%A5.gif)
### 대기방
![대기방](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%EC%9E%85%EC%9E%A5%EB%B0%8F%EB%A0%88%EB%94%94.gif)
### 인게임 화면
#### 게임 시작
![게임시작](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%EA%B2%8C%EC%9E%84%EC%8B%9C%EC%9E%91.gif)
#### 게임 종료
![게임종료](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/InGameGif/%EA%B2%8C%EC%9E%84%EB%81%9D.gif)
#### 스킬은 [여기](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/Skills.md)에서!
#### 아이템은 [여기](https://github.com/bumjin4u/YouCanRun/blob/master/%EC%82%B0%EC%B6%9C%EB%AC%BC/Item.md)에서!

#### 더 자세한 정보는 [여기](https://lab.ssafy.com/s09-metaverse-game-sub2/S09P22C101/-/tree/master/%EC%82%B0%EC%B6%9C%EB%AC%BC)에서!

---

## 개발 환경
### BackEnd
- FireBase
### Game Engine
- Unity Engine
- C#

## 협업 툴
- Git
- Jira
- Mattermost
- Plastic SCM
- Google Drive

## 요구사항 정의서
![image](/uploads/34b62a1344a6d581fe783033f6cfc1e1/image.png)
![image](/uploads/535b1ca6f06369a384e04826bceb0f17/image.png)

## ER Diagram
![image](/uploads/ec0b12d45179b250f5811e79a63afa76/image.png)

## 팀원 역할
1. 곽강한 (팀장) : 게임 제작 총괄, 캐릭터 스킬 제작, 캐릭터 이동 및 기능 구현, Photon 캐릭터 연결 구성, 애니메이션 관리, 게임 전반 기능 구성
2. 이재진 : FireBase 로그인 및 회원가입, 인게임 UI제작, GameManager 데이터 관리, 인게임 사운드 구성, 캐릭터 스킬 제작, 맵 제작
3. 이수민 : 인게임 장애물 및 물리로직 구현 , 인게임 사운드 구성, 캐릭터 스킬 구현, 애니메이션 관리 ,맵 기본 구성 및 맵 제작 
4. 손민우 : FireBase 로그인 및 회원가입, Photon서버 방 생성 입장 퇴장 제작, 인게임 시스템 구현, 맵 제작
5. 손임현 : 캐릭터 스킬 제작, 캐릭터 이동 및 기능 구현, 맵 제작, Photon Voice, Photon 캐릭터 연결 구성,
6. 박범진 : 인게임 아이템 구현, 캐릭터 스킬 제작, 캐릭터 이동 및 기능 구현, 발표 자료 및 발표, 
