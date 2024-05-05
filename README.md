# MLFow Tutorial

## How to Run Locally

### Start app

1. Start service by runing docker image
   ```bash
   docker compose up -d
   ```

### Start services

2. Create our bucket storage by visiting `http://localhost:9000`. use credential defined on docker-compose.yaml to login
3. Create bucket with name mlflow.
4. Access MLflow UI by visiting `http://localhost:5000`
5. And access jupyter lab by visiting `http://localhost:8888`, if prompted password or token use defined token on docker-compose.yaml

### Create Experiment

6. Access `random_forest_regressor_sample.ipynb` through jupyter lab web and run all codes
7. The recorded experiment will be stored in MLflow web
8. Try to create model inside the experiment
9. Run `diabetes_predict.ipynb` through jupyter lab web
10. Finish!
