FROM node:16

# Create app directory
WORKDIR /app

# Copy application files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Expose port
EXPOSE 3000

# Start the application
CMD ["npm", "start"]

