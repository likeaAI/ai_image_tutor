#  AI Image Tutor (AI Prompt Studio Pro 2.0)

> **애플 감성 프리미엄 디자인(macOS Tahoe / iOS 18 / VisionOS) 기반의 전문가용 한-영 프롬프트 해부학 학습 및 생성 스튜디오**  
> Google Gemini 3.1 Flash-Lite AI 실시간 엔진 탑재 · 100대 황금 레시피 라이브러리 수록 · 비파괴적 어휘 조합기 내장

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-Single--File-orange.svg)]()
[![Apple UI](https://img.shields.io/badge/Design-Apple%20Pro%20Liquid%20Glass-black.svg)]()
[![Gemini 3.1](https://img.shields.io/badge/AI%20Engine-Gemini%203.1%20Flash--Lite-blueviolet.svg)]()

---

## ✨ 핵심 기능 (Key Features)

### 1.  애플 프로 감성 프리미엄 인터페이스 (Apple Pro Studio UI)
* **리퀴드 글래스 (Liquid Frosted Glass)**: `backdrop-filter: blur(28px)` 기반의 깊이 있는 딥 블랙(`--apple-bg: #000000`) 및 1px 초미세 헤어라인 보더.
* **macOS 윈도우 신호등 & 캡슐 세그먼트 컨트롤러**: 🔴 🟡 🟢 신호등 버튼 및 애플 스타일의 알약형(Capsule) 모드 스위처 탑재.
* **iOS 다이내믹 아일랜드 감성의 플로팅 토스트**: 프롬프트 복사 및 연출 추가 시 화면 하단 중앙에서 우아하게 떠오르는 캡슐 팝업.

### 2. 🏆 나노바나나 Pro 검증된 황금 레시피 100선 (100 Golden Recipes)
* **9대 전문 카테고리 전수 수록**:
  * 📸 인물/하이패션 (15선)
  * 🎬 영화/SF 시네마 (15선)
  * 🎨 애니/서브컬처 (15선)
  * 🖼️ 명화/현대아트 (10선)
  * ⌚ 제품/테크 (10선)
  * 🍣 음식/F&B 미식 (10선)
  * 🏛️ 건축/인테리어 공간 (10선)
  * 🌿 자연/야생생태 (10선)
  * 🤖 토이/메카닉 디오라마 (5선)
* 실시간 키워드 검색 및 원클릭 한-영 해부학 학습 & 세팅 지원.

### 3. 🎯 실시간 의미론적 유사 레시피 매칭 & 전달 (Semantic Similar Recipe Matcher)
* 사용자가 입력창에 한글 아이디어를 작성하면, 100대 황금 레시피 중 문맥과 분위기가 가장 유사한 **TOP 3 명작을 실시간 발굴**.
* 전문가가 실제로 사용한 카메라 광학, 조명 연출, 피부 질감 구문을 눈앞에 카드로 전달.
* `[+ 광학 연출 가져오기]`, `[+ 조명 연출 가져오기]` 원클릭으로 내 프롬프트에 비파괴적 결합 가능.

### 4. 🧩 한-영 형태소 어휘 조합기 (Bilingual Morphological Assembler)
* 사용자가 작성한 한글 단어(인물, 직업, 의상, 소품, 행동, 장소, 분위기)를 단 하나도 삭제하지 않고 영문으로 1:1 정밀 번역 결합.
* **3-Way 뷰 모드**:
  1. `🎓 1. 한-영 해설`: 피사체 / 광학 / 조명 / 질감 4대 기둥별 1:1 대조 학습
  2. `📄 2. 내 원본 직역본`: 내가 쓴 단어들만 100% 충실하게 결합된 직역 영문본
  3. `✨ 3. 전문가 제안 완성본`: 내 원본 + 전문가 광학·조명·질감 풀스펙 마스터피스

### 5. 🤖 Google Gemini 3.1 Flash-Lite AI 실시간 연동
* 최신 경량 고속 모델인 `gemini-3.1-flash-lite` 1순위 호출 (폴백 체인 완비).
* 사용자의 한글 의도를 문맥까지 깊이 이해하여 전문가용 나노바나나 Pro 4대 기둥으로 자동 승격.

---

## 🚀 빠른 시작 (Getting Started)

본 프로젝트는 별도의 빌드 과정(Webpack, Vite 등)이나 Node.js 서버 없이, **단일 HTML 파일 자체로 완벽하게 구동되는 무설치 독립형 웹 애플리케이션**입니다.

### 1. 실행 방법
* `index.html` (또는 `AI_통합_프롬프트_스튜디오.html`) 파일을 더블 클릭하여 크롬, 엣지, 사파리 등의 브라우저에서 바로 실행합니다.

### 2. GitHub Pages 배포
* 본 저장소의 **Settings** ➔ **Pages**로 이동합니다.
* **Branch**를 `main`, 폴더를 `/(root)`로 지정하고 **Save**를 누르면, 즉시 나만의 프롬프트 스튜디오 웹사이트가 배포됩니다!
* 접속 주소 예시: `https://likeaAI.github.io/ai_image_tutor/`

---

## 📂 파일 구조 (Repository Structure)

```
ai_image_tutor/
├── index.html                     # 메인 단일 실행 웹 애플리케이션 (GitHub Pages 지원)
├── AI_통합_프롬프트_스튜디오.html  # 오프라인 한국어 명칭 미러 파일
├── golden_recipes_100.json        # 100대 황금 레시피 4대 해부학 데이터셋
├── README.md                      # 프로젝트 소개 및 가이드 문서
└── .gitignore                     # Git 제외 설정 파일
```

---

## 📄 라이선스 (License)

This project is licensed under the MIT License.
