# Use official Node.js image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the app source code
COPY . .

# Expose Angular default port
EXPOSE 4200

# Start Angular development server
CMD ["npx", "ng", "serve", "--host", "0.0.0.0"]
