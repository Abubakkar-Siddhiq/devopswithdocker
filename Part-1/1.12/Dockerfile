# Using Node as Base Image
FROM node:14-alpine

# Exposing Port
EXPOSE 5000

# Working Directory
WORKDIR /usr/src/app

# Copying Sources
COPY . .

# Install App
RUN npm install

# Build App
RUN npm run build

# Serve App
RUN npm install -g serve

# Final Command
CMD ["serve", "-s", "-l", "5000", "build"]
