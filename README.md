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

## Visualizando histórico de alterações
Para visualizar o histórico de alterações do repositório, execute o seguinte comando:

- git log

## Ramificação de código
Para criar uma nova ramificação de código, execute o seguinte comando:

- git branch <nome_da_ramificação>

## Para alternar para uma ramificação existente, execute o seguinte comando:

- git checkout <nome_da_ramificação>

## Mesclando ramificações
Para mesclar uma ramificação ao código principal, execute o seguinte comando:

- git merge <nome_da_ramificação>

## Ignorando arquivos
Para ignorar arquivos que não devem ser adicionados ao repositório, crie um arquivo chamado .gitignore e adicione os nomes dos arquivos a serem ignorados.

## Removendo arquivos do repositório
Para remover arquivos do repositório, execute o seguinte comando:

- git rm <nome_do_arquivo>

## Desfazendo alterações
Para desfazer as alterações feitas em um arquivo, execute o seguinte comando:

-git checkout <nome_do_arquivo>

## Desfazendo commits
Para desfazer um commit, execute o seguinte comando:

-git revert <hash_do_commit>

## Desfazendo commits localmente

Para desfazer um commit localmente, execute o seguinte comando:

- git reset HEAD~1

## fazendo tags

git tag v1.0.0 -m"entrega"

git tag -n

git push origin entrega

## conectando no repositório sem precisar baixar

- git remote add origin https://github.com/mistickesterio/exemplo_git.git
- 
- git branch -M main
- 
- git push -u origin main

## gerenciando tags

git tag -a v1.0.0 -m "Versão 1.0.0 - Entrega inicial" <hash_do_commit>

git tag -n

git push origin v1.0.0

Lembre-se de que a ordem e a necessidade de cada comando podem variar dependendo da situação em que você se encontra no uso do Git.
