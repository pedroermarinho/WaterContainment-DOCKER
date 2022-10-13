FROM eclipse-mosquitto:2.0.14

COPY ./config/mosquitto.conf /mosquitto/config/mosquitto.conf
COPY ./docker-entrypoint.sh /

ENTRYPOINT ["sh", "./docker-entrypoint.sh"]

CMD ["/usr/sbin/mosquitto", "-c", "/mosquitto/config/mosquitto.conf"]