<p align="center">
  <a href="https://www.chromatic.com/">
    <img alt="Chromatic" src="https://avatars2.githubusercontent.com/u/24584319?s=200&v=4" width="60" />
  </a>
</p>

<h1 align="center">
  Chromatic's Intro to Storybook tutorial code
</h1>

이 레포지토리에는 스토리북 소개 튜터리얼을 위한 리액트 및 스토리북 주요 구성 파일들이 보관되어 있습니다.

## 🚅 빠른 시작

1.  **레포지토리를 클론해주세요.**

    다음 코드를 로컬 환경에서 실행해주세요.

    ```shell
    # Clone the template
    git clone https://github.com/chromaui/learnstorybook-code.git
    ```

1.  **의존성 설치**

    복제한 레포지토리로 이동해 필요한 의존성 패키지를 설치합니다.

    ```shell
    # Navigate to the directory
    cd learnstorybook-code/

    # Install the dependencies
    yarn
    ```

1.  **소스 코드를 열고 수정해보세요!**

    애디터에서 `learnstoybook-code` 디렉토리를 열고 원하는 내용을 찾아보세요!

1.  **당신의 스토리를 실행해보세요!**

    `yarn storybook` 으로 실행하고 `http://localhost:6006` 를 열어 어떤 스토리가 있는지 확인해보세요.

## 🔎  폴더 구조

    .
    ├── .storybook
    ├── node_modules
    ├── public
    ├── src
    ├── .env
    ├── .gitignore
    ├── package.json
    ├── yarn.lock
    └── README.md

1.  **`.storybook`**: 이 디렉토리에는 스토리북의 [환경설정](https://storybook.js.org/docs/react/configure/overview) 파일들이 담겨 있습니다.

2.  **`node_modules`**: 이 디렉토리에는 프로젝트가 의존하는 모든 모듈이 포함되어 있습니다.

3.  **`public`**: 이 디렉토리에는 사이트 개발 및 프로덕션 필드가 포함되어 있습니다.

4.  **`src`**:  이 디렉토리에는 당신의 앱에 보여질 내욜과 관련된 모든 코드가 담겨 있습니다.

5.  **`.env`**: 앱 환경 변수를 제어하기 위한 간단한 텍스트 환경 파일

6.  **`.gitignore`**: 이 파일은 프로젝트 개발 과정에서 추적하거나 유지 관리하면 안되는 파일들을 git에게 알려줍니다.

7.  **`package.json`**: 프로젝트 메타데이터(예: 프로젝트 이름, 작성자 등)를 포함하는 Node.js 프로젝트 표준 메니페스트 파일. 이 파일을 기반으로 npm(yarn)이 프로젝트에 필요한 패키지를 알 수 있습니다.

8.  **`yarn.lock`**: 이 파일은 프로젝트에 설치된 정확한 버전의 npm 종속성을 기반으로 자동 생성된 파일입니다. **(수동으로 변경하지 마십시오.)**

9.  **`README.md`**: 프로젝트에 대한 유용한 참조 정보가 들어있는 텍스트 파일입니다.

## 기여

레포지토리에 문제가 있다면 Issue를 열어 문의해주세요.

## Learning Storybook

1. Read our introductory tutorial at [Learn Storybook](https://storybook.js.org/tutorials/intro-to-storybook/react/en/get-started/).
2. Learn how to transform your component libraries into design systems in our [Design Systems for Developers](https://storybook.js.org/tutorials/design-systems-for-developers/) tutorial.
3. See our official documentation at [Storybook](https://storybook.js.org/).
