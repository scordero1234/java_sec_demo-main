# spring-boot-demo con Security CI/CD
Demo project

Para verificacion simple:

```bash
mvnw verify
```

Para compilar se incluye el plugins de docker para empaquetar todo el proyecto:

```bash
mvnw clean package jib:dockerBuild
```

Para levantar el contenedor de la aplicacion, además de las dependencias; se debe ubicarse en el directorio donde se encuentra el archivo docker-compose.yml y ejecutar

```bash
docker-compose up
```
```yaml
cat /var/jenkins_home/secrets/initialAdminPassword
```
```
84a581bee2c547d6bff0327e482515f6
```

token

84a581bee2c547d6bff0327e482515f6: d5db0194b1f3d30dd7d5cc3c155f9154d17fcc44