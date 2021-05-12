# Teste dos comandos git

1- $ git add filename (OK) /* para adicionar um arquivo do seu repo local e poder fazer o commit

2- $ git commit -m "description" (OK) /*para fazer o commit e poder executar o $ git push 

3- $ git push (OK) /*para enviar o novo commmit adicionado para o repo do github

4- $ git pull (OK) /*para baixar o novo repo atualizado no github e poder fazer alterações caso o commit, add, push não funcione, pois para fazer qualquer comando precisa da versão atual do repo no github (pelo que eu entendi)

5- $ git clone (remoto e local) (OK) /* para criar uma cópia de um repo local ou remoto

6- $ git merge branch ( ) /* comando executado porém não deu bom, treina mais para entender e usar

7- $ git diff branch origem branch destino (OK) /* deu bom, é só fazer o git add e comparar o branch de origem (A) com o branch de destino (B) no caso do README.md por exemplo: git --diff a/README.md b/README.md 

# DICAS ÚTEIS

Interface gráfica padrão
gitk (bem daorinha)

Usar saídas do git coloridas
git config color.ui true (uma merda)

Exibir log em apenas uma linha por commit
git config format.pretty oneline (nem me dei ao trabalho)

Fazer inclusões interativas
git add -i (bem daorinha)