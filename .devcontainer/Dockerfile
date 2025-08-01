# Use an official image as base
FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Install MySQL server
RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y mysql-server && \
    apt-get clean

# Start MySQL when container runs
CMD ["sleep", "infinity"]
