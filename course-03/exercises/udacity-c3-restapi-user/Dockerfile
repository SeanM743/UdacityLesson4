FROM node:12
WORKDIR /udacity/app
COPY package*.json ./
RUN npm ci
COPY . .
EXPOSE 8080
CMD ["npm", "run", "prod"]
