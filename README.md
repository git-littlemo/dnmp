### 使用方法：
```
git clone https://github.com/git-littlemo/dnmp.git

cd dnmp

cp env .env

openssl dhparam -out ./www/ssl/dhparam.pem 2048

docker compose up -d
```