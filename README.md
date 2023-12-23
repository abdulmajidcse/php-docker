# Build docker image
docker run -p 8080:80 php-docker

# Run docker
docker run -v {directory_path}:/var/www/html - 8080:80 php-docker

# Open a browser and visit at
http://localhost:8080