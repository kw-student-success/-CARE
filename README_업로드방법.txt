Smart KW CARE - GitHub Pages / PWA 배포 파일

GitHub 저장소의 기존 index.html을 이 폴더의 index.html로 교체하고,
다음 4개 파일을 같은 최상위(root) 위치에 업로드하세요.

- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

GitHub Pages:
Settings > Pages > Deploy from a branch > main > /(root)

PC:
일반 웹사이트처럼 브라우저 URL로 이용할 수 있습니다.
Chrome/Edge에서 설치 기능이 제공되면 데스크톱 앱처럼 설치할 수도 있습니다.

모바일:
같은 URL로 접속합니다.
Android/Chrome: 브라우저 메뉴에서 앱 설치 또는 홈 화면에 추가.
iPhone/Safari: 공유 > 홈 화면에 추가.

주의:
이 버전의 커뮤니티 게시물 저장은 기존 HTML 구현을 유지하므로 localStorage 기반입니다.
즉, 작성 게시물이 모든 사용자에게 공유되는 서버 게시판은 아닙니다.
실제 공용 커뮤니티 운영 전 Google Apps Script/Sheets 연동이 필요합니다.
