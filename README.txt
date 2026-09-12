주식 매매 관리 PWA v2

파일 구성
- index.html : 메인 앱
- manifest.webmanifest : PWA 설치 정보
- sw.js : 오프라인 캐시
- icon-192.png / icon-512.png : 앱 아이콘

사용 방법
1) PC에서 그냥 확인할 때는 index.html을 브라우저로 열어도 기본 기능은 사용할 수 있습니다.
2) PWA 설치 기능은 HTTPS 또는 localhost 환경에서 동작합니다.
3) GitHub Pages에 이 폴더의 파일들을 그대로 올린 뒤 HTTPS 주소로 접속하세요.
4) Android/Chrome 및 데스크톱 Chrome/Edge는 설치 조건이 충족되면 앱 설치 버튼이 나타날 수 있습니다.
5) iPhone/iPad Safari에서는 공유 버튼 → 홈 화면에 추가를 사용하세요.

데이터
- 브라우저 localStorage에 저장됩니다.
- JSON 전체 백업을 정기적으로 내려받는 것을 권장합니다.
- 이전 stock_manager_v1 데이터가 같은 브라우저에 있으면 최초 실행 시 읽어와 v2 형식으로 사용합니다.
