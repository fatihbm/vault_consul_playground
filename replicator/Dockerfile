# base image
FROM nginx:latest


# download dependencies
RUN  apt-get update \
  && apt-get install -y wget iproute2 iproute2

# update PATH
ENV PATH="PATH=$PATH:/etc/replicator/"
