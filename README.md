**Docker comandos basicos**

`docker run -p 8080:80 runrun/hello-word`<br>
`docker run -d --name appi -p 8080:80 runrun/hello-word`<br>
`docker stop appi`

**PROYECTO CON SPRING BOOT**

Proyeto base<br>
https://github.com/pvpablo/spring-boot-template.git<br>
`docker build -t codelab/spring-boot-template .`<br>
`docker run -p 8080:8000 codelab/spring-boot-template`