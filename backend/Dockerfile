FROM node:14-alpine3.12
WORKDIR /app
COPY package*.json ./
RUN npm install
RUN npm audit fix
COPY . .
EXPOSE 4000
CMD ["node","index.js"]
