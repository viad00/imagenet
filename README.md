# OPTIONS
max_allowed_packet = 16M


CREATE USER 'image'@'localhost' IDENTIFIED BY 'image';
CREATE DATABASE image;
GRANT ALL PRIVILEGES ON image.* TO image@localhost;

# INSTALL
yum install httpd mysqld php php-gd -y

