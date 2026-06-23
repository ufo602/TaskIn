# TaskIn

![version](https://img.shields.io/badge/version-2.10.0-blue)

스마트 워크스페이스 — Claude Code로 개발한 업무 관리 서비스

## 주요 기능
- 태스크 관리 (리스트 / 칸반 보드)
- 캘린더 뷰 & 구글 캘린더 내보내기
- 아이젠하워 매트릭스 우선순위 분류
- AI 메일 분석 & 실적 보고서 (Groq)
- 지식 보관함 (Wiki)
- 다크 모드
- 모바일 반응형 (사이드바 드로어) & 저장공간 사용량 게이지

## 사용 방법
**바로 사용:** https://ufo602.github.io/TaskIn/ 접속 (항상 최신 버전)

또는 `TaskIn.html` 파일을 브라우저에서 열면 바로 사용할 수 있습니다.
별도 설치나 서버 없이 단일 파일로 동작합니다.

## 버전 관리
- 실제 버전의 단일 출처: `TaskIn.html` 내 `APP_VERSION` 상수 + `CHANGELOG.md`
- 파일명에는 버전을 넣지 않습니다 (파일명-버전 불일치 방지)

## 개발 환경
- Claude Code (claude.ai/code) 로 개발 및 버전 관리
- 단일 HTML 파일 (순수 HTML/CSS/JS)
- AI 기능: Groq API (llama-3.3-70b)
