###########################################################
# Dockerfile to build java 1.7 
# Based on Ubuntu 14.04
###########################################################

# Base image is ubuntu 14.04
FROM ubuntu:14.04

# Maintener of this image
MAINTAINER TASC


#Install Java
RUN \
  apt-get update && \
  apt-get install -y openjdk-7-jre && \
  rm -rf /var/lib/apt/lists/*

# Define working directory.
WORKDIR /data

# Define default command.
CMD ["bash"]