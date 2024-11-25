FROM node:latest
WORKDIR /app
COPY . .
RUN npm install mysql
CMD ["node","index.js"]
EXPOSE 3000