# NVM (MAC)
* NVM 은 Node Version Manager 

## 설치
### nvm 설치
* $ brew install nvm

### path 등록
* $ mkdir ~/.nvm
* $ vi ~/.zshrc

### .zshrc 파일 변경
* export NVM_DIR="$HOME/.nvm"
  [ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && \. "/opt/homebrew/opt/nvm/nvm.sh"  # This loads nvm
  [ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion

### 변경 적용
* $ source ~/.zshrc

### 확인
* $ nvm --version

## 사용
### 업그레이드
* $ nvm upgrade

### 설치할(된) node 버전 확인
* $ nvm list

### 특정 버전 node 설치
* $ nvm install v18.12.1
* $ nvm install lts/hydrogenxw

### 현재 사용중인 node 버전 확인
* $ nvm current 

### 원하는 버전 선택
* $ nvm use v18.12.1

### 특정 버전 삭제
* $ nvm uninstall v16

## etc
### node Release schedule 확인
* https://github.com/nodejs/release#release-schedule

