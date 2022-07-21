# docker-django

## 前提条件
### Docker
https://www.docker.com/

## ローカル開発環境
### 起動コマンド
cd %project_root%
docker-compose up

### 初回起動
docker exec -it gi_web /bin/bash  
python manage.py migrate

### 開発環境URL
http://localhost:8000/

### コンテナにログイン
#### web server
docker exec -it gi_web /bin/bash


