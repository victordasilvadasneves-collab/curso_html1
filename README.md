# meu projeto

git init
- inicia novo projeto com git

git add <nome-arquivo>/.
- add os aquivos estão pronto para serem commitados

git commit -m "mensagem commit"
- commit os arquivos no hitorico

git log
- mostra os ultimos commit, log de alterações

git status
- como está o estado da nossa ramificações

git diff
- que mostra o que foi alterado
- 0 que tem de alteração na ramificação

git merge 
- merge de ramificações, mescla ramificações

git branch 
-mostra a branch atual

git checkout <nome-branch>
-muda pra essa branch

git branch -b <nome-da-branch>
- criar uma nova branch a partir da da branch atual que estamos

git remote add <nome> <url>
- add novo repositório

git push <nome> <nome-da-branch>
-manda nossas alterações locais para o repositório remoto, pra cada branch 

git pull <nome> <nome-da-branch>
-pega as alterações do repositório remoto, e joga pra nossa maquina 

git fetch
-atualiza o novo historico local de acordo com o historico salvo la no repositorio
-sincronização do local com o remoto