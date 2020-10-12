FROM centos
MAINTAINER Devops Engineer
WORKDIR /data
RUN echo 'ping google.com' > runapp.sh
CMD sh runapp.sh

# Difference between CMD and ENTRYPOINT
# Build the image $ docker buil . -t cmdtest
# Run the container of cmd image $ docker run -d -it --name cmdtest-container cmdtest
# Run again with passing arugment in command line $ docker run -d -it --name cmdtest-conatiner1 cmdtest date
# See the difference between them CMD and ENTRYPOINT
