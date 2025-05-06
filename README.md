# Key Journal PWA

일일 시간 관리 및 기록을 위한 Progressive Web App (PWA)

## 주요 기능

- 5분 단위 시간 기록
- 색상별 카테고리 구분
- 시간 통계 및 시각화
- 오프라인 지원
- 모바일 최적화

## 개발 이력

### 2024-03-XX: PWA 설치 경로 수정
- manifest.json의 start_url 수정
- GitHub Pages 배포 환경에 맞는 경로 설정
- iPhone Safari/Chrome에서 정확한 PWA 설치 지원

### 2024-03-XX: 시간 통계 시각화 개선
- 파이 차트 추가로 시간 분포 시각화
- Chart.js 라이브러리 통합
- 각 카테고리별 시간 비율 표시
- 커스텀 범례 추가 (시간, 비율 정보 포함)

### 2024-03-XX: 시간 블록 표시 개선
- 시간 블록 시작/종료 시간 정확도 개선
- 60분 단위 시간 자동 변환 로직 추가
- 연속된 시간 블록 병합 로직 개선

### 2024-03-XX: 색상 팔레트 개선
- 색상 그라데이션 개선
- 모달 창 색상 스와치 2행 배치
- '자기계발' 스와치 타원형으로 변경
- '기타' 카테고리 추가

### 2024-03-XX: 초기 개발
- PWA 기본 구조 설정
- IndexedDB를 이용한 데이터 저장
- 반응형 그리드 레이아웃
- 모바일 터치 이벤트 지원

## 기술 스택

- HTML5
- CSS3
- JavaScript (ES6+)
- IndexedDB
- Chart.js
- Service Worker

## 설치 및 실행

1. 저장소 클론
```bash
git clone https://github.com/greenkey20/key-journal-pwa.git
```

2. 로컬 서버 실행
```bash
python -m http.server 8000
```

3. 브라우저에서 접속
```
http://localhost:8000
```

## PWA 설치 방법

### 데스크톱
1. Chrome 브라우저에서 https://greenkey20.github.io/key-journal-pwa/ 접속
2. 주소창 우측의 설치 아이콘 클릭
3. "Key Journal 설치" 클릭

### 모바일 (iPhone)
1. Safari나 Chrome에서 https://greenkey20.github.io/key-journal-pwa/ 접속
2. 공유 버튼(사파리) 또는 메뉴 버튼(크롬) 클릭
3. "홈 화면에 추가" 또는 "Add to Home Screen" 선택

## 배포

GitHub Pages를 통해 자동 배포됩니다:
https://greenkey20.github.io/key-journal-pwa/

## 라이선스

MIT License