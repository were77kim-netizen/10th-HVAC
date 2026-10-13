# 2026 제10회 HVAC Engineering 전문가 세미나 웹사이트

약 200명이 참석하는 엔지니어링 세미나를 위한 공식 안내 웹사이트입니다.  
GitHub Pages를 통해 별도의 서버 구축 비용 없이 안정적으로 무료 호스팅되며, 실시간 아젠다 공지, 연사 프로필, 장소 동선 안내, 출석체크 및 설문 참여를 지원합니다.

- **공식 웹사이트:** [https://were77kim-netizen.github.io/10th-HVAC/](https://were77kim-netizen.github.io/10th-HVAC/)
- **저장소 주소:** [https://github.com/were77kim-netizen/10th-HVAC](https://github.com/were77kim-netizen/10th-HVAC)

---

## 📂 프로젝트 구조

```text
├── index.html                   # 메인 세미나 공식 웹페이지 (일정표, 강사 프로필, 장소 동선, 모바일 플로팅 버튼)
├── qr/
│   └── index.html               # 현장 테이블/데스크 비치용 A4 QR코드 인쇄 페이지
├── admin_guide_261014_0001.md   # [운영자 필독] 세미나 운영 및 배포 가이드 매뉴얼
└── README.md
```

---

## 🚀 빠른 시작 및 배포

자세한 운영 및 설정 방법은 [관리자 매뉴얼 (admin_guide_261014_0001.md)](./admin_guide_261014_0001.md)을 참조하세요.

1. 로컬에서 코드 수정 후 아래 명령어로 푸시합니다:
   ```bash
   git add .
   git commit -m "feat: 업데이트 내용"
   git push origin main
   ```
2. 푸시 즉시 약 30초 후 [배포 사이트](https://were77kim-netizen.github.io/10th-HVAC/)에 자동 반영됩니다.