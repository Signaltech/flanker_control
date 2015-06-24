# Веб-приложение для мониторинга и загрузки конфигурации на NodeJS

## Установка
https://github.com/ildarka/flanker_control/archive/master.zip

## Установка NodeJS
Под Windows нужно установить NodeJS, в папке /distrib находятся 32-х и 64-х разрядные версии

## Установка PM2
Зайти в папку с приложением в консоли и набрать 
```
npm install
```

## Запуск и остановка приложения
+ Для запуска в консоли и набрать npm start.
+ Для остановки в консоли и набрать npm stop.
В Windows надо добавить команду запуска приложения в скрипт автозагрузки

## Мониторинг приложения
Приложение можно контролировать через pm2. 
Более подробно по ссылке https://www.npmjs.com/package/pm2

## Работа с приложением
После запуска приложение будет доступно по адресу http://localhost в Windows
или http://localhost:3000 в Linux

## Структура папок и файлов
+ configs/ — загруженные конфигурации
+ distrib/ — зависимости для Windows
+ node_modules/ — npm-модули
+ public/ — клиентская часть приложения
+ tmp/ — папка для временного хранения конфигураций
+ mock.sh — скрипт для тестирования под Linux
+ package.json — служебный файл
+ reboot.bat — скрипт перезапуска ОС (написать)
+ server.js — серверная часть приложения
+ server.log — лог действий пользователя
+ state.dnt — состояние входов/выходов (написать скрипт)
