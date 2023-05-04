# 엔트리 개발 환경 설정

<hr>﻿

# 개발환경 준비

## 0. Visual Studio Build Tools 설치

- 보류 / 2022를 설치해도 되는지 2015를 설치해야하는지 불확실. 재확인 후 수정 예정

https://visualstudio.microsoft.com/downloads/?q=build+tools

<br><br>

## 1. python 2.7 설치

- 보류

https://www.python.org/download/releases/2.7/

<br><br>

## 2. node LTS 버젼 설치

최신 LTS인 18.60에서는 프로젝트 빌드에 문제가 있음.

https://nodejs.org/dist/v16.20.0/

<br><br>

## 3. yarn 설치


```ps
npm install --global yarn
```

<br><br><hr><br><br>

# 프로젝트 준비


1. entryjs, entry-hw 모두 별도의 저장소에 fork



2. 각각 프로젝트를 로컬에 clone



3. 각각 프로젝트 모두 브랜치를 변경


```ps
git checkout develop-hw
```

<br><br>

## Entry JS 실행

```ps
yarn installl
```

```ps
yarn run serve
```

<br><br>

## Entry HW 실행

```ps
npm installl
```

```ps
npm run setting
```

```ps
npm run start
```
