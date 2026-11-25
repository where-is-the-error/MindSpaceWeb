<div align="center">

# 🧠 MindSpace Web

**뇌파·안면 표정 분석으로 감정을 인식하는 맞춤형 정신건강 케어 플랫폼 「MindSpace」 소개 웹사이트**

🏆 2025 동양미래EXPO 졸업작품전시회 장려상 · 팀 **MARS** (11인)

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)
![React Router](https://img.shields.io/badge/React_Router-7-CA4245?logo=reactrouter&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

</div>

---

## 📌 프로젝트 소개

MindSpace는 뇌파와 안면 표정으로 사용자의 감정 상태를 측정하고, 그에 맞는 VR 심리치료 게임
(「화풀고 가실게요」, 「멍하니, 불처럼」, 「조용히 함께 살아간다」)을 추천하는 플랫폼입니다.
이 레포는 서비스를 소개하는 **랜딩 웹사이트**이며, 웹 기능과 디자인을 맡아 만들었습니다.

## ✨ 주요 기능

- **히어로 · 기능 소개 섹션**: 심리치료 게임 3종과 서비스 콘셉트를 소개
- **자가진단 설문 팝업**: 불안(BAI)·우울(BDI)·스트레스(PSS) 척도 문항에 답하면 점수를 계산하고 수준을 해석해서 보여 줌
- **시스템 구조도**: 감정 측정 → 데이터 저장 → 맞춤 콘텐츠 추천 흐름을 시각화
- **소개 영상 · 뉴스 · 팀 소개 · FAQ**: 아코디언 FAQ, 팀원 역할 카드
- **스크롤 투 탑**과 반응형 레이아웃

## 👥 팀 MARS

| 역할 | 인원 |
|---|---|
| VR 콘텐츠 제작 | 5 |
| 앱 기능 / 디자인 | 2 |
| **웹 기능 / 디자인** | 2 (김병권 포함) |
| 총괄 · 감정 분석 · DB 통신 | 2 |

## 🧱 구조

```
src/
├─ pages/Main_Page.js
├─ components/   # Header, HeroSection, FeatureSection, SystemFlow, SurveyPopup,
│                #   VideoSection, NewsSection, TeamSection, FaqSection, ScrollToTop
├─ data/         # 설문 문항, 뉴스, 팀 정보
└─ utils/calculateResults.js   # BAI·BDI·PSS 점수 계산·해석
```

## 🚀 실행

```bash
npm install
npm start      # http://localhost:3000
```
