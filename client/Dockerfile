FROM node:20-alpine3.18
WORKDIR /app
COPY package*.json ./
RUN  yarn  
COPY . .
expose 5173
CMD ["yarn","dev","--host","0.0.0.0"]
