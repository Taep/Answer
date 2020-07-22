
## Overview
윈도우 클라이언트의 경력이 대부분인 제가 웹프론트 또는 웹백엔드의 분야로 커리어를 이어가는것이 쉽지 않음을 알고 있습니다.
다만, 대단하지도 특출나지도 않았지만 꾸준히 나름의 경력과 경험을 쌓으면서 얻은 점은 
어떤 분야이던 빠르고 성실하게 적응하고 익힐 수 있는 점이라고 생각합니다. 

이런 부분을 조금이라도 보여드리기 위해 웹 기반으로 이력서 작성하고 이 내용을 Github 환경으로 공유드립니다.


## Start
- 이력서는 parcel.js 으로 개발하였습니다.
- Parcel을 선정한 이유는 학습 및 빌드가 쉽고 정적 페이지를 만드는데 적합하다 라는 정보를 얻을 수 있었기 때문입니다.
- 기존에 무료로 만들어 두었던 azure vm에 언제든 올려두었습니다. 언제는 이력서 열람이 가능합니다!

## Installation
```shell
$ git clone https://github.com/Taep/Answer.git
$ cd career
$ yarn install
```

1. 프로젝트를 clone합니다. 
```shell
$ git clone https://github.com/Taep/Answer.git
```
2. simple-resume 폴더로 이동합니다. `cd simple-resume`
3. yarn을 통해 package를 설치합니다. `yarn install`

## How to use
```shell
$ npm run start
```
- run your program, go to http://localhost:1234

1. src/index.html을 내용을 수정합니다.
2. package.json에서 진입 파일을 확인/설정/수정합니다. src/index.html
```json
       `scripts`,
       {
         'start': 'parcel src/index.html',
		 'build': 'rm -rf docs; parcel build -d docs --public-url /resume src/index.html'
       },
   ```
3. http://localhost:1234 에서 이력서를 확인할 수 있습니다.

## Demo
* 서한호 이력서
<http://52.231.76.187:1234/>

