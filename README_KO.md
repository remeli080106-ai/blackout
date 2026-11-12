# BLACKOUT 리디자인 업데이트

## 포함 파일
- `index.html`: 홈, 3단계 덮어쓰기 흐름, 기록, 설정, 잠깐 쉬어가기 화면
- `sw.js`: 서비스 워커 캐시 버전 갱신
- `manifest.webmanifest`: 새 라벤더 테마 색상
- `icon.svg`: 앱 아이콘

## GitHub Pages 업데이트
1. ZIP 압축을 풉니다.
2. 저장소 `blackout`에서 Add file → Upload files를 선택합니다.
3. 이 폴더의 파일 4개를 저장소 루트에 업로드하고 기존 파일을 교체합니다.
4. Commit changes를 누릅니다.
5. 배포가 완료된 뒤 사이트를 새로고침합니다.

## 데이터
기존 `blackout_pwa_entries_v1` localStorage 키와 기존 기록 필드를 유지합니다. 기존 기록은 계속 표시되며 새 기록에는 감정 선택 필드가 추가됩니다. 기존 기록을 보존하려면 브라우저 데이터/사이트 데이터를 삭제하지 마세요.
