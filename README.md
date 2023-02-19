# 구르미의 분산 추적 시작하기

![logo](./logo.png)

분산 추적을 살짜쿵 맛볼 수 있는 튜토리얼입니다.

## 대상 독자

이 레포는 다음 대상의 독자들을 위해 작성되었습니다.

* `Distributed Tracing`을 도입하고자 하지만, `Distributed Tracing`을 1도 모르는 `Observability Engineer` (SRE/Devops 포함)
* `Observability`의 한 축인 `Distributed Tracing`에 대해 간단히 알고 싶은 신입 SRE 엔지니어

## 요구 사항

이 튜토리얼을 진행하기 위해서, 다음이 필요합니다.

* `Golang` 혹은 `Java`, `Python` 등 익숙한 프로그래밍 언어 1가지 
* `vim`, `vscode` 등 익숙한 코드 에디터 혹은 IDE
* `Docker`
* `Kubernetes` 클러스터

## 목적

1부. 분산 추적의 기본

* Observablility와 Distributed Tracing을 알아보자.
* Jaeger를 설치해보자.
* HOTROD 예제와 함께 Distributed Tracing을 톺아보자.

2부. 만들면서 배우는 분산 추적

* 분산추적 기본 계측(with Golang)
* 분산추적 비동기 계측(with MSA)

3부. 안전하고 탄탄한 분산추적 시스템 구축하기

* 전통적인 방식으로 Jaeger를 확장해보자.
* Grafana Agent와 Tempo로 변경해보자.
* Grafana와 Prometheus를 통해서 모니터링해보자.
