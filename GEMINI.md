# 프로젝트 개요: 권오 포트폴리오 (Owen's Portfolio)

이 프로젝트는 풀스택 개발자 **권오(Owen)**의 개인 포트폴리오 웹사이트입니다. 미니멀하고 현대적인 디자인을 지향하며, 사용자의 경험(UI/UX)과 깔끔한 코드 구조를 중점으로 제작되었습니다.

## 주요 기술 스택

- **Frontend:** HTML5, CSS3 (Custom Properties, Flexbox, Grid)
- **Typography:** Inter Font (Google Fonts)
- **Design System:** Cursor-Inspired 디자인 시스템, 반응형 웹 디자인 지원
- **Assets:** SVG 및 PNG 기반의 프로필 이미지

## 프로젝트 구조

- `index.html`: 웹사이트의 전체 구조와 콘텐츠를 담당하는 메인 파일입니다.
- `index.css`: 전역 디자인 시스템, 레이아웃, 컴포넌트 스타일 및 애니메이션을 정의합니다.
- `profile.svg`, `profile.png`: 웹사이트에서 사용되는 프로필 이미지 자산입니다.

## 빌드 및 실행 방법

이 프로젝트는 별도의 빌드 과정이 필요 없는 순수 정적 웹 프로젝트입니다.

### 실행 (Development/Production)
- 로컬 환경: `index.html` 파일을 웹 브라우저에서 직접 열거나, VS Code의 `Live Server` 확장을 사용하여 실시간으로 확인할 수 있습니다.
- 배포: `index.html`, `index.css`, 이미지 파일들을 정적 호스팅 서비스(GitHub Pages, Netlify, Vercel 등)에 업로드하여 즉시 배포 가능합니다.

## 개발 규칙 및 컨벤션

- **CSS 디자인 시스템:** `index.css`의 `:root` 섹션에 정의된 CSS 변수(Colors, Spacing, Typography, Shadows 등)를 우선적으로 사용하여 일관된 디자인을 유지합니다.
- **반응형 디자인:** `clamp()` 함수와 미디어 쿼리를 사용하여 모바일, 태블릿, 데스크탑 환경에 모두 대응합니다.
- **시맨틱 마크업:** 웹 접근성을 고려하여 HTML5 시맨틱 태그(`nav`, `section`, `main` 등)를 적극 활용합니다.
- **애니메이션:** 사용자 경험 향상을 위해 `fade-up`, `stagger` 등의 클래스를 통한 선언적 애니메이션을 적용합니다.

## TODO / 향후 계획
- [ ] JavaScript를 추가하여 상호작용성(모바일 메뉴 토글, 스크롤 애니메이션 정밀 제어 등) 강화
- [ ] 다크 모드(Dark Mode) 테마 전환 기능 구현
- [ ] 프로젝트 섹션에 상세 모달 또는 개별 프로젝트 페이지 링크 추가

## 추가지시사항
"Git 커밋 메시지 작성 가이드라인:"
- **형식**: Conventional Commits 규격(type(scope): subject)을 준수하라.
- **유형**: 기능 추가는 feat, 수정은 fix, 문서는 docs, 리팩터링은 refactor를 사용하라.
- **제목**: 50자 이내의 명령형으로 작성하고, 제목은 커밋 핵심 주제로 작성하라.
- **이슈**: 관련된 이슈 번호가 있다면 반드시 제목이나 본문에 #번호 형태로 포함하라.
- **언어**: 한국어로 일관되게 작성하라.
- **자동 종료**: 버그 수정 시 푸터에 Fixes #이슈번호를 명시하라.