계시록 암기 v4.0 Stable 배포 안내

포함 내용
- 요한계시록 404절 기본 본문 내장
- 모바일 화면 최적화
- GitHub Pages 배포 가능
- PWA 홈 화면 설치 가능
- 친구는 링크만 눌러 바로 사용 가능
- 학습기록/오답노트/암기현황은 사용자 브라우저별로 따로 저장됨

중요
- ZIP 파일을 모바일에서 직접 여는 방식은 권장하지 않습니다.
- GitHub Pages에 올린 뒤 링크로 공유하는 방식을 추천합니다.

GitHub Pages 업로드 순서
1. https://github.com 접속
2. Sign up 또는 Log in
3. 오른쪽 위 + 버튼 > New repository
4. Repository name 예시: revelation-memory
5. Public 선택
6. Create repository 클릭
7. Add file > Upload files 클릭
8. 이 ZIP을 압축 해제한 뒤 안의 파일들을 모두 업로드
   - index.html
   - app.js
   - style.css
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
   - README.txt
9. Commit changes 클릭
10. Settings > Pages 이동
11. Build and deployment > Source: Deploy from a branch
12. Branch: main / root 선택 후 Save
13. 1~3분 후 주소 생성
   예시: https://사용자이름.github.io/revelation-memory/

모바일 설치 방법
iPhone Safari:
1. GitHub Pages 링크 열기
2. 하단 공유 버튼
3. 홈 화면에 추가
4. 추가

Android Chrome:
1. GitHub Pages 링크 열기
2. 오른쪽 위 점 3개
3. 홈 화면에 추가 또는 앱 설치
4. 추가

업데이트 방법
- 같은 GitHub 저장소에 새 파일을 다시 업로드하면 링크는 그대로 유지됩니다.
- 친구들은 같은 링크로 최신 버전을 사용할 수 있습니다.

Version 5.0
- 백업 상태 표시 추가
- 마지막 백업 날짜/시간 기록
- 7일 이상 백업 없음: 백업 권장 알림
- 30일 이상 백업 없음: 위험 상태 표시
- 백업 파일명에 생성 시각 포함
- 백업 저장 후 완료 안내 개선
- 백업 불러오기 후 복원 기록 저장
- 기존 기능과 디자인 변경 최소화

Version 5.1
- 모바일 Safari에서 접기 버튼과 카드가 겹쳐 보이는 문제 보정
- 설정 > 초기화 제목 줄바꿈 문제 보정
- 모바일 공부 캘린더에서 현재/최고 스트릭을 같은 줄로 배치
- 월 표시 중앙 정렬 유지
- 백업 불러오기 실패 안내 메시지 개선
- 기존 기능과 디자인 변경 최소화

Version 5.2
- 모바일에서 책갈피/즐겨찾기 열기·삭제 버튼 가로 정렬
- 모바일에서 읽기 시작·읽기 기록 저장 버튼 가로 정렬
- 오답노트/오늘의 복습 실행 버튼을 접기 버튼 아래쪽에 정리
- 시험 피드백에서 '정답입니다.' 줄바꿈 방지
- 시험 피드백 접기 버튼을 아래쪽으로 배치
- 기존 기능 변경 없음

Version 5.3
- 구버전 백업(v3.x) 불러오기 호환성 개선
- 백업 JSON 검증 로직 보강
- 파일 파싱 오류와 화면 렌더링 오류를 분리해 안내
- 설정 데이터 복원 시 v5 기본 설정과 병합
- 불러오기 후 파일 선택값 초기화
- 기존 기능 변경 없음
