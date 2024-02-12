# Задание 2
Запуск контейнера:

Заменить при необходимости значение переменных в файле rest_api_container/stocks_products/.env
Собрать образ командой
docker image build rest_api_container/ --tag=netology_vorontsova2
Запустить контейнер командой
docker run --name=netology_vorontsova2_1 -d -p 6060:6060 netology_vorontsova2