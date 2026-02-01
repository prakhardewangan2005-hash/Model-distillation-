FROM mcr.microsoft.com/devcontainers/python:1-3.11-bullseye

# Keep the image lean; CPU-only is default.
ENV PIP_DISABLE_PIP_VERSION_CHECK=1 \
    PYTHONDONTWRITEBYTECODE=1 \
    PYTHONUNBUFFERED=1

RUN apt-get update && apt-get install -y --no-install-recommends \
    git \
    make \
    && rm -rf /var/lib/apt/lists/*
