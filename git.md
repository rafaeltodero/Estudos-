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

git commit -m "Aqui você pode deixar uma mensagem" *(Faz o commit dos arquivos e se quiser pode escrever uma mensagem sobre esse commit )*

git remote add origin https://github.com/rafaeltodero/Estudos-.git *(Esse comando adiciona um repositório remoto com nome 'origen')*

git branch -M main *(Ele altera o nome da brach de master para main)*

git brach *(Mostra todas as branch do nosso repositório)*

git branch novaBranch *(Nesse caso estamos criando uma nova branch dentro do nosso repositório, com nome de 'novaBranch')*

git checkout novaBranch *(Com esse código entramos na branch, basta passar o nome dela como fizemos.)*

git brach -d nomeDaBranch *(Deleta a brach local, no entanto você não pode estar nela, esta opção -d irá excluir somente se você já fez o push e o merge com o branch remoto)*

git push < remote> --delete nomeDaBranch *(Esse comando excluirá o branch remoto)*

git push -u origin main *(Esse comando ele pega tudo que está no repositório local para o repositório origin na branch main)*

git clone https://github.com/rafaeltodero/Estudos- *(Ele clona o repositório especificado no link)*

git pull origin main *(Ele atualiza todos os branchs atualiza tudo deixo tudo igual ao repositório remoto )*

