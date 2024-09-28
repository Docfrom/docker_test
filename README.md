Сборка образа
docker build -t my_nginx:1

Запуск контейнера
docker run --name my_app -d -p 8000:8000 my_nginx:1