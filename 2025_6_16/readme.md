# 🚀 웹 개발 심화 CSS 학습 및 실습 (Web Dev Advanced CSS Learning & Practice)

## 🗓️ 날짜: 2025년 6월 16일

---

### 🌟 개요
이 프로젝트는 HTML/CSS 기반 웹 개발의 심화 과정으로, 웹 페이지의 시각적인 표현과 사용자 인터랙션을 개선하기 위한 다양한 CSS 속성들을 학습하고 실제 예제를 통해 적용한 결과를 담고 있습니다. 특히 `form` 요소 스타일링, `animation`과 `transition` 효과, 그리고 `visibility`, `overflow`, `list-style`, `table` 꾸미기 등 폭넓은 CSS 기술을 다루었습니다.

---

### 📚 학습 내용 및 적용

1.  **폼 (Form) 요소 스타일링**
    * **학습 내용:** `input` (type `text`, `email`, `submit`), `textarea`, `label`, `span` 등 폼 관련 요소들을 CSS로 스타일링하는 방법을 익혔습니다. `display: block;`, `display: inline-block;`, `text-align: right;` 등을 활용하여 레이블과 입력 필드의 정렬을 제어했습니다.
    * **적용:** `input:hover`, `textarea:hover`와 같은 가상 클래스를 사용하여 마우스 오버 시 배경색이 변하는 효과를 주었으며, `input:focus` 시 글자 크기를 조절하여 사용자 인터랙션을 개선했습니다.
    * **관련 파일:** `input_type_text.html`

2.  **애니메이션 (Animation) 및 전환 (Transition)**
    * **학습 내용:** CSS `@keyframes` 규칙을 사용하여 복잡한 애니메이션을 정의하고, `animation-name`, `animation-duration`, `animation-iteration-count` 등의 속성을 통해 애니메이션을 제어하는 방법을 배웠습니다. 또한, `transition` 속성을 사용하여 요소의 특정 속성(예: `font-size`)이 변화할 때 부드러운 전환 효과를 주는 방법을 익혔습니다.
    * **적용:**
        * `animation.html`에서는 텍스트 크기가 주기적으로 변하는 애니메이션 효과를 구현했습니다.
        * `animation_1.html`에서는 텍스트에 마우스를 올렸을 때 글자 크기가 부드럽게 커지는 전환 효과를 적용했습니다.
    * **관련 파일:** `animation.html`, `animation_1.html`

3.  **레이아웃 및 시각적 제어 CSS 속성 (복습 및 심화)**
    * **학습 내용:**
        * **`visibility` 프로퍼티:** 요소를 보일지(`visible`) 숨길지(`hidden`, `collapse`) 결정하여 웹 페이지 레이아웃에 영향을 주지 않고 요소를 숨기는 방법을 학습했습니다.
        * **`overflow` 프로퍼티:** 콘텐츠가 요소의 경계를 넘어설 때(`scroll`, `hidden`, `visible`, `auto`) 어떻게 처리할지 제어하는 방법을 익혔습니다.
        * **리스트 스타일링 (`list-style`, `list-style-type`, `list-style-image`, `list-style-position`):** `<ul>`, `<li>` 등의 리스트 요소를 꾸미는 다양한 방법을 배웠습니다. (`05_latest.html`의 목차 `<ul>` 및 `styles.css`의 `header nav ul li` 등에서 리스트 스타일 초기화를 볼 수 있습니다).
        * **표(Table) 꾸미기:** `border-collapse: collapse;`를 사용하여 표의 테두리를 합치고, `<td>`의 패딩, 텍스트 정렬, 배경색 등을 조절하여 표의 가독성을 높이는 방법을 학습했습니다. (`05_latest.html`의 샘플 테이블에서 표 꾸미기 적용을 확인할 수 있습니다.).
    * **적용:**
        * `05_latest.html`에서 스마트폰 관련 정보를 제공하며, 테이블을 사용하여 정보를 깔끔하게 정리했습니다.
        * `survey.html`에서는 설문지 폼을 구성하며, `survey.css`를 통해 폼, 헤더, 푸터 등의 기본적인 레이아웃 및 색상 스타일링을 적용했습니다.

---

### 🎯 결론
이번 학습을 통해 CSS의 기본적인 속성들을 넘어, `form` 요소 스타일링, 동적인 웹 페이지를 위한 `animation`과 `transition` 효과, 그리고 `visibility`, `overflow`, 리스트, 테이블 등 다양한 요소를 세밀하게 제어하는 방법을 익혔습니다. 여러 실습 파일을 통해 각 속성의 기능과 활용법을 명확히 이해할 수 있었으며, 이는 **더욱 풍부하고 반응성 있는 웹 페이지를 구현하는 데 큰 도움이 될 것**입니다. 앞으로도 지속적으로 학습하며 **더 나은 웹 개발자**가 되도록 노력하겠습니다.

---

감사합니다! 😊
