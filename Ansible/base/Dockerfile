FROM ubuntu

#indicamos el timezone
ARG TZ=Europe/Madrid
ENV TZ=${TZ}
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apt update && apt install -yq --no-install-recommends \
    apt-utils \
    wget \
    nano \
    net-tools \
    sudo \
    curl \
    unzip \
    dos2unix \
    software-properties-common \
    git \
    tree \
    expect \
    python3 \
    iputils-ping \
    sudo \
    openssh-server \
    openssh-client \
    unzip

