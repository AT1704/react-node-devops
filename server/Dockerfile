# Use Node.js LTS base image
FROM node:18

# Set working directory inside the container
WORKDIR /app

# Copy only package.json first to install dependencies
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy all source files
COPY . .

# Expose the port your app runs on
EXPOSE 5000

# Start the application
CMD ["node", "index.js"]
