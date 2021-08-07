# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.187.0/containers/codespaces-linux/.devcontainer/base.Dockerfile

FROM mcr.microsoft.com/vscode/devcontainers/universal:1-focal

USER ROOT

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive && apt-get install -y  --no-install-recommends \
    autoconf \
    automake \
    bison \
    build-essential \
    curl \
    flex \
    gcc \
    git \
    libboost-all-dev \
    libevent-dev \
    libssl-dev \
    libtool \
    libxml2-dev \
    libxslt1-dev \
    nodejs \
    openssl \
    pkg-config \
    python-dev \
    python-pip \
    python-setuptools \
    python-yaml \
    unzip \
    wget \
    zip \
    zlib1g-dev && \
    apt-get clean && rm -rf /var/lib/apt/lists/* && rm -rf /tmp/* /var/tmp/*

USER codespace
