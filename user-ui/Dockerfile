FROM node:17
WORKDIR /opt 
COPY package*.json ./
RUN npm install 
COPY . . 
EXPOSE 7000
CMD ["node", "App.js"]
