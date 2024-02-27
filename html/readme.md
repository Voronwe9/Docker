Собираем Docker образ.
docker build -t my-nginx-image .

Для запуска контейнера
docker run -d -p 8080:80 my-nginx-image

Проверить можно вбив в браузере.
http://localhost:8080/