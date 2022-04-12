#### Run environment
- docker-compose up -d --build
- after command completed you will have running environment within php@8.1, nginx, mysql@8, phpmyadmin in your localhost 

#### Run container cli
- php: `docker-compose php exec /bin/bash`
- mysql: `docker-compose exec mysql mysql --host=127.0.0.1 --user=root --password=secret` 

#### Access app and other containers
- php & nginx: you must put your index.php file under public file then you can access your project from `http://localhost:10002/`
- phpmyadmin: `http://localhost:10001/`
