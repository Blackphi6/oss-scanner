FROM node:22-bookworm-slim
ENV DEBIAN_FRONTEND=noninteractive

COPY . /src
WORKDIR /src

RUN npm ci
RUN npx esbuild --version
RUN node --check background.js
