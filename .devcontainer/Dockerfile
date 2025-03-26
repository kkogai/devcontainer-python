FROM mcr.microsoft.com/devcontainers/python:3.11

USER vscode

RUN curl -LsSf https://astral.sh/uv/install.sh | sh
ENV PATH="/home/vscode/.local/bin:${PATH}"

WORKDIR /home/vscode
RUN uv venv