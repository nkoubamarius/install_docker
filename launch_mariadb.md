## Start MariaDB service
- start docker-compose:  `docker-compose up -d`
- Check the list of containers running:  `docker ps`
- Connect to a container : `docker exec -it container_name bash`
- Connect to MariaDb Server: `mariadb -u root -p`
- check the version of MariaDB: `select version();`
- Get the list of databases: `show databases;`