# project_deploy
Проект для деплоя приложения из нескольких модулей.  


1) Создать корневую директорию проекта
2) В корневой директории доздать поддиректорию ./db_data (там будут храниться данные)
3) В корневую директорию склонировать репозитории всех модулей
4) В корневую директорию поместить с docker-compose.yml из этого репозитория
5) В корневую директорию поместить файл .env, пример содержимого:
    POSTGRES_USER=example_user  
    POSTGRES_PASSWORD=example_password  
    POSTGRES_DB=example_mydatabase  
    DB_INIT_SCRIPT=./DB/creation_scripts.sql   
6) docker compose up -d
7) docker compose logs --follow  
