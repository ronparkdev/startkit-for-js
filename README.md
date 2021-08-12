# startkit-for-js

## 환경설정

### Mac 이라면

```Bash
# Brew 설치
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

# Node 환경 설치
brew install node npm
npm install -g yarn 
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.0/install.sh | bash

# OhMyZSH 설치
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#### OhMyZSH 설정
```Bash
vi ~/.zshrc
# zshrc 맨 위에 추가
ZSH_DISABLE_COMPFIX="true"
# 중간에 값 찾아서 수정
ZSH_THEME="agnoster" 
```

#### 폰트설치
https://github.com/naver/d2codingfont


### Window 이라면

#### 원기옥을 모으세요
* node : https://nodejs.org/ko/download/
* yarn : https://classic.yarnpkg.com/en/docs/install/#mac-stable

## 실행

```Bash
yarn start
yarn lint
yarn lint:fix
```