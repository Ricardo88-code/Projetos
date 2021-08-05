# Desafio Primeiro Projeto

### Digital Innovation One Inc.

Esse projeto foi desenvolvido com o intuito de completar o desafio "Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso" e mostrar o meu progresso com o Bootcamp Everis New Talents - Java. 

Ao decorrer do curso foi mostrado comandos do GIT e GITHUB, que vou mostrar passo a passo.

#### Criando o repositório.

Foi aberto o Explorer do Windows na pasta c:, clicando com o botão direito selecionei o GIT Bash Here assim foi iniciado o terminal na no repositório c:.

Para criar os repositórios foi utilizado o comando. Fiz o repositório git para deixar organizado os projetos. Usando o comando mkdir + o nome do repositorio.

mkdir git 

Para entrar no repositório foi usado o camando cd + o repositório.

cd git


Criei o repositório DIO que será armazenados o aprendizado na Digital Innovation One Inc. Usando o comando mkdir + o nome do repositorio.

mkdir DIO

Para entrar no repositório foi usado o camando cd + o repositório.

cd DIO

Para os projetos da DIO criei o repositório Projetos.

mkdir Projetos

Para entrar no repositório foi usado o camando cd + o repositório.

cd Projetos

Nesse momento foi iniciado os comandos do git usando o git init.

git init

Próximo passo foi criar um arquivo .md para isso foi usado o camando echo.

echo > Projeto_1.md

No Windows Explore foi aberto o arquivo Projeto_1.md, digitado o conteúdo realizado e salvo. Depois precisa adicionar as alterações com o comando add.

git add *

Assim foi feito o commit, com o comando commit + -m "mensagem", -m serve para deixar uma mensagem que referencie o commit e sempre colocar a descrição entre aspas dupla " ".

git commit -m "Inicio do repositório"

A seguir foi feito o repositório do projeto "Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso". Usando o comando mkdir + o nome do repositorio.

mkdir Desafio_primeiro_repositorio

Foi usado o comando mv, para mover o arquivo Projeto_1.md para o repositório Desafio_primeiro_repositorio. mv + o arquivo + ./ para referencia o repositório que estamos + o repositório de destino.

mv Projeto_1.md ./Desafio_primeiro_repositorio

Agora precisamos fazer o add, nesse caso temos que indicar o arquivo que foi movido e o repositório de destino.

git add Projeto_1.md Desafio_primeiro_repositorio/

Vamos agora criar um Index, para apresentar o projeto.

echo > README.md

Agora vamos usar o comando add para adicionar as alterações.

git add *

E usar o comando commit, para completar a operação.

git commit -m "Criado o Index, e adicionado conteúdo no arquivo Projeto_1.md"
