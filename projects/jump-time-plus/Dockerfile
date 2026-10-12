FROM node:22-bookworm-slim
ENV DEBIAN_FRONTEND=noninteractive

COPY . /src
WORKDIR /src

RUN node --test test/ || echo "WARNING: tests reported failures"
