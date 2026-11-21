# 봄날비누공방 홈페이지

터미널 없이 GitHub 웹 화면에서 파일만 올리면 되는 홈페이지예요.

## 처음 한 번만 (GitHub 웹)
1. GitHub에서 **New repository** 로 새 저장소 만들기 (Public)
2. 저장소 화면에서 **Add file → Upload files** → 이 폴더 안의 `index.html`, `README.md`, `images` 폴더를 통째로 끌어다 놓기 → **Commit changes**
3. **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main / (root)** → Save
4. 1~2분 뒤 `https://아이디.github.io/저장소이름/` 에서 열려요

## 사진 바꾸기
`images` 폴더에 들어가서 **Add file → Upload files** 로 아래 이름 그대로 올리면 바뀝니다.

| 파일 | 자리 |
|---|---|
| `images/hero.jpg` | 첫 화면 |
| `images/class-1.jpg` | 어린이 클래스 |
| `images/class-2.jpg` | 기업 체험 |
| `images/class-3.jpg` | 맞춤 주문제작 |
| `images/gallery/` 안의 아무 사진 | 공방의 하루 (무작위로 돌아감) |

- 공방의 하루 사진은 **파일 이름 상관없이** 폴더에 넣기만 하면 돼요. 빼고 싶으면 그 파일을 삭제하면 됩니다.
- 사진은 한 장에 500KB 이하로 줄여서 올리면 빨리 열려요.

## 글자 바꾸기
`index.html` 을 열고 연필 아이콘(Edit) → `[대괄호]` 와 `KAKAO_URL` 을 실제 정보로 바꾸고 **Commit changes**.
