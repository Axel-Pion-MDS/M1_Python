# Python

## Requirements

- [x] Docker

## Jupiterlab

```shell
docker pull jupyter/all-spark-notebook
docker run -p 10000:8888 jupyter/all-spark-notebook
```

### Get the token
```shell
2023-02-03 13:16:43 [C 2023-02-03 12:16:43.038 ServerApp] 
2023-02-03 13:16:43     
2023-02-03 13:16:43     To access the server, open this file in a browser:
2023-02-03 13:16:43         file:///home/jovyan/.local/share/jupyter/runtime/jpserver-7-open.html
2023-02-03 13:16:43     Or copy and paste one of these URLs:
2023-02-03 13:16:43         http://2febc5d6824d:8888/lab?token=theToken <-- get this token
2023-02-03 13:16:43      or http://127.0.0.1:8888/lab?token=theToken <-- Or this one, it's actually the same
```

## Python
```shell
docker compose up --build -d
```

## Run `main.py` script
```shell
docker compose up
```
