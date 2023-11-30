University: [ITMO University](https://itmo.ru/ru/) <br>
Faculty: [FICT](https://fict.itmo.ru) <br>
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies) <br>
Year: 2023/2024 <br>
Group: K4111c <br>
Author: Tarzyan Vera Pavlovna <br>
Lab: Lab3 <br>
Date of create: 30.11.2023 <br>
Date of finished: 30.11.2023 <br>

# ЛЛабораторная работа №3 "Сертификаты и "секреты" в Minikube, безопасное хранение данных."

### Описание
В данной лабораторной работе вы познакомитесь с сертификатами и "секретами" в Minikube, правилами безопасного хранения данных в Minikube.

### Цель работы
Познакомиться с сертификатами и "секретами" в Minikube, правилами безопасного хранения данных в Minikube.

### Ход работы
1. Был запущен Minikube <br>
![image](images/img1.png)
2. Был создан ConfigMap со значениями переменных <br>
![image](images/img2.png)
3. Был создан ReplicaSet, в который былы переданы указанные переменные <br>
![image](images/img3.png)
4. Был создан tls секрет, в который были прописаны созданные приватный и публичный ключи <br>
![image](images/img4.png)
5. Был создан Service для приложения <br>
![image](images/img5.png)
6. Был создан Ingress, в который были переданы ключи из секрета, а также был указан путь, по которому будет доступно приложение <br>
![image](images/img6.png)
7. Был произведён деплой <br>
![image](images/img7.png)
8. Был включён Ingress в Minikube <br>
![image](images/img8.png)
9. Был проложен сетевой туннель между локальным компьютером и кластером Kubernates <br>
![image](images/img9.png)
10. Для пользователей MacOS/Windows необходимо указывать в hosts localhost, что и было сделано. Хотя в документации сказано, что в hosts надо указывать ip minikube. Как позже выяснилось, эта информация актуальна только для Linux <br>
![image](images/img10.png)
11. Была проверена страница на веб-браузере <br>
![image](images/img11.png)
12. Сертификат <br>
![image](images/img12.png)


### Вывод
В результате выполнения работы ознакомились с сертификатами и  "секретами" в Minikube, правилами безопасного хранения данных в Minikube. Была проверена страница на веб-браузере. Также была создана схема организации контейеров и сервисов нарисованная в draw.io. <br>
![image](images/img13.png)