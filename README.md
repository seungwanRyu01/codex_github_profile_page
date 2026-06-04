# GitHub Pages Developer Portfolio

GitHub Pages에 바로 배포할 수 있는 정적 개발자 포트폴리오입니다. 빌드 도구 없이 루트의 `index.html`이 진입점으로 동작합니다.

## 구성

- `index.html`: 포트폴리오 섹션 구조
- `styles.css`: 디자인 토큰, 반응형 레이아웃, 접근성 스타일
- `script.js`: 모바일 메뉴 토글
- `assets/profile-visual.svg`: 교체 가능한 첫 화면 비주얼

## 콘텐츠 교체 위치

- 이름: `사용자 이름`
- 이메일: `hello@example.com`
- 위치: `Seoul, KR`
- 프로젝트: `프로젝트 A`, `프로젝트 B`, `프로젝트 C`
- 외부 링크: GitHub, LinkedIn, Blog URL

## GitHub Pages 배포

이 저장소는 GitHub Actions 워크플로우로 Pages 배포를 자동화합니다.

1. 변경 사항을 `main` 브랜치에 push합니다.
2. GitHub 저장소의 `Settings`로 이동합니다.
3. `Pages` 메뉴에서 source를 `GitHub Actions`로 설정합니다.
4. `.github/workflows/deploy-pages.yml` 워크플로우가 실행된 뒤 표시되는 GitHub Pages URL로 접속합니다.

수동 재배포가 필요하면 GitHub의 `Actions` 탭에서 `Deploy GitHub Pages` 워크플로우를 `Run workflow`로 실행할 수 있습니다.

## 로컬 확인

브라우저에서 `index.html` 파일을 직접 열어 확인할 수 있습니다.
