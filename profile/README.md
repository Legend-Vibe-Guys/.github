# 🏆 [KIT 바이브코딩 공모전] 👋 바이브가이즈

---

## 📝 1. 프로젝트 개요

* **✨ 프로젝트명:** 아이케어 AI - 키즈노트 : AI 기반 영유아 스마트 리포트 솔루션
* **📢 슬로건:** "교사에게는 여유를, 부모에게는 확신을."
* **💡 핵심 가치:** 파편화된 영유아 관찰 기록을 **🤖 AI가 통합 분석**하여 객관적인 성장 지표를 제공하고, 보육 현장의 **행정 업무 혁신**을 주도함.

---

## 🚀 2. 기획 배경 및 목적

### 🚨 2.1. 시장의 문제점 (Pain Points)

1.  **✍️ 교사의 기록 부담:** 현행 보육 지침상 필수적인 아동 관찰 기록은 교사 1인당 담당 아동 수가 많아질수록 기하급수적인 업무 부하를 초래함.
2.  **🗣️ 리포트의 주관성:** 수기 혹은 단순 텍스트 위주의 알림장은 교사의 컨디션이나 주관에 따라 내용의 질이 달라지며, 전문적인 발달 분석을 담기엔 한계가 있음.
3.  **🗂️ 소통 채널의 산재:** 출결 관리, 공지사항, 사진 공유, 관찰 기록이 각각 분산되어 있어 통합적인 데이터 관리가 불가능함.

### 🎯 2.2. 해결 방안 및 목적

* **🤖 AI 자동화:** `Gemini 2.0 Flash` 모델을 활용하여 한 달간의 관찰 데이터를 단 몇 초 만에 전문적인 발달 리포트로 변환.
* **🔗 데이터 통합:** 출결, 일정, 관찰 기록을 하나의 플랫폼으로 통합하여 관리 효율성 증대.
* **🤝 신뢰도 향상:** 데이터 기반의 객관적인 지표(그래프 및 분석 결과)를 제공하여 부모와 기관 간의 투명한 소통 체계 구축.

---

## 👥 3. 타겟 사용자 및 유저 시나리오

### 👤 3.1. 타겟 사용자

* **Primary:** 👩‍🏫 **어린이집 및 유치원 교사** (행정 업무 단축 필요군)
* **Secondary:** 👨‍👩‍👧 **영유아 자녀를 둔 학부모** (아이의 원내 생활 및 성장 데이터 요구군)

### 🎬 3.2. 핵심 유저 시나리오

1.  **👩‍🏫 교사:** 일과 중 특이사항 발생 시 모바일 앱의 **'퀵 메모'** 기능을 통해 짧은 텍스트와 사진을 즉시 등록.
2.  **⚙️ 시스템:** 등록된 데이터를 **Firebase Firestore**에 실시간 저장 및 카테고리화.
3.  **👩‍🏫 교사:** 월말, 리포트 생성 버튼 클릭. AI가 그동안의 메모를 분석해 초안 작성. 교사는 검토 후 확정.
4.  **👨‍👩‍👧 학부모:** 푸시 알림을 통해 전달된 자녀의 **성장 대시보드**와 **AI 분석 리포트**를 확인.

---

## ⭐ 4. 주요 기능 (Core Features)

| 카테고리 | 주요 기능 | 상세 설명 |
| :--- | :--- | :--- |
| **🤖 관찰/분석** | **📝 AI 스마트 리포트** | 관찰 기록을 분석하여 사회성, 활동성 등 5개 영역별 분석 및 총평 자동 생성 |
| | **📸 퀵 메모 (Quick Memo)** | 텍스트와 Cloudinary 기반 사진 업로드를 통한 실시간 현장 기록 기능 |
| **📋 행정/관리** | **📅 스마트 출결 시스템** | 학생별 실시간 등/하원 상태 관리 및 대시보드 시각화 |
| | **📢 공지 및 일정 관리** | 알림장 형태의 공지사항 및 학사 일정 공유 기능 |
| **📊 데이터 시각화** | **📈 성장 그래프** | 발달 영역별 점수를 레이더 차트 등으로 시각화하여 부모에게 제공 |
| **🔐 회원 체계** | **🔑 역할 기반 권한** | Teacher/Parent 역할 분리를 통한 맞춤형 UI/UX 및 데이터 접근 제어 |

---

## 🛠️ 5. 시스템 아키텍처 및 기술 스택

### 💻 5.1. Tech Stack

* **Frontend:** <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=flat-square&logo=Tailwind CSS&logoColor=white"/> <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=Vite&logoColor=white"/>
* **Backend:** <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white"/> <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=Express&logoColor=white"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white"/>
* **Database:** <img src="https://img.shields.io/badge/Firebase Firestore-FFCA28?style=flat-square&logo=Firebase&logoColor=black"/>
* **Authentication:** <img src="https://img.shields.io/badge/Firebase Auth-FFCA28?style=flat-square&logo=Firebase&logoColor=black"/>
* **Media:** <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=Cloudinary&logoColor=white"/>
* **AI Engine:** <img src="https://img.shields.io/badge/Gemini-8E75FF?style=flat-square&logo=googlegemini&logoColor=white"/>

### 🔄 5.2. Data Flow

1.  **📱 Client:** 기록 데이터 전송 (Auth Token 포함)
2.  **🖥️ Express API Server:** 미들웨어(Auth, Validator)를 거쳐 요청 검증
3.  **⚙️ Service Layer:** Firestore DB 연동 및 비즈니스 로직 수행
4.  **🤖 AI Service:** Gemini API 호출을 통한 리포트 생성 (Structured JSON 형식 활용)
5.  **📱 Client:** 최종 결과 수신 및 UI 렌더링 (Context API 기반 상태 관리)

---

## 🧠 6. AI 활용 및 최적화 전략

### 🗣️ 6.1. 프롬프트 엔지니어링

* **👤 System Persona:** "유아발달 전문가"로서의 전문적 어조와 "따뜻한 교육자"로서의 감성적 어조를 융합.
* **📋 Output Constraint:** 데이터의 재현성을 위해 반드시 지정된 **JSON 구조**로 응답하도록 설계하여 프론트엔드 그래프와의 호환성 확보.

### ⏱️ 6.2. 운영 효율화

* **🔍 Context Window 최적화:** 한 달간의 모든 메모 중 핵심 키워드를 추출하거나, 주차별 요약본을 먼저 생성하여 최종 리포트의 정확도를 높이고 토큰 낭비를 방지.

---

## 🎁 7. 기대 효과 및 비즈니스 모델

### 📈 7.1. 기대 효과

* **💖 사회적 가치:** 보육 교사의 업무 환경 개선을 통한 아동 방임 방지 및 교육 서비스 질 향상.
* **🔬 기술적 가치:** 파편화된 비정형 데이터를 정형화된 발달 지표로 전환하는 데이터 파이프라인 구축.

### 🚀 7.2. 향후 확장성

* **🛍️ 맞춤형 교육 상품 추천:** AI 리포트 결과에 따라 부족한 발달 영역을 보완할 수 있는 교구 및 도서 큐레이션 서비스 연계.
* **👁️ 멀티모달 심화:** AI가 활동 사진 속 아이의 표정을 분석해 정서 상태를 추가적으로 리포팅하는 기능 확장.

---

## 👥 팀원 정보
| 이름   | GitHub                                       |
| ------ | -------------------------------------------- |
| 이규현 | [@leekyuhyun](https://github.com/leekyuhyun) |
| 김선빈 | [@toran1678](https://github.com/toran1678)   |
| 정현구 | [@lhjjhg](https://github.com/lhjjhg)         |
| 김민한 | [@minari0v0](https://github.com/minari0v0) |
