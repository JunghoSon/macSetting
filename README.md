# Mac Setting


### * brew

#### 설치
https://brew.sh/

#### brew로 설치한 패키지를 전역적으로 사용 설정
1. vi ~/.bash_profile - vi 편집기로 .bash_profile 파일 생성 또는 실행
2. export PATH="/usr/local/Cellar:$PATH" - 작성
3. source .bash_profile - ~ 경로 에서 실행



### * git

#### 설치
1. brew install git

#### 자동완성
1. git-completion.bash 파일 다운 및 생성(Macintosh HD > 사용자 > 사용자명 > 에 저장 및 생성)
2. vi ~/.bash_profile - vi 편집기로 .bash_profile 파일 생성 또는 실행
3. #!/bin/bash - bash프로그램을 실행 선언
4. source ~/git-completion.bash - 작성



### * mongodb

#### 설치
1. brew install mongodb - 설치
2. sudo mkdir -p /data/db - 폴더 생성
3. sudo chown $USER /data/db - 권한 부여
4. mongod - mongodb 실행
5. mongo - mongodb shell 실행



### * node

#### pkg로 설치한 node 삭제
https://stackoverflow.com/questions/11177954/how-do-i-completely-uninstall-node-js-and-reinstall-from-beginning-mac-os-x

#### node 설치
1. brew search node - stable version확인
2. brew install node@version --without-npm - 설치(version에 따라 변경)
3. vi ~/.bash_profile - vi 편집기로 .bash_profile 파일 생성 또는 실행
4. export PATH="/usr/local/Cellar/node@version/0.0.0/bin:$PATH" - 작성(version에 따라 변경)
5. source .bash_profile - ~ 경로 에서 실행

#### npm 설치
1. brew install npm
