# Домашнее задание к занятию «Конфигурация приложений» - Тертерян Вячеслав

---

### Задание 1  

Создать Deployment приложения и решить возникшую проблему с помощью ConfigMap. Добавить веб-страницу.  

1. Создать Deployment приложения, состоящего из контейнеров nginx и multitool.
2. Решить возникшую проблему с помощью ConfigMap.
3. Продемонстрировать, что pod стартовал и оба конейнера работают.
4. Сделать простую веб-страницу и подключить её к Nginx с помощью ConfigMap. Подключить Service и показать вывод curl или в браузере.
5. Предоставить манифесты, а также скриншоты или вывод необходимых команд.  

Ответ:  

Скрин 1  
![alt text](https://github.com/Marsianec/homework23-8/blob/main/img/1.png)  

Скрин 2  
![alt text](https://github.com/Marsianec/homework23-8/blob/main/img/2.png)  

Скрин 3  
![alt text](https://github.com/Marsianec/homework23-8/blob/main/img/3.png)  

---

### Задание 2  

Создать приложение с вашей веб-страницей, доступной по HTTPS.  

1. Создать Deployment приложения, состоящего из Nginx.
2. Создать собственную веб-страницу и подключить её как ConfigMap к приложению.
3. Выпустить самоподписной сертификат SSL. Создать Secret для использования сертификата.
4. Создать Ingress и необходимый Service, подключить к нему SSL в вид. Продемонстировать доступ к приложению по HTTPS.
5. Предоставить манифесты, а также скриншоты или вывод необходимых команд.  

Ответ:  

Скрин 1  
![alt text](https://github.com/Marsianec/homework23-8/blob/main/img/4.png)  

Скрин 2  
![alt text](https://github.com/Marsianec/homework23-8/blob/main/img/5.png)  

Скрин 3  
![alt text](https://github.com/Marsianec/homework23-8/blob/main/img/6.png)  

Скрин 4  
![alt text](https://github.com/Marsianec/homework23-8/blob/main/img/7.png)  
