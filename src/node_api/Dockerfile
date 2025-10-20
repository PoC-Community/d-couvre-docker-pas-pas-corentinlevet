# Use node:12-alpine as base image
FROM node:12-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

ENV PORT=8080

EXPOSE 8080

# Start the application
CMD ["npm", "start"]
