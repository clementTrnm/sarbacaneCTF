FROM node:12-buster-slim

WORKDIR /app
COPY package.json .

ENV NODE_ENV production
ENV PORT 3000
RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "/app/server.js"]
