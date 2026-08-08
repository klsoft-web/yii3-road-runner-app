# YII3-ROAD_RUNNER-APP

The repository contains the [YII3 application template](https://github.com/yiisoft/app) and the additional configuration required to run Yii with RoadRunner.

## How to use

 1. Clone the repository.
 2. Run `composer install`.
 3. Run `./vendor/bin/rr get --no-config  --no-interaction`.
 4. Start the application: 
    ```bash 
    ./rr serve
    ```
Open your browser to the URL [http://localhost:8080](http://localhost:8080)

## How to use with Docker

 1. Clone the repository.
 2. Start the application: 
    ```bash 
    docker compose up -d 
    ```
Open your browser to the URL [http://localhost:8080](http://localhost:8080)

## Additional configuration has been added to the YII3 application template

 1. Added  "yiisoft/yii-runner-roadrunner": "^3.2" to the `composer.json`.
 2. Added `worker.php`.
 3. Added `.rr.yaml`.
 4. Added `Dockerfile`.
 5. Added `docker-compose.yml`.
 6. Modified `.dockerignore`.
