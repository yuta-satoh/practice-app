FROM --platform=linux/amd64 node:lts

COPY . ./var/www

WORKDIR /var/www/react-app

RUN yarn install

ENV PORT 3000

CMD ["yarn", "start"] 
