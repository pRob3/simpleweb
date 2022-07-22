# Docker Node.js server

A simple node express server running in a Docker container.

## Run Locally

Clone the project

```bash
  git clone https://github.com/pRob3/simpleweb.git
```

Go to the project directory

```bash
  cd simpleweb
```

Build docker image and tag it.

```bash
  docker build -t <YourDockerName>/simpleweb .
```

Run container and start the server

```bash
  docker run -p 8080:8080 <YourDockerName>/simpleweb
```

Go to http://localhost:8080 in your browser.

## Good Docker commands

Build an image based on the dockerfile in the current directory.
Tag it as '<YourDockerName>/simpleweb'

```bash
  docker build -t <YourDockerName>/simpleweb
```

Create and start a container based on the provided image id or tag.

```bash
  docker run [image id or image tag]
```

Create and start container, but also override the default command.

```bash
  docker run [image id or image tag] [cmd]
```

Print out information about all of the running containers.

```bash
  docker ps
```

Execute the given command in a running container.

```bash
  docker exec -itr [container id] [cmd]
```

Print out logs from the given container.

```bash
  docker logs [container id]
```

## Tech Stack

**Server:** Docker, Node, Express
