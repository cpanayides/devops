# Automation / Docker

## Setup

1. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. Install [Boot2Docker](https://docs.docker.com/installation/mac/#install-boot2docker)
3. Setup [boot2docker](https://docs.docker.com/installation/mac/#from-your-command-line)

## Building Image

Using local [base image](./centos-base/) as an example

    docker build -t centos-base -q .

See [Dockerfile reference](https://docs.docker.com/reference/builder/#maintainer) for details.


