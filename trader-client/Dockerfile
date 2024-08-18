FROM node:22-alpine3.19

WORKDIR /frontend

COPY ./package.json /frontend/package.json
COPY ./package-lock.json /frontend/package-lock.json

RUN npm install

COPY . /frontend/

CMD [ "npm", "run", "dev", "--", "--host", "0.0.0.0" ]