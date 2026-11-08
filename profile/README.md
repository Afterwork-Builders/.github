# Afterwork Builders

퇴근 후 함께 모여 직접 만들고, 각자의 결과물을 공유하는 스터디입니다.

## 프로젝트

주제별 프로젝트가 시작되면 이곳에서 각 레포지토리로 바로 이동할 수 있습니다.
레포지토리 이름은 순번과 주제를 함께 적습니다. 예: `01-todo-app`, `02-expense-tracker`.

| 주제 | 기간 | 레포지토리 |
| --- | --- | --- |
| 미래 자산 계산기 | 2026-11-08 ~ 2026-11-16 (예정) | [01-future-asset-calculator](https://github.com/Afterwork-Builders/01-future-asset-calculator) |

## 그라운드 룰

> 정해진 사항을 기록하고, 미정 항목은 회의에서 함께 논의해 채워갑니다. [그라운드 룰 회의 템플릿](https://github.com/Afterwork-Builders/.github/blob/main/meetings/ground-rules-template.md)을 참고하세요.

| 항목 | 함께 정할 내용 | 결정 사항 |
| --- | --- | --- |
| **모임** | 세부 날짜와 시간 | 주 1회 퇴근 후 모임. 월요일을 선호하며 온라인으로 진행 |
| **주제와 목표** | — | 같은 주제를 각자 구현하고, 기능과 요구사항은 자유롭게 정함 |
| **진행 방식** | 개인 작업과 모임의 세부 진행 방법 | 각자 구현한 결과물을 모임에서 발표 |
| **기술과 환경** | 그 외 기술과 개발 환경 | Python을 사용하며 버전은 각자 자유롭게 선택 |
| **AI 활용** | 세부 질문 범위와 난이도별 조정 | AI에 질문할 수 있으나 제시된 코드를 그대로 붙여넣지 않음 |
| **레포지토리** | 브랜치와 PR 사용 방식 | 주제별 레포지토리 하나를 만들고 각자 폴더에 구현물을 올림. 이름은 `01-주제`처럼 순번과 주제를 함께 표기 |
| **문서화** | 문서의 세부 구성 | 각자 폴더의 README에 프로젝트를 설명하고, `docs/`에 트러블슈팅을 기록 |
| **트러블슈팅 파일명** | — | `YYYY-MM-DD-문제-요약.md` 형식. 기록한 날짜와 영문 소문자·하이픈으로 된 문제 요약을 사용 |
| **발표와 피드백** | 발표 시간과 세부 방식 | 각자 결과물을 공유하고 가독성·유지보수성·구현 의도를 함께 리뷰 |
| **다음 주제** | — | 모임 당일 정하며 만들고 싶은 아이디어를 미리 준비 |
| **회의 문서** | — | `meetings/YYYY-MM-DD-주제.md` 형식으로 실제 회의 날짜를 포함 |
| **기타** | 불참, 일정 변경 등 추가로 필요한 약속 | 미정 |

## 주제별 레포지토리 구조 예시

주제마다 레포지토리를 만들고, 각자 GitHub 닉네임으로 된 폴더에 구현물과 문서를 정리합니다. 아래는 예시이며, 소스 코드의 세부 구조는 프로젝트에 맞게 구성할 수 있습니다.

```text
01-주제/
├── README.md                  # 주제 및 공통 요구사항
├── pileuszu/
│   ├── README.md              # 프로젝트 설명과 실행 방법
│   ├── docs/
│   │   ├── 2026-11-05-database-connection-error.md         # 문제별 해결 과정
│   │   └── 2026-11-06-package-install-error.md
│   └── ...                    # 구현 코드 및 필요한 파일
├── Minji6/
│   ├── README.md
│   ├── docs/
│   │   └── 2026-11-05-database-connection-error.md
│   └── ...
└── josephuk77/
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

- [2026-11-08 그라운드 룰 및 첫 프로젝트 회의](https://github.com/Afterwork-Builders/.github/blob/main/meetings/2026-11-08-ground-rules.md) — 오후 9시 (한국 시간)
