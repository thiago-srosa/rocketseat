FROM node

# Define o diretório de trabalho para /app
WORKDIR /app

# Copia o src do projeto
#COPY ./.env /app

COPY package.json .
RUN npm i

# Copia os arquivos do seu projeto para /app
COPY . .

## EXPOSE [Port you mentioned in the vite.config file]
EXPOSE 5173

# Comando para iniciar o aplicativo
CMD ["npm", "run", "dev"]