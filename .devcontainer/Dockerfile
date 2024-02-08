FROM mcr.microsoft.com/devcontainers/base:bullseye

ARG TYPST_VERSION=v0.10.0

RUN wget https://github.com/typst/typst/releases/download/${TYPST_VERSION}/typst-x86_64-unknown-linux-musl.tar.xz && \
    tar -xvf typst-x86_64-unknown-linux-musl.tar.xz && \
    mv typst-x86_64-unknown-linux-musl/typst /usr/local/bin/typst && \
    rm -rf ./typst-x86_64-unknown-linux-musl*
