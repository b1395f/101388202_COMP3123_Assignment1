FROM node:14

WORKDIR /app/backend

COPY ../package*.json ./

RUN npm install

COPY . .

EXPOSE 3002

CMD ["npm", "start"]