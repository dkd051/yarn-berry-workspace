# Monorepo 학습
- yarn workspace 설정을 통해 다중 패키지 관리
- @koo/lib 패키지를 정의하여 @koo/web의 의존성에 추가하여 import 후 호출하여 사용
- @koo/ui 패키지를 정의하고 생성한 버튼 리액트 컴포넌트를 @koo/web next.js 프로젝트에서 사용
- 공통되는 eslint, prettier, tsconfig 설정을 하나로 통합 및 확장

## Getting Started

First, run the development server:

```bash
npm install yarn -g # yarn이 설치가 되지 않은 경우 yarn 설치

yarn set version berry # 프로젝트 폴더에서 해당 명령어를 실행하여 yarn 2+ 버전 이상 설치합니다. 4.0에서 테스트됨

yarn install # 의존성 모듈들을 내려받습니다.

yarn workspace @koo/web run dev # next.js 프로젝트를 실행합니다.
```

## Reference
[yarn-berry-test](https://github.com/sungkwangkim/yarn-berry-test/tree/main)
