# Use the official Alpine base image
FROM alpine:latest

# Install any packages your application needs
RUN apk add --no-cache \
    bash \
    curl

# Copy application files
COPY . /app

# Set the working directory
WORKDIR /app

# Define the default command
CMD ["sh"]
