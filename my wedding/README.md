# 💍 모바일 청첩장 — 정연제 ♥ 윤주영

## 📁 파일 구조

```
/
├── index.html        ← 청첩장 메인 파일
├── wedding.mp4       ← 인트로 영상 (직접 추가)
├── photo1.jpg        ← 신랑 사진 (직접 추가)
├── photo2.jpg        ← 신부 사진 (직접 추가)
├── photo3.jpg        ← 갤러리 사진 (직접 추가)
├── photo4.jpg        ← 갤러리 사진 (직접 추가)
├── photo5.jpg        ← 갤러리 사진 (직접 추가)
└── README.md
```

---

## 🚀 GitHub Pages로 배포하는 방법

### 1단계 — GitHub 계정 만들기
1. https://github.com 접속 → Sign up

### 2단계 — 새 저장소(Repository) 만들기
1. 로그인 후 우측 상단 **+** 버튼 → **New repository**
2. Repository name: `wedding` (원하는 이름)
3. **Public** 선택
4. **Create repository** 클릭

### 3단계 — 파일 올리기
1. 저장소 페이지에서 **uploading an existing file** 클릭
2. `index.html`, `wedding.mp4`, `photo1.jpg` ~ `photo5.jpg` 모두 드래그해서 업로드
3. 하단 **Commit changes** 클릭

### 4단계 — GitHub Pages 활성화
1. 저장소 상단 **Settings** 탭 클릭
2. 왼쪽 메뉴 **Pages** 클릭
3. Source: **Deploy from a branch**
4. Branch: **main** / **/ (root)** 선택 → **Save**
5. 잠시 후 `https://[내 아이디].github.io/wedding/` 주소로 접속 가능!

---

## ✏️ 수정이 필요한 항목

`index.html`을 메모장(또는 VS Code)으로 열어서 아래 항목을 찾아 교체하세요.

| 항목 | 찾을 내용 | 교체할 내용 |
|------|-----------|-------------|
| 신랑 전화번호 | `010-0000-0000` | 실제 번호 |
| 신부 전화번호 | `010-1111-1111` | 실제 번호 |
| 혼주 전화번호 | `010-1234-5678` | 각 실제 번호 |
| 계좌번호 | `123-456789-01234` 등 | 실제 계좌번호 |
| 혼주 이름 | `정OO`, `김OO`, `윤OO`, `강OO` | 실제 이름 |
| 예식 시간/홀 | `5F 그랜드볼룸` | 실제 홀 이름 |

---

## 📱 Netlify로 배포하는 방법 (더 간단)

1. https://netlify.com 접속 → 회원가입
2. **Add new site** → **Deploy manually**
3. 파일 전체를 드래그 앤 드롭
4. 자동으로 주소 생성됨 (예: `https://xxx.netlify.app`)

---

## ❓ 자주 묻는 질문

**Q. 영상이 안 나와요**  
A. `wedding.mp4` 파일이 `index.html`과 같은 폴더에 있는지 확인하세요. 파일명이 정확히 일치해야 합니다.

**Q. 사진이 안 나와요**  
A. `photo1.jpg` ~ `photo5.jpg` 파일명이 정확한지 확인하세요. 대소문자도 구분합니다.

**Q. 카카오맵이 안 나와요**  
A. 카카오맵은 실제 서버에 올렸을 때만 작동합니다. 로컬(내 컴퓨터)에서 파일을 바로 열면 보이지 않아요.

**Q. 모바일에서 영상 소리가 안 나요**  
A. iOS/Android에서 자동재생은 무음(muted)으로만 가능합니다. 이는 브라우저 정책으로 정상입니다.
