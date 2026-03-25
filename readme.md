# Comandos Git

## Configuração de utilizador

- git config --global user.name "NOME"
- git config --global user.email "EMAIL"

## Comandos

- git init &#8594; inicia o repositório
- git status &#8594; verifica o estado do repositório
- git add NOMEFICHEIRO &#8594; adiciona um ficheiro específico ao repositório
- git commit -m "MENSAGEM" &#8594; cria ponto no controlo de versões do repositório com os ficheiros adicionados
- git commit -am "MENSAGEM" &#8594; cria um commit e adiciona os ficheiros modificados já adicionados a um commit
  anterior do repositório
- git log &#8594; mostra as informações de todos os commit feitos
- git show CODIGOCOMMIT&#8594; apresenta as alterações efetuadas no commit do código fornecido
- git show &#8594; apresenta as alterações efetuadas no último commit
- git branch NOME &#8594; cria uma branch
- git branch &#8594; mostra as branch existentes
- git checkout NOME &#8594; troca para a branch NOME
- git merge NOME &#8594; estando numa branch acrescenta as funcionalidades da branch NOME à atual
- git branch -D NOME &#8594; elimina a branch NOME

- git remote add origin LINK &#8594; liga o repositório atual local a um repositório online
- git push -u origin master &#8594; envia a branch master para o repositório online (necessário apenas no primeiro envio)
- git push &#8594; enviar o repositório atual local para o repositório online
