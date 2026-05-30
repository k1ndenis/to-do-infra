# To-Do App Infrastructure

## Быстрый запуск

# Клонируем инфраструктуру вместе с кодом приложений
git clone --recursive https://github.com/k1ndenis/to-do-infra.git
cd to-do-infra

# Настраиваем окружение
cp .env.example .env
# отредактируй .env

# Запускаем
docker-compose up -d