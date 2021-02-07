Docker nginx-php stack for the Raspberry pi zero
================================================
![Docker](https://github.com/vrestihnat/nginx-php-rpi-zero/workflows/Docker/badge.svg)

# Prerequisites
- unix like OS armv6 (raspbian, dietPi, armbian, ubuntu, ...)
- docker for armv6
- docker-compose

# Install Prereq
## unix like OS 
see https://en.wikipedia.org/wiki/Raspberry_Pi_OS#Linux_distributions 
## docker
```sh
# apt install -y lsb-release
# curl -sSL https://get.docker.com | sh
```
## docker-compose
```sh
# apt install -y python3-dev python3-pip python3-setuptools libffi-dev
# pip3 install wheel
# pip3 install docker-compose
```
# Run container
## run
```sh
# docker-compose up
```
## run on background
```sh
# docker-compose up -d
```
## run container with mysql support
```sh
# docker-compose -f docker-compose.yml -f docker-compose-mysql.yml up
```
## run container with pgsql support
```sh
# docker-compose -f docker-compose.yml -f docker-compose-pgsql.yml up
```
# Stop container
## stop
```sh
# docker-compose stop
```
## stop and remove
```sh
# docker-compose down
```
# Test
http://127.0.0.1

