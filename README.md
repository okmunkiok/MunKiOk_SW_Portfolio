# 문기옥 소프트웨어 포트폴리오

* 재미있어 보이는 것은 뭐든지 끝까지 프로그래밍 해내는 문기옥입니다.
* (재미있어 보이지 않아도 해야 하는 것 역시 끝까지 프로그래밍 해냅니다)
* 하드웨어와 가까운 임베디드 시스템부터 웹, 모바일, 데이터 분석에 이르기까지 다양한 프로젝트를 통해 복잡한 문제를 해결하고, 실제 동작하는 시스템을 구축하는 경험을 쌓았습니다.

<br>

## 🛠️ 기술 스택 (Tech Stack)

*   **Languages**: C, Python, MATLAB, JavaScript, TypeScript, Java
*   **Frameworks & Libraries**:
    *   **Embedded**: FreeRTOS, ESP-IDF, painlessMesh, Arduino
    *   **Web**: React, Node.js, Slate.js, Zustand, Express
    *   **Data**: Pandas, Selenium, BeautifulSoup, Konlpy
*   **Platforms & Tools**: ESP32, Git, GitHub, Google Apps Script, Android

<br>

## 🚀 프로젝트 (Projects)

---

### 1. 임베디드 시스템: UWB 측위, BLDC 모터 및 로봇 팔 제어
*   **한 줄 요약**: 펌웨어 개발, 실시간 제어, 무선 통신 등 임베디드 시스템의 핵심 역량을 종합적으로 보여주는 3가지 프로젝트 모음입니다.
*   **주요 기술**: `ESP32`, `C++`, `FreeRTOS`, `UWB`, `WiFi-Mesh`, `UART`, `BLDC 모터`, `홀 센서`
*   **핵심 역량 및 경험**:
    *   **하드웨어와 SW 통합 능력**: MCU, 통신 모듈, 센서, 모터 등 다양한 하드웨어를 직접 제어하는 펌웨어를 개발하며 임베디드 시스템의 End-to-End 개발 사이클을 경험하였습니다.
    *   **실시간 제어 시스템 설계**: 센서 피드백 기반의 폐쇄 루프(Closed-loop) 제어 시스템과 하드웨어 인터럽트를 활용하여 실시간성과 안정성을 확보하는 능력을 길렀습니다.
    *   **통신 프로토콜 및 네트워크 구현**: DS-TWR, UART, WiFi-Mesh 등 다양한 유무선 통신 방식을 직접 구현하며 분산 제어 시스템과 네트워크 프로그래밍에 대한 이해도를 높였습니다.
*   **[➡️ GitHub 리포지토리 바로가기](https://github.com/okmunkiok/2020WinterPracticeTransition)**

---

### 2. MATLAB 기반 OFDM 음파 통신 시스템
*   **한 줄 요약**: 비가청음파 대역을 이용해 이미지와 텍스트를 전송하는 OFDM 통신 시스템의 송신부와 수신부를 모두 구현한 종합설계 프로젝트입니다.
*   **주요 기술**: `MATLAB`, `Signal Processing`, `Communications Toolbox`, `OFDM`, `QPSK`, `Python 연동`
*   **핵심 역량 및 경험**:
    *   **통신/신호처리 이론의 실용적 적용**: 변복조, 채널 코딩, 동기화, 채널 등화 등 통신 시스템의 핵심 이론을 실제 음향 신호에 적용하며 전공 지식의 응용 능력을 증명하였습니다.
    *   **End-to-End 시스템 설계 및 구현**: 아이디어 구상부터 전체 통신 파이프라인을 직접 설계하고 MATLAB 코드로 완성하며 복잡한 시스템을 구축하는 개발 역량을 보여주었습니다.
    *   **다양한 기술의 융합 능력**: MATLAB 환경에서 Python의 OCR 라이브러리를 연동하여, 주어진 환경에 얽매이지 않고 최적의 도구를 통합해 문제를 해결하는 융합적 사고를 경험하였습니다.
*   **[➡️ GitHub 리포지토리 바로가기](https://github.com/okmunkiok/KECE404_24_2)**

---

### 3. BreinSinc: 계층적 구조의 웹 기반 노트 애플리케이션
*   **한 줄 요약**: 복잡한 지식을 체계적으로 정리하고 학습하기 위해 React와 Slate.js 기반으로 개발한 개인 맞춤형 웹 노트 앱입니다.
*   **주요 기술**: `React`, `TypeScript`, `Slate.js`, `Zustand`, `Google Drive API`
*   **핵심 역량 및 경험**:
    *   **모던 웹 프론트엔드 개발**: React, TypeScript, Zustand 등 최신 기술 스택을 활용하여 SPA(Single Page Application)를 구축하고, 복잡한 전역 상태를 효율적으로 관리하였습니다.
    *   **창의적인 아키텍처 설계**: 별도 백엔드 서버 없이 Google Drive API를 파일 기반 DB로 활용하는 독창적인 Serverless 아키텍처를 구현하여 비용 효율성과 데이터 소유권을 모두 확보하였습니다.
    *   **개발 생산성 향상**: 자체 로깅/디버깅 시스템을 구축하여 개발 과정의 문제를 선제적으로 추적하고 해결하는 등 안정적인 개발 환경을 만드는 데 기여하였습니다.
*   **[➡️ GitHub 리포지토리 바로가기](https://github.com/okmunkiok/BreinSinc/tree/archive-main)**

---

### 4. DCinside 웹 크롤러 & 데이터 분석기
*   **한 줄 요약**: Python을 이용해 커뮤니티 사이트의 대용량 게시글/댓글 데이터를 수집하고, 자연어 처리로 토픽을 분석/시각화하는 프로젝트입니다.
*   **주요 기술**: `Python`, `BeautifulSoup`, `Selenium`, `multiprocessing`, `pandas`, `konlpy`
*   **핵심 역량 및 경험**:
    *   **대용량 데이터 수집 및 처리**: 정적/동적 크롤링을 결합한 하이브리드 전략과 병렬 처리(`multiprocessing`)를 적용하여 수십만 건의 데이터를 안정적이고 빠르게 수집하였습니다.
    *   **SW 공학적 설계**: 크롤링 로직을 설치 가능한 패키지 형태로 모듈화하고, 설정 파일 분리, 예외 처리 등 코드의 재사용성과 유지보수성을 고려하여 설계하였습니다.
    *   **데이터 가공 및 분석**: 수집한 텍스트 데이터를 자연어 처리 라이브러리로 분석하고 워드 클라우드로 시각화하며, 원시 데이터로부터 의미 있는 가치를 창출하는 경험을 하였습니다.
*   **[➡️ GitHub 리포지토리 바로가기](https://github.com/okmunkiok/DCinsideRead)**

---

### 5. 자동차 번호판 인식 안드로이드 앱
*   **한 줄 요약**: 외부 라이브러리 의존을 최소화하고, 영상 처리의 핵심 알고리즘을 Java로 직접 구현한 자동차 번호판 인식(ANPR) 안드로이드 앱입니다.
*   **주요 기술**: `Android`, `Java`, `Digital Image Processing`, `Rule-based OCR`
*   **핵심 역량 및 경험**:
    *   **알고리즘 직접 구현 능력**: 이진화, 형태학적 연산, 문자 분할(Segmentation) 등 핵심 영상 처리 알고리즘을 픽셀 단위 조작으로 직접 구현하며 SW 개발의 기본기를 다졌습니다.
    *   **논리적 문제 해결**: 머신러닝 모델 없이, 각 문자의 기하학적/위상적 특징을 분석하여 규칙 기반(Rule-based) OCR 엔진을 설계하며 복잡한 문제를 논리적으로 해결하는 능력을 보였습니다.
*   **[➡️ GitHub 리포지토리 바로가기](https://github.com/okmunkiok/Embedded_System_Design_Project)**

---

### 6. 구글 앱스크립트를 활용한 동아리 일지 작성 자동화
*   **한 줄 요약**: Google Apps Script를 활용하여 반복적인 수기 데이터 입력 업무를 자동화하고, 동아리 운영 효율을 개선한 생산성 도구입니다.
*   **주요 기술**: `Google Apps Script`, `JavaScript`, `HTML Service`, `SpreadsheetApp API`
*   **핵심 역량 및 경험**:
    *   **업무 프로세스 분석 및 개선**: 기존의 비효율적인 업무 방식을 파악하고, 이를 해결하기 위한 자동화 시스템을 직접 기획, 개발, 배포하여 실질적인 생산성 향상을 이끌었습니다.
    *   **사용자 중심적 사고**: 복잡한 스프레드시트 대신 친숙한 웹 UI를 제공하고, 데이터 유효성 검사를 통해 사용자의 실수를 방지하는 등 사용자 편의성을 최우선으로 고려하여 설계하였습니다.
*   **[➡️ GitHub 리포지토리 바로가기](https://github.com/okmunkiok/KUMAC)**
