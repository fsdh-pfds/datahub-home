ARG NODE_VERSION=22@sha256:cfef4432ab2901fd6ab2cb05b177d3c6f8a7f48cb22ad9d7ae28bb6aa5f8b471
FROM node:${NODE_VERSION}

ARG HUGO_VERSION=0.126.3
ARG GO_VERSION=1.22.3

RUN apt-get update && \
    apt-get install -y ca-certificates openssl git curl make && \
    rm -rf /var/lib/apt/lists/*

RUN ARCH=$(uname -m) && \
    if [ "$ARCH" = "aarch64" ]; then ARCH=arm64; else ARCH=amd64; fi && \
    echo "Architecture: $ARCH" && \
    wget -O hugo_extended_${HUGO_VERSION}.tar.gz https://github.com/gohugoio/hugo/releases/download/v${HUGO_VERSION}/hugo_extended_${HUGO_VERSION}_linux-${ARCH}.tar.gz && \
    tar xf hugo_extended_${HUGO_VERSION}.tar.gz && \
    mv hugo /usr/bin/hugo && \
    rm hugo_extended_${HUGO_VERSION}.tar.gz && \
    echo "Hugo ${HUGO_VERSION} installed" && \
    wget -O go${GO_VERSION}.linux-${ARCH}.tar.gz https://dl.google.com/go/go${GO_VERSION}.linux-${ARCH}.tar.gz && \
    tar -C /usr/local -xzf go${GO_VERSION}.linux-${ARCH}.tar.gz && \
    rm go${GO_VERSION}.linux-${ARCH}.tar.gz && \
    echo "Go ${GO_VERSION} installed"

ENV PATH=$PATH:/usr/local/go/bin

USER node
