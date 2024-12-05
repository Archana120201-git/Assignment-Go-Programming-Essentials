# Use the official Go image as the base
FROM golang:1.20

# Set the working directory inside the container
WORKDIR /workspace

# Copy the current project into the container
COPY . .

# Install additional utilities (if needed)
RUN apt-get update && apt-get install -y git && apt-get clean

# Set user permissions for Codespaces
USER vscode
