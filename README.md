# Start

## Installation
1. project clone 후 서브모듈 client, server clone
    ```shell
    $ git clone https://github.com/Kim-Yoo-Shin/project.git
    $ cd SoTong
    SoTong$ git clone https://github.com/Kim-Yoo-Shin/client.git
    SoTong$ git clone https://github.com/Kim-Yoo-Shin/server.git
    ```

2. 리액트 npm 패키지 설치
    ```shell
    $ cd client
    client$ npm install
    ```
3. 스프링부트 gradle 빌드
    ```shell
    $ cd server
    server$ ./gradlew build
    ```
# Usage
- 도커 이미지 빌드 및 컨테이너 실행
    ```shell
    $ docker-compose up --build
    ```
- 컨테이너 실행
    ```shell
    $ docker-compose up
    ```
- 컨테이너 다운
    ```shell
    $ docker-compose down
    ```