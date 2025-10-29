FROM ubuntu:latest

# Update package list and install zsh
RUN apt-get update && \
  apt-get install -y zsh && \
  apt-get clean && \
  rm -rf /var/lib/apt/lists/*

# Set zsh as the default shell
SHELL ["/bin/zsh", "-c"]

# Set working directory
WORKDIR /home

# Default command
CMD ["/bin/zsh"]
