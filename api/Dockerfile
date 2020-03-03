FROM node 

RUN mkdir  /usr/src/app
WORKDIR /app  

ENV PATH /usr/src/app/node_modules/.bin:$PATH

COPY package*.json /usr/src/app/

RUN npm install

COPY . /app/

EXPOSE 4000

CMD ["npm", "start"]

