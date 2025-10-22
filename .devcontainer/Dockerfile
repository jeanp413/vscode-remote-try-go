FROM mcr.microsoft.com/devcontainers/go:1-1.22-bookworm

ENV FOO=3

# Install squid
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install squid
