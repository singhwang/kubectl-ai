FROM ubuntu:22.04

RUN mkdir -p /app/bin && \
    mkdir -p /app/config
ADD kubectl-ai /app/bin/
ADD kubectl /app/bin/
ADD config.yaml /app/config/
ENV PATH="${PATH}:/app/bin"
