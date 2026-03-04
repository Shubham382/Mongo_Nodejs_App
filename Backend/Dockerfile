FROM node
LABEL author="SHUBHAM"
WORKDIR /app

RUN apt update -y 

COPY . .
EXPOSE 5050

CMD ["node", "server.js"]
