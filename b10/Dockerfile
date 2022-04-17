# Specify Ubuntu as base image
FROM ubuntu:bionic


# Install dependencies with apt (Ubuntu's Package Manager)
# Install required Python packages
RUN apt-get update -y && apt install fortune -y && \
    apt install fortunes-min -y


# Specify the command to be run on container creation
CMD ["/usr/games/fortune"]