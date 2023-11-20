University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)

Year: 2023/2024

Group: K4112C

Author: Borisov Nikita Alexandrovich

Lab: Lab4

Date of create: 18.11.2023

Date of finished: 23.11.2023

# Развернул 2 ноды с плагином Calico
![image](https://github.com/luka-mag1c/2023_2024-introduction_to_distributed_technologies-k4112c-borisov_n_a/assets/55001395/6658cf91-dacd-41bd-a942-2af2fbf8c88c)

# Удалил дефолтный IPPool 
![image](https://github.com/luka-mag1c/2023_2024-introduction_to_distributed_technologies-k4112c-borisov_n_a/assets/55001395/c00282ea-bab9-4d5d-86d0-862b967d8cfa)

# Пометил ноды
![image](https://github.com/luka-mag1c/2023_2024-introduction_to_distributed_technologies-k4112c-borisov_n_a/assets/55001395/87eac717-5e0a-4a1e-bdd1-38118d64164d)

# Применил манифест для создания IPPool для виртуальных стоек
![image](https://github.com/luka-mag1c/2023_2024-introduction_to_distributed_technologies-k4112c-borisov_n_a/assets/55001395/307cd4b7-7d1f-456f-9131-05107412f191)

# Развернул приложение 
![image](https://github.com/luka-mag1c/2023_2024-introduction_to_distributed_technologies-k4112c-borisov_n_a/assets/55001395/349638e2-d3ff-4854-8dbe-d92e24799b4a)

# Пробросил порт и открыл страницу в браузере
![image](https://github.com/luka-mag1c/2023_2024-introduction_to_distributed_technologies-k4112c-borisov_n_a/assets/55001395/2692ac0a-13fa-4849-bd49-ebaa8aab1acc)

![image](https://github.com/luka-mag1c/2023_2024-introduction_to_distributed_technologies-k4112c-borisov_n_a/assets/55001395/6b415d7e-bf34-4fec-bcb2-fafda6810732)

# Пропинговал вторую ноду
![image](https://github.com/luka-mag1c/2023_2024-introduction_to_distributed_technologies-k4112c-borisov_n_a/assets/55001395/f9d12cd4-8426-4558-8ba1-509e63b7e7b6)

# Схема
![image](https://github.com/luka-mag1c/2023_2024-introduction_to_distributed_technologies-k4112c-borisov_n_a/assets/55001395/ac95a508-411b-4940-8217-55c57323521f)

```sh
openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout tls.key -out tls.crt
```
