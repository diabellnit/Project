# Project

1. Открыть терминал (или командную строку) и перейти в корневую директорию сервера.
   
cd express-threads-api

3. Переименовать файл .env.local (убрать .local)
.env

5. docker run --name mongo \
       -p 27017:27017 \
       -e MONGO_INITDB_ROOT_USERNAME="monty" \
       -e MONGO_INITDB_ROOT_PASSWORD="pass" \
       -d mongo:latest

4. Запустить команду docker compose которая поднимет сервер, клиент и базу данных

docker compose up
