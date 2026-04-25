# AXON - Professional Development Website

## 🚀 GitHub Pages 배포 방법

### 1. GitHub 저장소 생성
1. https://github.com 접속 후 로그인
2. 우측 상단 "+" → "New repository"
3. Repository name: `axon-website` (또는 원하는 이름)
4. **Public** 선택 (중요!)
5. "Create repository" 클릭

### 2. 파일 업로드
터미널이나 Git Bash에서:

```bash
# 저장소 클론
git clone https://github.com/사용자명/axon-website.git
cd axon-website

# 파일 복사 (다운로드한 index.html과 logo.png를 이 폴더에 복사)

# Git 추가 및 커밋
git add .
git commit -m "Initial commit: AXON website"
git push origin main
```

### 3. GitHub Pages 활성화
1. GitHub 저장소 페이지에서 "Settings" 클릭
2. 좌측 메뉴에서 "Pages" 클릭
3. Source: "Deploy from a branch" 선택
4. Branch: "main" 선택, 폴더: "/ (root)" 선택
5. "Save" 클릭
6. 약 1-2분 후 `https://사용자명.github.io/axon-website/` 에서 접속 가능!

### 4. 커스텀 도메인 (선택사항)
Settings → Pages → Custom domain에 도메인 입력

## 📁 필요한 파일
- `index.html` - 메인 웹사이트 파일
- `logo.png` - AXON 로고 (보라-파랑 그라디언트 W)
- `README.md` - 이 파일

## ✨ 기능
- ✅ Discord OAuth 로그인
- ✅ 실시간 채팅
- ✅ 관리자 포털
- ✅ SMS 발송 (솔라피 API)
- ✅ FAQ
- ✅ 반응형 디자인

## 🔐 관리자 계정
- ID: `admin` / PW: `axon2026!`
- ID: `axon` / PW: `axon@2026`

## 🔗 Discord OAuth 설정
Discord Developer Portal에서 Redirect URI 추가:
```
https://사용자명.github.io/axon-website/
```

## 📱 SMS API 설정
- API Key: NCS0G6QYNCGRFCSI
- API Secret: BRG6QGISSFTTSZF6GCHJ6HBRDEOWW49E
- 발신번호: 01059148077

---

Made with ❤️ by AXON Team
