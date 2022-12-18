FROM node:18.2.0

WORKDIR /app

COPY . /app/

COPY package*.json /app/

COPY ./ ./
RUN npm install  \
    && npm run build 

EXPOSE 3000 
EXPOSE 3306

CMD [ "npm", "run", "start:prod" ]