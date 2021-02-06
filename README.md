Docker nginx-php stack for the Raspberry pi zero
================================================

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

