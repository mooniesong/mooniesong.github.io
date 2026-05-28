# 📝 My Blog

개인 블로그 홈페이지 — GitHub Pages로 무료 호스팅

---

## 📁 파일 구조

```
my-blog/
├── index.html          ← 메인 홈페이지
├── css/
│   └── style.css       ← 전체 스타일
└── posts/
    ├── post1.html      ← 글 예시 1
    ├── post2.html      ← 글 예시 2
    └── post3.html      ← 글 예시 3
```

---

## 🚀 GitHub Pages 배포 방법

### 1단계 — GitHub 저장소 만들기

1. [github.com](https://github.com) 로그인
2. 오른쪽 위 **+** → **New repository** 클릭
3. 저장소 이름을 정확히 `username.github.io` 로 입력  
   (예: 아이디가 `hong` 이면 → `hong.github.io`)
4. **Public** 선택 후 **Create repository** 클릭

### 2단계 — 파일 업로드

방법 A (웹에서 직접):
1. 저장소 페이지에서 **Add file → Upload files** 클릭
2. 이 폴더 안의 파일 전체 드래그 & 드롭
3. **Commit changes** 클릭

방법 B (Git 명령어):
```bash
git init
git add .
git commit -m "첫 블로그 배포"
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main
```

### 3단계 — GitHub Pages 활성화

1. 저장소 → **Settings** 탭
2. 왼쪽 메뉴 → **Pages**
3. Source → **Deploy from a branch** 선택
4. Branch → **main** / **(root)** 선택
5. **Save** 클릭

### 4단계 — 완료! 🎉

몇 분 후 `https://username.github.io` 에서 블로그 확인!

---

## ✏️ 블로그 커스터마이즈

### 내 정보로 수정하기

`index.html` 에서 아래 항목을 찾아 수정하세요:

| 항목 | 찾을 내용 | 바꿀 내용 |
|------|----------|----------|
| 블로그 이름 | `✏️ My Blog` | 원하는 이름 |
| 소개 이름 | `홍길동` | 본인 이름 |
| 소개 글 | 개발자이자 글 쓰는... | 본인 소개 |
| 태그 | 💻 개발, 📚 독서 등 | 본인 관심사 |
| 이메일 | `your@email.com` | 본인 이메일 |
| GitHub | `yourusername` | 본인 아이디 |

### 새 글 작성하기

1. `posts/post1.html` 파일을 복사해서 새 파일 만들기 (예: `post4.html`)
2. 제목, 날짜, 내용 수정
3. `index.html` 글 목록에 새 카드 추가

---

## 🎨 디자인

- 라이트/다크 모드 자동 전환 지원
- 모바일 반응형
- 순수 HTML/CSS (외부 라이브러리 없음)
