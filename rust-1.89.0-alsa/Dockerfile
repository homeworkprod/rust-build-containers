FROM rust:1.89.0-slim

RUN apt-get --update install --no-install-recommends -y libasound2-dev pkg-config \
    && rm -rf /var/lib/apt/lists/*
