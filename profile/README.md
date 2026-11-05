# Afterwork Builders

퇴근 후 함께 모여 직접 만들고, 각자의 결과물을 공유하는 스터디입니다.

## 프로젝트

주제별 프로젝트가 시작되면 이곳에서 각 레포지토리로 바로 이동할 수 있습니다.
레포지토리 이름은 순번과 주제를 함께 적습니다. 예: `01-todo-app`, `02-expense-tracker`.

| 주제 | 기간 | 레포지토리 |
| --- | --- | --- |
| 추가 예정 | 시작일 ~ 종료일 | — |

## 그라운드 룰

> 정해진 사항을 기록하고, 미정 항목은 회의에서 함께 논의해 채워갑니다. [그라운드 룰 회의 템플릿](https://github.com/Afterwork-Builders/.github/blob/main/meetings/ground-rules-template.md)을 참고하세요.

| 항목 | 함께 정할 내용 | 결정 사항 |
| --- | --- | --- |
| **모임** | 요일, 시간, 장소 | 주 1회 모임 |
| **주제와 목표** | 주제를 정하는 방법과 프로젝트 범위 | 같은 주제를 각자 구현 |
| **진행 방식** | 개인 작업과 모임의 세부 진행 방법 | 각자 구현한 결과물을 모임에서 발표 |
| **기술과 환경** | 사용할 기술과 개발 환경 | Python 3.13으로 통일 |
| **AI 활용** | AI 사용 범위와 참고 자료 | 코드 작성과 문제 해결에 AI 도움 없이 직접 진행 |
| **레포지토리** | 브랜치와 PR 사용 방식 | 주제별 레포지토리 하나를 만들고 각자 폴더에 구현물을 올림 |
| **문서화** | 문서의 세부 구성 | 각자 폴더의 README에 프로젝트를 설명하고, `docs/`에 트러블슈팅을 기록 |
| **발표와 피드백** | 발표 내용, 시간, 피드백 방법 | 각자 만든 결과물을 발표 |
| **기타** | 불참, 일정 변경 등 추가로 필요한 약속 | 미정 |

## 주제별 레포지토리 구조 예시

주제마다 레포지토리를 만들고, 각자 이름으로 된 폴더에 구현물과 문서를 정리합니다. 아래는 예시이며, 소스 코드의 세부 구조는 프로젝트에 맞게 구성할 수 있습니다.

```text
01-주제/
├── README.md                  # 주제 및 공통 요구사항
├── member-a/
│   ├── README.md              # 프로젝트 설명과 실행 방법
│   ├── docs/
│   │   ├── 2026-11-05-database-connection-error.md         # 문제별 해결 과정
│   │   └── 2026-11-06-package-install-error.md
│   └── ...                    # 구현 코드 및 필요한 파일
├── member-b/
│   ├── README.md
│   ├── docs/
│   │   └── 2026-11-05-database-connection-error.md
│   └── ...
└── member-c/
    ├── README.md
    ├── docs/
    │   └── 2026-11-05-database-connection-error.md
    └── ...
```

### 문서 템플릿

- [주제별 레포지토리 README 템플릿](https://github.com/Afterwork-Builders/.github/blob/main/templates/topic-readme.md) — 주제별 레포지토리 루트의 `README.md`에 복사해서 사용합니다.
- [개인 프로젝트 README 템플릿](https://github.com/Afterwork-Builders/.github/blob/main/templates/project-readme.md) — 각자 폴더의 `README.md`에 복사해서 사용합니다.
- [트러블슈팅 템플릿](https://github.com/Afterwork-Builders/.github/blob/main/templates/troubleshooting.md) — 각자 폴더의 `docs/`에 복사해서 사용합니다.

## 회의 기록

회의 문서는 `meetings/YYYY-MM-DD-주제.md` 형식으로 저장합니다. 날짜는 실제 회의한 날을 기준으로 합니다.
