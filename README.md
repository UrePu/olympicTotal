# OlympicTotal

**OlympicTotal**는 React와 Vite를 사용하여 개발된 웹 애플리케이션으로, 올림픽 메달 집계 데이터를 시각화하여 제공합니다.

## 주요 기능

- **국가별 메달 집계**: 각 국가의 금, 은, 동메달 수를 확인할 수 있습니다.
- **국가별 수정 편의성**: 각 국가별로 클릭하면 바로 값이 입력되어 수정을 편하게 했습니다.
- **국가별 or 메달별 or 메달 총합 정렬**: 각 항목별로 헤더를 클릭하면 정렬 하도록 했습니다.

## 설치 및 실행 방법

1. **리포지토리 클론**:

   ```bash
   git clone https://github.com/UrePu/olympicTotal.git
   cd olympicTotal
   ```

2. **의존성 설치**:

   ```bash
   yarn install
   ```

3. **개발 서버 실행**:

   ```bash
   yarn dev
   ```

   브라우저에서 `http://localhost:5173`로 접속하여 애플리케이션을 확인할 수 있습니다.

## 프로젝트 구조

- **/src**: 주요 소스 코드 디렉토리
  - **/components**: React 컴포넌트 모음
  - **/assets**: 이미지 및 스타일 파일
  - **App.jsx**: 메인 애플리케이션 컴포넌트

## 사용된 기술 스택

- **프론트엔드**: React, JavaScript, CSS
- **번들러**: Vite
