Install Symfony5 with PHP7.4 and MySQL8 with Docker
===

**build project**
```
docker-compose up --build -d
```
**open container**
```
docker exec -it symfony-app-php bash
```

**install Symfony**
```
composer create-project symfony/website-skeleton .
```

**open app in the browser**
```
http://127.0.0.1:8081/
```