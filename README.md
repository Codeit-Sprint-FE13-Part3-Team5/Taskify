# Taskify

코드잇 스프린트 13기 Part 3 과정에서 5팀이 진행한 중급 프로젝트 **Taskify** 레포지토리입니다.

## 🗂️ 폴더 구조

```
📂 public                         # 공개 정적 파일 디렉토리
│
├── 📂 logo                       # 로고 이미지
│
├── 📂 icon                       # 아이콘 이미지
│
├── 📂 page-modal                 # 각 페이지 또는 모달에 필요한 이미지
│
│
📂 src                            # 소스 코드 루트 디렉토리
│
├── 📂 actions                    # 서버 액션 관리
│
├── 📂 app                        # Next.js app 디렉토리
│   │
│   ├── 📂 page-path              # 각 페이지 경로에 해당하는 컴포넌트
│
├── 📂 components                 # 컴포넌트 관리
│       │
│       ├── 📂 common             # 공통 컴포넌트 관리
│       │   │
│       │   ├── 📂 common-name    # 각 공통 컴포넌트 컴포넌트
│       │
│       ├── 📂 page-modal         # 각 페이지 또는 모달에 사용하는 컴포넌트
│
├── 📂 constants                  # 상수 값 관리
│
├── 📂 hooks                      # 커스텀 훅 관리
│
├── 📂 utils                      # 유틸리티 함수 관리
│
├── 📄 types.tsx                  # 타입 정의

```

## ✅ 컨벤션

### 타입

- **feat** : 새로운 기능 추가
- **fix** : 버그 수정
- **docs** : 문서 내용 변경
- **style** : 코드 스타일 변경(코드 포메팅, 코드 변경이 없는 경우)
- **design** : 사용자 UI 디자인 변경(CSS 등)
- **refactor** : 코드 리팩토링
- **test** : 테스트 코드 작성
- **build** : 빌드 파일 수정
- **ci** : CI 설정 파일 수정
- **perf** : 성능 개선
- **chore** : 빌드 수정, 패키지 매니저 설정, 운영 코드 변경이 없는 경우
- **rename** : 파일명 혹은 폴더명을 수정한 경우
- **remove** : 파일 삭제만 한 경우

### 커밋 메세지

```
타입: 요약
```

### 브랜치명

```
타입/#이슈번호/내용
```

### 이슈 제목

```
[타입] 내용
```

### PR 제목

```
타입: #이슈번호/내용
```
