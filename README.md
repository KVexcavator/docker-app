запустить после изменения
$ docker run -p 3000:3000 dockerapp
если захотим другую команду, например посмотреть Rake задачи
$ docker run --rm dockerapp bin/rails -T


запуск с компосером
$ docker-compose up
в тижои режиме
$ docker-compose up -d
