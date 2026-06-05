# 푸데푸데 Pudepude Homewear Shopping Mall

부드러운 파스텔 무드의 잠옷·홈웨어 쇼핑몰 포트폴리오 프로젝트입니다.
푸데푸데는 편안한 하루의 마무리와 포근한 집의 분위기를 담은 홈웨어 브랜드를 콘셉트로 제작되었습니다.

<br>

## Language

* [한국어](#한국어)
* [English](#english)

<br>

---

# 한국어

## 프로젝트 소개

**푸데푸데**는 잠옷과 홈웨어를 판매하는 온라인 쇼핑몰 콘셉트의 웹 포트폴리오입니다.
노랑과 핑크를 중심으로 한 muted pastel 컬러를 사용하여 귀엽지만 과하지 않고, 부드럽고 세련된 브랜드 이미지를 표현했습니다.

본 프로젝트는 사용자가 상품을 쉽고 편안하게 둘러볼 수 있도록 메인 배너, 상품 카테고리, 공지사항, 자주 묻는 질문, 퀵메뉴 등을 구성한 쇼핑몰형 웹사이트입니다.

또한 iWeb 기반 쇼핑몰 환경을 활용하되, 기본 제공 스타일에만 의존하지 않고 SCSS를 사용하여 사용성과 시각적 완성도를 주도적으로 개선했습니다.

<br>

## 제작 목적

* 홈웨어 브랜드에 어울리는 부드럽고 포근한 쇼핑몰 분위기 구현
* 사용자가 주요 상품과 이벤트를 빠르게 확인할 수 있는 구조 설계
* 공지사항, FAQ, 퀵메뉴 등을 통해 실제 쇼핑몰처럼 자연스러운 사용 흐름 구성
* iWeb 기반 쇼핑몰 환경에 맞춘 디자인 및 스타일 커스터마이징
* iWeb의 기본 템플릿 한계를 보완하기 위해 SCSS를 활용한 스타일 개선
* 사용자의 이동 동선, 메뉴 접근성, 정보 확인 흐름을 더 편리하게 만드는 사용성 개선

<br>

## 디자인 콘셉트

푸데푸데의 디자인은 **차분한 파스텔, 따뜻한 홈웨어 감성**을 중심으로 구성했습니다.

* Main Color: muted yellow, dusty pink
* Sub Color: cream beige, lavender gray, cocoa brown
* Mood: soft, cozy, warm, calm, minimal
* Keyword: pajama, homewear, comfort, pastel, relaxing mood

<br>

## 주요 기능 및 섹션

### Main Banner

키즈 잠옷과 여름 시즌 홈웨어를 중심으로 한 메인 히어로 배너를 구성했습니다.
상품의 분위기와 계절감을 시각적으로 전달할 수 있도록 부드러운 카피와 여백 중심의 레이아웃을 적용했습니다.

### Product Category

BEST, NEW, WOMEN, MEN, COUPLE, SALE, CS 메뉴를 통해 사용자가 원하는 상품군으로 쉽게 이동할 수 있도록 구성했습니다.

### Notice

배송, 교환 및 반품, 신규 컬렉션, 시즌 기획전 등 쇼핑몰 운영에 필요한 기본 공지사항을 배치했습니다.

### FAQ

배송, 사이즈, 세탁, 교환 및 반품, 품절 상품, 선물 포장 등 고객이 자주 궁금해할 내용을 정리했습니다.

### Quick Menu

홈, 문의, 장바구니, 주문내역, TOP 버튼을 통해 쇼핑몰 이용 중 필요한 메뉴에 빠르게 접근할 수 있도록 구성했습니다.

<br>

## 사용 기술

* iWeb
* HTML
* CSS
* SCSS
* GitHub
* Photoshop
* Figma

<br>

## 협업 방식

iWeb은 일반적인 코드 기반 웹 프로젝트처럼 GitHub와 직접 연동하여 실시간 공동작업을 진행하기에는 한계가 있는 환경입니다.

이러한 특성을 보완하기 위해 팀원 각자의 GitHub 저장소를 연결하고, SCSS와 CSS 파일을 기준으로 스타일 작업을 공유하며 협업했습니다.
이를 통해 iWeb의 기본 템플릿 구조 안에서도 팀원 간 스타일 수정 사항을 비교하고, 필요한 부분을 반영하며 보다 체계적으로 디자인을 개선할 수 있었습니다.

특히 기본 제공 템플릿에만 의존하지 않고, 퀵메뉴, 네비게이션, 공지사항, FAQ 등 사용자의 탐색 흐름과 관련된 영역을 SCSS로 직접 수정하여 사용성을 개선했습니다.

<br>

## Commit Convention

본 프로젝트에서는 작업 내용을 명확하게 구분하고 협업 시 변경 사항을 쉽게 파악하기 위해 아래와 같은 커밋 prefix 규칙을 사용했습니다.

| Prefix | 설명 | 예시 |
|---|---|---|
| `feat` | 새로운 기능 추가 | `feat: 로그인 페이지 UI 추가` |
| `fix` | 버그 수정 | `fix: 모바일에서 버튼 클릭 오류 수정` |
| `design` | UI/스타일 변경, CSS 수정 | `design: 히어로 섹션 애니메이션 추가` |
| `style` | 코드 포맷 정리, 기능 변화 없음 | `style: 들여쓰기 및 세미콜론 정리` |
| `refactor` | 코드 리팩토링, 동작은 동일 | `refactor: 헤더 구조 개선` |
| `comment` | 주석 추가 또는 수정 | `comment: 함수 설명 주석 추가` |
| `docs` | 문서 수정, README 등 | `docs: 커밋 규칙 문서 추가` |
| `rename` | 파일 또는 폴더 이름 변경 | `rename: hero.css → main.css` |
| `remove` | 파일 삭제 | `remove: 사용하지 않는 이미지 삭제` |
| `test` | 테스트 코드 추가 또는 수정 | `test: 로그인 테스트 추가` |
| `chore` | 설정, 패키지, 빌드 관련 작업 | `chore: bootstrap 업데이트` |
| `init` | 초기 프로젝트 설정 | `init: 프로젝트 초기 세팅` |
| `merge` | 공동 작업 병합 | `merge: Gbranch -> main으로 병합` |

<br>
## 프로젝트 구조

```text
pudepude-homewear-shoppingmall/
├── README.md
├── css/
│   ├── style.css
│   └── style.min.css
├── scss/
│   └── style.scss
├── images/
│   ├── banner/
│   ├── product/
│   └── icon/
└── assets/
```

<br>

## 프로젝트 링크

* [IWEB](https://www.i-web.kr/green30/)
* [GitHub](https://github.com/Gillian-Salley/pude-pude-homewear)

<br>

## 작업 포인트

* 브랜드 컬러와 무드를 통일하여 전체적인 쇼핑몰 분위기를 구성했습니다.
* 실제 쇼핑몰처럼 보일 수 있도록 공지사항과 FAQ 콘텐츠를 기획했습니다.
* iWeb을 기반으로 제작했지만, 기본 템플릿의 한계를 보완하기 위해 SCSS를 활용하여 스타일을 직접 설계하고 수정했습니다.
* 사용자가 쇼핑몰을 더 편하게 탐색할 수 있도록 퀵메뉴, 네비게이션, FAQ, 공지사항 영역의 사용성을 개선했습니다.
* SCSS 구조를 활용하여 유지보수하기 쉬운 스타일 관리 방식을 적용하고, 이후 CSS 및 minified CSS로 확장할 수 있도록 작업했습니다.
* iWeb의 특성상 플랫폼 내부에서 직접적인 공동 코드 작업이 어렵기 때문에, GitHub를 활용하여 팀원 간 스타일 파일을 공유하고 협업했습니다.
* 각자의 GitHub 저장소를 연결하여 SCSS/CSS 수정 내용을 관리하고, 변경 사항을 비교하며 스타일 작업을 진행했습니다.
* iWeb의 제한적인 개발 환경을 GitHub 기반 협업 방식으로 보완하여, 보다 주도적이고 체계적인 스타일 개선 작업을 진행했습니다.

<br>

## 향후 개선 방향

* 상품 상세 페이지 구성
* 장바구니 및 주문 페이지 디자인 확장
* 모바일 화면 최적화
* 시즌별 배너 및 이벤트 페이지 추가
* 브랜드 스토리 페이지 제작

<br>

---

# English

## Project Overview

**Pudepude** is a pajama and homewear shopping mall portfolio project.
The brand concept focuses on soft comfort, cozy home moments, and a calm pastel mood.

This project presents an online shopping mall structure with main banners, product categories, notices, frequently asked questions, and a quick menu. The goal is to create a warm and user-friendly shopping experience.

Although the project was built on an iWeb-based shopping mall environment, the design was not limited to the default template styles. SCSS was used to proactively improve usability and visual quality.

<br>

## Project Purpose

* To create a soft and cozy shopping mall design for a homewear brand
* To help users quickly explore products, events, and key information
* To design a realistic shopping mall structure with notice, FAQ, and quick menu sections
* To customize the visual style for an iWeb-based shopping mall environment
* To improve the limitations of the default iWeb template by using SCSS
* To create a more convenient browsing flow through improved navigation, menu accessibility, and information structure

<br>

## Design Concept

The design direction of Pudepude is based on **muted pastel colors, soft shapes, and a warm homewear mood**.

* Main Color: muted yellow, dusty pink
* Sub Color: cream beige, lavender gray, cocoa brown
* Mood: soft, cozy, warm, calm, minimal
* Keywords: pajama, homewear, comfort, pastel, relaxing mood

<br>

## Main Features and Sections

### Main Banner

The main hero banners focus on kids’ pajamas and seasonal summer homewear.
Soft copywriting and spacious layouts are used to communicate the product mood and seasonal concept.

### Product Category

The navigation menu includes BEST, NEW, WOMEN, MEN, COUPLE, SALE, and CS, allowing users to move easily between product categories.

### Notice

The notice section includes essential shopping mall information such as shipping, exchange and return policies, new collection updates, and seasonal events.

### FAQ

The FAQ section provides answers to common customer questions about shipping, sizing, washing, exchange and return policies, restocked items, and gift wrapping.

### Quick Menu

The quick menu includes Home, Contact, Cart, Order History, and TOP buttons so users can access key pages quickly while browsing.

<br>

## Tech Stack

* iWeb
* HTML
* CSS
* SCSS
* GitHub
* Photoshop
* Figma

<br>

## Collaboration

Since iWeb is not a development environment that directly supports GitHub-based collaboration, it has limitations for real-time code-based teamwork.

To overcome this limitation, each team member connected their own GitHub repository and collaborated by sharing SCSS and CSS files.
This allowed the team to compare style changes, manage revisions, and improve the overall design more systematically within the iWeb-based website environment.

Instead of relying only on the default template, the team customized key user-facing areas such as the quick menu, navigation, notice, and FAQ sections with SCSS to improve usability and browsing flow.

<br>

## Commit Convention

| Prefix | Description | Example |
|---|---|---|
| `feat` | Adds a new feature | `feat: add login page UI` |
| `fix` | Fixes a bug | `fix: fix button click issue on mobile` |
| `design` | Updates UI, styling, or CSS | `design: add hero section animation` |
| `style` | Code formatting only, with no functional changes | `style: clean up indentation and semicolons` |
| `refactor` | Refactors code without changing behavior | `refactor: improve header structure` |
| `comment` | Adds or updates comments | `comment: add function description comments` |
| `docs` | Updates documentation such as README | `docs: add commit convention guide` |
| `rename` | Renames files or folders | `rename: hero.css → main.css` |
| `remove` | Removes files | `remove: delete unused images` |
| `test` | Adds or updates test code | `test: add login test` |
| `chore` | Updates settings, packages, or build-related tasks | `chore: update bootstrap` |
| `init` | Sets up the initial project structure | `init: initial project setup` |
| `merge` | Merges collaborative work | `merge: merge Gbranch into main` |

<br>

## Project Structure

```text
pudepude-homewear-shoppingmall/
├── README.md
├── css/
│   ├── style.css
│   └── style.min.css
├── scss/
│   └── style.scss
├── images/
│   ├── banner/
│   ├── product/
│   └── icon/
└── assets/
```

<br>

## Project Links

* Website: Coming soon
* Figma: Coming soon
* GitHub: Coming soon

<br>

## Key Points

* Built a consistent shopping mall mood using the brand’s color palette and visual direction.
* Planned realistic notice and FAQ content to make the website feel like an actual online store.
* Built on iWeb, but customized beyond the default template by using SCSS to improve the overall style and usability.
* Enhanced the user experience by refining key shopping mall elements such as navigation, quick menu, notice, and FAQ sections.
* Structured the SCSS for easier style management and future expansion into CSS and minified CSS files.
* Since iWeb does not easily support direct collaborative code editing, GitHub was used to share and manage style files between team members.
* Each team member connected their GitHub repository and collaborated by comparing SCSS/CSS changes.
* The limitations of the iWeb environment were supplemented through a GitHub-based collaboration workflow, allowing the team to improve the website style in a more structured and proactive way.

<br>

## Future Improvements

* Product detail page design
* Cart and order page design
* Mobile optimization
* Seasonal banner and event page updates
* Brand story page design
