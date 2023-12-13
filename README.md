# Kittygram
## Спринт 16: Проект Kittygram

[![Main Kittygram workflow](https://github.com/Kseniya2806/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/andprov/kittygram/actions/workflows/main.yml)

## **Описание проекта**

Проект находится по адресу: https://host28061997kseniya.ddns.net
В github расположен по адресу: https://github.com/Kseniya2806/kittygram_final

## Описание

Cоциальная сеть для обмена фотографиями котиков. Состоит из бэкенд-приложения, написанном на Django, и фронтенд-приложения на React. 
Поддерживает регистрацию и авторизацию.
С помощью данного сервиса вы сможете добавить нового котика на сайт или изменить существующего, а также просмотреть котиков других пользователей.


## Технологии

- Python 3.7
- Django
- Django REST Framework
- PostgreSQL
- Node.js
- React
- Gunicorn
- Nginx
- Docker
- GitHub Actions


## Как развернуть проект

1. Клонируйте репозиторий и перейдите в него в командной строке:
```bash
  git clone https://github.com/Kseniya2806/kittygram_final
  cd kittygram
```

2. В папке ```kittygram/``` создайте файл ```.env``` по образцу

```bash
  POSTGRES_DB=kittygram
  POSTGRES_USER=kittygram_user
  POSTGRES_PASSWORD=kittygram_password
  DB_NAME=kittygram
  DB_HOST=db
  DB_PORT=5432
```

3. Добавьте в Secrets на GitHub Actions следующие переменные:
```

`DOCKER_USERNAME` _#  логин на Docker Hub_

`DOCKER_PASSWORD` _# пароль на Docker Hub_

`SSH_KEY` _# закрытый SSH-ключ для подключения к серверу_

`SSH_PASSPHRASE` _# пароль от этого ключа_

`USER` _#и мя пользователя на сервере_

`HOST` _# IP-адрес сервера_

`TELEGRAM_TO` _# ID телеграм-аккаунта для сообщений об успешном деплое_

`TELEGRAM_TOKEN` _# токен телеграм-бота_
```

4. При отправке коммита в ветку `main` с помощью `push` будет выполнен полный деплой проекта. 
Подробности в файле [main.yml](https://github.comKseniya2806/kittygram_final/.github/workflows/main.yml).

## Как развернуть проект
Автор Ксения Заболоцкая
Github https://github.comKseniya2806/