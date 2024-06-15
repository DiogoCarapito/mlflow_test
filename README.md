[![Github Actions Workflow](https://github.com/DiogoCarapito/python_project_template/actions/workflows/main.yaml/badge.svg)](https://github.com/DiogoCarapito/mlflow_test/actions/workflows/main.yaml)

# mlflow tests
mlflow tests
(https://github.com/mlflow/mlflow/tree/master/examples/sklearn_logistic_regression)[https://github.com/mlflow/mlflow/tree/master/examples/sklearn_logistic_regression]

## cheat sheet

### venv
create venv
```bash
python3 -m venv .venv
```

activate venv
```bash
source .venv/bin/activate
```

### MLFlow
```bash
mlflow server --host 127.0.0.1 --port 8080
```

### Docker
build docker image
```bash
docker build -t main:latest .
```

