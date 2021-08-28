# Imagem de Origem
FROM node:14
# Diretório de trabalho(é onde a aplicação ficará dentro do container).
WORKDIR /chat-front-app/
COPY package.json /chat-front-app/package.json
RUN npm install --silent
EXPOSE 7001
CMD ["npm", "watch"]