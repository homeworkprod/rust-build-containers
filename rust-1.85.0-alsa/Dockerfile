FROM rust:1.85.0-slim

RUN apt-get update \
    && apt-get install --no-install-recommends -y libasound2-dev pkg-config \
    && rm -rf /var/lib/apt/lists/*
