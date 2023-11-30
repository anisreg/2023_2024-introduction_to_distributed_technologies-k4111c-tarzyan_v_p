University: [ITMO University](https://itmo.ru/ru/) <br>
Faculty: [FICT](https://fict.itmo.ru) <br>
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies) <br>
Year: 2023/2024 <br>
Group: K4111c <br>
Author: Tarzyan Vera Pavlovna <br>
Lab: Lab2 <br>
Date of create: 30.11.2023 <br>
Date of finished: 30.11.2023 <br>

# Лабораторная работа №2 "Развертывание веб сервиса в Minikube, доступ к веб интерфейсу сервиса. Мониторинг сервиса."

### Описание
В данной лабораторной работе вы познакомитесь с развертыванием полноценного веб сервиса с несколькими репликами.

### Цель работы
Ознакомиться с типами "контроллеров" развертывания контейнеров, ознакомится с сетевыми сервисами и развернуть свое веб приложение.

### Ход работы
1. Был запущен Minikube <br>
![image](images/img1.png)
2. Был создан Deployment с двумя репликами контейнера из указанного образа <br>
![image](images/img1.png)
3. Был создан Service для доступа к подам <br>
![image](images/img3.png)
4. Был запущен Deployment и Service <br>
![image](images/img4.1.png)
5. Был проверен статус подов <br>
![image](images/img5.png)
6. Были проброшены порты через minikube <br>
![image](images/img6.png)
7. Была проверена страница на веб-браузере <br>
![image](images/img7.png)
![image](images/img8.png)
8. Были проверены логи контейнеров <br>
![image](images/img9.png)

### Вывод
В результате выполнения работы ознакомились с типами "контроллеров" развертывания контейнеров, был создан сервис, через который был предоставлен доступ на эти "поды". Была проверена страница на веб-браузере. Были проверены логи контейнеров. Также была создана схема организации контейеров и сервисов нарисованная в draw.io. <br>
![image](images/picture8.png)
