FROM node:18
WORKDIR /app
COPY package.json package-lock.json ./
RUN npm install

COPY . .
EXPOSE 3003
CMD ["node", "index.js";]