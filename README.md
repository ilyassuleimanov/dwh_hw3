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
