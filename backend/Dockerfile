# Use a base image
FROM node:18

# Set the working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the app files
COPY . .

# Expose the application's port
EXPOSE 9000

# Run the application
CMD ["npm", "start"]
