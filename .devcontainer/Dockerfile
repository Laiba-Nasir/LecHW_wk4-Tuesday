FROM ubuntu:latest

RUN apt update && DEBIAN_FRONTEND=noninteractive TZ=US/LosAngeles apt install -y qemu-system-arm qemu-user gcc gcc-arm-linux-gnueabi git file

ENV VNC_RESOLUTION="1920x1200x16" \
    VNC_DPI="96"

WORKDIR /home/ubuntu

ENTRYPOINT ["/bin/bash"]