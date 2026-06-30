# my-first-plugin

기본 사항을 배우기 위한 Claude Code 플러그인입니다.

## Skills

### `hello`
사용자 이름을 받아 따뜻한 인사말을 전합니다.

```
/my-first-plugin:hello <이름>
```

### `code-review`
코드의 구조, 에러 처리, 보안, 테스트 커버리지를 검토합니다.

```
/my-first-plugin:code-review
```

## 설치

```bash
claude plugin marketplace add github:3DKIDS/my-first-plugin
claude plugin install my-first-plugin
```

## 라이선스

MIT
