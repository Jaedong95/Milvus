# Milvus
The files required to run Milvus.

#### 01. get milvus.yaml file 
```bash 
$ wget https://raw.githubusercontent.com/milvus-io/milvus/v2.4.9/configs/milvus.yaml
```
#### 02. get docker compose file 
```bash
$ wget https://github.com/milvus-io/milvus/releases/download/v2.4.9/milvus-standalone-docker-compose.yml -O docker-compose.yml
```
#### 03. start container 
```bash
$ sudo docker compose up -d
```
#### 04. stop container 
```bash
$ sudo docker compose down
```
#### 05. remove volume
```bash
$ sudo rm -rf volumes
```
