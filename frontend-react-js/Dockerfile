FROM node:16.18

ENV PORT=3000

COPY . /frontend-react-js
WORKDIR /frontend-react-js
RUN yarn install
EXPOSE ${PORT}
CMD ["yarn", "start"]