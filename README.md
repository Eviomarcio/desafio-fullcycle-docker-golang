# desafio-fullcycle-docker-golang
Desafio do curso FullCycle, no módulo de DevOps, trabalhando com docker.

### Descrição do desafio
> Deverá ser criada uma imagem docker de golang, que ao executar o comando de running, imprima na tela a mensagem: "Full Cycle Rocks!!"

### Requisitos
1. O nome da imagem deverá ser: username/codeeducation
2. A imagem deverá ter menos de __2MB__ de tamanho

  
### Para rodar
##### Dockerhub :whale:
```docker pull eviojoaquim/fullcycle 
docker run eviojoaquim/fullcycle 
```
<br/>

##### Diretamente :zap:
```
git clone https://github.com/Eviomarcio/desafio-fullcycle-docker-golang.git

cd desafio-fullcycle-docker-golang

docker build -t eviojoaquim/fullcycle  .

docker run eviojoaquim/fullcycle
```
<br/>
<br/>
