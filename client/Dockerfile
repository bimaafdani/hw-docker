FROM node:alpine
WORKDIR /app-client
COPY package.json . 
RUN npm install
RUN npm install react-scripts@latest 
COPY . .
EXPOSE 3000
CMD ["npm", "start"]