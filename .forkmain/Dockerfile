FROM node:16

WORKDIR /workdir

COPY ./ ./

RUN yarn install --frozen-lockfile

EXPOSE 1337

CMD ["sh", "-c", "yarn start"]
