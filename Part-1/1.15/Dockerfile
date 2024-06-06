FROM node:22-alpine
EXPOSE 3000
RUN apk update; apk add git;
RUN git clone https://github.com/Abubakkar-Siddhiq/hello-docker.git
WORKDIR /hello-docker
RUN npm install
CMD ["npm", "start"]