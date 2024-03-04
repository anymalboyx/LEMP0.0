COPY nginx.conf /etc/nginx/nginx.conf

# Устанавливаем рабочую директорию
WORKDIR /usr/share/nginx/html

# Определяем порт, который контейнер будет использовать
EXPOSE 80

# Команда для запуска NGINX в режиме демона
CMD ["nginx", "-g", "daemon off;"]
