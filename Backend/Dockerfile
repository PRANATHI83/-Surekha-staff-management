FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# ✅ This must come **after** the previous line
COPY .env .env

EXPOSE 3014
CMD ["node", "server.js"]


