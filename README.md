# 식물서가 이커머스

초보 식집사의 라이프스타일과 공간의 결을 담아 가장 적합한 식물을 제안하는 이커머스입니다.
깃을 통한 지속적인 버전 관리와 기능 확장을 중심으로 운영합니다.

---

## 프로젝트 개요

식물서가는 사용자의 라이프스타일을 분석해 가장 적합한 식물을 추천하고, 식물 입문자를 위해 식물의 기초 관리법을 모아 제공하는 이커머스입니다.
단순한 식물 판매를 넘어 고객이 일상 속에서 식물을 건강하고 오래 함께할 수 있도록 돕는 든든한 가이드가 되어 줍니다.

---

## 배포 환경

- GitHub 소스 관리

---

## 디자인 시안

**Figma link**

[[UX/UI Design](https://m.site.naver.com/2dhwW)]
[[기획서](https://m.site.naver.com/2dhwa)]

---

## 사용 기술

### 기본
- HTML5
- CSS3
- JavaScript

### 플러그인
- Bootstrap 5
- Swiper

---

## 추후 확장 예정

- 네이버 애널리틱스 연동
- 광고 성과 측정 기능

---

## 깃 커밋 관리 규칙

| 말머리 | 의미 | 사용 예시 |
|-------|------|----------|
| chore | 초기 세팅 및 환경 설정 | chore: 프로젝트 초기 세팅 |
| feat | 새로운 기능 추가 | feat: 뉴스레터 구독 기능 추가 |
| style | UI 및 스타일 수정 | style: 메인 배너 디자인 수정 |
| fix | 오류 수정 | fix: 파비콘 경로 오류 수정 |
| refactor | 코드 구조 개선 | refactor: 섹션 구조 정리 |
| docs | 문서 수정 | docs: README 업데이트 |

---

## 주요 라이브러리 및 플러그인 버전 정보

| 라이브러리/플러그인 | 버전 |
| :--- | :--- |
| **Bootstrap** | v5.3.8 |
| **Swiper** | v8 |

---

## 폴더 구조

```plaintext
skin2/
├── index.html
├── amj/
│   ├── main/
│   │   ├── page/
│   │   │   ├── quration.html
│   │   └── mainBanner.html
│   ├── page/
│   │   ├── common_quration.html
│   │   ├── guide.html
│   │   └── quration.html
│   ├── amj.css
│   └── amj.js
├── board/
│   ├── gallary/
│   │    ├── list.html
│   │    └── list2.html
│   ├── index.html
│   └── report_popup.html
├── layout\basic/
│   ├── css/
│   │   ├── common.css
│   │   └── layout.css
│   ├── js/
│   │   ├── basic.js
│   │   ├── common.js
│   │   ├── layout.js
│   │   └── main.js
│   ├── header.html
│   └── layout.html
├── product/
│   ├── list_product_slide_pick.html
│   └── list_product.html
├── .gitignore
└── README.md