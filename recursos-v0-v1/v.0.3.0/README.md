# V.0.2.0 
## Automação de backup's 

* Nesta versão, seram instalandos os plugins definidos do arquivo plugins.txt no jenkins da imagem; 

## Biuld
* Biuld                 : docker build . --tag renatoschlogel/missaodevopsjenkins:0.3.0

## Executar imagem
* executando a imagem
   : docker container run --name jenkins-v030 -p 8080:8080 renatoschlogel/missaodevopsjenkins:0.3.0