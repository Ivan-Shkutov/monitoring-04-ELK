## Домашнее задание к занятию 15 «Система сбора логов Elastic Stack»

## Шкутов Иваг Владимирович


### Задание 1

  1. Вам необходимо поднять в докере и связать между собой:

    elasticsearch (hot и warm ноды);
    logstash;
    kibana;
    filebeat.

  2.Logstash следует сконфигурировать для приёма по tcp json-сообщений.

  3. Filebeat следует сконфигурировать для отправки логов docker вашей системы в logstash.

  4. В директории help находится манифест docker-compose и конфигурации filebeat/logstash для быстрого выполнения этого задания.

Результатом выполнения задания должны быть:

  - скриншот docker ps через 5 минут после старта всех контейнеров (их должно быть 5);
  
  - скриншот интерфейса kibana;
  
  - docker-compose манифест (если вы не использовали директорию help);
  
  - ваши yml-конфигурации для стека (если вы не использовали директорию help).

- - - - - 

### Решение:


![1](https://github.com/Ivan-Shkutov/monitoring-04-ELK/blob/main/img/1.png)

![2](https://github.com/Ivan-Shkutov/monitoring-04-ELK/blob/main/img/2.png)

![3](https://github.com/Ivan-Shkutov/monitoring-04-ELK/blob/main/img/3.png)

![4](https://github.com/Ivan-Shkutov/monitoring-04-ELK/blob/main/img/4.png)

![5](https://github.com/Ivan-Shkutov/monitoring-04-ELK/blob/main/img/5.png)

![6](https://github.com/Ivan-Shkutov/monitoring-04-ELK/blob/main/img/6.png)

![7](https://github.com/Ivan-Shkutov/monitoring-04-ELK/blob/main/img/7.png)

![8](https://github.com/Ivan-Shkutov/monitoring-04-ELK/blob/main/img/8.png)









- - - - - 


### Задание 2

  1. Перейдите в меню создания index-patterns в kibana и создайте несколько index-patterns из имеющихся.

  2. Перейдите в меню просмотра логов в kibana (Discover) и самостоятельно изучите, как отображаются логи и как производить поиск по логам.

  3. В манифесте директории help также приведенно dummy-приложение, которое генерирует рандомные события в stdout-контейнера. Эти логи должны порождать индекс logstash-* в elasticsearch. Если этого индекса нет — воспользуйтесь советами и источниками из раздела «Дополнительные ссылки» этого задания.

- - - - - 

### Решение:

![9](https://github.com/Ivan-Shkutov/monitoring-04-ELK/blob/main/img/9.png)

![10](https://github.com/Ivan-Shkutov/monitoring-04-ELK/blob/main/img/10.png)










- - - - - 
