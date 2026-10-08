# kangeunkim.github.io

김강은 개인 홈페이지 (구글 사이트 https://sites.google.com/view/kangeunkim 이전본)

## 파일 구성

| 파일 | 내용 |
|---|---|
| `index.html` | Home (소개, 학력, 경력, 수상) |
| `publications.html` | Talks & Publications |
| `teaching.html` | Teaching & Projects |
| `book-club.html` | Korean Literature Book Club |
| `style.css` | 전체 디자인 (청자빛 종이·먹·쪽빛·인주 색 체계, 다크 모드 자동 대응) |
| `images/` | 사진 넣는 폴더 |

## 사진

구글 사이트에 있던 사진과 책 표지가 모두 `images/` 폴더에 들어 있어서, 구글 사이트를 지워도 그대로 보입니다. 사진을 바꾸려면 같은 이름의 파일로 덮어쓰면 됩니다.

- `images/eaf2026.jpg` : 홈 화면 사진 (EAF Meets SKKU, 2026년 9월)
- `images/class-2025.jpg` : Teaching 페이지 수업 사진
- `images/books/` : 북클럽 책 표지 8장

## GitHub Pages에 올리기

1. GitHub에서 새 저장소를 만든다. 이름을 `아이디.github.io`로 하면 주소가 `https://아이디.github.io`가 된다.
2. 이 폴더의 파일을 모두 올린다 (웹에서 "Add file → Upload files"로 끌어다 놓아도 됨).
3. 저장소 Settings → Pages → Source를 `Deploy from a branch`, Branch를 `main` / `/ (root)`로 지정한다.
4. 1~2분 뒤 주소로 접속해 확인한다.

## 내용 고치기

새 논문이나 발표를 추가할 때는 `publications.html`에서 같은 해 `<section class="section">` 안의 `<li class="entry" ...>...</li>` 한 줄을 복사해 맨 위에 붙이고 월·제목·학술지·링크만 바꾸면 됩니다. `data-kind`는 article, talk, book, thesis 중 하나로 두면 상단 필터가 그대로 작동합니다. 새해 항목이면 `<section>` 덩어리를 통째로 복사해 연도를 바꿉니다. 상단 요약 문장의 편수와 필터 버튼의 숫자는 직접 고쳐야 합니다.
