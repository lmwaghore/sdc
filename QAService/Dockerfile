FROM node:lts
WORKDIR /app
COPY ["package.json", "package-lock.json*", "./"]
RUN npm ci
COPY . .
# RUN chown -R node:node /app
# USER node
EXPOSE 80
CMD ["npm", "start"]

