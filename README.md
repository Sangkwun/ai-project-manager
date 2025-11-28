# AI Project Manager

AI 웹 에이전트(Claude, Codex, Cursor 등)로 여러 프로젝트를 관리하는 마크다운 템플릿입니다.

## 워크플로우

```
[AI 웹 에이전트] → GitHub 레포의 md 파일 수정 → [GitHub Pages] 렌더링
```

## 파일 구조

| 파일 | 설명 |
|------|------|
| `AGENTS.md` | AI 에이전트가 읽는 가이드라인 |
| `dashboard.md` | 프로젝트 현황 대시보드 |
| `memory.md` | 세션 간 컨텍스트 메모리 |

## 시작하기

### 1. 템플릿 사용

**Use this template** 버튼을 클릭하여 자신의 레포지토리를 생성하세요.

### 2. GitHub Pages 활성화

Settings > Pages > Source를 `main` 브랜치로 설정하세요.

### 3. AI 에이전트 연결

사용하는 AI 도구(Claude Web, Codex, Cursor 등)에서 레포지토리를 연결하고, `AGENTS.md`를 컨텍스트로 제공하세요.

### 4. 프로젝트 관리 시작

AI와 대화하며 `dashboard.md`를 업데이트하세요. 변경사항은 GitHub Pages에서 바로 확인할 수 있습니다.

## 커스터마이징

### AGENTS.md

AI 에이전트의 역할과 동작 방식을 정의합니다. 자신의 워크플로우에 맞게 수정하세요:

- 톤과 언어 설정
- 태스크 상태 규칙
- 대화 템플릿

### dashboard.md

프로젝트 현황을 표시하는 대시보드입니다. 테이블 구조와 상태 이모지를 원하는 대로 수정하세요.

### memory.md

세션 간 유지되는 메모입니다. 사용자 선호, 프로젝트 히스토리 등을 저장합니다.

## 라이선스

MIT
