#definir imagem base
FROM debian:latest

#definir o desenvolvedor
LABEL maintainer="ARINFOTEC"

#atualiza a imagem 
RUN apt-get update && apt-get upgrade -y

#instala o nginx
RUN apt-get install nginx -y

#expor a porta do serviço nginx
EXPOSE 80

#iniciar o nginx
CMD ["nginx", "-g", "daemon off;"]

