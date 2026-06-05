# Cotton Tip (면봉상사) Project

(사)면봉상사 공식 웹사이트 프로젝트입니다.

## 폴더 구조 (Project Structure)
- `docs/`: PRD, 설계 문서 및 `rules.md`를 보관합니다.
- `working/`: 실제 코딩 및 파일 생성 등 모든 작업이 이루어지는 공간입니다.
- `Original/`: 중요 코드/파일 변경 및 삭제 전 원본 백업 폴더입니다.
- `trash_bin/`: 삭제 예정 파일들을 임시 보관하는 휴지통입니다.
- `tests/`: 작성된 기능이 제대로 동작하는지 검증하는 테스트 코드가 위치합니다.

## 실행 방법
1. `working/` 폴더 안의 파일들을 웹 서버(Apache + PHP)에 배포합니다.
2. `working/index.html`이 메인 페이지입니다.
