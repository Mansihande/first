# Use Node.js official image
FROM node:14

# Set working directory inside the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the application
COPY . .

# Expose the frontend port
EXPOSE 3000

# Command to run the frontend
CMD ["npm", "start"]

