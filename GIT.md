# GIT #


## O  que é GIT ? ##

É um versionador de código, mas que pode ser usado para versionar arquivos de modo geral.

Como o GIT  realiza o versionamento? 
------------------------------------

- Cria registros da versão do código (snapshot) no momento em que o arquivo foi commitado
- Cria referencias para esses registros. Essas referências usam hash para identificar.


Estados do GIT 

### Comandos ###

- git clone: clona o repositório
- git init: inicia o repositório local
- git status: verifica o status atual do repositório.
- git add nome_arquivo: adiciona as modificações para área de staged (pré-commit)
- git diff: verifica quais as modificações foram feitas no arquivo.
- git diff -- staged: É a mesma coisa do diff, porém consegue visualizar no momento em que o arquivo está no staged area.
- git log: é o histórico dos commits
- git restore: volta o status do arquivo de unmodified para modified
- git restore --staged: volta da staged area para modfied;
- git pull: baixa os todas as modificações contidas no repositório remoto
- git fetch: verifica as modificações contidas no reposistório remoto, mas não as baixam.
- git branch nome_da_branch: cria uma branch com o nome passado por parâmetro.
- git checkout nome_da_branch_de_destino: muda para branch de destino
- git branch -a: verifica em qual branch o usuário está
- git merge "branch que deseja trazer": junta as alterações da branch em que você está e a branch para qual você deseja trazer as alterações.
