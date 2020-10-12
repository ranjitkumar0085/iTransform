FROM docker.io/centos:latest
MAINTAINER Devops Engineer
WORKDIR /data
RUN echo 'ping google.com' > runapp.sh
ENTRYPOINT sh runapp.sh

# Difference between ENTRYPOINT and CMD
# Build the image $ docker buil . -t entrypointtest
# Run the container of cmd image $ docker run -d -it --name entrypointtest-container entrypointtest
# Run again with passing arugment in command line $ docker run -d -it --name entrypointtest-conatiner1 entrypointtest date
# See the difference between them ENTRYPOINT and CMD
