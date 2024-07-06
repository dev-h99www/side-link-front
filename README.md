# 개발환경
## 환경설정 : 
 - nvm으로 node 16.15.0버전 설치
 - docker 설치(테스트용)

# 명령어
## 로컬환경 테스트
 1. npm install
 2. npm run build(도커 이미지 생성을 위한 명령어 /build 폴더 기반으로 이미지 생성)
 3. docker build -t side-react . (side-react 이름의 이미지 생성)
 4. docker run -p 3000:3000 side-react
이후 localhost:3000으로 접속해 컨테이너 실행 확인