# 11-03-ELK Kondakov Pavel

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.  

![alt text](https://github.com/PavelKondakov22/11-03-ELK/blob/main/z1.png)


---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.  

![alt text](https://github.com/PavelKondakov22/11-03-ELK/blob/main/z2.png)  

**На этом этапе понял, что ютиться на виртуальной машине не очень-то и удобно, установил docker desktop. Работал через него.** 
---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*  

![alt text](https://github.com/PavelKondakov22/11-03-ELK/blob/main/z3.png)  

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.   
![alt text](https://github.com/PavelKondakov22/11-03-ELK/blob/main/z4.png)


*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*
