# Docker for PHP
Can be used for PHP and WordPress.
Using database MariaDB and phpmyadmin

<img src="https://img.shields.io/badge/php-%5E7.4.3-blue" />  <img src="https://img.shields.io/badge/wordpress-v5.4.2%20tested-brightgreen" />  <img src="https://img.shields.io/badge/platform%20build-win%20%7C%20osx%20%7C%20linux-%23989898" />


### Instructions
Line 11.
Project folder name insert here

```
volumes:
  - ../my-folder-name-here:/app
```

You can change containers names too

# How install Docker
Terminal command...
```
docker-compose up -d
```

After the all install...
```
docker-compose start
```

Open in the Browser:
```
http://localhost:4500/ (you project)
http://localhost:8080/ (phpmyadmin)
```
