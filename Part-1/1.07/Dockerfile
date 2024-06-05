# Start from the Ubuntu image
FROM ubuntu:22.04

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

# Copy the hello.sh file from this location to /usr/src/app/ creating /usr/src/app/script.sh.
COPY script.sh .

# Execute a commands with `/bin/sh -c` prefix.
RUN apt update; apt install -y curl; 

# Run the Script
CMD ./script.sh