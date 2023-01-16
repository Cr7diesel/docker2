Для создания контейнера REST APi сервера выполните команду из директории проекта:
    docker build -t any_project .

Для запуска контейнера выполните команду:
    docker run --name=project_test -d -p 8000:8000 any_project