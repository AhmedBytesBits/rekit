FROM node:12.18.1-buster-slim

  # Dev servier port
EXPOSE 6075
EXPOSE 3100
  # Studio port
EXPOSE 6076

  # Build port
EXPOSE 6077

  # Update npm and yarn
RUN npm install npm@latest -g
RUN npm install -g rekit
RUN npm install -g rekit-studio

VOLUME /home/node/app
WORKDIR /home/node/app

CMD ["npm", "start"]