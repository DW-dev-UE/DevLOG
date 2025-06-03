# DevLOG
언리얼 엔진 기반 게임 개발 및 툴 제작, Python을 활용한 자동화·데이터 처리, API 설계·통합 기술을 소개합니다.

Learn about Unreal Engine-based game development and tooling, automation and data processing with Python, and API design and integration.

[Click here to go to the introduction page in English](./README_EN.md)

## 🎮 Unreal Engine 프로젝트 모음

아래 프로젝트를 클릭하면 상세한 소개 페이지로 이동합니다.

1. [🗺️ 자동화 도면](#자동화-도면)  
2. [💰 P2E 게임](#p2e-게임)  
3. [🔫 FPS 게임](#fps-게임)  
4. [🌟 1인 개발 Steam 게임](#1인-개발-steam-게임)  

---

### 🗺️ 자동화 도면
- **주요 기능**  
  - 액터를 클릭하면 건물 디자인을 미리 확인  
  - 도면 이미지를 업로드하여 2D → 3D 모델을 **런타임**에 자동 생성  
- **사용 기술**  
  - Unreal Engine C++  
  - Runtime Geometry 생성  
  - UI: UMG 위젯으로 간편한 클릭·미리보기 시스템 구축  

---

### 💰 P2E 게임
- **프로젝트 개요**  
  - 완전히 합법적으로 설계된 Play-to-Earn(플레이 투 언) 게임  
  - **MMORPG**와 P2E 기능을 Unreal Engine Dedicated 서버로 구현  
- **백엔드 & 인프라**  
  - Python Flask 기반 RESTful API  
  - GCP(Google Cloud Platform)를 활용한 HTTPS 인증 및 서버 호스팅  
  - GoogleAuth API 연동으로 **안전한 로그인** 구현  
  - MetaMask 연동으로 지갑 주소 확보  
  - Blockchain API를 통해 실시간 코인·NFT 거래 지원  
- **주요 특징**  
  - 서버 간 분리된 Dedicated 환경으로 안정적인 멀티플레이 구현  
  - 사용자 지갑과 연동된 아이템 거래 시스템  
  - 실시간 거래 정보 반영 및 투명한 자산 관리  

---

### 🔫 FPS 게임
- **프로젝트 설명**  
  - 구글 Play 스토어에 등록된 **모바일 FPS 게임**  
  - Unreal Engine 5 기반으로 개발  
- **주요 기능**  
  - 실시간 멀티플레이어 매치메이킹  
  - 모바일 최적화 렌더링 및 네트워크 동기화  
  - 터치·조이스틱 지원 컨트롤  
  - 다양한 무기·맵을 지원하는 콘텐츠  

---

### 🌟 1인 개발 Steam 게임
- **프로젝트 개요**  
  - **단독 개발**으로 제작 및 출시된 Steam용 게임  
  - 기획·디자인·프로그래밍·아트워크까지 **혼자서** 구현  
- **주요 성과**  
  - Steam 플랫폼 출시 및 사용자 피드백 반영  
  - 언리얼 엔진 기반으로 최적화된 빌드 배포  
  - 커뮤니티 관리 및 업데이트 패치 주기적 진행  
