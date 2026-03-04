# 🌟 나를 응원하는 한마디 (Encouragement Card Maker)

초등학생을 위한 **자기긍정 응원 카드 제작 도구** - localStorage 자동 저장, WCAG 2.1 AA 접근성 준수

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Accessibility: WCAG 2.1 AA](https://img.shields.io/badge/Accessibility-WCAG%202.1%20AA-green)](https://www.w3.org/WAI/WCAG21/quickref/)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red)](https://github.com/plusiam/encouragement-card-maker)

## 📖 프로젝트 소개

**"나를 응원하는 한마디"** 는 초등학생들이 스스로를 격려하고 응원하는 문구를 선택·작성하여, 아름다운 카드로 만들어 저장/인쇄할 수 있는 **인터랙티브 웹 애플리케이션**입니다.

### ✨ 주요 기능

#### 🎯 4단계 프로세스
1. **문구 선택** - 17가지 긍정 문구 중 선택 (다중 선택 가능)
2. **나만의 문구** - 커스텀 응원 문구 직접 작성
3. **결과 확인** - 선택한 문구 미리보기
4. **카드 꾸미기** - 6가지 테마 템플릿으로 카드 완성

#### 💾 localStorage 자동 저장
- 실시간 진행 상태 자동 저장
- 새로고침 후에도 데이터 유지
- 선택한 문구, 템플릿, 학생 정보 모두 복원

#### ♿ 완벽한 접근성 (WCAG 2.1 AA)
- **ARIA 레이블** 완벽 지원
- **키보드 네비게이션** 전체 지원
- **스크린 리더** 완벽 호환
- **포커스 관리** 명확한 시각적 표시

#### 🎨 6가지 카드 테마
- 🌸 봄꽃 정원
- 🌊 바다 하늘
- 🌿 초록 숲속
- ⭐ 반짝 별빛
- 🌈 무지개 빛
- 🔥 열정 불꽃

---

## 🚀 빠른 시작

### 온라인 사용
**[데모 바로가기](https://plusiam.github.io/encouragement-card-maker/)** ← 클릭!

### 로컬 실행
```bash
# 저장소 클론
git clone https://github.com/plusiam/encouragement-card-maker.git

# 디렉토리 이동
cd encouragement-card-maker

# 브라우저로 열기 (로컬 서버 권장)
python3 -m http.server 8000
# → http://localhost:8000 접속
```

---

## 🎓 교육적 가치

### 정서적 목표
✅ **자기긍정감 향상** - 스스로를 격려하는 습관 형성
✅ **내적 동기 부여** - 긍정적 자아상 확립
✅ **감정 인식** - 나에게 필요한 응원 찾기

### 디지털 리터러시
✅ **인터랙티브 웹 도구 경험**
✅ **디지털 콘텐츠 제작** (카드 디자인)
✅ **출력물 생성 과정 이해**

### 포용성 교육
✅ **모든 학생 참여 가능** - 신체적 제약 없이 활동 참여
✅ **다양한 입력 방식** - 마우스, 키보드, 터치, 음성 지원

---

## 🛠️ 기술 스택

| 기술 | 용도 |
|------|------|
| **HTML5** | 시맨틱 마크업, Canvas API |
| **CSS3** | 커스텀 디자인 시스템, 애니메이션 |
| **Vanilla JavaScript** | 순수 JS (프레임워크 없음) |
| **localStorage API** | 진행 상태 자동 저장 |
| **Canvas API** | 카드 템플릿 렌더링 |
| **ARIA** | 접근성 레이블 |

---

## ⌨️ 키보드 네비게이션

| 키 | 기능 |
|----|------|
| `Tab` | 요소 간 이동 |
| `Enter` / `Space` | 선택/실행 |
| `Arrow Left/Right` | 템플릿 이동 |
| `Esc` | 팝업 닫기 |

---

## 📊 접근성 기능 상세

### ARIA 레이블
- 모든 상호작용 요소에 명확한 레이블
- 진행 단계 상태 자동 업데이트
- 선택 상태 실시간 알림 (`aria-live`)

### 키보드 지원
- 완전한 키보드 접근성
- 팝업 포커스 트랩
- 명확한 포커스 표시 (주황색 3px 아웃라인)

### 스크린 리더
- VoiceOver (macOS) 완벽 지원
- NVDA (Windows) 완벽 지원
- 실시간 상태 변경 알림

---

## 📁 프로젝트 구조

```
encouragement-card-maker/
├── index.html              # 메인 애플리케이션 (단일 파일)
├── 개선사항_요약.md         # 개선 이력 문서
├── README.md               # 프로젝트 문서 (이 파일)
└── LICENSE                 # MIT 라이선스
```

---

## 🎯 사용 시나리오

### 1. 학기 시작
자기 이해 및 목표 설정 활동

### 2. 힘든 시기
정서적 지원 및 회복탄력성 강화

### 3. 학급 문화
서로 응원하는 긍정적 분위기 조성

---

## 📈 개선 이력

### v1.1.0 (2026-03-04)
- ✅ **localStorage 기능 추가** - 진행 상태 자동 저장/복원
- ✅ **접근성 개선** - WCAG 2.1 AA 준수
- ✅ **키보드 네비게이션** - 완벽한 키보드 지원
- ✅ **스크린 리더 지원** - 실시간 상태 알림

### v1.0.0 (초기 버전)
- 기본 기능 구현

상세 내용: [개선사항_요약.md](개선사항_요약.md)

---

## 🧪 브라우저 호환성

| 브라우저 | 버전 | 지원 |
|---------|------|------|
| Chrome | 90+ | ✅ |
| Firefox | 88+ | ✅ |
| Safari | 14+ | ✅ |
| Edge | 90+ | ✅ |

**Canvas API 필수**: 일부 구형 브라우저는 지원하지 않습니다.

---

## 🤝 기여하기

기여를 환영합니다! 다음 방법으로 참여하실 수 있습니다:

1. **이슈 제출** - 버그 리포트, 기능 제안
2. **Pull Request** - 코드 개선, 새 기능 추가
3. **문서 개선** - README, 주석 개선

### 기여 가이드라인
1. Fork 후 브랜치 생성
2. 변경사항 커밋
3. Pull Request 생성
4. 코드 리뷰 후 병합

---

## 📝 라이선스

MIT License - 자유롭게 사용, 수정, 배포 가능

Copyright (c) 2026 plusiam

자세한 내용: [LICENSE](LICENSE)

---

## 💡 향후 개선 계획

### 단기
- [ ] 인쇄 전용 CSS 최적화
- [ ] 터치 제스처 개선 (모바일)
- [ ] 색맹 대비 색상 대비 강화

### 중기
- [ ] 다국어 지원 (i18n)
- [ ] 다크 모드
- [ ] 카드 템플릿 커스터마이징

### 장기
- [ ] 교사 대시보드 (학급 전체 카드 모아보기)
- [ ] 소셜 기능 (친구에게 카드 보내기)
- [ ] AI 추천 (감정 상태 기반 문구 제안)

---

## 📞 문의 및 지원

- **GitHub Issues**: [이슈 제출](https://github.com/plusiam/encouragement-card-maker/issues)
- **이메일**: yeohanki@gmail.com

---

## 🙏 감사의 말

이 프로젝트는 **실제 교육 현장의 경험**을 바탕으로 제작되었습니다.
모든 학생이 스스로를 사랑하고 격려할 수 있기를 바랍니다. 💖

---

## 🌟 Star 주세요!

이 프로젝트가 도움이 되었다면 ⭐ Star를 눌러주세요!

---

**Made with ❤️ for educators and students**

[![GitHub stars](https://img.shields.io/github/stars/plusiam/encouragement-card-maker?style=social)](https://github.com/plusiam/encouragement-card-maker/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/plusiam/encouragement-card-maker?style=social)](https://github.com/plusiam/encouragement-card-maker/network/members)
