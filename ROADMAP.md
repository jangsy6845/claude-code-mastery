# 개발자 웹 이력서 개발 로드맵

## 📋 프로젝트 개요
HTML, CSS, JavaScript, TailwindCSS를 활용한 반응형 개발자 웹 이력서 포트폴리오 사이트

---

## 🛠️ 기술스택
- **HTML5**: 시맨틱 마크업
- **CSS3**: TailwindCSS 유틸리티 스타일
- **JavaScript**: 인터랙션 및 동적 기능
- **TailwindCSS**: 반응형 디자인 및 스타일링

---

## ✨ 주요 기능

### Phase 1: 기본 구조
- [ ] 헤더/네비게이션 (스크롤 효과)
- [ ] 히어로 섹션 (소개, 프로필 사진)
- [ ] 풋터

### Phase 2: 핵심 콘텐츠
- [ ] 자기소개 섹션
- [ ] 경력/경험 섹션
- [ ] 기술 스택 섹션 (스킬 카드)
- [ ] 프로젝트 포트폴리오 섹션

### Phase 3: 인터랙션
- [ ] 스무스 스크롤
- [ ] 모바일 메뉴 토글
- [ ] 프로젝트 호버 이펙트
- [ ] 다크모드 토글 (선택)

### Phase 4: 최적화 및 배포
- [ ] SEO 메타 태그 추가
- [ ] 반응형 디자인 검증 (모바일/태블릿/데스크톱)
- [ ] 성능 최적화
- [ ] GitHub Pages 또는 Vercel 배포

---

## 📁 프로젝트 구조
```
resume-portfolio/
├── index.html           # 메인 페이지
├── styles/
│   └── style.css       # TailwindCSS + 커스텀 스타일
├── scripts/
│   └── script.js       # 인터랙션 로직
├── assets/
│   ├── images/         # 프로필, 프로젝트 이미지
│   └── icons/          # 기술 아이콘
└── README.md           # 프로젝트 설명
```

---

## 📝 이력서 콘텐츠 구성

### 기본 정보
- 이름, 직급
- 이메일, 깃허브, 링크드인
- 한 문장 소개

### 경력
- 회사명, 직책, 기간 (3개 항목)
- 주요 업무 및 성과

### 기술
- Frontend: HTML, CSS, JavaScript, React, Vue
- Backend: Node.js, Python, Java
- Tools: Git, Docker, AWS

### 프로젝트 (3-4개)
- 프로젝트명, 설명, 기술스택
- 깃허브/라이브 링크

### 교육/자격증
- 학위, 과정, 자격증

---

## 🎯 개발 단계별 예상 일정

| Phase | 작업 | 예상 기간 |
|-------|------|---------|
| 1 | 기본 레이아웃 & 마크업 | 2-3일 |
| 2 | 콘텐츠 추가 & 스타일링 | 2-3일 |
| 3 | 인터랙션 & 애니메이션 | 2일 |
| 4 | 테스트 & 배포 | 1-2일 |

---

## 🚀 시작하기
```bash
# 프로젝트 초기화
git init
git add .
git commit -m "초기 이력서 프로젝트 설정"

# TailwindCSS 설정 (옵션)
npm init -y
npm install -D tailwindcss postcss autoprefixer
```

---

## 📌 추가 고려사항
- 반응형 디자인 우선
- 접근성(A11y) 준수
- 로딩 성능 최적화
- 버전 관리 (깃허브)
