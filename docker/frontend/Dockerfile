FROM node:14.18.0

RUN mkdir -p /var/www/frontend
WORKDIR /var/www/frontend

COPY ./frontend/package.json ./package.json

CMD ["npm", "start"]