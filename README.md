
# Docker Node.js server

A simple node express server running in a Docker container.




## Dockerizing your Node.js application

Run following command inside the simpleweb directory

```bash
  docker build -t <YourDockerName>/simpleweb .
```


## Run docker image

Run following command inside the simpleweb directory

```bash
  docker run -p 8080:8080 <YourDockerName>/simpleweb
```
    
## Tech Stack


**Server:** Docker, Node, Express




