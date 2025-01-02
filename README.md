## 라이브러리 / 기술 스택
- **Kotlin**

--

## Branch 전략
- **배포용 브랜치**: `main`
- **개발용 브랜치**: `develop`
- **기능별 브랜치**: 맡은 기능에 따라 별도의 브랜치 생성

---

## Issue / PR / Commit 컨벤션
- 형식: `#이슈번호-카테고리/기능명`
  - 예시: `#1-FEATURE/로그인-기능`

---

## Code 컨벤션
1. **파일명 규칙**  
   - Kotlin 파일: CamelCase 사용, 확장자는 `.kt`  
     - 예시: `MainActivity.kt`
   - XML 파일: 소문자 사용, 단어 간 언더바 `_` 사용  
     - 예시: `main_layout.xml`

2. **레이아웃 및 코드 스타일**  
   - `left`/`right` 대신 `start`/`end` 사용
   - **버튼 레이아웃 사용 지양**
   - 필요 시 개발 중 업데이트

---

## Android Studio 버전
- **Koala**

---

## 기타
- **Target SDK**: 34  
- **Min SDK**: 24  
- 개발 시 **에뮬레이터 사용**
