# Milvus
The files required to run Milvus.

### get milvus.yaml file 
$ wget https://raw.githubusercontent.com/milvus-io/milvus/v2.4.9/configs/milvus.yaml

### get docker compose file 
$ wget https://github.com/milvus-io/milvus/releases/download/v2.4.9/milvus-standalone-docker-compose.yml -O docker-compose.yml

### start container 
$ sudo docker compose up -d

### stop container 
$ sudo docker compose down

### remove volume
$ sudo rm -rf volumes
