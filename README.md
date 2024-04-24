## Команда для сборки образа
* docker build -t my-nginx .

## Командра для запуска контейнера
* docker run --name my-nginx-server -d -p 8081:80 my-nginx

## Командра для отправки запроса
* curl localhost:8081
