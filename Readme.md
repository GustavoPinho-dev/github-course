### Git Course 
Este é um repositório teste para ensinar como Git funciona


Este comando é usado para definir o nome do usuário do Git
# git config --global user.name "Gustavo de Pinho Rezende"

Este comando é usado para definir o email do usuário do Git
# git config --global user.email "gustavo.pinhorezende@gmail.com"

Comando usado para definir o VS Code como editor de texto padrão do Git
# git config --global core.editor "code --wait"

Comando usado para abrir o arquivo '.gitconfig' no VS Code
# git config global -e

<!--init-->
Após estar na pasta do projeto desejado basta executar este comando para adicionar o arquivo git à pasta:
# git init

<!--status-->
Para ver o status de cada documento do projeto em relação ao reposiótio git:
# git status

<!--alterar e adicionar-->
Para abrir um arquivo para alterá-lo basta executar este comando:
# code {nome do arquivo}

Para adicionar esse arquivo ao repositório Git basta executar este comando:
# git add {nome do arquivo}

<!--commit-->
Para salvar uma versão do documento no repositório Git basta:
# git commit -m "{nome da versão do documento}"

<!--log-->
Para visualizar os commits feitos no Git basta realizar o comando: 
# git log

É possível filtrar os commits pelo autor:
# git log --author = "{nome do autor}"

É possível também organizar os commits pelos autores e pela ordem alfabética:
# git shortlog

Através do log também é possível ver a mudança feita através da href:
# git show {rest}

<!--diff-->
