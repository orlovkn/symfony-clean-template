Symfony5, PHP7.4, MySQL8 with Docker
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

**open app in the browser**
```
http://127.0.0.1:8081/
```