# 받아? 쳐내! (3D Mini Game Prototype)

브라우저에서 실행되는 Three.js 미니게임 프로토타입입니다.

## 실행
- `index.html`을 로컬에서 바로 열면 모듈 로딩이 제한될 수 있습니다.
- 가장 쉬운 방법은 GitHub Pages에 배포하는 것입니다.
- 로컬 테스트는 VS Code의 Live Server 확장 또는 `python -m http.server 8000`으로 실행한 뒤 `http://localhost:8000`에 접속하세요.

## 조작
- PC: 화면의 오른쪽 팔 영역을 마우스로 위/아래 드래그하고 놓기
- 모바일: 오른쪽 팔을 손가락으로 위/아래 드래그하고 놓기
- 아래로 드래그: 지갑, 돈, 담배, 모자, 라이터 받기
- 위로 드래그: 돌멩이, 벽돌, 막대기, 수배 전단지, 옥수수, 신문 쳐내기

## 규칙
- 60초 동안 최대한 많은 물건 처리
- 한 물건이 등장한 뒤 3초 안에 결정하지 못하면 게임 종료
- 오답이면 즉시 게임 종료
- 동일 물건은 3회 연속 등장하지 않음
- Three.js는 CDN에서 불러옵니다. 인터넷 연결이 필요합니다.

## GitHub Pages 배포
1. GitHub에서 새 Public repository를 만듭니다.
2. 이 프로젝트의 `index.html`, `README.md`를 저장소 루트에 업로드합니다.
3. 저장소의 Settings → Pages로 이동합니다.
4. Build and deployment에서 `Deploy from a branch`를 선택합니다.
5. Branch는 `main`, folder는 `/ (root)`로 설정하고 Save를 누릅니다.
6. 잠시 기다리면 `https://깃허브아이디.github.io/저장소이름/` 주소로 게임이 공개됩니다.
