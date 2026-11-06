# Agent Team Studio 설치 파일

Windows x64 서버와 브라우저/PWA로 AI 팀을 설계하고 실행하는 앱입니다. 이 저장소는 공개 설치 파일과 SHA-256 체크섬만 배포합니다. 원본 소스, 사용자 데이터와 키는 포함하지 않습니다. 설치 파일의 실행 코드·리소스는 추출될 수 있습니다.

[최신 릴리스](https://github.com/HeesungYang1/Agent-Team-Studio-releases/releases/latest)에서 설치 EXE와 `SHA256SUMS.txt`를 받으세요. 현재 설치 파일은 **미서명**입니다. PowerShell의 `Get-FileHash 설치파일.exe -Algorithm SHA256` 결과를 체크섬과 대조하고 Windows의 보안 확인 절차를 따르세요.

설치는 현재 사용자 범위이며 Node 런타임과 한국어 오프라인 도움말을 포함합니다. 시작 메뉴의 **최초 관리자 등록** 후 **Agent Team Studio**를 실행합니다. Windows 서버가 켜져 있어야 접속·작업을 사용할 수 있습니다. 기존 관리 서버와 데이터는 임의로 이전하지 않습니다.

사용자 데이터는 `%LOCALAPPDATA%\AgentTeamStudio`에 보관하며 업데이트·제거 시 유지됩니다. 업데이트 전 데스크톱 서버를 정상 종료하고 새 설치 파일을 같은 위치에 실행하세요. PWA 화면은 업데이트 알림에서 미저장 초안을 내보낸 후 적용합니다.

지원: Windows 10/11 x64 서버, PC Chrome/PWA. Android/iPhone은 반응형 웹 접속을 제공하지만 이번 릴리스의 실제 기기 설치·복귀 검증은 완료하지 않았습니다. 별도 APK·IPA는 없습니다. 공급자 CLI·계정·키와 Tailscale 원격 공개는 별도로 설정해야 합니다. 실행은 텍스트 업무이며 PC 파일·셸 도구를 제공하지 않습니다. 연결별 지원·미검증 범위는 릴리스 변경 내역과 앱의 **도움말**을 확인하세요.
