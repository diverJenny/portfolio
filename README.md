# 신유라 Portfolio

##  👋 소개
### 반갑습니다. 경험을 중요시하는 DevOps, 신유라입니다.<br>
Kubernetes 설치 자동화와 솔루션 패키징을 수행하며 고객사 환경에 직접 설치/검증하는 업무를 하는 2년차 DevOps입니다.<br>
모든 경험은 자산이라는 생각으로 기록하여 문서로 정리하는 과정을 좋아하고, 발생한 문제를 동료들과 함께 고민하며 해결해 나갈 때 가장 큰 성취감을 느낍니다.
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
*2023.06 - 재직중 (2년 7개월)*
- 대규모 OpenStack 기반 환경에서 Kubernetes 클러스터 솔루션 설치 자동화 및 패키징·설치·검증
- 사내 개발환경 CI/CD 운영   
<br>

__메가존클라우드__   
*2022.03 - 2022.07 (5개월)*
- Salesforce 개발 및 운영   
<br>

__디케이테크인__   
*2018.02 - 2020.05 (2년 4개월)*   
- 서버·네트워크 장애 대응
- 업무용 웹페이지 개발 및 유지보수
- 데이터센터 자산 관리
<br>
<br>

## 🗂️ Project
__Kubernetes·솔루션 설치 자동화__   
*2024.02 - 현재*   
OpenStack 기반 대규모 인프라 환경에서 Kubernetes와 클러스터용 솔루션의 설치 자동화 및 패키징을 담당하여 설치·검증 프로세스를 표준화하는 프로젝트입니다.
- 기존 Kubeadm 기반 Kubernetes 수동 설치 절차를 Ansible기반 설치 자동화하여 고객사 환경 기준 평균 설치 소요 시간 약 80% 단축에 기여
- Kustomize 중심의 수동 배포 체계를 Helm 기반 템플릿으로 재구성하여 환경별 설정 관리와 재배포 안정성을 강화
- 솔루션 설치 및 검증 절차를 문서화하고 표준 가이드로 정리하여 신규 인력 및 사내·파트너사 대상 설치 교육 진행
사용기술 : Ansible, Helm, Shell script   

<br><br>
__CI/CD 운영 · 표준화__   
*2024.02 - 현재*   
프로젝트를 진행할 때마다 각 고객사 환경에 맞춰 새로운 브랜치를 만들고, 파이프라인을 생성해서 수동으로 빌드하여 이미지 파일을 업로드 후 배포하는 반복된 작업을 자동화한 프로젝트입니다.
- Jenkins 기반 CI(빌드·이미지 생성/Push)와 Argo CD 기반 GitOps CD(배포 동기화)로 파이프라인을 표준화하여 고객사 환경별 반복 배포 작업을 자동화하여 일 배포 횟수 100% 감소
- 사용기술 : Jenkins, ArgoCD, GitOps

<br><br>
__사회보장정보원__   
*2025.12 - 2025.12*   
자사 Openstack 솔루션 설치와 검증을 수행한 프로젝트입니다.
- Kubernetes 인프라 구축
  - Openstack 환경 VM에서 Kubernetes 클러스터 구축
  - TUI 버전 Ansible 기반 Kubernetes 설치 자동화 적용으로 설치 소요 시간 80% 단축하는 데 기여
- 모니터링 시스템 구성
  - Prometheus, Grafana, Thanos, Alertmanager를 활용한 모니터링 환경 구축
  - MinIO를 활용한 스토리지 솔루션 구성
- 솔루션 검증 및 테스트 수행 매뉴얼을 활용하여 작업 기간 40% 단축

<br><br>
__국방통합데이터센터__   
*2023.10 - 2025.07*   
자사 CMP 솔루션 설치와 검증 및 HPA 전 과정을 수행한 프로젝트입니다.
- CMP 솔루션 운영 및 유지보수
  - 자사 CMP 솔루션 운영 및 유지보수 상주 근무
  - 시스템 안정성 확보를 위한 지속적인 모니터링 및 장애 대응
- 버전 업그레이드 및 성능 최적화
  - 보안 정책 및 방화벽 정책 확인 및 적용
  - 자사 CMP 솔루션 버전 업그레이드를 위한 Kubernetes 환경 Ansible Shell Script를 활용하여 설치 기간 80% 단축
  - 솔루션 설치·검증·HPA 테스트까지 전 과정 수행
  - Helm Packaging을 활용한 제품 설치로 설치 기간 40% 단축
  - HPA 정책 최적화를 통한 리소스 효율성 20% 개선
- 사용기술: Kubernetes, Ansible, Helm
<br>

<br><br>
__하나금융TI__   
*2024.06 - 2024.10*   
반복되는 배포 작업의 불편함을 개선하고자 GitLab 기반 CI/CD 파이프라인 구축 및 배포 자동화를 기획하고 구현하여 배포 소요 시간을 70% 단축한 프로젝트입니다.
Architecture   
<img width="823" height="343" alt="gitlab-cicd" src="https://github.com/user-attachments/assets/487b6a31-b05a-4f9a-9e93-9176ae06d814" />   
- GitLab CI/CD 파이프라인 구축
  - GitLab 기반 파이프라인 기획 및 구성하여 배포마다 반복되는 패키징 작업과 파일 반입 절차를 간소화
  - 배포 소요 시간 약 70% 단축
- 배포 안정성 개선
  - GitLab Runner 구성 및 .gitlab-ci.yml 스크립트를 통해 배포 안정성 향상
  - 장애 발생률 약 30% 감소 달성
- 인프라 구성 및 솔루션 배포
  - Kubernetes 클러스터 구축 및 솔루션 설치
- 사용기술: Kubernetes, Ansible, Jenkins, Nexus, Harbor, SCM-Manager, SonarQube, GitLab, GitLab-runner
<br>
<br>

## ✏️ 자격증 및 교육
[자격] __정보처리기사__   
*2018.08* 한국산업인력공단

[자격] __리눅스마스터2급__   
*2017.12* 한국정보통신인력개발센터

[교육] __T아카데미 ASAC 웹풀스택 개발자 양성__   
*2022.09 - 2023.03* 대한상공회의소

[교육] __프로젝트 기반의 Spring Cloud 개발자 양성__   
*2020.05 - 2020.07* KOSTA
