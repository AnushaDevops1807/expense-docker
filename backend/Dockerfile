FROM node:20
# RUN mkdir /opt/backend
WORKDIR /opt/backend
COPY package.json .
COPY *.js .
RUN npm install
ENV DB_HOST="mysql"
CMD ["node", "index.js"]