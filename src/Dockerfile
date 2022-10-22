FROM node:18.11.0
# Cria pasta de trabalho
WORKDIR /app
# Copia o arquiv9 das dependências
COPY package*.json ./
# Npm instala as dependências
RUN npm install
# Copia todo os dados para a pasta /app
COPY . .
# Expõe a porta 8080
EXPOSE 8080
CMD ["node", "server.js"]