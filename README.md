# GabrielChaves
## Projeto Trainee, Code Jr, 2019.2

Desenvolvedores:
- Alexande Pacelli
- Henrique Silva
- Pedro Reis
- Nádia Kappaun


Scrum Master:
- Vitor Mouro


## GIT TUTORIAL
### Primeira configuração

- Entre na pasta onde irá guardar o projeto: cd /caminho/para/a/pasta

- Inicialize o git na pasta: git init

- Crie um clone do repositório: git clone <link-para-o-repositorio>

- Entre na pasta criada pelo comando clone: cd /caminho/para/a/pasta/nova

- Crie sua branch usando como o padrão o nome da feature que você está a desenvolver: git checkout -b frontend_painel_adm
### Rotina
- Adicione as alterações feitas: git add .

- Cheque em qual branch está e quais alterações foram adicionadas: git status

- Dê um commit com uma mensagem especificando as alterações realizadas: git commit -m "mensagem especificando o que foi feito"

- Envie o commit feito para sua branch: git push origin suabranch

### Quando estiver tudo prontinho
- Volte para a master: git checkout master

- Atualize a master: git pull

- Volte para a sua branch: git checkout nomedabranch

- Mescle a master com a sua branch : git merge master

- Confirme o merge (apenas quando solicitado pelo SM): git push origin suabranch

- Espera a confirmação do seu SCRUM 

- Mescle a master com as alterações enviadas para sua branch (apenas quando solicitado pelo SM): git merge suabranch

- Confirme o merge (apenas quando solicitado pelo SM): git push origin master

- Para atualizar a master: git pull

- Para atualizar alguma branch: git pull origin branch

- Para mesclar sua branch com a master (estando dentro da sua branch): git merge master

- Para confirmar o merge: git push origin suabranch
