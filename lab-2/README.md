# Разработка и безопасность веб-приложений
Лабораторная работа №2

Вариант №3. 
Создать в текущей директории текстовый файл с содержимым переменной окружения $PATH и с помощью скрипта ограничить права на чтение только для владельца, запись и запуск запретить всем.

Используя Docker, запустить в контейнере скрипт, разработанный для лабораторной работы №1. В качестве базового образа рекомендуется выбрать alpine:latest. 
Результатом работы должен быть скриншот с окном терминала, в котором выполнена команда docker, запускающая скрипт, вместе с результатом его работы. Если есть дополнительные файлы (docker-compose.yml, Dockerfile и проч.), их нужно прикрепить к заданию.
Замечание: вместо отсутствующего ~/.bashrc можно использовать /lib/sysctl.d/00-alpine.conf

Результат работы представлен ниже
![Image](https://github.com/MYP4/web-security-basics/blob/main/lab-2/lab_2.jpg)
