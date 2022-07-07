# Boas vindas ao repositório do projeto Docker Todo List!

_Neste projeto:_
  * Usei comandos dockers no CLI - Interface de linha de comando;
  * Criei um contêiner Docker para uma aplicação de front-end;
  * Criei um contêiner Docker para uma aplicação de back-end;
  * Criei um contêiner Docker para uma aplicação de testes; 
  * Orquestrei os três contêiners utilizando Docker Compose;
  
  ### Descrição dos requisitos (files):
    * Desafio 01 - Criei um novo container de modo interativo sem roda-lo nomeando-o como 01container e utilizando a imagem alpine usando a versão 3.12;
    * Desafio 02 - Iniciei o container "01container";
    * Desafio 03 - Listei os containers filtrando pelo nome "01container";
    * Desafio 04 - Executei o comando cat /etc/os-release no container 01container sem se acoplar a ele;
    * Desafio 05 - Removi o container 01container que está em andamento;
    * Desafio 06 - Fiz o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container;
    * Desafio 07 - Rodei um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro;
    * Desafio 08 - Parei o container 02images que está em andamento;
    * Desafio 09 - Gerei uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend;
    * Desafio 10 - Gerei uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend;
    * Desafio 11 - Gerei uma build a partir do Dockerfile dos testes do todo-app nomeando a imagem para todotests;
    * Desafio 12 - Subi uma orquestração em segundo plano com o docker-compose de forma que backend, frontend e tests consigam se comunicar;
    
    ---
    
    Projeto feito na Escola de Programação da Trybe
    
