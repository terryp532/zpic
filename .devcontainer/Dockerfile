FROM mcr.microsoft.com/devcontainers/python:1-3.10-bookworm

RUN apt-get update \
    && export DEBIAN_FRONTEND=noninteractive \
    && apt-get install -y --no-install-recommends ffmpeg \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

COPY binder/requirements.txt /tmp/zpic-requirements.txt

RUN python -m pip install --upgrade pip \
    && python -m pip install -r /tmp/zpic-requirements.txt jupyterlab ipykernel
