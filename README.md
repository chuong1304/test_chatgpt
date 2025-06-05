# Demo Docker Project

This repository contains a minimal Python web application packaged with Docker.

## Building the image

```bash
docker build -t demo-app .
```

## Running the container

```bash
docker run -p 5000:5000 demo-app
```

Open <http://localhost:5000> to view the greeting message.
