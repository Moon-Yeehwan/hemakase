# 💇‍♀️ 헤마카세(Hemakase) – AI 기반 헤어스타일 분석 프로젝트

**헤마카세**는 미용실 이용자들을 위한 AI 기반 스타일 분석 및 커뮤니케이션 시스템입니다.  
딥러닝 기반 이미지 분석을 통해 사용자의 얼굴 이미지에서 헤어영역을 분리하고, 다양한 스타일을 시뮬레이션하거나 추천하는 기능을 목표로 합니다.

---

## 📁 프로젝트 구조

hemakase/
├── ai-model/
│   ├── hair_transfer.py
│   ├── requirements.txt
│   └── networks/
│       ├── deeplab_v3_plus.py
│       ├── mobile_hair.py
│       └── pspnet.py
├── assets/
│   └── images/
│       ├── dongchan.png
│       └── unu.png
└── .gitignore


### 🚀 실행 방법

1. 패키지 설치
pip install -r ai-model/requirements.txt

2. 실행
python ai-model/hair_transfer.py


#### 사용 기술

Python, PyTorch

DeepLab v3+, PSPNet

이미지 세그멘테이션

미용실 고객 UX 개선
