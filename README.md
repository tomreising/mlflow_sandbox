# Getting Started
open a terminal in the current working directory and run
``` bash
docker compose --env-file config.env up -d --build
```
when done run
``` bash
docker compose down
```

To access the MlFlow UI go to localhose:5000  
  
for full docs see https://blog.min.io/setting-up-a-development-machine-with-mlflow-and-minio/