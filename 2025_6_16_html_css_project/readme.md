# 프로그래밍 언어 정보 웹사이트 (Programming Language Information Website)

## 🚀 프로젝트 소개
이 프로젝트는 HTML과 CSS만을 사용하여 프로그래밍 언어의 종류, 특징, 순위 및 학습 가이드라인 등 다양한 정보를 제공하는 웹사이트입니다. 코딩 입문자들이 프로그래밍 언어 선택에 도움을 받을 수 있도록 정보를 시각적이고 구조적으로 정리하여 보여줍니다.

## ✨ 주요 기능
* **프로그래밍 언어 소개:** 프로그래밍의 정의, 코딩과의 차이점 등 기본적인 개념을 설명합니다.
* **언어별 순위:** TIOBE 인덱스를 기반으로 한 프로그래밍 언어의 최신 순위 정보를 제공합니다.
* **언어별 특징:** 파이썬, C언어, 자바 등 주요 프로그래밍 언어의 특징을 소개합니다.
* **목표별 언어 추천:** 웹 개발, 게임 개발, 모바일 앱 개발 등 목표에 따른 프로그래밍 언어 추천 가이드를 제공합니다.
* **학습 순서 추천:** 전공자와 비전공자를 위한 프로그래밍 학습 순서를 제안합니다.
* **외부 자료 연동:** 관련 Wikipedia, 블로그, 유튜브 강의 등의 외부 자료를 `iframe`을 통해 웹페이지 내에서 바로 확인할 수 있습니다.
* **다국어 지원 (한국어/영어):** 웹페이지 상단에서 한국어 버전(`index.html`)과 영어 버전(`eng.html`)으로 전환할 수 있도록 링크를 제공합니다.

## 🛠️ 사용 기술
* **HTML5:** 웹페이지의 구조와 콘텐츠를 정의합니다.
    * 시맨틱 태그 ( `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>` )를 활용하여 의미 있는 문서 구조를 구축했습니다.
    * `iframe`을 통해 외부 콘텐츠를 임베드했습니다.
* **CSS3:** 웹페이지의 시각적인 스타일을 담당합니다.
    * **Flexbox:** 내비게이션 바와 같은 요소들의 정렬 및 배치를 위해 사용했습니다.
    * **중앙 정렬:** `margin: 0 auto;`를 사용하여 주요 블록 요소들을 가로 중앙에 배치했습니다.
    * **카드형 레이아웃:** `box-shadow`와 `border-radius`를 사용하여 `article` 섹션을 깔끔한 카드 형태로 디자인했습니다.
    * **반응형을 넣어 768px 이하의 페이지에서 표현되는 별도에 레이아웃을 넣었습니다.

## 💡 배운 점
이 프로젝트를 통해 다음과 같은 HTML/CSS 웹 개발의 핵심 역량을 강화할 수 있었습니다:
* HTML 시맨틱 태그를 활용한 웹 표준 준수 및 구조화의 중요성
* CSS Flexbox를 이용한 효율적인 레이아웃 설계 방법
* `margin: auto;`를 활용한 블록 요소의 가로 중앙 정렬 기법
* `box-shadow`, `border-radius` 등 CSS 속성을 이용한 시각적 디자인 개선
* `iframe`을 통한 외부 콘텐츠 통합 및 활용
* 다국어 웹페이지를 위한 기본적인 구조 설계 (HTML 파일 분리)

## 📂 프로젝트 파일 구성

```text
.
├── index.html       # 한국어 버전 메인 페이지
├── eng.html         # 영어 버전 메인 페이지
├── styles.css       # 모든 페이지에 적용되는 CSS 스타일시트
├── media/           # 이미지 및 미디어 파일 폴더
│   ├── sign.PNG     # 로고 이미지 (한국어 버전)
│   ├── signE.png    # 로고 이미지 (영어 버전 - 사용되지 않음)
│   ├── dit.png      # DIT 로고 (사용되지 않음)
│   └── tiobe.PNG    # TIOBE 인덱스 이미지
└── README.md        # 현재 파일
```

## 👨‍💻 개발자
이현규

## 🗓️ 개발 날짜
2025년 6월 16일
