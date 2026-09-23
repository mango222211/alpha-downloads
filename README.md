# Alpha AI 다운로드

[앱 다운로드 페이지](https://mango222211.github.io/alpha-downloads/) · [최신 릴리스](https://github.com/mango222211/alpha-downloads/releases/latest) · [웹에서 대화](https://spent-undiluted-spring.ngrok-free.dev/)

이 저장소에는 공개 앱 배포 파일과 설치 안내만 있습니다. 서버 개발 소스와 계정 데이터는 포함하지 않습니다.

## v2.0 설치 및 업데이트

- **Windows 10/11 x64:** [설치 프로그램 다운로드](https://github.com/mango222211/alpha-downloads/releases/download/v2.0.0/Alpha-AI-2.0.0-Setup-x64.exe). Setup.exe를 실행하고 설치 마법사를 완료하세요. 필요한 파일 전체와 바탕화면·시작 메뉴 바로가기를 설치합니다. 압축 해제나 PowerShell 명령은 필요하지 않습니다.
- **macOS:** CPU에 맞는 Apple Silicon 또는 Intel용 ZIP을 풀고 Alpha AI.app을 응용 프로그램에 넣으세요.
- **업데이트:** 기존 Alpha를 메뉴 막대 또는 시스템 트레이에서 완전히 종료한 뒤 새 버전을 설치하세요. 로그인·설정 데이터는 보존합니다. 이전 포터블 폴더는 자동 삭제하지 않습니다.
- **Windows 제거:** Windows 설정 → 앱 → 설치된 앱 → Alpha AI에서 제거할 수 있습니다.

v1.8 이상 Windows 업데이트 다운로드는 Setup.exe를 제공합니다. v1.5–1.7의 ZIP 전용 업데이트에는 Setup.exe와 설치 안내가 담긴 호환 ZIP을 제공합니다. v1.4 이하 앱은 최신 배포본을 한 번 직접 설치해야 업데이트 확인 기능을 사용할 수 있습니다. 새 버전 확인과 다운로드를 지원하며 설치는 사용자가 진행합니다. AI 대화는 운영자의 서버가 켜져 있어야 합니다.

## 검증 범위

Python 58개와 Node 109개 검사, 설치 파일 내부 77개 앱 파일의 무결성과 제거 프로그램 포함 여부, 구버전 업데이트 호환성을 확인했습니다. Windows 실제 기기의 설치·업데이트·제거는 아직 확인하지 못했습니다.

현재 개발용 미서명 배포본으로 Windows 코드 서명 및 macOS Developer ID 서명·공증은 적용되지 않았습니다.

## v2.0 서버 이미지 이해
사용자 PC에는 Ollama·이미지 모델 설치가 필요하지 않습니다. 질문 시 최신 화면 한 장을 Alpha 서버로 보내 분석합니다. 전송 동의를 받은 뒤 처리하며, 앱 서버는 화면 원본을 파일·대화 DB에 저장하지 않습니다. 분석 설명은 대화에 남고 이미지 추론 토큰도 집계됩니다. 전체 화면 캡처는 데스크톱 앱에서 지원합니다.
