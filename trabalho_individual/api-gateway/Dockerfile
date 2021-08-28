# Imagem de Origem
FROM node:14
# Diretório de trabalho(é onde a aplicação ficará dentro do container).
WORKDIR /api-gateway/
COPY package.json /api-gateway/package.json
RUN yarn 
EXPOSE 7000
CMD ["yarn", "watch"]