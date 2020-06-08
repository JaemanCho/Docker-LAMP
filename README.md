# Dokerを使ってLAMP環境を作る

## 開発環境

VirtualBox 6.1  
Docker Client 19.03.1  
Docker Engine 19.03.5  
PHP:7.3.3-apache  
MySQL 5.6   
phpMyAdmin 4.7  

# 構築手順

```bash
git clone https://github.com/JaemanCho/Docker-LAMP.git project_name
cd project_name
docker-compose up -d
```

# 確認

## Apache
http://[Docker Machine IP]/index.php

## phpMyAdmin
http://[Docker Machine IP]:8080

## DB情報
HostName : Docker Machine IP  
Port : 3306  
Root Name : root  
Root Password : root  
User Name : dev  
User Password : dev  
DB : development  
