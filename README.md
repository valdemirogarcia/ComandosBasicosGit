## Comandos Git
![](https://cdn.iconscout.com/icon/free/png-256/git-2752184-2285001.png)
### Principais comandos utilizados para gerenciar o versionamento no Git. <br>
`git init` - Cria a estrutura inicial do repositório Git no computador local.\
`git add README.md` - Cria arquivo README.md e o adiciona ao histórico do projeto, na staging.\
`git add .` - O ponto no final define que todos os arquivos que foram alterados serão adicionados ao histórico do projeto, na staging.\
`git commit -m "comentario"` - Registra/salva a alteração no repositório.\
`git remote add origin https://github.com/userName/repoName.git` - Informa a pasta remota.\
`git push -u origin main` - Publica as alterações no repositório remoto.\
ou\
`git push --force origin main` - Força a publicação das alterações no repositório remoto.\ <br>
---
`git remote -v` - Permite visualizar o repositório remoto.\
`git log` - Permite visualizar as alterações feitas.\
`git add` - Adiciona arquivos ao histórico do projeto, na staging.\
`git status` - Verifica o status das alterações realizadas no repositório.\
`git pull` - Baixa todas as alterações do repositório remoto para o diretório local (equivalente a fetch e depois o merge).\
`git clone "link do repositorio"` - faz uma cópia da pasta do Github.\
`git merge` - incorpora os arquivos no nosso repositório local depois do git fetch.\
`git merge --abort` - abortará o processo de mesclagem e tentará reconstruir a condição anterior a mesclagem.\
`git checkout -b tarefa/minha-primeira-branch` - cria uma branch (O parâmetro "–b" é utilizado para informar que desejamos criar uma branch e que esse ramo ainda não existe.)\
`git branch` - lista as branches já criadas.
