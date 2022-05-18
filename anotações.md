#Anotações Git e Github
##
####Comandos Básicos
**ls -** lista diretórios e repositórios presentes na pasta atual (**+ Flag -a:** revela também os itens ocultos)

__cd (change directory)__ - Te leva ao diretório solicitado. __( + ".." : leva para a diretório anterior; + "/" : vai para a base do windows)__

__Ctrl + l -__ Limpa a tela

**mkdir (make directory) -** Cria um diretório na pasta atual

**mvdir (move directory) -** Move o diretório de um local para outro. **(./ : de para)**

###Comandos Principais

**Git init -** Cria um repositório Git dentro da pasta que esta sendo utilizada.

**Git add -** adiciona itens modificados para staged para ser comitado.**( + " * " : adiciona tudo modificado para staged)** 

**Git commit -m -** comita para o repositório local, mudando o status para unmodified (carrega autor, data, ...).

**Git push -** Passa o repositório local para o repositório remoto

**Git push origin (apelido para o link) master ou main: -** Manda todos os commits que temos localmente para o remoto.


**Git clone link HHTPS copiado(github) -** Clona um repositório remoto em um local, puxando-o.

*__OBS:__* Quando ocorrer um conflito é necessário usar o git pull, fazer as alterações manualmente e fazer novamente o processo (git add e git commit -m)


