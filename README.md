# 무한매수법 트래커

라오어 무한매수법 V2.2/V3.0/V4.0 자동 계산 + Finnhub 실시간 시세 연동

## 배포 방법 (Vercel)

### 1단계: GitHub에 올리기
1. GitHub에서 새 저장소 생성 (예: `infinite-buying-tracker`)
2. 이 폴더의 모든 파일 업로드

### 2단계: Vercel 배포
1. vercel.com 접속 → 저장소 연결
2. Environment Variables 설정:
   - `FINNHUB_API_KEY` = Finnhub API 키
3. Deploy 클릭

### 3단계: 핸드폰 홈화면 추가
1. 배포된 URL을 핸드폰 브라우저에서 열기
2. iOS: 공유 → 홈 화면에 추가
3. Android: 메뉴 → 앱 설치 또는 홈 화면에 추가

## API

- `GET /api/quote?symbol=SOXL` → 전일 종가 반환
