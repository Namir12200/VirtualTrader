FROM node:22-alpine3.19

WORKDIR /frontend

COPY . /frontend/

RUN npm install

CMD [ "npm", "run", "dev", "--", "--host", "0.0.0.0" ]