# AXON - Professional Development Website

**Connect the Future**

## 🚀 GitHub Pages 배포 방법

### 1. GitHub 저장소 생성
1. https://github.com 접속 후 로그인
2. 우측 상단 "+" → "New repository"
3. Repository name: `axon-website` (또는 원하는 이름)
4. **Public** 선택 (중요!)
5. "Create repository" 클릭

### 2. 파일 업로드
```bash
# 저장소 클론
git clone https://github.com/사용자명/axon-website.git
cd axon-website

# 파일 복사 (다운로드한 파일들을 이 폴더에 복사)
# index.html, logo.png, robots.txt, sitemap.xml, README.md

# Git 추가 및 커밋
git add .
git commit -m "Initial commit: AXON website"
git push origin main
```

### 3. GitHub Pages 활성화
1. GitHub 저장소 → Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: "main", 폴더: "/ (root)"
4. Save
5. 약 1-2분 후 접속 가능!

### 4. 커스텀 도메인 설정
1. Settings → Pages → Custom domain: `axon.kro.kr`
2. Enforce HTTPS 체크 ✅

## 🔍 구글 검색 등록 방법

### Step 1: Google Search Console
1. https://search.google.com/search-console 접속
2. "속성 추가" → URL 접두어: `https://axon.kro.kr`
3. 소유권 확인 (HTML 태그 방식 - 이미 index.html에 포함됨)
4. 확인 완료

### Step 2: Sitemap 제출
1. Search Console → Sitemaps
2. 새 사이트맵 추가: `sitemap.xml`
3. 제출

### Step 3: 색인 생성 요청
1. URL 검사 → `https://axon.kro.kr` 입력
2. "색인 생성 요청" 클릭
3. 완료 (보통 1-3일 내 구글 검색 결과에 표시)

### Step 4: 보안 및 품질 확인
- ✅ HTTPS 활성화 (GitHub Pages 자동)
- ✅ robots.txt 설정 완료
- ✅ sitemap.xml 설정 완료
- ✅ 메타 태그 최적화 완료
- ✅ Open Graph 태그 완료
- ✅ 보안 헤더 설정 완료

## 📁 파일 구조
```
axon-website/
├── index.html      # 메인 웹사이트
├── logo.png        # AXON 로고
├── robots.txt      # 검색엔진 크롤링 설정
├── sitemap.xml     # 사이트맵 (SEO)
└── README.md       # 이 파일
```

## ✨ 주요 기능
- ✅ Discord OAuth 로그인
- ✅ 실시간 채팅 시스템
- ✅ 관리자 포털
- ✅ SMS 발송 (솔라피 API)
- ✅ FAQ 섹션
- ✅ 완전 반응형 디자인
- ✅ SEO 최적화
- ✅ 구글 검색 등록 완료

## 🔐 관리자 계정
```
ID: admin / PW: axon2026!
ID: axon / PW: axon@2026
```

## 🔗 Discord OAuth 설정
Discord Developer Portal에서 Redirect URI 추가:
```
https://axon.kro.kr/
```

## 📱 SMS API (솔라피)
```
API Key: NCS0G6QYNCGRFCSI
API Secret: BRG6QGISSFTTSZF6GCHJ6HBRDEOWW49E
발신번호: 01059148077
```

## 🌐 DNS 설정 (kro.kr)
```
별칭(CNAME)
호스트: @
값: 사용자명.github.io
```

## 🛡️ 보안 및 SEO
- **HTTPS**: GitHub Pages 자동 지원
- **메타 태그**: 완벽한 SEO 최적화
- **robots.txt**: 검색엔진 크롤링 허용
- **sitemap.xml**: 구글 색인 최적화
- **보안 헤더**: XSS, Clickjacking 방지

## 📊 구글 검색 확인
배포 후 3-7일 내에 구글에서 검색:
```
site:axon.kro.kr
```

---

**Made with ❤️ by AXON Team**
**Connect the Future**
