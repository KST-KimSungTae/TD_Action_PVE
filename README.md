<div align="center">

# 🛸 GALAXY DEFENDER : LAST STAND

### 탑다운 액션 타워디펜스 · 무한 웨이브 생존

플레이어가 직접 총을 들고 전장에 개입하는 액션 타워디펜스.
그리드에 방어선을 짓고, 무한히 몰려오는 적으로부터 중앙 거점(Core)을 지켜라.

<br>

![Unreal Engine 5](https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)
![Blueprint](https://img.shields.io/badge/Blueprint-1E88E5?style=for-the-badge&logo=unrealengine&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Solo](https://img.shields.io/badge/1인_개발-4C9A2A?style=for-the-badge)

<br>

**[▶️ 게임플레이 영상](https://youtu.be/rb2Tf1CdQXQ)** &nbsp;·&nbsp;
**[⬇️ 다운로드](https://github.com/KST-KimSungTae/TD_Action_PVE/releases/tag/v0.02.0000)** &nbsp;·&nbsp;
**[🕹️ 소스 보기](https://github.com/KST-KimSungTae/TD_Action_PVE)**

<br>

![게임 플레이 전경](docs/screenshots/InGame_Foreground.png)

</div>

---

## 🎬 게임플레이 영상

<div align="center">

[![Galaxy Defender 게임플레이 영상](docs/screenshots/Boss_Dramatic.png)](https://youtu.be/rb2Tf1CdQXQ)

▲ 이미지를 클릭하면 유튜브에서 플레이 영상을 볼 수 있습니다

</div>

---

## 📖 소개

**Galaxy Defender : Last Stand** 는 Unreal Engine 5(Blueprint)로 제작한 탑다운 액션 타워디펜스 게임입니다.

일반적인 타워디펜스가 방어물을 배치하고 지켜보는 **'건설·관전'** 중심이라면, 이 게임은 플레이어 캐릭터가 **우클릭 이동·좌클릭 사격**으로 전장에 직접 개입하는 **액션 요소**를 결합했습니다. 플레이어는 수동적 관찰자가 아닌 **능동적 주체**가 됩니다.

**준비 단계**(그리드에 타워·벽 건설, 상점 이용)와 **전투 단계**(사격·수리로 직접 방어)가 무한히 순환하며, 웨이브가 진행될수록 난이도가 절차적으로 상승합니다. 중앙 거점(Core)이 파괴되면 게임 오버입니다.

> 설계의 핵심은 **데이터 주도(Data-Driven) 아키텍처** 입니다. 소수의 상속 클래스가 다수의 콘텐츠를 데이터로 처리하도록 구성해, 새 타워·적·웨이브를 **코드 수정 없이 데이터 행 추가만으로** 확장할 수 있습니다.

---

## ✨ 핵심 특징

- 🎯 **액션 + 디펜스** — 우클릭 이동·좌클릭 사격의 직접 전투와 그리드 건설의 결합
- ♾️ **무한 생존** — 끝없는 웨이브, 절차적으로 상승하는 난이도
- 🧩 **데이터 주도 설계** — 타워·적·웨이브를 데이터로 정의해 코드 수정 없이 확장
- 🏪 **성장 · 전략** — 상점 강화·연구·해금으로 매 판 다른 빌드 구성
- 🐉 **보스전** — 주기적으로 등장하는 특수 패턴 보스 2종
- 🧠 **우선순위 기반 적 AI** — 적 유형별로 벽/타워/코어/플레이어 중 타겟 선택

---

## 🎮 조작법

### 전투 단계

| 입력 | 기능 |
| :---: | :--- |
| 우클릭 | 플레이어 이동 |
| 좌클릭 (홀드) | 사격 (자동 연사) |
| 마우스 커서 | 조준 |
| `Q` | 근처 대상 유료 수리 (돈 = 생존 시간) |
| `Spacebar` | 웨이브 시작 |

### 준비 / 건설 단계

| 입력 | 기능 |
| :---: | :--- |
| `Tab` | 건설 모드 전환 |
| 좌클릭 | 타워 · 벽 배치 (그리드 스냅 + 고스트 프리뷰) |
| `Q` / `E` | 배치물 회전 (±90°) |
| 선택 → 제거 | 설치물 제거 (비용 50% 환불) |

*준비 단계 진입 시 타워·벽은 자동으로 전부 무료 수리됩니다.*

---

## ⬇️ 다운로드 / 실행

> **[📦 최신 릴리스에서 다운로드 (v0.02)](https://github.com/KST-KimSungTae/TD_Action_PVE/releases/tag/v0.02.0000)**

릴리스에서 빌드를 받아 압축을 풀고 실행 파일을 실행하세요.

### 소스 코드로 직접 빌드

```bash
git clone https://github.com/KST-KimSungTae/TD_Action_PVE.git
```

1. `.uproject` 를 **Unreal Engine 5** 로 엽니다.
2. 에디터에서 실행하거나, **File → Package Project → Windows** 로 빌드합니다.

---

## 📄 프로젝트 문서

프로젝트의 기획 · 시스템 · 클래스 구조를 정리한 문서입니다.

- **[📖 프로젝트 매뉴얼 (Google Drive)](https://drive.google.com/file/d/1WCadifzXJvB1oTlASAHGlVCZmUvOR21e/view?usp=drive_link)** — 게임 개요, 조작법, 시스템 · 기술 특징, 클래스 다이어그램 · 역할, 개발 정보
- **[📊 프로젝트 소개 PPT (Google Drive)](https://drive.google.com/file/d/1pZESwx44rkRMs0tpdHm6NulRZuBwGQ7u/view?usp=drive_link)** — 핵심 구현과 설계를 요약한 발표 자료

---

## 🖼️ 스크린샷

| 플레이어 액션 전투 | 타워 배치 & 업그레이드 |
| :---: | :---: |
| ![액션 전투](docs/screenshots/Player_Fire_EX.png) | ![타워 배치](docs/screenshots/Tower_Deploy_And_Upgarde_UI.png) |
| **상점 (3탭 성장)** | **벽 업그레이드** |
| ![상점](docs/screenshots/Shop_UI.png) | ![벽 업그레이드](docs/screenshots/Wall_Upgrade_EX.png) |

---

## 🛡️ 방어 수단 — 타워 3종과 벽

모든 방어물은 **데이터로 정의**되며, 티어 업그레이드와 상점 연구로 강화·해금됩니다. 발사 방식은 `E_FireType` 열거형으로 분기됩니다.

| 머신건 (Homing) | 캐논 (Missile) | 스나이퍼 (Laser) |
| :---: | :---: | :---: |
| ![머신건](docs/screenshots/MachineGun_Fire_EX.png) | ![캐논](docs/screenshots/Canon_Fire_EX.png) | ![스나이퍼](docs/screenshots/Laser_Fire_EX.png) |
| 유도 투사체 연사 | 포물선 곡사 + 범위 폭발<br>벽 너머 포격 | 즉발(hitscan) 명중<br>레이저 빔 연출 |

> **벽** — 적의 진격을 물리적으로 막고 지연시키는 방어물. `BP_Wall`이 `BP_Tower`를 상속해 타워 시스템에 통합되어 있습니다.

---

## 👾 적 4종과 보스 2종

<div align="center">

![보스](docs/screenshots/Two_Boss_EX.png)

</div>

| 일반 적 | 특성 |
| :--- | :--- |
| **Grunt** | 표준 능력치 기본 근접, 물량으로 압박 |
| **Tank** | 느리지만 높은 체력의 탱커형 |
| **Rusher** | 벽을 유령처럼 통과하는 관통 돌격형 (Vehicle 콜리전 채널) |
| **Ranged** | 투사체로 원거리 견제 |

**보스** — 근접 보스(지속 피해 독 장판) · 거미 보스(직선 투사체 + 부채꼴 거미줄 둔화). 일반 적 4종은 **별도 클래스 없이 `DT_Enemies` 데이터로만 구분**됩니다.

---

## 🛠️ 기술적 특징 & 구현

### ① 데이터 주도 아키텍처

단일 `Blueprint` + `Struct` + `DataTable` 조합으로, 런타임에 `InitFromRow`가 데이터 행을 읽어 스탯·외형·동작을 구성합니다. **새 타워·적·웨이브 = 데이터 행 추가만으로 완료**됩니다.

![데이터 주도 구현](docs/screenshots/Core_Implementation_Data_driven_EX.png)

### ② 무한 웨이브 & 우선순위 AI

`Wave 1~10`은 수동 설계로 초반 난이도를 통제하고, `11~`은 절차적으로 생성해 무한 확장합니다. 적은 유형별 `TargetPriority`로 타겟을 선택하며, `BPI_Targetable` 인터페이스의 표면거리 판정(`GetClosestSurfacePoint`)으로 큰 적·긴 벽도 정확히 근접 판정합니다.

![무한 웨이브 & AI](docs/screenshots/Infinite_Wave_AI_Design_EX.png)

### ③ 그 외 구현 디테일

- **NavMesh 비카빙 벽** — '직진하다 막히면 부순다' 방식으로 길찾기 없이 명료한 AI 구현
- **관통 채널** — Vehicle 콜리전 채널로 Rusher만 벽 통과
- **Animation Notify** — 타격 프레임에 공격 판정을 심어 모션과 데미지 동기화
- **3D 공간 사운드** — 거리·방향 감쇠 + 리스너를 플레이어로 오버라이드
- **타워 조준 연출** — 360° 스캔 후 RInterp로 부드러운 조준

---

## 🧩 클래스 구조 — 상속 + 데이터 주도 3계층

소수의 상속 클래스가 다수의 콘텐츠를 데이터로 처리하는 구조입니다. **관리 계층**이 흐름을 통제하고, **게임플레이 액터**가 데이터를 읽어 동작하며, **데이터 계층**이 이를 뒷받침합니다.

![클래스 구조도](docs/screenshots/Galaxy_Defender_Class_Structure_Diagram.png)

---

## 🐛 트러블슈팅 (구조적 문제 해결)

<details>
<summary><b>1. 벽/타워 상속으로 인한 캐스팅 매칭 버그 — Tank가 벽을 무시</b></summary>

<br>

벽을 타워 시스템에 통합하려 `BP_Wall`을 `BP_Tower`에서 상속시켰더니, 적 AI의 `Cast To BP_Tower`가 **자식인 벽에도 매칭**되어 Tank가 벽을 타워로만 인식하고 무시하는 문제가 발생했습니다.

- **원인:** 상속 구조상 자식(`BP_Wall`)이 부모(`BP_Tower`) 캐스팅에 전부 걸림
- **해결:** 타겟 판별에서 `BP_Wall`을 **먼저** 캐스팅한 뒤 `BP_Tower`를 확인하도록 순서 조정
- **장기 대안:** `Category` 필드 도입을 설계 문서에 정리 (순서 의존 회피)

</details>

<details>
<summary><b>2. UI 초기화 순서 버그 — WBP_HUD가 None</b></summary>

<br>

게임 시작 전 도움말(Help)을 먼저 열면 `BP_Core`의 `WBP_HUD` 참조가 `None`이 되던 문제가 있었습니다.

- **해결:** HUD를 `BeginPlay`에서 미리 **생성·변수 할당**(참조는 즉시 유효)하되, 화면 표시(`Add to Viewport`)만 시작 버튼 시점으로 **지연**

</details>

---

## 📦 개발 정보

| 항목 | 내용 |
| :--- | :--- |
| 엔진 | Unreal Engine 5 (Blueprint) |
| 장르 | 탑다운 액션 타워디펜스 / 무한 웨이브 생존 |
| 플랫폼 | PC (Windows) |
| 개발 형태 | 1인 개발 (Solo Project) |
| 핵심 설계 | 데이터 주도 · 상속 확장 · 인터페이스 · 관심사 분리 |

<div align="center">

<br>

**김성태 (KimSungTae)**

**[▶️ 플레이 영상](https://youtu.be/rb2Tf1CdQXQ)** &nbsp;·&nbsp;
**[⬇️ 다운로드](https://github.com/KST-KimSungTae/TD_Action_PVE/releases/tag/v0.02.0000)**

</div>
