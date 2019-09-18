FROM node:lts-alpine

MAINTAINER Jean-Baptiste Delhommeau "jeanbadel@gmail.com"

RUN apk add --no-cache git

RUN yarn global add grunt bower

#Bower config
ENV CI true
RUN echo '{ "allow_root": true }' > /root/.bowerrc

CMD [ 'node' ]
