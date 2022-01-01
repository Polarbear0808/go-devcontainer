ARG VARIANT=1-bullseys

FROM mcr.microsoft.com/vscode/devcontainers/go:0-${VARIANT}

LABEL maintainer polarbear08

ARG NODE_VERSION="LTS/*"
RUN if [ "${NODE_VERSION}" != "none" ]; then su vscode -c ". /usr/local/share/nvm/nvm.sh && nvm install ${NODE_VERSION} 2>&1"; fi

RUN mkdir /home/vscode/workspace
WORKDIR /home/vscode/workspace