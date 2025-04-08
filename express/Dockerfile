FROM node:19-alpine
RUN npm install -g nodemon
WORKDIR /app
COPY package.json package-lock.json ./
RUN npm install
COPY . ./
EXPOSE 8080
CMD ["npm", "run", "dev"]