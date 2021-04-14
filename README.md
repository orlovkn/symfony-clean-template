Install Symfony 5 with PHP 7.4 and MySQL 8 with Docker
===

### build project
```
docker-compose up --build -d
```

### open container
```
docker exec -it symfony-app-php bash
```

### install Symfony
```
composer create-project symfony/website-skeleton .
```

### open app in the browser
```
http://127.0.0.1:8081/
```