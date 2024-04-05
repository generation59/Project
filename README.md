# Установка Nexus Repository и проксирование через 80 порт
[![docker](https://img.shields.io/badge/-Docker-464646?style=flat-square&logo=docker)](https://www.docker.com/)
[![Nginx](https://img.shields.io/badge/-NGINX-464646?style=flat-square&logo=NGINX)](https://nginx.org/ru/)
[![Nexus](https://img.shields.io/badge/-NEXUS-464646?style=flat-square&logo=NEXUS)](https://www.sonatype.com/products/sonatype-nexus-repository)
## Использование
Для запуска приложения необходимо выполнить следующие шаги:

1. Клонируем проект на компьютер по SSH.
    ```bash
    https://github.com/generation59/Project.git
    ```
2. Соберите Docker образ:
    ```bash
    docker compose up --build -d
    ```
3. Проверьте работспособность контейнеров:
    ```bash
    docker container -ls
    ```
   Команда выводи список контейнеров
   
5. Проверить работоспособность Nexus можно открыть по локальному IP адресу компьютера
   ```bash
    http://127.0.0.1/
   ```
