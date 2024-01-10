Commands:

- To start MLflow UI server:
mlflow ui

- To kill all processes associated with port 5000:
kill -9 $(lsof -i:5000 -t) 2> /dev/null