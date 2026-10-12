FROM python:3.12-slim
ENV DEBIAN_FRONTEND=noninteractive

COPY . /src
WORKDIR /src

RUN python3 scripts/validate_extension.py
