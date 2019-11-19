# V.0.2.0 

* Nesta versao será ima imagem com a atualização dos plugins (pliguins.txt)

## Biuld
* Biuld                 : docker build . --tag renatoschlogel/missaodevopsjenkins:1.0.0 --tag renatoschlogel/missaodevopsjenkins:latest

## Executar imagem
* executando a imagem
   : docker container run --name jenkins \
    -d \
    -p 8080:8080 \
    -v jenkins_home:/var/jenkins_home \
    -v jenkins_backup:/srv/backup \ 
    renatoschlogel/missaodevopsjenkins