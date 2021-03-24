FROM base
RUN apt update

EXPOSE 22

COPY ./id_rsa.pub /root
COPY ./start.sh /root

#WORKDIR /var/www/html
#RUN curl -sS https://getcomposer.org/installer | php 
#RUN mv composer.phar /usr/local/bin/composer
#RUN chmod +x /usr/local/bin/composer

RUN dos2unix /root/start.sh 
RUN chmod +x /root/start.sh
ENTRYPOINT [ "/root/start.sh" ]

#entrypoint usuario,sudoers,ssh
#main
#tail -f /dev/null
