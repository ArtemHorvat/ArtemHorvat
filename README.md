# Hi there 👋

## About Me

Практикующий Data Engineer. Проектирую и разрабатываю ETL/ELT-пайплайны, системы хранения данных и аналитические платформы.

Работаю со стеком:

`Python` • `SQL` • `Airflow` • `Spark` • `Greenplum` • `ClickHouse` • `PostgreSQL` • `dbt` • `S3/MinIO` • `Docker`

---

## Projects

### Pipeline: API → S3 → Greenplum → ClickHouse

**Repository:** https://github.com/ArtemHorvat/pet-pipeline

Полноценный Data Engineering проект, демонстрирующий построение аналитической платформы на современном стеке.

**Функциональность:**

* Получение данных из New York Times API
* Загрузка сырых данных в S3/MinIO
* Обработка и хранение данных в Greenplum
* Построение слоев `stage`, `ods` и `mart` с помощью dbt
* Загрузка витрин в ClickHouse
* Оркестрация процессов через Airflow
* Сбор технических логов выполнения DAG в PostgreSQL

**Стек:**
`Airflow` • `Python` • `Spark` • `S3/MinIO` • `Greenplum` • `dbt` • `ClickHouse` • `PostgreSQL` • `Docker`

---

### from_csv_to_sql

**Repository:** https://github.com/ArtemHorvat/from_csv_to_sql

Платформа для загрузки, анализа и массовой миграции табличных данных в PostgreSQL.

**Функциональность:**

* Загрузка CSV-файлов / excel
* Анализ структуры данных
* Многопоточная обработка с использованием multithreading
* Массовая загрузка данных в PostgreSQL

**Стек:**
`Python` • `PostgreSQL` • `SQLAlchemy` • `Multithreading`

---

## Contact

Telegram: https://t.me/ArtemHorvat
