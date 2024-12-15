FROM node:18-alpine

# Set the working directory

WORKDIR /nodejs-app/

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install application dependencies
RUN npm install express

# Copy the application code to the working directory
COPY . .

# Expose the application port
EXPOSE 3000

# Specify the command to run the application
CMD ["node", "app.js"]