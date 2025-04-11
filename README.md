# Atividade Avaliativa - Git Colaborativo com Portugol

## Integrantes do grupo
- Luis Henrique
- Witor Tenã

## Objetivo
Desenvolver colaborativamente um algoritmo em Portugol de soma de dois número digitados pelo usuário.

## Etapas realizadas por cada membro

### Luis Henrique
- Criou por meio do github um repositório público com um arquivo .md.
- Foi criada uma chave SSH após definir o usuário git da maquina, com ele usamos um agente para realizar a conexão com o repositório remoto.
- Criou o arquivo `algoritmo.pg` com a estrutura inicial:
- Aguardou o push do colega Witor Tenã, realizou o comando `git clone` e atualizou o arquivo .por.
- Utilizou os comandos `git add`, `git commit -m` e `git push` para atualizar os arquivos do repositório remoto.
- Aguardou o push do colega Witor Tenã, realizou o comando `git pull` e atualizou novamente o arquivo .por.
- Utilizou os comandos `git add`, `git commit -m` e `git push` para atualizar os arquivos do repositório remoto.
- Aguardou o push do colega Witor Tenã, realizou o comando `git pull` e atualizou novamente o arquivo .por para seu estado final.
- Utilizou os comandos `git add`, `git commit -m` e `git push` para atualizar os arquivos do repositório remoto.
- Aguardou o push do colega Witor Tenã, realizou o comando `git pull` e atualizou o arquivo .md.
- Realizou o comando `git add`, `git commit -m` e `git push`, final do arquivo README.md

### Witor Tenã
- Foi criada uma chave SSH após definir o usuário git da maquina, com ele usamos um agente para realizar a conexão com o repositório remoto do colega Luis Henrique.
- Fez o primeiro `git clone` após a criação do repositório do colega Luis Henrique.
- Criou o arquivo estrutural .por principal.
- Realizou o comando `git add`, `git commit -m` e `git push`.
- Aguardou o push do colega Luis Henrique, realizou o comando `git pull` e atualizou novamente o arquivo .por criando a variável soma.
- Realizou o comando `git add`, `git commit -m` e `git push`.
- Aguardou o push do colega Luis Henrique, realizou o comando `git pull` e atualizou o arquivo .md.
- Realizou o comando `git add`, `git commit -m` e `git push`.

## Comandos utilizados
Todos os comandos foram executados via terminal utilizando chave SSH:
### Comandos de Witor Tenã
`
compuni@Lab6m17 MINGW64 ~
$^C

compuni@Lab6m17 MINGW64 ~
$ ^C

compuni@Lab6m17 MINGW64 ~
$ ^C

compuni@Lab6m17 MINGW64 ~
$

compuni@Lab6m17 MINGW64 ~
$

compuni@Lab6m17 MINGW64 ~
$

compuni@Lab6m17 MINGW64 ~
$

compuni@Lab6m17 MINGW64 ~
$

compuni@Lab6m17 MINGW64 ~
$
git config --global user.name

compuni@Lab6m17 MINGW64 ~
$ git config --global user.email

compuni@Lab6m17 MINGW64 ~
$ git config --global user.name "witortenadev"

compuni@Lab6m17 MINGW64 ~
$ git config --global user.email "witortena@edu.unifil.br"

compuni@Lab6m17 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "witortena@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase for "/c/Users/compuni/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:/iNGbvtl48y/rgkEr7BaHIX4TILGr0T2PSO1GolagAU witortena@edu.unifil.br
The key's randomart image is:

compuni@Lab6m17 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1190

compuni@Lab6m17 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (witortena@edu.unifil.br)

compuni@Lab6m17 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m17 MINGW64 ~
$ ssh -T git@github.com
Hi witortenadev! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m17 MINGW64 ~
$ git clone git@github.com:LuisRines/Atividade-Avaliativa-Git.git
Cloning into 'Atividade-Avaliativa-Git'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

compuni@Lab6m17 MINGW64 ~
$ cd Atividade-Avaliativa-Git

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ code .

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git add .

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git commit -m "estrutura principal .por"
[main 0390802] estrutura principal .por
 1 file changed, 5 insertions(+)
 create mode 100644 calculo.por

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git push
ERROR: Permission to LuisRines/Atividade-Avaliativa-Git.git denied to witortenadev.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git push
ERROR: Permission to LuisRines/Atividade-Avaliativa-Git.git denied to witortenadev.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 324 bytes | 324.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:LuisRines/Atividade-Avaliativa-Git.git
   da10b6e..0390802  main -> main

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 377 bytes | 3.00 KiB/s, done.
From github.com:LuisRines/Atividade-Avaliativa-Git
   0390802..3686a16  main       -> origin/main
Updating 0390802..3686a16
Fast-forward
 calculo.por | 5 +++++
 1 file changed, 5 insertions(+)

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git add .

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git commit -m "Adicionada a variavel soma"
[main 717268a] Adicionada a variavel soma
 1 file changed, 3 insertions(+), 1 deletion(-)

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 348 bytes | 348.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:LuisRines/Atividade-Avaliativa-Git.git
   3686a16..717268a  main -> main

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 3 (delta 1), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 345 bytes | 3.00 KiB/s, done.
From github.com:LuisRines/Atividade-Avaliativa-Git
   717268a..1bed749  main       -> origin/main
Updating 717268a..1bed749
Fast-forward
 calculo.por | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

compuni@Lab6m17 MINGW64 ~/Atividade-Avaliativa-Git (main)
$
`
### Comandos de Luis Henrique
`
compuni@Lab6m169 MINGW64 ~
$ idiosyncrasies
bash: idiosyncrasies: command not found

compuni@Lab6m169 MINGW64 ~
$ git config --global user.email

compuni@Lab6m169 MINGW64 ~
$ git config --global --unset user.name

compuni@Lab6m169 MINGW64 ~
$ git config --global --unset user.email

compuni@Lab6m169 MINGW64 ~
$ ls -al ~/.ssh
total 21
drwxr-xr-x 1 compuni 1049089   0 Mar 28 20:07 ./
drwxr-xr-x 1 compuni 1049089   0 Apr 11 19:08 ../
-rw-r--r-- 1 compuni 1049089 828 Mar 28 19:52 known_hosts
-rw-r--r-- 1 compuni 1049089  92 Mar 28 19:52 known_hosts.old

compuni@Lab6m169 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@Lab6m169 MINGW64 ~
$ git config --global user.name "Luis.Rines"

compuni@Lab6m169 MINGW64 ~
$ git config --global user.email "uwann4@edu.unifil.br"

compuni@Lab6m169 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "uwann4@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:aa9tQ2BOIaOrq1RPrjtPanvfhgLeZgnmyynqwH7p6tE uwann4@edu.unifil.br
The key's randomart image is:

compuni@Lab6m169 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1908

compuni@Lab6m169 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (uwann4@edu.unifil.br)

compuni@Lab6m169 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m169 MINGW64 ~
$ ssh -T git@github.com
Hi LuisRines! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m169 MINGW64 ~
$ git clone git@github.com:LuisRines/Atividade-Avaliativa-Git.git
Cloning into 'Atividade-Avaliativa-Git'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@Lab6m169 MINGW64 ~
$ cd Atividade-Avaliativa-Git

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ code .

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git add .

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git commit -m "Adicionado variaveis"
[main 3686a16] Adicionado variaveis
 1 file changed, 5 insertions(+)

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 397 bytes | 132.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:LuisRines/Atividade-Avaliativa-Git.git
   0390802..3686a16  main -> main

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 3 (delta 1), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 328 bytes | 2.00 KiB/s, done.
From github.com:LuisRines/Atividade-Avaliativa-Git
   3686a16..717268a  main       -> origin/main
Updating 3686a16..717268a
Fast-forward
 calculo.por | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git add .

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git commit -m "Finalizado o projeto de soma"
[main 1bed749] Finalizado o projeto de soma
 1 file changed, 1 insertion(+), 1 deletion(-)

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 365 bytes | 365.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:LuisRines/Atividade-Avaliativa-Git.git
   717268a..1bed749  main -> main

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 2.11 KiB | 22.00 KiB/s, done.
From github.com:LuisRines/Atividade-Avaliativa-Git
   1bed749..8628beb  main       -> origin/main
Updating 1bed749..8628beb
Fast-forward
 README.md | 206 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-
 1 file changed, 205 insertions(+), 1 deletion(-)

compuni@Lab6m169 MINGW64 ~/Atividade-Avaliativa-Git (main)
$
`

## Observações
Ocorreu um erro ao dar push para o repositorio do gerenciador do projeto, foi necessário que ele liberasse o acesso do repositorio para o aluno Witor.
