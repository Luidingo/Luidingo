# 👋 Client Programmer 정용표입니다

Unreal Engine 기반 **클라이언트 개발자**로  
VR/XR, 실시간 오디오 싱크, 물리 기반 인터랙션, 데이터 중심 아키텍처에 강점이 있습니다.

> 기능 구현에서 끝나지 않고  
> **실기기 환경에서 안정적으로 동작하도록 만드는 개발자**를 지향합니다.

---

## 🎮 Featured Projects

### 🥁 Tales of Bori  
**VR Rhythm Game (Meta Quest 3 / 3S)**

- **Engine / Platform**: Unreal Engine 5.4.4 / Meta Quest  
- **Team**: 클라이언트 개발자 1, 디자이너 1, PM/기획 1, 외부 백엔드 1  
- **Role**: 팀 내 유일 클라이언트 개발자  

**Project Overview**  
Meta Quest 기기에서 장구를 연주하는 VR 리듬 게임입니다.  
다운로드한 음악과 악보를 기반으로 실시간으로 날아오는 장단에 맞춰 연주하는 **음악 모드**,  
배경을 변경하며 자유롭게 연습할 수 있는 **자유 모드**를 제공합니다.

**What I Did**
- 게임 전체 클라이언트 구조 설계 및 구현
- 악보 / 음악 / 계정 데이터 구조 설계
- VR 물리 기반 인터랙션 구현
- UI / HUD / 메뉴 전반 개발
- JWT 기반 인증 및 HTTP 통신
- 오디오 재생 및 싱크 처리
- 비동기 프리로딩 시스템 구축
- Meta Quest 실기기 기준 성능 최적화

**Challenging Point**
- 실제 물리 연주에 가까운 장구 연주 구현 요구
- PhysicsHandle 기반 Grab 방식의 한계 경험
- 커스텀 Grab 시스템의 필요성 인지
- 마감 기한 문제로 완전한 해결에는 도달하지 못했으나,  
  VR 물리 인터랙션 구조 설계에 대한 이해도 크게 향상

---

### 🎼 Rhythm Editor  
**Rhythm Chart Authoring Tool**

- **Engine / Platform**: Unreal Engine 5.4.4 / Windows  
- **Team**: 클라이언트 개발자 1, 디자이너 1, PM/기획 1, 외부 백엔드 1  
- **Role**: 클라이언트 전반 담당  

**Project Overview**  
*Tales of Bori*에 사용될 악보 데이터를 제작하기 위한 상용 툴입니다.  
비전문가도 쉽게 사용할 수 있도록 UI를 구성했으며,  
사용자 및 데이터를 관리하는 관리자 모드를 포함합니다.

**What I Did**
- 메인 게임과 연동되는 데이터 구조 설계
- 악보 편집 UI 구현
- 키 입력 기반 노트 입력 시스템
- 오디오 재생 및 싱크 처리
- 서버 통신 및 관리자 모드 개발

**Challenging Point**
- 런타임 중 악보 노트 사운드와 음악 간 싱크 불일치 문제 발생
- 원인을 오디오 청크 확보 문제로 파악
- 전체 재확보가 아닌 부분 청크 재확보 방식으로 최적화
- 안정적인 오디오 싱크 확보 및 성능 개선

---

### 🔫 Unreal Destiny  
**Multiplayer FPS (Study Project)**

- **Engine / Platform**: Unreal Engine 5.1 / Windows  
- **Team**: 클라이언트 개발자 5명  

**What I Did**
- 플레이어 애니메이션 서버 동기화
- 1인칭 ↔ 3인칭 카메라 전환 구현
- 스킬 및 공격 시스템 구현
- 플레이어 스탯 연동 HUD 개발

**Challenging Point**
- 본인 시점은 1인칭, 타 클라이언트에는 3인칭 애니메이션 표시 필요
- Replication 구조를 활용해 시점별 애니메이션 분기 처리

---

### 🗡 Unreal Skyrim  
**Action RPG (Study Project)**

- **Engine / Platform**: Unreal Engine 5.1 / Windows  
- **Team**: 클라이언트 개발자 5명  

**What I Did**
- 아이템 데이터 구조 설계
- 인벤토리 및 UI 개발
- 대화 시스템 및 퀘스트 시스템 구현
- 아이템 상호작용 구현

**Challenging Point**
- 인벤토리에서 선택된 아이템을 실시간 3D 모델로 표시
- 맵 외부에 렌더 타겟 전용 액터를 구성하여 UI에 출력

---

### 🧱 Direct3D Skyrim  
**Engine-Level Study Project**

- **Engine / Platform**: Direct3D / Windows  
- **Team**: 클라이언트 개발자 4명  

**What I Did**
- 몬스터 데이터 구조 설계
- 몬스터 AI 구현
- 하이트맵 기반 지형 생성 알고리즘 구현

---

### 🌌 하늘못의 전설  
**Mobile Action Roguelike**

- **Engine / Platform**: Unity / Android  
- **Team**: 프로그래머 4, 디자이너 2  
- **Role**: 프로그래밍 및 기획  

**What I Did**
- 세이브 / 로드 시스템 구현
- CSV 기반 데이터 구조 설계
- 플레이어 및 몬스터 데이터 설계
- 프로젝트 전반 기획 참여

---

## 🔧 Tech Stack

### Main
- C++
- Unreal Engine
- VR / XR Interaction
- Audio Sync & Runtime Audio Handling
- Data-driven Architecture

### Used
- Unity / C#
- Direct3D
- JSON / CSV
- HTTP / JWT

---

## 🧠 Strengths
- Meta Quest 실기기 기준 문제 해결 경험
- 런타임 오디오 싱크 및 최적화 경험
- Blueprint ↔ C++ 역할 분리 설계
- 팀 내 단독 클라이언트 개발 경험

---

## 📬 Contact
- **Email**: boboss4253@gmail.com
