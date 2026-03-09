# Stage 1 - Build
FROM node:18 As builder
LABEL author="SHUBHAM"
WORKDIR /app

COPY package*.json ./app
COPY . .

# Stage 2 - Production
FROM node:18-alpine
WORKDIR /app
COPY --from=builder /app .

EXPOSE 5050

CMD ["node","server.js"]
