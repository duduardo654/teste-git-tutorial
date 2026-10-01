##Comandos GITHUB

**
- git clone <url>: copia um repositório remoto para sua máquina;
- git init: inicia um repositório Git em uma pasta local;
- git status: mostra arquivos alterados, adicionados e o estado atual do repositório;
- git add <arquivo>: adiciona um arquivo para preparação do commit;
- git add .: adiciona todas as alterações para o commit;
- git commit -m "mensagem_qualquer": salva as alterações localmente com uma descrição;
- git pull: baixa e aplica as atualizações do repositório remoto;
- git push: envia commits locais para o repositório remoto;
**
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
- git fetch: baixa atualizações do remoto sem aplicar automaticamente;
- git merge: junta alterações de outra branch na branch atual;
- git branch: lista as branches existentes;
- git branch <nome>: cria uma nova branch;
- git checkout <branch>: troca para outra branch;
- git checkout -b <branch>: cria e já troca para uma nova branch;
- git switch <branch>: alternativa moderna para trocar de branch;
- git switch -c <branch>: cria e troca para uma nova branch;
- git log: mostra o histórico de commits;
- git diff: exibe diferenças entre alterações feitas;
- git restore <arquivo>: desfaz alterações locais em um arquivo. Tira da staging;
- git reset: mexe no ponteiro, volta commits ===> git reset --soft HEAD~1: Desfaz o último commit, mas mantém as alterações preparadas (staged);;;; --hard desfaz último commit e apaga as alterações locais;
- git rm <arquivo>: remove um arquivo do repositório;
- git mv <origem> <destino>: move ou renomeia arquivos;
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
- git stash: salva alterações temporariamente sem commit;
- git stash pop: recupera alterações salvas no stash;
- git remote -v: mostra os repositórios remotos conectados;
- git remote add origin <url>: conecta o repositório local a um remoto;
- git tag <nome>: cria uma tag de versão;
- git cherry-pick <commit>: aplica um commit específico em outra branch;
- git rebase <branch>: reorganiza commits com base em outra branch;
- git config --global user.name "Seu Nome": define seu nome no Git;
- git config --global user.email "email@email.com": define seu e-mail no Git;
