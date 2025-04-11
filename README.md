# Atividade-Final

## Integrantes do grupo:
- Daniel de Sales
- Davi Gongora
- Bianca Durães

## Objetivo
Desenvolver colaborativamente um algoritmo em Portugol que recebe um nome e devolve, "Seu nome é" e 'nome'

## Etapas realizadas por cada membro

### Daniel de Sales 
Criou um Repositório "Atividade-Final" e adiciou um arquivo .por, e um arquivo README, após isso, configurou sua chave SSH atráves do git bash; e clonou o repositório na máquina
- Após o integrante Davi fazer as alterações no arquivo,por, o integrante Daniel fez git pull no git bash e trouxe as alterações mais recentes do arquivo. após isso o integrante fez novas alterações adicionando um leia(nome), após isso Daniel executou o codigo "git add ." e executou git commit -m "Segunda Alteração", por ultímo executou git push

### Davi Gongora Ribeiro
Configurou o git bash usando os comandos do tutorial Deluxe até a etapa do clone, onde antes da etapa do clone criou a pasta 'trabfinaleron' no Desktop, usando o comando cd para entrar na pasta antes de finalmente dar clone
Após o clone modificou o arquivo portugol, criando a variavel cadeia nome e logo em seguida executando o comando escreva("Escreva seu nome \n").
Com as alterações feitas, fez o resto dos comandos, git add, git commit e por final git push com descrição de "Primeira alteração"

 

### Bianca Durães
primeiro configurou sua chave SSH atráves do Git bash e clonou o repósitório
-Após a Alteração de Daniel, fez git pull no git bash e trouxe as alterações mais recentes do arquivo. após isso o integrante fez novas alterações adicionando um "escreva("Seu nome é: ",nome)", após isso Bianca executou o codigo "git add ." e executou git commit -m "terceira alteração", por ultímo executou git push


## Comandos utilizados
Todos os comandos foram executados via terminal utilizando chave SSH:
### Comandos de Daniel
compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta
$ git config --global user.name danielsales

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta
$ git config --global user.email danielsales50@gmail.com

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta
$ rm -f ~/.ssh/id_rsa*

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta
$ ssh-keygen -t rsa -b 4096 -C danielsales50@gmail.com
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase for "/c/Users/compuni/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
The key's randomart image is:


compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta
$ eval "$(ssh-agent -s)"
Agent pid 1517

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (danielsales50@gmail.com)

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta
$ ssh -T git@github.com
Hi danielsaaa! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta
$ git clone https://github.com/danielsaaa/Atividade-Final.git
Cloning into 'Atividade-Final'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta
$ cd Atividade-Final

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ pull
bash: pull: command not found

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 363 bytes | 3.00 KiB/s, done.
From https://github.com/danielsaaa/Atividade-Final
   117560c..a798388  main       -> origin/main
Updating 117560c..a798388
Fast-forward
 ATIVIDADE FINAL.por | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git add .

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git commit -m "Segunda alteração"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git push
fatal: User cancelled dialog.
error: unable to read askpass response from 'C:/Users/compuni/AppData/Local/Programs/Git/mingw64/bin/git-askpas
s.exe'
Username for 'https://github.com':
error: unable to read askpass response from 'C:/Users/compuni/AppData/Local/Programs/Git/mingw64/bin/git-askpas
s.exe'
Password for 'https://github.com':
remote: No anonymous write access.
fatal: Authentication failed for 'https://github.com/danielsaaa/Atividade-Final.git/'

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git add .

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git commit -m "Segunda Alteração"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git add .

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git commit -m "Segunda Alteração"
[main 56484d0] Segunda Alteração
 2 files changed, 7 insertions(+)
 create mode 100644 ATIVIDADE FINAL.por.bak

compuni@Lab6m23 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git push
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 368 bytes | 368.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/danielsaaa/Atividade-Final.git
   a798388..56484d0  main -> main


### Comandos de Davi
compuni@Lab6m22 MINGW64 ~
$ git config --global user.name

compuni@Lab6m22 MINGW64 ~
$ git config --global user.email

compuni@Lab6m22 MINGW64 ~
$ git config --global user.email

compuni@Lab6m22 MINGW64 ~
$ ls -al ~/.ssh
total 21
drwxr-xr-x 1 compuni 1049089   0 Mar 28 20:34 ./
drwxr-xr-x 1 compuni 1049089   0 Apr  9 21:03 ../
-rw-r--r-- 1 compuni 1049089 828 Mar 28 19:43 known_hosts
-rw-r--r-- 1 compuni 1049089  92 Mar 28 19:43 known_hosts.old

compuni@Lab6m22 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@Lab6m22 MINGW64 ~
$ git config --global user.name "Davi-cloud-dev"

compuni@Lab6m22 MINGW64 ~
$ git config --global user.email "davi.gongora@edu.unifil.br"

compuni@Lab6m22 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "davi.gongora@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is: (instruido a não colocar por você mesmo :D )

compuni@Lab6m22 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1385

compuni@Lab6m22 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (davi.gongora@edu.unifil.br)

compuni@Lab6m22 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m22 MINGW64 ~
$ ssh -T git@github.com
Hi Davi-cloud-dev! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m22 MINGW64 ~
$ cd Desktop

compuni@Lab6m22 MINGW64 ~/Desktop
$ cd trabfinaleron

compuni@Lab6m22 MINGW64 ~/Desktop/trabfinaleron
$ git clone git@github.com:danielsaaa/Atividade-Final.git
Cloning into 'Atividade-Final'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@Lab6m22 MINGW64 ~/Desktop/trabfinaleron
$ git add .
fatal: not a git repository (or any of the parent directories): .git

compuni@Lab6m22 MINGW64 ~/Desktop/trabfinaleron
$ git add .
fatal: not a git repository (or any of the parent directories): .git

compuni@Lab6m22 MINGW64 ~/Desktop/trabfinaleron
$ cd Atividade-Final

compuni@Lab6m22 MINGW64 ~/Desktop/trabfinaleron/Atividade-Final (main)
$ git add .

compuni@Lab6m22 MINGW64 ~/Desktop/trabfinaleron/Atividade-Final (main)
$ git commit -m "Primeira alteração"
[main a798388] Primeira alteração
 1 file changed, 2 insertions(+), 1 deletion(-)

compuni@Lab6m22 MINGW64 ~/Desktop/trabfinaleron/Atividade-Final (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 383 bytes | 95.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:danielsaaa/Atividade-Final.git
   117560c..a798388  main -> main

### Comandos de Bianca
compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta
$ git config --global user.name biancduraes

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta
$ git config --global user.email biduraes@edu.unifil.br

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta
$ rm -f ~/.ssh/id_rsa*

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta
$ ssh-keygen -t rsa -b 4096 -C biduraes@edu.unifil.br
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase for "/c/Users/compuni/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:


compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta
$ eval "$(ssh-agent -s)"
Agent pid 1517

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (biduraes@edu.unifil.br)

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta
$ ssh -T git@github.com
Hi biancduraes! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta
$ git clone https://github.com/danielsaaa/Atividade-Final.git
Cloning into 'Atividade-Final'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta
$ cd Atividade-Final

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 363 bytes | 3.00 KiB/s, done.
From https://github.com/danielsaaa/Atividade-Final
   117560c..a798388  main       -> origin/main
Updating 117560c..a798388
Fast-forward
 ATIVIDADE FINAL.por | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git add .

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git commit -m "terceira alteração"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git push
fatal: User cancelled dialog.
error: unable to read askpass response from 'C:/Users/compuni/AppData/Local/Programs/Git/mingw64/bin/git-askpas
s.exe'
Username for 'https://github.com':
error: unable to read askpass response from 'C:/Users/compuni/AppData/Local/Programs/Git/mingw64/bin/git-askpas
s.exe'
Password for 'https://github.com':
remote: No anonymous write access.
fatal: Authentication failed for 'https://github.com/danielsaaa/Atividade-Final.git/'

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git add .

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git commit -m "Segunda Alteração"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git add .

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git commit -m "terceira alteração"
[main 56484d0] terceira alteração 
 2 files changed, 7 insertions(+)
 create mode 100644 ATIVIDADE FINAL.por.bak

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$ git push
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 368 bytes | 368.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/danielsaaa/Atividade-Final.git
   a798388..56484d0  main -> main

compuni@Lab6m24 MINGW64 ~/Desktop/Nova pasta/Atividade-Final (main)
$




## Observações
(caso tenha ficado confuso, o Daniel quem fez as configurações do relatório, mas Davi fez a primeira alteração)
