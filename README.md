# Airflow Sandbox
Creates a AirFlow sandbox environment in docker desktop

## Startup 
Run these command 

``echo -e "AIRFLOW_UID=$(id -u)" > .env``

``docker compose up airflow-init``

To start environemnt run 

``docker compose up``

To stop environment run 

``docker compose down``
