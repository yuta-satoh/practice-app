FROM --platform=linux/amd64 node:lts

COPY . ./var/www

WORKDIR /var/www

RUN yarn install

RUN yarn build

ENV PORT 3000

CMD ["yarn", "start"] 
