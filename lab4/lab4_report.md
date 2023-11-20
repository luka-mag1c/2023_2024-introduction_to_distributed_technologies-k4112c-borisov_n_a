University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)

Year: 2023/2024

Group: K4112C

Author: Borisov Nikita Alexandrovich

Lab: Lab4

Date of create: 18.10.2023

Date of finished: 23.11.2023

# Создаем самоподписанный сертификат

```sh
openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout tls.key -out tls.crt
```
