# 🚀 웹 개발 기초 CSS 심화 학습 및 실습 (Form, Animation, Layout Control)

## 🗓️ 날짜: 2025년 6월 16일

---

### 🌟 개요
이 프로젝트는 웹 페이지의 다양한 요소들을 CSS로 제어하고 꾸미는 방법을 학습하고 실습한 내용을 담고 있습니다. 특히 폼(Form) 요소의 스타일링, 동적인 효과를 위한 애니메이션과 전환(Transition), 그리고 레이아웃 및 콘텐츠 표현을 위한 `visibility`, `overflow`, 리스트, 표 꾸미기 등 기본적인 CSS 속성들을 깊이 있게 다루었습니다.

---

### 📚 학습 내용 및 적용

1.  **폼 (Form) 요소 스타일링**
    * **학습 내용:** `input` (텍스트, 이메일, 제출 버튼 타입), `textarea`, `label`, `span` 등 HTML 폼 관련 요소들을 CSS로 스타일링하는 방법을 익혔습니다. `display: block;`, `display: inline-block;`, `text-align: right;` 등을 사용하여 레이블과 입력 필드의 정렬 및 배치를 제어했습니다.
    * **적용:**
        * `input:hover`, `textarea:hover`와 같은 가상 클래스를 사용하여 마우스 오버 시 배경색이 부드럽게 변하는 효과를 주었습니다.
        * `input:focus` 시 글자 크기를 조절하여 사용자 입력 시 시각적인 피드백을 제공했습니다.
    * **관련 파일:** `input_type_text.html`

2.  **애니메이션 (Animation) 및 전환 (Transition)**
    * **학습 내용:**
        * **애니메이션 (`@keyframes`):** CSS `@keyframes` 규칙을 사용하여 요소가 여러 단계에 걸쳐 변하는 복잡한 애니메이션을 정의하고, `animation-name`, `animation-duration`, `animation-iteration-count` 등의 속성으로 애니메이션의 이름, 지속 시간, 반복 횟수 등을 제어하는 방법을 배웠습니다.
        * **전환 (`transition`):** 요소의 특정 속성(예: `font-size`)이 변화할 때, 그 변화가 즉시 일어나는 것이 아니라 지정된 시간 동안 부드럽게 이어지도록 하는 `transition` 속성 사용법을 익혔습니다.
    * **적용:**
        * `animation.html`에서는 텍스트(`<h3>꽝!</h3>`)의 `font-size`가 주기적으로 커졌다 작아지는 무한 반복 애니메이션 효과를 구현했습니다.
        * `animation_1.html`에서는 특정 텍스트(`<span>꽝!</span>`)에 마우스를 올렸을 때 `font-size`가 부드럽게 커지는 전환 효과를 적용했습니다.
    * **관련 파일:** `animation.html`, `animation_1.html`

3.  **기본 레이아웃 및 콘텐츠 제어 (Visibility, Overflow, List, Table)**
    * **학습 내용:**
        * **`visibility` 프로퍼티:** 요소를 시각적으로 숨기거나 보이게 하는 방법을 학습했으며, 이 속성이 요소의 레이아웃 공간 차지 여부에 미치는 영향을 이해했습니다.
        * **`overflow` 프로퍼티:** 컨텐츠가 요소의 경계를 넘어설 때 (`visible`, `hidden`, `scroll`, `auto`) 어떻게 처리할지 제어하는 방법을 익혔습니다.
        * **리스트 스타일링:** `list-style-type` (마커 종류), `list-style-image` (이미지 마커), `list-style-position` (마커 위치) 등 리스트(`<ul>`, `<li>`)의 스타일을 세밀하게 제어하는 다양한 방법을 배웠습니다. (`styles.css`에서 `list-style-type: none;`과 같은 리스트 초기화 예시를 볼 수 있습니다).
        * **표(Table) 꾸미기:** `border-collapse: collapse;`를 사용하여 표 테두리를 합치는 방법을 익히고, `<td>` 등에 패딩, 배경색, 텍스트 정렬 등을 적용하여 표의 가독성과 미려함을 높였습니다. (`05_latest.html`에서 스마트폰 샘플 표가 이 스타일링의 예시입니다).
    * **적용:**
        * `05_latest.html`에서는 스마트폰 관련 정보를 정리하며 테이블을 활용하여 데이터 시각화를 개선했습니다.
        * `survey.html`에서는 설문지 폼의 헤더, 푸터, 그리고 전반적인 폼 영역의 색상 및 크기를 `survey.css`를 통해 기본적으로 스타일링 했습니다.
    * **관련 파일:** `05_latest.html`, `styles.css`, `survey.html`, `survey.css`

---

### 🎯 결론
이번 학습을 통해 CSS의 기본적인 스타일링부터 동적인 효과, 그리고 복잡한 레이아웃 제어에 이르는 다양한 속성들을 폭넓게 다루었습니다. 폼, 애니메이션, 리스트, 표 등 실용적인 웹 요소들에 CSS를 적용하며 각 속성의 기능과 활용법을 명확히 이해할 수 있었으며, 이는 **더욱 풍부하고 인터랙티브한 웹 페이지를 구현하는 데 필요한 실질적인 역량**을 기르는 데 크게 기여했습니다. 앞으로도 지속적으로 학습하며 **더 나은 웹 개발자**가 되도록 노력하겠습니다.

---

감사합니다! 😊
