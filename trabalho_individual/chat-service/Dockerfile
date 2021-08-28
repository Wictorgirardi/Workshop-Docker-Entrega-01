# Imagem de Origem
FROM node:14
# Diretório de trabalho(é onde a aplicação ficará dentro do container).
WORKDIR /chat-service/
COPY package.json /chat-service/package.json
RUN yarn 
EXPOSE 7100
CMD ["yarn", "watch"]