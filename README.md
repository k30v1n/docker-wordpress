# docker-wordpress
Wordpress installation using docker compose and persistence data.

References
- Quickstart: Compose and WordPress: https://docs.docker.com/compose/wordpress/
- How to install WordPress: https://wordpress.org/support/article/how-to-install-wordpress/

- $~/my-wordpress-site/ `docker compose up -d`
- `docker container ls`
- access `localhost:8000`
- stop all containers `docker stop $(docker ps -a -q)`