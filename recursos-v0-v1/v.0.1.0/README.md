# V.0.1.0

## Biuld
* Primeiro biuld                 : docker build . --tag renatoschlogel/missaodevopsjenkins:0.1.0
* Logar no dockerhub             : docker login
* Enviar imagem para o dockerhub : docker push renatoschlogel/missaodevopsjenkins:0.1.0

## Executar imagem
* executando a imagem
   : docker container run --name jenkins-v010 -p 8080:8080 renatoschlogel/missaodevopsjenkins:0.1.0