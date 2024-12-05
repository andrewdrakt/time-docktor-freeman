FROM node:alpine
LABEL authors="LEGION"
WORKDIR /time-app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 5000
CMD ["npm", "run", "dev"]