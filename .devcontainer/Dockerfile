FROM mcr.microsoft.com/vscode/devcontainers/python:3.9

# Pasang kebergantungan sistem tambahan
RUN apt-get update && apt-get install -y \
    chromium-browser \
    chromium-chromedriver

# Tetapkan laluan untuk ChromeDriver
ENV PATH="/usr/bin/chromedriver:${PATH}"
