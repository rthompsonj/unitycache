FROM ubuntu:18.04
MAINTAINER Robert Thompson <rthompsonj@gmail.com>

# system packages
RUN apt-get update && apt-get install -y npm

RUN npm install unity-cache-server -g

CMD ["unity-cache-server", "-P", "/opt/cache", "--NODE_CONFIG_DIR=/config"]