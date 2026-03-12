# AI Workkflow Lab

현업 사용자가 AI를 실제 업무에 적용할 수 있도록 돕는 AX 교육 / 실습 / 워크숍 지원용 웹페이지입니다.

이 프로젝트는 단순한 AI 도구 소개 페이지가 아니라, 다음 흐름을 중심으로 구성되어 있습니다.

- 현업 문제 정의
- AX Enablement Cycle
- 사용자 유형별 교육 맥락
- 실습 도구 연계
- 워크숍 / 가이드 / PoC 지원
- 기대 효과와 다음 행동 유도

## Project Goal

이 페이지가 전달하려는 핵심 메시지는 다음과 같습니다.

> AI를 도입하는 것이 아니라, 일하는 방식을 바꾸는 것.

또한 아래 방향을 중심으로 설계되었습니다.

- 현업이 AI를 실제 업무에 적용하도록 돕는 교육 + 실습 플랫폼
- 진단부터 학습, 실습, PoC까지 연결되는 AX Enablement Cycle
- 제약/바이오, 운영, 품질, 문서, 교육 등 실무 맥락에 맞는 표현과 구조

## Main Sections

현재 페이지는 아래 순서로 구성되어 있습니다.

1. Hero
2. Why This Platform
3. Enablement Cycle
4. Audience
5. Practice Tools
6. Workshop Support
7. Outcome
8. CTA

## Practice Tools

기존 3개 서비스는 이 프로젝트 안에서 “제품”이 아니라 “교육용 실습 도구”로 포지셔닝되어 있습니다.

- `Translation QA`
  - 품질 기준과 검수 관점을 익히는 실습
- `AX Checklist`
  - 현업 프로세스의 AI 적용 가능성을 점검하는 진단 실습
- `SOP Assistant`
  - 문서 검색 및 지식 활용 방식 개선을 체험하는 실습

## Tech

- Single-file HTML
- Embedded CSS
- Static page structure

## File Structure

```text
ax-hub/
├── index.html
└── README.md
```

## Local Preview

정적 HTML 페이지이므로 브라우저에서 `index.html`을 바로 열어 확인할 수 있습니다.

필요 시 간단한 로컬 서버로도 확인할 수 있습니다.

```bash
python3 -m http.server
```

그 뒤 브라우저에서 `http://localhost:8000`으로 접속하면 됩니다.

## Notes

- 밝고 전문적인 톤의 AX 교육 플랫폼 UI를 목표로 합니다.
- 기능 나열보다 현업 적용 맥락과 교육 흐름을 우선합니다.
- CTA 역시 제품 사용 유도보다 진단, 실습, 워크숍 참여 중심으로 작성합니다.
