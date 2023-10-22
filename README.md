# Список команд для запуска сбора и запуска контейнера:
1. docker build -t=docker_project .
2. docker run -it -d -p 8080:80 --name=changed_nginx docker_project
3. curl localhost:8080/