
# Git e GitHub

Armazenagem de comandos e dicas com suas explicações através de minhas próprias palavras.




## Autores

- [@Arthur-84](https://github.com/Arthur-84)


# FAQ

## *init*

~~Comando

git init

~~Objetvo

Inicializa o endereço onde foi executado em um repositório vazio.

## *clone*

~~Comando

git clone +endeço do repositório no Git

~~Objetvo

Criar um repositório novo identico ao selecionado

## *branch*

~~Comando

git branch

~~Objetvo

Criar uma ramificação do mesmo projeto para tratativa separada. Nome deve ser adicionado após o comando. Havendo espaços, colocar entre aspas duplas.

## *checkout*

~~Comando

[1]

git checkout

[2]

git checkout -b

~~Objetvo

[1]

Caminhar pelos locais do projeto. Nome deve ser adicionado após o comando. Havendo espaços, colocar entre aspas duplas.

[2]

Criar uma ramificação do mesmo projeto para tratativa separada E já entrar nela. Nome deve ser adicionado após o comando. Havendo espaços, colocar entre aspas duplas.

## *push*

~~Comando

[1]

git push

[2]

git push --set-upstream origin

~~Objetvo

[1]

Realiza upload de toda ramificação onde foi executado o comando.

[2]

Realiza upload de toda ramificação onde foi executado o comando, caso ainda não exista no repositório remoto original.

## *status*

~~Comando

git status 

~~Objetvo

Exibe o status de mudança e alterações que foram realizadas.

## *add*

~~Comando

[1]

git add .

[2]

git add 

~~Objetvo

[1]

Update para todos os arquivos no diretório.

[2]

Update para o arquivo nomeado. Nome deve ser adicionado após o comando. Havendo espaços, colocar entre aspas duplas.

## *restore*

~~Comando

git restore

~~Objetivo

Restaurar o projeto ao ponto anterior.

## *commit*

~~Comando

git commit

~~Objetivo

Adicionar um comentário que conta um relatório de modificação. Nome deve ser adicionado após o comando. Havendo espaços, colocar entre aspas duplas.

## *stash*

~~Comando

[1]

git stash

[2]

git stash list

[3]

git stash --include untracked

[4]

git stash pop

[5]

git stash pop stash@{n}

~~Objetivo

[1]

Reserva alterações feitas para futuros comits.

[2]

Lista as reservas feitas.

[3]

Reserva alterações feitas para futuros comits em arquivos não rastreados.

[4]

Restaura alterações salvas. Nome deve ser adicionado após o comando. Havendo espaços, colocar entre aspas duplas.

[5]

Aplica alteração em um stash específico. Apontamento realizado no {n} exibido por (stash list), onde  "n" é igual ao número referente ao stash desejado.


## *pull*

~~Comando

git pull

~~Objetivo

Baixa as alterações da main remota para local.