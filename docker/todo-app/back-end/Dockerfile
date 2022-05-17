FROM node:14-alpine
WORKDIR ./todo-app/back-end/ 
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3001
CMD ["npm", "start"]

# WORKDIR é o caminho onde a imagem vai ser trabalhada
# ADD copio da minha maquina pro workdir
# COPY . pasta atual e todas as pastas dentro dela
