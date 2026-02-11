## Como iniciar um projeto no git:
git init --initial-branch=main

## O que é:
é um parametro opcional que informa o git a utilizar a branch inicial sendo a main e não mais a master. O nome é um nome em desuso.

## Branch:
sao ramos de trabalho. Linhas, versoes para sereme implementadas.

## Commitando:
1. crie arquivos, ex:
a. criar arquivo index.js
b. criar pasta docs e dentro da pasta criar um arquivo aula1.md

2. dados que os arquivos foram criados mas ainda não identificados como não rastreáveis para o GIT, vamos adicionar eles ao rastreio com o comando. 
```sh
git add *
```
3. Uma vez que foram adicionado, estão aptos a serem incluídos em um commit

*Definição de commit
Comando para commitar
```
git commit -m 'mensagem do commit'
```

## Segue os trabalhos
git add *
git commit -m 'add mensagem' 