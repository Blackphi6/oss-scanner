FROM node:22-bookworm-slim
ENV DEBIAN_FRONTEND=noninteractive

COPY . /src
WORKDIR /src

RUN node --check background.js newtab.js popup.js
