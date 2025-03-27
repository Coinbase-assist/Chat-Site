#Use a lightweight Node.js image
From node:18-bullseye

#Set working directory
WORKDIR/app

RUN git clone https://github.com/Coinbase-assist/Chat-Site.git /app

# Set correct permissions 
RUN chmod -R 777 /app

# Install project dependencies
WORKDIR /app
RUN npm install

# Expose a port 
  EXPOSE 3000

# Start the application 
CMD ["node,"server.js"]
