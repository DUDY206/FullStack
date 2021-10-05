FROM node:14.18.0

RUN mkdir -p /var/www/backend
WORKDIR /var/www/backend

COPY ./backend/package.json ./package.json

RUN npm install
RUN npm install -g @nestjs/cli

CMD ["npm", "run", "start:dev"]