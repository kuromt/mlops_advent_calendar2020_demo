```
git clone https://github.com/kuromt/mlops_advent_calendar2020_demo.git
```




How to Run
---

- change current directry to `docker-compose`.

```
cd docker-compose
```

- prepare `.env` for MySQL.

```.env
MYSQL_ROOT_PASSWORD="mlflow"
MYSQL_DATABASE="mlflow"
MYSQL_USER="mlflow"
MYSQL_PASSWORD="mlflow"
```

- Run containers

```
docker-compose up -d
```

How to install a mlflow plugin
---

- install the mlflow plugin python package in notebook container.

```
pip install git+http://xxxx
```