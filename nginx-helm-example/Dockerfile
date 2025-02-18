# Используем официальный образ Nginx как базовый
FROM nginx:latest

# Копируем файл index.html в директорию, которая используется Nginx для отдачи веб-страниц
COPY index.html /usr/share/nginx/html/index.html

# Открываем порт 80 для доступа к приложению
EXPOSE 80
