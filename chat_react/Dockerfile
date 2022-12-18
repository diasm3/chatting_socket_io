FROM node:18.2.0

WORKDIR /app

COPY . /app/

COPY package*.json /app/

COPY ./ ./
RUN yarn \
    && yarn run build 

EXPOSE 3000 

CMD [ "yarn", "run", "start" ]