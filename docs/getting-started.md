# Codex 시작하기

이 문서에서는 Codex를 설치하고 기본 명령을 실행하는 방법을 설명합니다.

## 설치

```bash
pip install codex-agent
```

## 설정 파일 예시

프로젝트 루트에 `codex.yml` 파일을 생성하여 에이전트 동작을 정의합니다.

```yaml
agents:
  docs:
    tasks:
      - generate
```

## 문서 생성

```bash
codex run docs
```

위 명령을 실행하면 `docs/` 폴더에 자동으로 문서가 생성됩니다.
