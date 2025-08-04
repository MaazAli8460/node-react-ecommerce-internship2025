# Use Node.js image
FROM node:18
# working directory
WORKDIR /app
# Copy package files and install dependencies
COPY package*.json ./
RUN npm install
# Copy rest of the backend code
COPY . .
# Expose the backend port
EXPOSE 5000
# Start the backend server
CMD ["npm", "start"]


