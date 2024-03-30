# Домашнее задание к занятию "ELK" - `Курапов Антон`

## Задание 1. Elasticsearch
  * Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. (Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.)

  * Запущенный  Elasticsearch 

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/01_0.PNG)

  * Скрин команды проверки 

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/01_1.PNG)

## Задание 2. Kibana
  * Установите и запустите Kibana.(Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty)
  
  * Запущенная Kibana

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/02_0.PNG)

   * Скрин из Kibana 

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/02_1.PNG)


## Задание 3. Logstash
  * Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.(Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.)

  * Скрин конф.файла /etc/logstash/conf.d/nginx.conf

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/03_0.PNG)

   * Скрин из Kibana с логами nginx

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/03_1.PNG)


## Задание 4. Filebeat.
  * Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.(Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.)

   * Скрин конф.файла /etc/filebeat/filebeat.yml

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/04_0_0.PNG)

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/04_0_1.PNG)

   * Скрин из Kibana с логами nginx отправленные через Filebeat

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/04_1.PNG)

 
