# Використання базового образу Ubuntu
FROM ubuntu:latest

# Оновлення пакетів та встановлення Apache2
RUN apt-get update && apt-get install -y apache2

# Старт сервера Apache
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]