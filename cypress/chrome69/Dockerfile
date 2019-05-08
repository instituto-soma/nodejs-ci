FROM cypress/browsers:chrome69

WORKDIR /var/www
RUN npm install -g npm@6.7.0
RUN npm install -g envsub
RUN chown -R node:node .
USER node
