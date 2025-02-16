# order_food
## environment setup  

### frontend
1. 软件需要
```
brew install nginx
```
2. 配置nginx
```
cp ./config/nginx.conf nginx配置目录
# 修改nginx.conf
root 修改为前端目录
```

### backend
1. database
```
brew install mysql
```

```
mysql 
user: root
password: root
```

```
source order_food.sql
```
2. java
```
brew install openjdk
```
3. 