# 安裝 mysql and phpMyAdmin
實行前請確認是否安裝 docker-compose  
並將 .env.example 更名為 .env  
各項參數請參照以下 env 設定

## env 設定
```
MYSQL_DATABASE= #新增 database
MYSQL_ROOT_PASSWORD= #設定 root 密碼
MYSQL_USER= #新增帳號
MYSQL_PASSWORD= #新增帳號的密碼
```

## 如需匯入 sql 請放置於資料夾內:
mysql-dump  
裡面放需要匯入的 .sql 檔

## 執行
docker-compose up -d

## phpMyAdmin
http://domain{ip}:8080
