docker run -p 8080:80 runrun/hello-word
docker run -d --name appi -p 8080:80 runrun/hello-word
docker stop appi


proyecto con sprint boot
https://github.com/pvpablo/spring-boot-template.git
mvn install
mvn spring-boot:run

docker build -t codelab/spring-boot-template .
docker run -p 8080:8000 codelab/spring-boot-template
