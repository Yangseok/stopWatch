# stopWatch
스탑워치가 맥용으로 유료길래 웹기술인 일렉트론으로 만들어 보았습니다.
집으로 다운받던 깃클론을 받던 하여, dist폴더 안에 stopwatch-darwin-x64폴더 안에
stopWatch.app를 응용프로그램에 넣어 사용하시면 되겠습니다.
작동법은 간단합니다 start를 누르면 스탑워치가 실행되고, stop을 누르면 멈춥니다.
형식은 시간 : 분 : 초 이렇게 증가합니다.
혹시 윈도우나 여타 다른데 빌드하시려면 
node를 다운받고 개발환경은 6.6.9 버전입니다.
npm install 하여 기존 의존성 모듈들을 다운받으시고,
상황에 맞게 빌드하시면 되겠습니다.
혹시 맥에서 변경하시려면, 기존 설치된 패키지를 통해서 아래 명령어를 실행하여 dist폴더에 새로이 변경된 파일을 빌드 하실 수 있습니다.
./node_modules/.bin/electron-packager ./ stopWatch --platform=darwin --arch=x64 --out dist
