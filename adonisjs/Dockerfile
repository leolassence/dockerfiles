FROM node:8
RUN npm i -g @adonisjs/cli
WORKDIR /var/www
COPY init.sh /init.sh
RUN chmod 755 /init.sh
CMD ["/init.sh"]
