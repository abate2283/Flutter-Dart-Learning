# Custom Flutter and Dart Development Container

FROM cirrusci/flutter:latest

# Install additional tools if needed
RUN apt-get update && apt-get install -y \
    git \
    curl

# Set the working directory
WORKDIR /workspace

# Copy the current project files into the container
COPY . .
