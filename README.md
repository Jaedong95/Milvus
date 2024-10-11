# Milvus
The files required to run Milvus.

#### 01. get milvus.yaml file 
$ wget https://raw.githubusercontent.com/milvus-io/milvus/v2.4.9/configs/milvus.yaml

#### 02. get docker compose file 
$ wget https://github.com/milvus-io/milvus/releases/download/v2.4.9/milvus-standalone-docker-compose.yml -O docker-compose.yml

#### 03. start container 
$ sudo docker compose up -d

#### 04. stop container 
$ sudo docker compose down

#### 05. remove volume
$ sudo rm -rf volumes
