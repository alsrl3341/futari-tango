# ふたりの単語帳 · 우리 둘의 단어장

한국어 ⇄ 日本語 기초 단어장 사이트입니다. 서버나 설치가 필요 없는 정적 사이트라서, 이 폴더의 파일을 그대로 올리면 됩니다.

## 파일 구성
- `index.html` — 화면과 학습 기능
- `words.js` — 단어 데이터 (단어를 추가·수정할 때는 이 파일만 바꾸면 됩니다)
- `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — 휴대폰 "홈 화면에 추가"용 아이콘

## GitHub Pages로 올리기 (무료, 계속 유지)
1. github.com에 가입하고 로그인합니다.
2. 오른쪽 위 `+` → `New repository`를 누르고, 이름(예: `futari-tango`)을 적은 뒤 **Public**으로 만듭니다.
3. 만든 저장소 화면에서 `uploading an existing file`(또는 `Add file` → `Upload files`)을 누릅니다.
4. 이 폴더 안의 **파일들**을 전부 끌어다 놓고 `Commit changes`를 누릅니다. (폴더째가 아니라 파일들을 올려야 `index.html`이 맨 위에 놓입니다.)
5. 저장소의 `Settings` → `Pages`에서 Source를 `Deploy from a branch`, Branch를 `main` / `(root)`로 고르고 `Save`를 누릅니다.
6. 1~2분 뒤 같은 화면에 주소가 나옵니다: `https://아이디.github.io/futari-tango/`

수정할 때는 바뀐 파일을 3~4번처럼 다시 올리면 같은 주소에 반영됩니다.

## 알아둘 점
- 진도는 각자 쓰는 브라우저에 저장됩니다. 다른 기기에서는 처음부터 시작해요.
- 발음 듣기는 기기에 들어 있는 음성을 씁니다. 일본어·한국어 음성이 없는 기기에서는 소리가 안 날 수 있어요.
- 휴대폰에서 사이트를 연 뒤 공유 메뉴의 "홈 화면에 추가"를 누르면 앱처럼 아이콘으로 열 수 있어요.
