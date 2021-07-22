# traffic-light

# Проект "Traffic Light" на Vue.js
------------------

## Доступен по ссылке: https://traffic-light-mocha.vercel.app

## Описание
Имитация работы светофора.
Через определенное время меняет сигнал вместе с роутом (/red, /yellow, /green).
Реализован счетчик, который показывает сколько времени осталось до переключения. За 3 секунды до переключения сигнал начинает мигать.
Можно передвигаться по роутам сигналов вручную и светофор будет продолжать работу в штатном режиме (в соответствии с включенным сигналом).
После перезагрузки страницы счетчик продолжает работу с того же места.

## Технологии
Проект сделан на Vue.js с использованием Vue Router.

## Установка
1. Клонирование репозитория:
    + git clone https://github.com/Rodion257/traffic-light.git

2. Установить зависимости:
    + npm install

3. Запустить:
    + npm run serve