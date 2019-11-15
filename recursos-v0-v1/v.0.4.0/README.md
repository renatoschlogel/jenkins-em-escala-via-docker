# V.0.2.0 

* Nesta versao são retirado os wizard qiniciais de configuração e inciado a configuração com o backup previo 

## Biuld
* Biuld                 : docker build . --tag renatoschlogel/missaodevopsjenkins:0.4.0

## Executar imagem
* executando a imagem
   : docker container run --name jenkins-v040 \
    -d \
    -p 8080:8080 \
    -v jenkins_home_4:/var/jenkins_home \
    -v jenkins_backup_4:/srv/backup \ 
    renatoschlogel/missaodevopsjenkins:0.4.0