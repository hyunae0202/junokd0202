# junokd02 FREE CMS NO STORAGE

Firebase Storage를 쓰지 않는 무료 버전입니다.
사진 업로드 버튼 대신 GitHub `images` 폴더에 올린 사진 경로를 선택/입력합니다.

## 업로드
압축 풀고 아래를 GitHub에 올리세요.
- index.html
- images 폴더 전체

## Vercel 설정
- Framework: Other
- Build Command: 비우기
- Output Directory: 비우기 또는 ./
- Install Command: 비우기

## 관리자
- 주소: https://junokd02.com/#/admin
- 아이디: junokd02
- 비밀번호: junokd1917!

## 사진 추가 방법
1. GitHub 저장소에서 `images/designers` 폴더로 이동
2. Add file → Upload files
3. 사진 업로드
4. Commit changes
5. 관리자모드에서 디자이너 추가/수정 시 사진 경로 입력:
   예: images/designers/hyejin.jpg

## 갤러리 사진
`images/gallery` 폴더에 넣고:
예: images/gallery/salon-02.jpg

## Firebase
Firestore만 사용합니다. Storage 필요 없습니다.
Firestore 규칙은 테스트 중에는 read/write true로 열어두세요.
