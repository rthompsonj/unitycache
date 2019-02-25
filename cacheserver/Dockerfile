FROM ubuntu:18.04
MAINTAINER Robert Thompson <rthompsonj@gmail.com>

# system packages
RUN apt-get update && apt-get install -y npm

RUN mkdir -p /opt/cache

RUN npm install unity-cache-server -g

CMD ["unity-cache-server", "--NODE_CONFIG_DIR=/config"]