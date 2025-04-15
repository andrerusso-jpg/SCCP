## INTEGRANTES DO GRUPO
- Andre Russo
- Leonardo Ranali

## OBJETIVO
Desenvolver colaborativamente um algoritmo em Portugol de uma pessoa atravessando a rua.

## ETAPAS REALIZADAS POR CADA MEMBRO

## ANDRE RUSSO
Configurei o git ultilizando o tutorial disponibilizado pelo professor
Criei o repositorio
Criei o arquivo do algoritimo com a estrutura inicial no git hub, depois ultilizei o VSCODE
Criei a chave SSH
Desenvolvi e terminei o processo no Portugol.

## LEONARDO RANALI
Deu git pull após o commit de Andre

## COMANDOS ULTILIZADOS

### ANDRE RUSSO

compuni@maker08 MINGW64 ~
$ git config --global --unset user.name

compuni@maker08 MINGW64 ~
$ git config --global --unset user.email

compuni@maker08 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@maker08 MINGW64 ~
$ git config --global user.name "Andre Russo"

compuni@maker08 MINGW64 ~
$ git config --global user.email "andrerusso@edu.unifil.br"

compuni@maker08 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "andrerusso@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:e3XNCQgs8nkCliKD8YaZBg/pkNTAFONENXFWSNQteXc andrerusso@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
|X%=++==.+.       |
|O@.o+* = +...E   |
|*o* o + = ....   |
|.o     + .    .o.|
|        S   . ..o|
|         . . .   |
|        . .      |
|         .       |
|                 |
+----[SHA256]-----+

compuni@maker08 MINGW64 ~
$

compuni@maker08 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 685

compuni@maker08 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (andrerusso@edu.unifil.br)

compuni@maker08 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@maker08 MINGW64 ~
$ ssh -T git@github.com
Hi andrerusso-jpg! You've successfully authenticated, but GitHub does not provide shell access.

compuni@maker08 MINGW64 ~
$ git clone git@github.com:usuario/repositorio.git
Cloning into 'repositorio'...
ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

compuni@maker08 MINGW64 ~
$ cd repositorio
bash: cd: repositorio: No such file or directory

compuni@maker08 MINGW64 ~
$ git.pull
bash: git.pull: command not found

compuni@maker08 MINGW64 ~
$ git.add
bash: git.add: command not found

compuni@maker08 MINGW64 ~
$ git pull
fatal: not a git repository (or any of the parent directories): .git

compuni@maker08 MINGW64 ~
$ git add
fatal: not a git repository (or any of the parent directories): .git

compuni@maker08 MINGW64 ~
$ cd repositorio
bash: cd: repositorio: No such file or directory

compuni@maker08 MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/compuni/.git/

compuni@maker08 MINGW64 ~ (master)
$ ^C


compuni@maker08 MINGW64 ~ (master)
$


compuni@maker08 MINGW64 ~ (master)
$



compuni@maker08 MINGW64 ~ (master)
$


compuni@maker08 MINGW64 ~ (master)
$



compuni@maker08 MINGW64 ~ (master)
$


compuni@maker08 MINGW64 ~ (master)
$



compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$


compuni@maker08 MINGW64 ~ (master)
$









compuni@maker08 MINGW64 ~ (master)
$






compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$

compuni@maker08 MINGW64 ~ (master)
$ git config --global --unset user.name
git config --global --unset user.email

compuni@maker08 MINGW64 ~ (master)
$ rm -f ~/.ssh/id_rsa*

compuni@maker08 MINGW64 ~ (master)
$ git config --global user.name "Andre"

compuni@maker08 MINGW64 ~ (master)
$ git config --global user.email "andrerusso@edu.unifil.br"

compuni@maker08 MINGW64 ~ (master)
$ ssh-keygen -t rsa -b 4096 -C "andrerusso@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:JR8PWrwo7IeuLqonyzoIINXmNq53N3qsLZYr9lADLRE andrerusso@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
|   .E.           |
|  . oo   .       |
| . oo . . *      |
|o   ++   B =     |
|o  o .= S o .    |
|.   .o +         |
|o  .. oo.        |
|= + +o=o=        |
|BB =o**B..       |
+----[SHA256]-----+

compuni@maker08 MINGW64 ~ (master)
$ eval "$(ssh-agent -s)"
Agent pid 901

compuni@maker08 MINGW64 ~ (master)
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (andrerusso@edu.unifil.br)

compuni@maker08 MINGW64 ~ (master)
$ clip < ~/.ssh/id_rsa.pub

compuni@maker08 MINGW64 ~ (master)
$ ssh -T git@github.com
Hi andrerusso-jpg! You've successfully authenticated, but GitHub does not provide shell access.

compuni@maker08 MINGW64 ~ (master)
$ git clone git@github.com:usuario/repositorio.git
Cloning into 'repositorio'...
ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

compuni@maker08 MINGW64 ~ (master)
$ git clone git@github.com:usuario/repositorio.git
Cloning into 'repositorio'...
ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

compuni@maker08 MINGW64 ~ (master)
$ cd repositorio
bash: cd: repositorio: No such file or directory

compuni@maker08 MINGW64 ~ (master)
$ git clone git@github.com:andrerusso-jpg/SCCP.git
Cloning into 'SCCP'...
warning: You appear to have cloned an empty repository.

compuni@maker08 MINGW64 ~ (master)
$ cd repositorio
bash: cd: repositorio: No such file or directory

compuni@maker08 MINGW64 ~ (master)
$ cd SCCP

compuni@maker08 MINGW64 ~/SCCP (main)
$ git pull
Your configuration specifies to merge with the ref 'refs/heads/main'
from the remote, but no such ref was fetched.

compuni@maker08 MINGW64 ~/SCCP (main)
$ code .

compuni@maker08 MINGW64 ~/SCCP (main)
$ code .

compuni@maker08 MINGW64 ~/SCCP (main)
$ git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 1.03 KiB | 70.00 KiB/s, done.
From github.com:andrerusso-jpg/SCCP
 * [new branch]      main       -> origin/main

compuni@maker08 MINGW64 ~/SCCP (main)
$ code .

compuni@maker08 MINGW64 ~/SCCP (main)
$ code .

compuni@maker08 MINGW64 ~/SCCP (main)
$ git pull
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (5/5), 1.72 KiB | 39.00 KiB/s, done.
From github.com:andrerusso-jpg/SCCP
   a3998d7..b7d15f7  main       -> origin/main
Updating a3998d7..b7d15f7
Fast-forward
 PORTUGOL |  1 +
 Portugol | 25 -------------------------
 2 files changed, 1 insertion(+), 25 deletions(-)
 create mode 100644 PORTUGOL

compuni@maker08 MINGW64 ~/SCCP (main)
$ git add .

compuni@maker08 MINGW64 ~/SCCP (main)
$ git commit -m "adicionado codigo no arquivo"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

compuni@maker08 MINGW64 ~/SCCP (main)
$ git push
Everything up-to-date

compuni@maker08 MINGW64 ~/SCCP (main)
$ git add .

compuni@maker08 MINGW64 ~/SCCP (main)
$ git commit -m "adicionado codigo no arquivo"
[main 950e658] adicionado codigo no arquivo
 1 file changed, 26 insertions(+)

compuni@maker08 MINGW64 ~/SCCP (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 487 bytes | 487.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:andrerusso-jpg/SCCP.git
   b7d15f7..950e658  main -> main

compuni@maker08 MINGW64 ~/SCCP (main)
$ ^C


compuni@maker08 MINGW64 ~/SCCP (main)
$


## OBSERVAÇÕES
Andre ultilizou todos os codigos citados acima, leo ultilizou apenas "git pull"

