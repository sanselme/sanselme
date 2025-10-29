FROM ubuntu:latest

# Update package list and install zsh and ZFS utilities
RUN apt-get update && \
    apt-get install -y \
    zsh \
    zfsutils-linux \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace
COPY . .
CMD ["zsh"]
