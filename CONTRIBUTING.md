# Contributing Guide

## 작업 흐름
1. 이슈 템플릿(feat / fix / refactor / docs / chore)으로 이슈를 생성합니다.
2. 이슈 번호를 포함한 브랜치를 만듭니다. 예: `feat/12-login-api`
3. 작업 후 PR을 올리고, 본문에 `Closes #이슈번호`를 적습니다.
4. 리뷰어 1명 이상의 승인을 받은 뒤 머지합니다.

## 브랜치 네이밍
`<type>/<이슈번호>-<간단한-설명>`

| type | 용도 |
|------|------|
| feat | 새로운 기능 |
| fix | 버그 수정 |
| refactor | 리팩터링 |
| docs | 문서 작성 및 수정 |
| chore | 설정, 빌드, 의존성 등 |

## 커밋 메시지
`<type>: <제목>` 형식을 사용합니다.

```
feat: 로그인 API 추가
fix: 토큰 만료 시 401 반환하도록 수정
```

## 라벨
각 레포에 아래 라벨을 만들어 두어야 이슈 템플릿의 자동 라벨이 적용됩니다.
`feat`, `fix`, `refactor`, `docs`, `chore`
