# sample-app
Explorar CI/CD con GitHub y Jenkins

## Arrancar el contenedor de Jenkins Docker
```
Docker pull jenkins/jenkins:lts
```

```
docker run --rm -u root -p 8080:8080 -v jenkins-data:/var/jenkins_home -v $(which docker):/usr/bin/docker -v /var/run/docker.sock:/var/run/docker.sock -v "$HOME":/home --name jenkins_server jenkins/jenkins:lts
```
User 
```
009341bc61b8
```

Pass
```
d256ee30cea04e14a65994f96740faed
```
