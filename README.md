# 신유라 Portfolio

##  👋 소개
### 반갑습니다. 경험을 중요시하는 DevOps, 신유라입니다.<br>
Kubernetes 설치 자동화와 솔루션 패키징을 수행하며 고객사 환경에 직접 설치/검증하는 업무를 하는 2년차 DevOps입니다.<br>
현재 Kubernetes 인프라에서 ArgoCD 기반 GitOps를 운영하고 있습니다.
모든 경험은 자산이라는 생각으로 기록하여 문서로 정리하는 과정을 좋아하고, 발생한 문제를 동료들과 함께 고민하며 해결 방법을 찾을때 가장 큰 성취감을 느낍니다.<br>
<br>
<br>

##  🔧 기술
### Orchestration / GitOps
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)

### CI/CD
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

### OS / Platform
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![RHEL](https://img.shields.io/badge/RHEL-EE0000?style=for-the-badge&logo=redhat&logoColor=white)

### Scripting
![Shell Script](https://img.shields.io/badge/Shell_Script-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
<br>
<br>

## 🏃🏻‍♀️ 경력
__오케스트로__   
*2023.06 - 재직중 (2년 10개월)* DevOps Engineer
- 대규모 OpenStack 기반 환경에서 Kubernetes 클러스터 설치 자동화 및 패키징·설치·검증
- Kubernetes 기반 환경에 솔루션 패키징·설치·검증
- Jenkins 기반 CI 파이프라인과 ArgoCD 기반 GitOps 배포 체계를 운영
- 고객사 프로젝트 수행
- 솔루션 설치 절차를 문서화하여 사내 표준 프로세스 확립
- 신규 인력 및 사내·고객사 대상 설치 교육 진행   
<br>

__메가존클라우드__   
*2022.03 - 2022.07 (5개월)* Salesforce Developer
- Salesforce 기반 서비스 개발 및 운영   
<br>

__디케이테크인__   
*2018.02 - 2020.05 (2년 4개월)* IDC Engineer   
- 서버·네트워크 장애 대응
- 업무용 웹페이지 개발 및 유지보수
- 서버·네트워크·부품 자산 관리
<br>
<br>

## 🗂️ Project
__Kubernetes·솔루션 설치 자동화__   
*2024.02 - 현재*   
OpenStack 기반 대규모 인프라 환경에서 Kubernetes와 클러스터용 솔루션의 설치 자동화 및 패키징을 담당하여 설치·검증 프로세스를 표준화하는 프로젝트입니다.
- 기존 Kubeadm 기반 Kubernetes 수동 설치 절차를 Ansible기반 설치 자동화를 구현하여 고객사 환경 기준 평균 설치 소요 시간 약 80% 단축
- Kustomize 중심의 수동 배포 체계를 Helm 기반 템플릿으로 재구성하여 환경별 설정 관리와 재배포 안정성을 강화
- 솔루션 설치 및 검증 절차를 문서화하고 표준 가이드로 정리하여 신규 인력 및 사내·파트너사 대상 설치 교육 진행
사용기술 : Ansible, Helm, Shell script   

<br><br>
__CI/CD 운영 · 표준화__   
*2024.02 - 현재*   
프로젝트를 진행할 때마다 각 고객사 환경에 맞춰 새로운 브랜치를 만들고, 파이프라인을 생성해서 수동으로 빌드하여 이미지 파일을 업로드 후 배포하는 반복된 작업을 자동화한 프로젝트입니다.
- Jenkins 기반 CI(빌드·이미지 생성/Push)와 Argo CD 기반 GitOps CD(배포 동기화)로 구성헤 고객사 환경별 반복 배포 작업을 자동화
- 배포 이력 추적과 롤백이 가능한 구조를 정착시켜 수동 배포 리스크를 줄이고 운영 안정성 향상
- 사용기술 : Jenkins, ArgoCD, GitOps


<br><br>
__한국은행__   
*2026.02 - 현재*   
Kubernetes 기반 CI/CD 플랫폼을 구축하는 과정에서 서비스 노출 구조와 미들웨어 보안 구성을 운영 환경에 맞게 개선한 프로젝트입니다.   
- Kubernetes 인프라 구축
  - TUI 버전 Ansible 기반 Kubernetes 설치
- 기존 Ingress 기반 서비스 노출 구조를 Istio Gateway, VirtualService 기반으로 전환하여 서비스별 트래픽 제어와 라우팅 정책을 더 일관되게 관리할 수 있도록 개선
- Harbor, GitLab, SonarQube, Nexus 등 주요 미들웨어를 HTTPS 기반으로 재구성 테스트하여 서비스 간 통신 보안과 운영 표준을 강화
- 단순 설치에 그치지 않고, 실제 운영 환경에서 더 안정적으로 사용할 수 있는 구조로 배포 기반을 정비
- 사용기술 : Kubernetes, Ansible, Helm, Nexus, Harbor, Sonarqube, Jenkins, GitLab

<br><br>
__사회보장정보원__   
*2025.12 - 2025.12*   
자사 Openstack 기반 솔루션 설치와 검증을 수행한 프로젝트입니다.   
- Kubernetes 인프라 구축
  - Openstack 환경 VM에서 Kubernetes 클러스터 구축
  - TUI 버전 Ansible 기반 Kubernetes 설치 자동화 적용으로 설치 소요 시간 80% 단축하여 생산성 향상
- 모니터링 시스템 구성
  - Prometheus, Grafana, Thanos, Alertmanager 기반 모니터링 환경과 MinIO 스토리지를 구성해 운영 가시성을 확보
- 솔루션 검증 및 테스트 수행 매뉴얼을 활용하여 작업 절차를 표준화하고 검증 기간을 40% 단축

<br><br>
__국방통합데이터센터__   
*2023.10 - 2025.07*   
국방 환경의 제약 조건 아래에서 CMP 솔루션 운영, Kubernetes 기반 설치·검증·자동화, 개선까지 수행하며 운영 안정성과 구축 효율을 높인 프로젝트입니다.   
- CMP 솔루션 운영 및 유지보수
  - 자사 CMP 솔루션 운영 및 유지보수 상주근무
  - 시스템 안정성 확보를 위한 지속적인 모니터링 및 장애 대응
- 버전 업그레이드 및 성능 최적화
  - 보안 정책과 방화벽 정책을 반영한 운영 환경에서 Kubernetes 기반 설치·검증 절차 수행
  - Ansible 및 Shell Script 기반 설치 자동화를 적용해 솔루션 버전 업그레이드와 구축 절차를 표준화하고 설치 기간 80% 단축
  - 솔루션 설치·검증·HPA 테스트까지 전 과정 수행
  - Helm Packaging 기반 제품 설치를 적용해 배포 절차를 단순화하여 설치 기간 40% 단축
  - 솔루션 설치·검증·HPA 테스트까지 전 과정을 수행하며 운영 환경 관점의 확장성과 안정성을 검증
- 사용기술: Kubernetes, Ansible, Helm
<br>

<br><br>
__하나금융TI__   
*2024.06 - 2024.10*   
수동 배포 중심 환경에서 반복되는 패키징·파일 반입·배포 절차를 GitLab 기반 CI/CD로 자동화해, 배포 리드타임과 운영 리스크를 줄인 프로젝트입니다.   
__Architecture__   
<img width="823" height="343" alt="gitlab-cicd" src="https://github.com/user-attachments/assets/487b6a31-b05a-4f9a-9e93-9176ae06d814" />   
- GitLab CI/CD 파이프라인 구축
  - GitLab 기반 CI/CD 파이프라인을 기획·구성해 배포마다 반복되던 패키징 작업과 파일 반입 절차를 자동화
  - 배포 절차 표준화를 통해 배포 소요 시간을 약 70% 단축
- 배포 안정성 개선
  - GitLab Runner 구성과 .gitlab-ci.yml 스크립트 정비를 통해 배포 구조를 구축하여 배포 안정성 향상
  - 수동 작업 비중을 줄여 장애 발생률을 약 30% 낮추는 데 기여
- 인프라 구성 및 솔루션 배포
  - Kubernetes 클러스터 구축 및 자사 CI/CD 솔루션 설치까지 수행하며 운영 가능한 배포 기반 구축
- 사용기술: Kubernetes, Ansible, Jenkins, Nexus, Harbor, SCM-Manager, SonarQube, GitLab, GitLab-runner
<br>
<br>

## ✏️ 자격증 및 교육
[자격] __정보처리기사__   
*2018.08* 한국산업인력공단

[자격] __리눅스마스터2급__   
*2017.12* 한국정보통신인력개발센터

[자격] __네트워크관리사2급__   
*2017.10* 한국정보통신자격협회

[자격] __CompTIA Linux+__   
*2018.01* CompTIA Linux+

[자격] __LPIC Level 1__   
*2018.01* LPIC

[자격] __해킹보안전문가__   
*2017.12* 한국해킹보안협회

[자격] __인터넷보안관리사__   
*2017.09* 한국정보통신자격협회

[교육] __T아카데미 ASAC 웹풀스택 개발자 양성__   
*2022.09 - 2023.03* 대한상공회의소

[교육] __프로젝트 기반의 Spring Cloud 개발자 양성__   
*2020.05 - 2020.07* KOSTA





