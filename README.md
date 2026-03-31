## 시그널 크래프트 ML 서버
### 202604
### 목적
1. PoC 검증
2. 스테이징 전 테스트

### 배포 전략
feature/xxx → main → GitHub Environment로 분기
                    ├── train environment  → Cloud Run Jobs
                    └── inference environment → Cloud Run