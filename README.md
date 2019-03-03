# DNMP
- the simplest lnmp of docker
- just has linux, nginx, mysql(mariadb), php
- no extensions, no configurations
# Usage
0. make sure you have installed [git](https://git-scm.com/downloads), [docker](https://docs.docker.com/install/) and [docker-compose](https://docs.docker.com/compose/install/)
1. clone this project with "git clone https://github.com/HSwift/dnmp.git"
2. deploy your application in folder "app"
3. change mysql root password in docker-compose.yml
4. run "docker-compose up" in a shell
5. test your application at 127.0.0.1:8080
# Remember
the database hostname is "db" not "localhost", the connection string would look like mysql://db:3306
