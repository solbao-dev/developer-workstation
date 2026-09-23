# Developer Workstation — Learning Log

> CODYSSEY Foundation Program에서 개발 워크스테이션을 구축하며 남긴 상세 실습·검증·트러블슈팅 기록입니다.

이 문서는 기존 README에 기록했던 학습 과정을 보존하기 위한 **Learning Log**입니다.

## Learning Scope | 학습 범위

- Linux/macOS CLI와 파일·디렉토리 조작
- 파일 권한과 `chmod`
- OrbStack 기반 Docker 환경
- 컨테이너 실행 및 `exec`
- Dockerfile과 이미지 빌드
- 포트 매핑
- Bind Mount와 Docker Volume
- Git/GitHub 및 VS Code 연동

## Environment | 실습 환경

- macOS 15.7.4
- `/bin/zsh`
- OrbStack / Docker 28.5.2
- Git 2.53.0

## Completed Practice | 수행 기록

- [x] 터미널 기본 조작 및 디렉토리 구성
- [x] 파일·디렉토리 권한 변경 및 검증
- [x] Docker 데몬 및 실행 환경 점검
- [x] `hello-world`, `ubuntu` 컨테이너 실행
- [x] Dockerfile 작성 및 커스텀 이미지 빌드
- [x] 포트 매핑과 접속 검증
- [x] Bind Mount와 Volume을 통한 데이터 영속성 확인
- [x] Git 환경 설정 및 GitHub/VS Code 연동

## Key Learning Notes | 핵심 학습 로그

### CLI & Permissions

`pwd`, `mkdir`, `touch`, `cp`, `mv`, `rm`, `cat` 등을 직접 사용하며 GUI가 아닌 터미널에서 파일 시스템을 다루는 흐름을 익혔습니다. 절대경로와 상대경로의 차이, 홈 디렉토리(`~/`)의 의미, `mkdir -p`의 동작을 실습했습니다.

`chmod 755`, `644`, `700` 등을 적용하며 `r/w/x` 권한과 숫자 표기법의 관계를 확인했습니다.

### Docker & OrbStack

교육 환경의 제약을 고려해 Docker Desktop 대신 OrbStack을 사용했습니다. `docker info`를 통해 Client와 Server, Docker daemon의 관계를 확인하고 컨테이너 실행 상태를 검증했습니다.

`docker run`, `docker exec`, `docker ps`, `docker stop` 등을 사용하며 컨테이너 생성·접속·종료의 차이를 실습했습니다.

### Image, Port & Storage

Dockerfile을 작성해 이미지를 직접 빌드하고 컨테이너를 실행했습니다. 포트 매핑을 통해 host와 container 사이의 네트워크 연결을 확인했습니다.

Bind Mount와 Docker Volume을 각각 사용해 컨테이너가 삭제되어도 데이터를 보존하는 방법과 두 저장 방식의 차이를 학습했습니다.

### Git & GitHub

로컬 Git 설정, repository 연결, commit/push/pull 흐름을 실습하고 VS Code와 GitHub를 연결했습니다. 이를 통해 로컬 작업 공간과 원격 저장소의 역할 차이를 이해했습니다.

## Troubleshooting Log | 문제 해결 기록

초기 실습 과정에서 Docker daemon 연결 상태, 명령어 오타, 경로 불일치 등 여러 문제를 직접 확인하고 원인을 추적했습니다. 단순히 명령어를 실행하는 데 그치지 않고 **오류 메시지 → 원인 추론 → 수정 → 재검증** 흐름으로 기록한 것이 이 미션의 중요한 학습 결과입니다.

---

> 이 문서는 초기 학습 당시의 상세 기록을 포트폴리오 README와 분리해 보존하기 위해 정리한 문서입니다.