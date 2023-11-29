С помощью Ansible:

В директории hello

ansible -m ping cute (Для проверки доступности, где "cute", имя хоста)

Запускаем playbook.

ansible-playbook deploy.yaml




С помощью докера:

Создаем образ

docker build -t diman035/hello:1.0 .

Прверяем images

docker images

Запускаем контайнер.

docker container run --publish 80:80 --detach diman035/hello:1.0


С помощью docker-compose

docker-compose up
