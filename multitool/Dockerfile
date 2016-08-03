FROM ubuntu:16.04
MAINTAINER Brandon Tomlinson ( thebwt@gmail.com )

RUN apt-get update && apt-get install -y \
	vim \
	telnet \
        ssh \
        rsync \
        curl \
        wget \
        debhelper \
        devscripts \
 && rm -rf /var/lib/apt/lists/*
