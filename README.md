# project_deploy
Проект для деплоя приложения из нескольких модулей.  


1) Склонировать в одной директории все модули данного проекта, в том числе этот (с docker-compose.yml) 
2) В этой же директории создать файл .env и задать в нем необходимые переменные окружения. Пример:  
    POSTGRES_USER=example_user  
    POSTGRES_PASSWORD=example_password  
    POSTGRES_DB=example_mydatabase  
    DB_INIT_SCRIPT=./DB/creation_scripts.sql  
3) docker compose up -d
