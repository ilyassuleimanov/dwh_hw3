# DWH HW4

Поднята grafana, расчитываю на минимальный балл за дз.

Вдохновлялся инструкцией с официального сайта: https://grafana.com/docs/grafana/latest/setup-grafana/installation/docker/

Запуск: 
  1) docker-compose up
  2) ОПЦИОНАЛЬНО: для корректной работы функционала из ДЗ №3 и №2, надо также следовать соответствующей инструкции ниже (dwh_hw3)

Запуск grafana: http://localhost:3000/

# dwh_hw3

Тут поднят только airflow, ETL не делал. 

Вдохновлялся инструкцией с официального сайта: https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html

Запуск: 

  1) docker-compose up airflow-init
  2) docker-compose up
  3) ОПЦИОНАЛЬНО: чтобы работала kafka из ДЗ №2, надо прогнать .ipynb ноутбук, там создаются коннекторы для дебезиума и проверяется работа кафки

Airflow:

  http://localhost:8080/
  
  login: airflow
  
  password: airflow


