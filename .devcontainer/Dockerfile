# https://github.com/devcontainers/images/blob/main/src/universal/.devcontainer/Dockerfile

FROM mcr.microsoft.com/devcontainers/universal:2-focal

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get install -y --no-install-recommends emacs \
    ripgrep
   
