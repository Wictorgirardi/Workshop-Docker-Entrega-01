# Imagem de Origem
FROM node:14
# Diretório de trabalho(é onde a aplicação ficará dentro do container).
WORKDIR /users-service/
COPY package.json /users-service/package.json
RUN yarn 
EXPOSE 7101
CMD ["yarn", "watch"]