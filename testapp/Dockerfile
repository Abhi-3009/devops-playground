# FROM baseImage
FROM node:20

# WORKDIR /the/workdir/path
WORKDIR /myapp

# COPY source dest
COPY . .

# RUN command
RUN npm install

# CMD [ "executable" ]
CMD [ "npm", "start" ]
