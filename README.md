### 1. Build Project : 

mvn clean install

### 2. Build Docker Image : 

docker build -t docker-image:latest -f target/docker-resources/Dockerfile target/
