# Estudos de GIT
![status!](https://img.shields.io/badge/GIT-Em%20Desenvolvimento-green)
## Indice

* [O que é o GIT](#O-que-é-o-GIT)
* [Como inicializa o GIT](#Como-inicializa-o-GIT)


## O que é o GIT
É um sistema de versionamento, através dele podemos navegar entre diferentes versões que nós criamos de nossos arquivos.

## Como inicializa o GIT
**Fluxo do GIT**

git config --global user.name "escreva seu nome aqui" *(Aqui será o nome em que outras pessoas te veram no git)*

git config --global user.email "seuEmail@seuemail.com" *(Aqui você coloca seu email)*

git init *(Inicializa o repositório git)*

git status *(Ele mostra os arquivos que não estão preparados para commit mas tem alterações nele)*

git add . *(Prepara todos arquivos para serem comitados)* 

git add nomeDoArquivo.html *(Prepara apenas o arquivo digitado para ser comitado)

git rm --cached nomeDoArquivo.html *(Remove o arquivo que estava comitado)*

git commit-m"mensagem" *(Faz o commit dos arquivos )*


