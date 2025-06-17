
# Kubernetes 학습 가이드 📚

## 🎯 학습 목표
이 폴더는 **Kubernetes 초보자**를 위한 단계별 학습 자료입니다. 복잡한 개념을 쉬운 비유와 실습을 통해 차근차근 배울 수 있도록 구성했습니다.

## 📖 학습 순서

### 1단계: 기초 개념 이해
- **[[00. Kubernetes란 무엇인가]]** 
  - 쿠버네티스의 기본 개념과 필요성
  - 컨테이너 오케스트레이션의 이해
  - 아파트 관리사무소 비유로 쉽게 이해

### 2단계: 아키텍처 파악
- **[[01. Kubernetes 기본 구조]]**
  - 마스터 노드 vs 워커 노드
  - 회사 조직 비유로 각 컴포넌트 역할 이해
  - API Server, Scheduler, Controller, etcd 등

### 3단계: 기본 리소스 학습
- **[[02. Pod와 Container]]**
  - 쿠버네티스의 최소 실행 단위
  - 원룸 비유로 Pod 개념 이해
  - 컨테이너와 Pod의 관계

- **[[03. Service와 Networking]]**
  - Pod에 접근하는 방법
  - ClusterIP, NodePort, LoadBalancer 차이점
  - 호텔 프런트 데스크 비유로 Service 이해

### 4단계: 애플리케이션 배포 관리
- **[[04. Deployment와 ReplicaSet]]**
  - Pod를 안정적으로 관리하는 방법
  - Rolling Update와 롤백
  - 생산 라인 관리자 비유로 ReplicaSet 이해

### 5단계: 설정 및 데이터 관리
- **[[05. ConfigMap과 Secret]]**
  - 애플리케이션 설정 외부화
  - 비밀번호 안전한 관리
  - 설정 파일 보관함과 금고 비유

- **[[06. Volume과 Storage]]**
  - 데이터 영구 저장 방법
  - PV, PVC 개념과 활용
  - 창고 임대 시스템 비유로 스토리지 이해

### 6단계: 실전 연습
- **[[07. Kubernetes 실습 가이드]]**
  - 단계별 실습 프로젝트
  - 실제 애플리케이션 배포
  - 문제 해결 가이드

## 🚀 학습 팁

### 순서대로 학습하세요
각 문서는 이전 개념을 바탕으로 구성되어 있습니다. 건너뛰지 말고 순서대로 읽어보세요.

### 실습과 함께 진행하세요
개념 학습 후에는 반드시 실습으로 확인해보세요. 특히 [[07. Kubernetes 실습 가이드]]를 적극 활용하세요.

### 비유로 이해하세요
각 개념마다 일상생활의 비유를 들어 설명했습니다. 비유를 통해 추상적인 개념을 구체적으로 이해해보세요.

## 🛠️ 필요한 준비물

### 로컬 환경
- **Docker Desktop** 또는 **minikube**
- **kubectl** CLI 도구
- 텍스트 에디터 (VS Code 추천)

### 클라우드 환경 (선택사항)
- AWS EKS, GCP GKE, Azure AKS 중 하나
- 무료 티어로도 충분히 실습 가능

## 📊 학습 진도 체크

### 기초 단계 ✅
- [ ] Kubernetes가 무엇인지 설명할 수 있다
- [ ] 마스터 노드와 워커 노드의 차이를 안다
- [ ] Pod의 개념을 이해했다
- [ ] Service가 왜 필요한지 안다

### 중급 단계 ✅
- [ ] Deployment로 애플리케이션을 배포할 수 있다
- [ ] ConfigMap과 Secret을 활용할 수 있다
- [ ] PVC를 사용해서 데이터를 저장할 수 있다
- [ ] Rolling Update와 롤백을 수행할 수 있다

### 고급 단계 ✅
- [ ] 실제 웹 애플리케이션을 배포했다
- [ ] 데이터베이스와 연동된 서비스를 구성했다
- [ ] 마이크로서비스 아키텍처를 구현했다
- [ ] 모니터링과 로깅을 설정했다

## 🔗 관련 링크

### 공식 문서
- [Kubernetes 공식 문서](https://kubernetes.io/docs/)
- [kubectl 치트시트](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)

### 실습 환경
- [Play with Kubernetes](https://labs.play-with-k8s.com/)
- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [minikube](https://minikube.sigs.k8s.io/docs/)

### 커뮤니티
- [Kubernetes Slack](https://slack.kubernetes.io/)
- [Reddit r/kubernetes](https://www.reddit.com/r/kubernetes/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/kubernetes)

## 🎯 다음 단계

### 이 가이드 완료 후
1. **Helm** - 쿠버네티스 패키지 매니저
2. **Istio** - 서비스 메시
3. **Prometheus + Grafana** - 모니터링
4. **CI/CD** - Jenkins, GitLab CI 연동
5. **보안** - RBAC, Network Policy

### 실전 프로젝트
- 개인 프로젝트를 쿠버네티스에 배포
- 클라우드 환경에서 운영 환경 구축
- 오픈소스 프로젝트 기여

## 💬 도움이 필요하다면

### 문제 해결 순서
1. 각 문서의 "문제 해결" 섹션 확인
2. 공식 문서 검색
3. Stack Overflow에서 유사한 문제 검색
4. 커뮤니티에 질문

### 질문할 때 포함할 정보
- 시도한 명령어
- 에러 메시지 전문
- kubectl 버전 및 클러스터 정보
- 기대했던 결과와 실제 결과

---

**Happy Learning! 🚀**

쿠버네티스는 처음에는 복잡해 보이지만, 단계별로 차근차근 배우면 충분히 마스터할 수 있습니다. 포기하지 말고 꾸준히 실습해보세요!

#Kubernetes #학습가이드 #초보자 #목차
