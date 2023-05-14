# Exemplo de uso do Git

## Iniciando um novo repositório

Para iniciar um novo repositório, execute os seguintes comandos:

echo "# exemplo_git" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/mistickesterio/exemplo_git.git
- git push -u origin main

## Conectando-se a um repositório remoto

Para conectar seu repositório local a um repositório remoto existente, execute os seguintes comandos:

- git remote add origin https://github.com/mistickesterio/exemplo_git.git
- git branch -M main
- git push -u origin main

## Atualizando seu repositório local

Para atualizar seu repositório local com as últimas alterações do repositório remoto, execute o seguinte comando:

- git pull

## Verificando o status do seu repositório

Para verificar o status do seu repositório, execute o seguinte comando:

- git status

## Configurando suas informações de usuário

Antes de começar a utilizar o Git, é importante configurar suas informações de usuário. Para fazer isso, execute os seguintes comandos, substituindo "seu email" e "seu nome" pelos seus próprios dados:

- git config --global user.email "seu email"
- git config --global user.name "seu nome"

## Clonando um repositório existente

Para clonar um repositório existente em sua máquina, execute o seguinte comando:

- Git clone https://github.com/mistickesterio/exemplo_git.git

## Verificando a versão do Git instalada

Para verificar a versão do Git instalada em sua máquina, execute o seguinte comando:

- git --version

Lembre-se de que a ordem e a necessidade de cada comando podem variar dependendo da situação em que você se encontra no uso do Git.
