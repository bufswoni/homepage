[활동 갤러리 사진 넣는 방법]

1. 이 폴더에 사진 파일을 넣으세요 (영문 파일명 권장 — 한글 파일명은 웹에서 깨질 수 있음).
   현재 등록된 사진:
   - conference-01.jpg, conference-02.jpg  (진학 콘퍼런스, 대외활동 / outreach)
   - overseas-01.jpg                        (학생 해외연구 프로그램, 해외프로젝트 / overseas)
   - research-01.jpg                        (동료 교수진 공동 프로젝트, 연구활동 / research)

2. 사진을 더 추가하거나 캡션을 바꾸려면 index.html에서
   "const GALLERY = [" 부분을 찾아 한 줄 추가/수정하면 됩니다.
   tag 종류: 'research'(연구활동) | 'overseas'(해외프로젝트) | 'outreach'(대외활동)
   예) { src: 'photos/research-02.jpg', caption: '세미나 발표', tag: 'research' },

3. 사진 파일이 없는 항목(예: 위 예시처럼 추가했는데 파일이 아직 없을 때)은
   홈페이지에 자동으로 placeholder 카드로 표시됩니다.
