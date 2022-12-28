FROM nginx
    LABEL maintainer="mail@solopenkov.ru"
    
    COPY index.html /usr/share/nginx/html
    ADD custom.conf /etc/nginx/conf.d/

    EXPOSE 8000

    ENV FOO bar

    CMD ["nginx","-g", "daemon off;"]