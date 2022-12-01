- docker-compose up -d
- change php version: PHP_VERSION -> docker-compose build --no-cache php-fpm
- change node version: WORKSPACE_NODE_VERSION -> docker-compose build --no-cache workspace  

- chmod -R 777 storage/*