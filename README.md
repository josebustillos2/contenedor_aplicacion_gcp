**Docker comandos basicos**

`docker run -p 8080:80 runrun/hello-word`

`docker run -d --name appi -p 8080:80 runrun/hello-word`

`docker stop appi`

**PROYECTO CON SPRING BOOT**
Proyeto base
https://github.com/pvpablo/spring-boot-template.git
`docker build -t codelab/spring-boot-template .`

`docker run -p 8080:8000 codelab/spring-boot-template`