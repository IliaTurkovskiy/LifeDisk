
# LifeDisk  
![4840917-middle](https://github.com/Ilcheg/LifeDisk/assets/101619164/22cc702f-31cd-4ad1-a5e2-47631d278fdf)
**LifeDisk** - REST сервис для загрузки файлов и вывода списка уже загруженных файлов пользователя.  
Данное приложение является учебным в рамках моей дипломной работы по профессии Java - разработчик и может быть свободно использовано в образовательных целях.  
*Буду признателен вашим замечаниям, вопросам и пожеланиям: связь со мной здесь в **github или ilcheg@yandex.ru.***
## Основной функционал
1. Авторизация пользователя.
2. Сохранение файла на сервере.
3. Переименование файла на сервере.
4. Скачавание файла с сервера.
5. Удаление файла с сервера.
6. Выход пользователя.
## Работа с сервисом
Работа с сервисом предусматривается через FRONT приложение. Сервис LifeDisk взаимодествует с FRONT согласно api, который можно посмотреть здесь: [yaml-файле](./CloudServiceSpecification.yaml).  
Предусмотрен запуск сервиса через Docker. Используйте docker-compose.yml файл в корне проекта для сборки контейнера сервера и базы данных.
## Запуск LifeDisk и FRONT
1. Установите nodejs (версия не ниже 19.7.0) на компьютер, следуя [инструкции](https://nodejs.org/ru/download/current/).
2. Скачайте [FRONT](./netology-diplom-frontend) (JavaScript).
3. Запустите собранный контейнер lifedisk в Docker.
4. Перейдите в папку FRONT приложения и все команды для запуска выполняйте из неё.
5. Следуя описанию README.md FRONT проекта, запустите nodejs-приложение (`npm install`, `npm run serve`).  
## При разработке были использованы:
*Java 17  
Spring boot  
Maven  
VCS Git  
MySQL  
Docker  
Postman  
IntelliJ IDEA*