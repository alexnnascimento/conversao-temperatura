FROM node
WORKDIR /app
COPY Package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]

