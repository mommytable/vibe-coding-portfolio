# Todo Backend

Node.js와 Express를 사용한 Todo 백엔드 API 서버입니다.

## 설치 방법

```bash
npm install
```

## 실행 방법

### 개발 모드
```bash
npm run dev
```

### 프로덕션 모드
```bash
npm start
```

서버는 `http://localhost:3000`에서 실행됩니다.

## API 엔드포인트

- `GET /` - 서버 상태 확인
- `GET /api/todos` - Todo 목록 조회 (현재 빈 배열 반환)

## 환경 변수

`.env` 파일을 생성하여 환경 변수를 설정할 수 있습니다:

```
PORT=3000
```

## 기술 스택

- Node.js
- Express
- CORS
- dotenv


