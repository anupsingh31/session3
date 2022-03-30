FROM node:alpine
WORKDIR /app
# COPY . /home/app/
# RUN npm install
# CMD ["npm","start"]
COPY package.json ./
RUN npm install
COPY . .
CMD ["npm","start"]
