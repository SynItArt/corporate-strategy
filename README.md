# 대표님 재무전략 프레젠테이션

GitHub Pages를 통한 자동 배포용 파일 모음입니다.

## 📁 파일 구조

```
배포용/
├── index.html                          # 자동 리다이렉트 (진입점)
├── 대표님_Intro_202512_공감.html        # 인트로 페이지
├── 법인대표님_Strategy_공감.html        # 종합 안내 페이지
├── StrategyAbled.html                  # 프레젠테이션 + 상담 신청
├── ｓｙｎ.html                          # 상세 프로필
├── 신대식 사진.png                      # 프로필 사진
└── .nojekyll                           # GitHub Pages 설정
```

## 🚀 배포 방법

### 1. GitHub 저장소 생성
1. GitHub에서 새 저장소 생성
2. 저장소 이름: `corporate-strategy` (또는 원하는 이름)

### 2. 파일 업로드
```bash
# 저장소 클론
git clone https://github.com/사용자명/corporate-strategy.git
cd corporate-strategy

# 배포용 폴더의 모든 파일을 루트로 복사
cp -r 배포용/* .

# 커밋 및 푸시
git add .
git commit -m "Initial deployment"
git push origin main
```

### 3. GitHub Pages 활성화
1. 저장소 Settings → Pages
2. Source: `Deploy from a branch`
3. Branch: `main` / `/ (root)`
4. Save

### 4. 접속
- URL: `https://사용자명.github.io/corporate-strategy/`
- 자동으로 `대표님_Intro_202512_공감.html`로 이동

## 📱 사용 흐름

1. **인트로 페이지** (`대표님_Intro_202512_공감.html`)
   - 신대식 소개
   - "한 걸음씩 정리하는 방법 보기" 버튼

2. **종합 안내 페이지** (`법인대표님_Strategy_공감.html`)
   - PART 1~4 개요
   - "여기를 클릭하세요" 버튼

3. **프레젠테이션 페이지** (`StrategyAbled.html`)
   - PART 1~4 상세 프레젠테이션
   - 상담 신청 폼

4. **상세 프로필** (`ｓｙｎ.html`)
   - 신대식 상세 정보

## ✅ 확인 사항

- [x] 모든 파일이 같은 폴더에 있음
- [x] 모든 경로가 상대 경로로 설정됨
- [x] 모바일 호환성 확인
- [x] 외부 리소스 (CDN) 사용 확인

## 🔧 문제 해결

### 파일이 열리지 않을 때
- GitHub Pages가 활성화되었는지 확인
- 파일 경로가 올바른지 확인
- 브라우저 캐시 삭제 후 재시도

### 이미지가 보이지 않을 때
- 파일명에 공백이 있는지 확인
- 대소문자 구분 확인

## 📞 문의

문제가 발생하면 저장소 Issues에 등록해주세요.

