# Ruby:2.3.1 + Nodejs Dockerfile

This repository contains a Dockerfile of Ruby, nodejs and npm(> v6.8.0) for Docker's automated build published to the public Docker Hub Registry.

## What's included
- Ruby 2.3.1
- Nodejs (latest)
- npm(> v6.8.0)

### Installation
1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://hub.docker.com/r/sub2u/ruby-2.3.1-node-6.8.0/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull sub2u/ruby-2.3.1-node-6.8.0`

   (alternatively, you can build an image from Dockerfile: `docker build -t="sub2u/ruby-2.3.1-node-6.8.0" github.com/sub2u/ruby-2.3.1-node-6.8.0`)


### Usage

    docker run -it --rm sub2u/ruby-2.3.1-node-6.8.0

#### Run `ruby`

    docker run -it --rm sub2u/ruby-2.3.1-node-6.8.0 ruby

#### Run `node`

    docker run -it --rm sub2u/ruby-2.3.1-node-6.8.0 node
