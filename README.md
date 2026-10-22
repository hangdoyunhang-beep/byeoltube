# 별튜브 LIVE 통합 HTML

- `index.html` 하나에 기존 카메라/화면 공유 데모와 Firebase 설정 및 연결 상태 확인을 합쳤습니다.
- Firebase 상태는 `/connectionTest`를 읽어 확인합니다. `Permission denied`가 뜨면 보안 규칙 또는 인증을 설정해야 합니다. 전체 데이터베이스를 공개하지 마세요.
- 회원가입/로그인, 채팅의 여러 사용자 간 동기화, 별 잔액 저장, 실제 결제/정산, 실제 다중 시청자 라이브 송출은 아직 구현되지 않았습니다.
- ES module을 사용하므로 HTTPS 호스팅(예: GitHub Pages/Netlify)에서 실행하세요. `file://`로 직접 열면 제한될 수 있습니다.
