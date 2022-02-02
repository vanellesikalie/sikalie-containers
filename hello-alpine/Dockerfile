FROM alpine 3.15.0

LABEL maintainer="vanellesikalie" os="alpine" distro="Alpine 3.15.0"

ENV CONTAINER_USER="vanellesikalie"

RUN adduser $CONTAINER_USER --disabled-password && mkdir "/home/vanellesikalie/receipts"

CMD echo "hello-alpine, I'm $CONTAINER_USER and this is a container from my first
image"
