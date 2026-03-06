# 🐍 Python Project Template

간단하고 강력한 파이썬 기반 애플리케이션 예제 프로젝트입니다.  
이 프로젝트는 FastAPI를 백엔드로 사용하고, Docker 및 CI/CD 환경에서 쉽게 배포할 수 있도록 구성되어 있습니다.

---

## 🚀 프로젝트 소개

이 프로젝트는 RESTful API 서버를 구현하고, 예측 모델이나 데이터 처리 로직을 손쉽게 적용할 수 있는 구조를 제공합니다.

**주요 특징**
- FastAPI 기반의 비동기 REST API 서버
- Docker를 이용한 컨테이너 기반 배포
- GitHub Actions로 자동 테스트 및 배포
- Pydantic을 이용한 안전한 데이터 검증

---

## 🏗️ 프로젝트 구조

```bash
📦 python-project
├── app
│   ├── main.py          # FastAPI 서버 엔트리포인트
│   ├── routers/         # 요청 라우트 관리
│   ├── models/          # 데이터모델 및 스키마
│   ├── services/        # 비즈니스 로직
│   └── utils/           # 공통 유틸리티 함수
├── tests/               # pytest 기반 테스트 코드
├── requirements.txt     # 파이썬 의존성 목록
├── Dockerfile
└── README.md
