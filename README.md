Nginx, PHP7.4, MySQL8 with Docker
===

**build project**
```
docker-compose up --build -d
```
**open container**
```
docker exec -it s5-app-php bash
```

**install Symfony**
```
composer create-project symfony/website-skeleton .
```

**open app in browser**
```
127.0.0.1:8080
```

**connect your database**
```
DATABASE_URL="mysql://admin:secret@s5-app-mysql:3306/s5_db?serverVersion=8"
```