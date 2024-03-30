# Домашнее задание к занятию "ELK" - `Курапов Антон`

## Задание 1. Elasticsearch
  * Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. (Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.)

  * Запущенный  Elasticsearch 

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/01_0.PNG)

  * Скрин команды проверки 

 ![alt text](https://github.com/AntonKurapov66/elk_hw/blob/main/img/01_1.PNG)

## Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

## Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

## Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.
  
 
