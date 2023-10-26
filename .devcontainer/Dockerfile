FROM mcr.microsoft.com/devcontainers/javascript-node:1-18-bullseye

RUN sudo apt-get update --fix-missing \
    && sudo apt-get install -y --no-install-recommends libnss3 \
    ibnspr4 \
    ibatk1.0-0 \
    ibatk-bridge2.0-0 \
    ibcups2 \
    ibdrm2 \
    ibdbus-1-3 \
    libxkbcommon0 \
    libatspi2.0-0 \
    libxcomposite1 \
    libxdamage1 \
    libxfixes3 \
    libxrandr2 \
    libgbm1 \
    libasound2 \
    && sudo apt-get auto-remove -y \
    && sudo apt-get clean -y
