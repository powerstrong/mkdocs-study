# Codex 활용 가이드

이 저장소는 [Codex](https://docs.coding.ai/) 사용법을 한글로 정리한 문서를 MkDocs로 관리합니다. 문서는 `docs/` 폴더에 위치하며 `mkdocs serve` 명령으로 로컬에서 바로 확인할 수 있습니다.
### 배포 페이지 바로가기
https://powerstrong.github.io/mkdocs-study/

## 문서 구조

```bash
.
├── docs/          # Codex 관련 문서가 위치하는 폴더
│   ├── index.md   # 첫 페이지
│   └── getting-started.md  # 기본 사용법
├── mkdocs.yml     # MkDocs 설정 파일
└── README.md      # 현재 문서
```

## 사이트 실행 방법

```bash
mkdocs serve
```

로컬에서 위 명령을 실행하면 `http://127.0.0.1:8000/` 주소에서 문서를 미리 볼 수 있습니다.
