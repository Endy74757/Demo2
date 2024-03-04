FROM node:18-alpine

WORKDIR /app
COPY . .

# Install node packages, install serve, build the app, and remove dependencies at the end
RUN npm install \
    && npm install parcel

EXPOSE 3000

# Start the app using serve command
CMD [ "npm", "start"]
