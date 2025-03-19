# Use Node.js official image
FROM node:18

# Set working directory
WORKDIR /app

# Copy files
COPY package.json package-lock.json ./
RUN npm install
COPY . .

# Expose the port
EXPOSE 5000

# Start the app
CMD ["node", "server.js"]
