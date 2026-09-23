# Developer Workstation

> **Building a reproducible development environment with CLI, Docker, and Git**  
> CLI·Docker·Git을 직접 다루며 개발 환경의 기본 구조를 익힌 CODYSSEY Foundation 프로젝트

`Linux CLI` `Docker` `OrbStack` `Git` `GitHub` `macOS`

---

## Overview | 프로젝트 소개

This project focuses on the environment that comes before application development: the terminal, filesystem permissions, containers, persistent storage, and version control.

애플리케이션을 만들기 전에 개발자가 사용하는 **터미널, 파일 권한, 컨테이너, 저장소와 버전 관리 환경이 어떻게 동작하는지 직접 구축하고 검증**한 프로젝트입니다.

관리자 권한이 제한된 교육 환경을 고려해 Docker Desktop 대신 **OrbStack**을 활용했고, 단순 설치가 아니라 실제 명령어와 검증 과정을 통해 개발 워크스테이션을 구성했습니다.

## What I Built | 수행 내용

- CLI-based file and directory management | CLI 기반 파일·디렉토리 관리
- Unix permission practice with `chmod` | 파일·디렉토리 권한 실습
- Docker environment with OrbStack | OrbStack 기반 Docker 환경 구성
- Container lifecycle practice | 컨테이너 생성·접속·종료 실습
- Custom Docker image build | Dockerfile 및 이미지 빌드
- Port mapping and connectivity checks | 포트 매핑과 접속 검증
- Bind Mount & Docker Volume | 데이터 영속성 실습
- Git/GitHub & VS Code integration | 버전 관리 환경 연결

## Environment | 환경

| Area | Environment |
|---|---|
| OS | macOS 15.7.4 |
| Shell | zsh |
| Container Runtime | OrbStack / Docker 28.5.2 |
| Version Control | Git 2.53.0 / GitHub |

## Key Learning | 핵심 학습

이 프로젝트를 통해 개발 환경은 단순히 프로그램을 설치하는 과정이 아니라 **OS → Shell → Container → Storage → Version Control**이 연결된 하나의 작업 환경이라는 점을 익혔습니다.

또한 오류가 발생했을 때 명령어를 그대로 반복하기보다 상태를 확인하고 원인을 좁혀 다시 검증하는 기본적인 troubleshooting 흐름을 연습했습니다.

## Learning Log | 상세 학습 기록

초기 학습 당시의 명령어 실습, 검증 과정과 시행착오는 별도 로그로 보존했습니다.

➡️ **[View Detailed Learning Log](./docs/LEARNING_LOG.md)**

---

**CODYSSEY AI All-in-One · Foundation Program**