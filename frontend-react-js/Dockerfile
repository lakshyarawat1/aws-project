FROM node:14-alpine

WORKDIR /app

COPY package*.json ./

# Install dependencies
RUN npm install

COPY . .

# RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]