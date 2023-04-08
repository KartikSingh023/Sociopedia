FROM node:16
LABEL maintainer="Rohan Rustagi"
WORKDIR /app
COPY package.json ./
COPY package-lock*.json ./
RUN npm install --legacy-peer-deps
COPY . .
EXPOSE 6001
CMD ["npm","start"]
