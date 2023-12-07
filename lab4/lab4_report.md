University: [ITMO University](https://itmo.ru/ru/) <br>
Faculty: [FICT](https://fict.itmo.ru) <br>
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies) <br>
Year: 2023/2024 <br>
Group: K4111c <br>
Author: Tarzyan Vera Pavlovna <br>
Lab: Lab4 <br>
Date of create: 6.12.2023 <br>
Date of finished: 7.12.2023 <br>

# Лабораторная работа №4 "Сети связи в Minikube, CNI и CoreDNS"

### Описание
Это последняя лабораторная работа в которой вы познакомитесь с сетями связи в Minikube. Особенность Kubernetes заключается в том, что у него одновременно работают underlay и overlay сети, а управление может быть организованно различными CNI.

### Цель работы
Познакомиться с CNI Calico и функцией IPAM Plugin, изучить особенности работы CNI и CoreDNS.

### Ход работы
1. Был запущен Minikube с подключенным плагином calico и двумя нодами <br>
![image](images/img1.png)
2. Было проверено наличие подов calico <br>
![image](images/img2.png)
3. Было проверено наличие двух разных нод <br>
![image](images/img3.png)
4. Были созданы лэйблы нодам <br>
![image](images/img4.png)
5. Был установлен calicoctl для Mac OSX <br>
![image](images/img5.png)
6. Был удален дефолтный ippool <br>
![image](images/img6.png)
![image](images/img7.png)
7. Были созданы собственные ippool<br>
![image](images/img8.png)
8. Было проверено, что наши ippool созданы, был произведён деплой <br>
![image](images/img9.png)
9. Было развернуто приложение с сервисом <br>
![image](images/img10.png)
10. Были проверены ip адреса <br>
![image](images/img11.png)
11. Было подключение к одному из подов и пинганули соседний. Пинг прошел, значит связь между ними есть <br>
![image](images/img12.png)
12. Были проброшены порты сервиса <br>
![image](images/img13.png)
13. Была проверена страница на веб-браузере <br>
![image](images/img14.png)


### Вывод
В результате выполнения лабораторной работы, ознакомились с CNI Calico и функцией IPAM Plugin, а также изучили особенности работы CNI и CoreDNS. Была проверена страница на веб-браузере. Также была создана схема организации контейеров и сервисов нарисованная в draw.io. <br>
![image](images/img15.png)