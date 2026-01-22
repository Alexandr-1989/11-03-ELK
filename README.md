Задание 1. Elasticsearch  
  
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.  
Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.  
Ответ:  
<img width="606" height="331" alt="Screenshot_6" src="https://github.com/user-attachments/assets/9cfd2149-112d-4f11-ae8b-7fcd27b1a9f3" />  
Задание 2. Kibana  
  
Установите и запустите Kibana.  
Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.  
Ответ:  
<img width="2139" height="730" alt="Screenshot_9" src="https://github.com/user-attachments/assets/4bd20ba1-181b-48a7-accd-32ce8419afa5" />  
Задание 3. Logstash  
  
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.  
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.  
Ответ:  
  
Задание 4. Filebeat.  
  
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.  
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.  
Ответ:  
   
