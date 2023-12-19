FROM node

WORKDIR /user/app

COPY package* .

RUN npm install

COPY . .

EXPOSE 3001

CMD ["npm", "start"]
