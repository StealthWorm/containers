FROM node

WORKDIR /src

COPY package*.json .

RUN npm install
# Indica que ira copiar tudo para o container
COPY . .

EXPOSE 3000
# Maneira de executar a imagem no container
CMD ["node", "app.js"]