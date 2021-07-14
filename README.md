# my-docker

### OBJECTIVE

Using available images: mysql, wordpress, phpMyAdmin and php-app (need to create an image) to compose an environment that meets the requirements as below:

* Access localhost:8080 for phpMyAdmin web service
* Access localhost:8000 for wordpress to show contents of database
* Access localhost:9090 for a web showing content of todo_list table as in todo_list.php (burn as image with Dockerfile)


#### Command:

Build & run PHP image:
* cd phpMyAdmin/my-php-image
* docker build -t my-php-app:latest .
* docker run my-php-app

Compose: 
* cd phpMyAdmin 
* docker-compose up -d

