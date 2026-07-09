# macOS Sonoma Finder Tistory Skin

Version: 1.0.0 (Development)

---

# Goal

본 프로젝트는 티스토리에서 실제 운영 가능한 macOS Sonoma Finder 스타일 스킨을 제작하는 것을 목표로 한다.

다음 사항을 반드시 만족한다.

- 티스토리 공식 치환자만 사용
- Handlebars 미사용
- HTML5 Semantic
- CSS3
- ES6+
- Responsive
- Dark Mode
- Cover 지원
- 업로드 오류 없음

---

# Design Philosophy

Apple Human Interface Guidelines를 참고하여 Finder의 사용성을 웹으로 재해석한다.

단순히 Finder처럼 보이는 UI가 아니라 실제 Finder의 탐색 경험을 목표로 한다.

---

# Layout

Window

├── Toolbar

├── Sidebar

├── Content

│ ├── Breadcrumb

│ ├── Cover

│ ├── Article List

│ ├── Article

│ ├── Comment

│ └── Guestbook

└── Status Bar

---

# Component

Toolbar

Sidebar

Breadcrumb

Content

Grid View

List View

Article Card

Article

Comment

Guestbook

Footer

Modal

Search

Pagination

Dark Mode

---

# CSS Architecture

CSS Variables

Layout

Component

Utility

Responsive

Dark Mode

Animation

---

# JavaScript Architecture

App

Theme

View

Navigation

Search

Storage

Animation

Accessibility

---

# Folder Structure

assets/

css/

js/

icons/

images/

fonts/

docs/

skin.html

style.css

script.js

index.xml

README.md

---

# Coding Rules

- Semantic HTML
- BEM 스타일 네이밍을 참고하되 과도하게 사용하지 않는다.
- CSS Variables 적극 사용
- JavaScript ES6+
- Inline JavaScript 금지
- Inline CSS 금지
- 접근성 고려
- 중복 코드 최소화

---

# Development Order

1. Architecture

2. Layout

3. Styling

4. Interaction

5. Tistory Integration

6. Optimization

7. Release
