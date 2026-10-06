# Dockerfile do portal institucional da Cooperativa AgroVale
FROM nginx:1.27-alpine

LABEL maintainer="Victor Henrique" \
      matricula="26128554"

# Copia o site para a pasta de onde o Nginx serve os arquivos
COPY html/ /usr/share/nginx/html/

EXPOSE 80
