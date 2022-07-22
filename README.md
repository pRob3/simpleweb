# Docker Node.js Express Server

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

## Tech Stack

**Server:** Docker, Node, Express
