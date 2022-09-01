FROM nginx:latest

COPY ../multistage /usr/share/nginx/html

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD [ "nginx", "-g", "daemon off;" ]
