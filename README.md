### Overview
A brief presentation on the current state of containerization circa mid-2017.

Just to make things fun and meta, a simple Dockerfile is included that will boot
up an nginx server to serve the built assets (after they've been compiled by
gulp):

```bash
docker build -t tt-containerization-demo .
docker run -p 80:80 tt-containerization-demo
```

And if you really want to get fancy, you can spin up a remote instance using
`docker-machine` on e.g. Digital Ocean, and deploy the static site with the
push of a button:

```bash
# Spin up a new Droplet on Digital Ocean...
docker-machine create --driver digitalocean --digitalocean-access-token {insert_your_api_key} tt-containerization-demo
docker-machine env tt-containerization-demo
eval $(docker-machine env tt-containerization-demo)
# Then build + run the docker image.
docker build -t tt-containerization-demo .
docker run -p 80:80 tt-containerization-demo
```
