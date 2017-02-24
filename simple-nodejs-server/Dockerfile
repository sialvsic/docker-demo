FROM node:7.6.0
RUN npm install -g yarn
WORKDIR /App
ADD index.js .
ADD package.json .
RUN yarn --pure-lockfile
EXPOSE 8080
CMD ["yarn","start"]
