FROM node:18
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 15000
CMD ["npm", "start"]


# docker build -t backend .
# ipconfig | findstr 192.
# docker run -d -p 15000:15000 -e MONGO_URL=mongodb://192.168.1.166:27017/todos backend
# docker build -t backend .

# docker run -d -p 27017:27017 -v "C:\Users\acer\todo101\data:/data/db" mongo  