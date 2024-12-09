# maze-game

```
project-root/
├── src/                   # 소스 코드 디렉터리
│   ├── main.cpp           # 메인 파일 (엔트리 포인트)
│   ├── menu.cpp           # 메인 메뉴 및 난이도 선택 화면
│   ├── menu.h             # 메뉴 관련 헤더
│   ├── maze.cpp           # 미로 생성 및 렌더링
│   ├── maze.h             # 미로 생성 관련 헤더
│   ├── player.cpp         # 플레이어 이동 관련 로직
│   ├── player.h           # 플레이어 관련 헤더
│   └── utils.cpp          # 공용 유틸리티 함수 (ex: 타이머)
│
├── assets/                # 이미지, 폰트, 사운드 리소스 파일
│   ├── sounds/            # 효과음, 배경음악
│   └── fonts/             # 폰트 파일
│
├── include/               # 외부 라이브러리 및 사용자 정의 헤더
├── build/                 # 빌드 파일 (Makefile, CMakeLists.txt)
├── bin/                   # 빌드된 실행 파일
└── README.md              # 프로젝트 설명 파일
```