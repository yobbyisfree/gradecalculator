# 졸업하자, 호랑이

고려대 전기전자공학부 스타일의 4년치 수강계획 웹 플래너입니다.

## 포함된 파일

- `index.html`: 기본 배포 버전
- `index-inline-tools.html`: 대안 레이아웃 버전
- `style.css`: 공통 스타일
- `style-inline-tools.css`: 대안 레이아웃 전용 스타일
- `script.js`: 데이터, 상호작용, 계산 로직

## 로컬에서 보기

1. `index.html`을 브라우저로 엽니다.
2. 대안 배치를 보려면 `index-inline-tools.html`을 엽니다.

## 무료 배포 방법

이 프로젝트는 정적 사이트라서 `GitHub Pages`로 무료 배포가 가능합니다.

### 1. GitHub 저장소 만들기

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더의 파일을 저장소에 올립니다.

### 2. GitHub Pages 자동 배포

이 프로젝트에는 `.github/workflows/deploy-pages.yml`이 포함되어 있습니다.

1. 저장소에 푸시합니다.
2. GitHub 저장소에서 `Settings -> Pages`로 이동합니다.
3. `Build and deployment`의 Source가 `GitHub Actions`인지 확인합니다.
4. 잠시 기다리면 배포가 완료됩니다.

배포 주소 예시:

`https://<github-username>.github.io/<repository-name>/`

## 중요한 점

- 현재 데이터 저장은 브라우저 `localStorage` 기반입니다.
- 즉 사용자별 계획은 각자 자기 브라우저에만 저장됩니다.
- 로그인, 계정 동기화, 여러 기기 동기화는 아직 없습니다.

## 배포 후 추천 작업

1. 저장소 이름과 서비스 이름을 맞추기
2. 커스텀 도메인이 필요하면 나중에 연결하기
3. 실제 사용자용으로는 `샘플로 초기화` 버튼 위치를 더 숨기거나 관리자 전용으로 바꾸기
