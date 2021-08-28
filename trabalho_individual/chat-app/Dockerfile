# Imagem de Origem
FROM node:14
# Diretório de trabalho(é onde a aplicação ficará dentro do container).
WORKDIR /chat-app/
COPY package.json /chat-app/package.json
RUN yarn 
EXPOSE 7001
CMD ["yarn", "watch"]