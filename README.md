# PaperDesk-Downloads

PaperDesk의 Mac 및 Windows 실행 파일을 배포하는 저장소입니다. 로컬 PDF를 읽으면서 요약과 메모를 남기고, 논문마다 태그와 읽기 상태를 정리할 수 있습니다.

[Mac·Windows 다운로드](https://github.com/Jusond-code/PaperDesk-Downloads/releases) · [버전별 변경 기록](CHANGELOG.md)

## 주요 기능

- **PDF 보관함** — PDF와 폴더를 추가하고, 제목을 검색하거나 태그와 읽기 상태로 논문을 찾습니다. PDF는 원래 위치에 두고 앱에서 참조합니다.
- **메모와 논문 연결** — 읽으면서 메모를 남기고, 관련 논문을 연결해 함께 찾아볼 수 있습니다.
- **AI 요약과 논문 질문** — 설정에서 OpenAI 또는 Claude를 선택합니다. 열린 PDF를 요약하거나, PDF에서 선택한 구절과 이전 답변을 첨부해 질문할 수 있습니다.
- **PDF 원문 링크** — 요약이나 답변에 표시된 쪽 번호를 눌러 근거가 있는 PDF 페이지로 이동합니다.

AI 기능을 사용하려면 선택한 제공자의 API 키가 필요합니다. 요약이나 질문을 보낼 때 해당 기능에 필요한 PDF 텍스트가 선택한 제공자에게 전송되며 API 사용량이 발생할 수 있습니다.

## 설치 및 업데이트

- **Mac** — Apple Silicon, macOS 14 이상. ZIP을 풀고 `PaperDesk.app`을 응용 프로그램 폴더로 옮겨 실행하세요. 이후에는 앱 메뉴 **PaperDesk → 업데이트… → GitHub**에서 새 버전을 확인할 수 있습니다.
- **Windows** — Windows 10/11 x64. 릴리스에서 `.exe`를 받아 실행하세요. 새 버전은 릴리스에서 설치 파일을 받아 설치합니다.

0.3.0에서 OpenAI·Claude 선택, PDF 선택문 첨부, 이전 답변 인용, 답변의 원문 페이지 링크, Windows 첫 설치판을 추가했습니다. [전체 변경 기록](CHANGELOG.md)
