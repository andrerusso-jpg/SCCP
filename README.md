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
Deu git pull após o commit de Andre e editou o README.md

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


### LEONARDO RANALI

compuni@maker311 MINGW64 ~
$ git config --global user.name
Leonardo Ranali

compuni@maker311 MINGW64 ~
$ git config --global user.email
leoranli@edu.unifil.br

compuni@maker311 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -c "leoranli@edu.unifil.br"
Too many arguments.
usage: ssh-keygen [-q] [-a rounds] [-b bits] [-C comment] [-f output_keyfile]
                  [-m format] [-N new_passphrase] [-O option]
                  [-t dsa | ecdsa | ecdsa-sk | ed25519 | ed25519-sk | rsa]
                  [-w provider] [-Z cipher]
       ssh-keygen -p [-a rounds] [-f keyfile] [-m format] [-N new_passphrase]
                   [-P old_passphrase] [-Z cipher]
       ssh-keygen -i [-f input_keyfile] [-m key_format]
       ssh-keygen -e [-f input_keyfile] [-m key_format]
       ssh-keygen -y [-f input_keyfile]
       ssh-keygen -c [-a rounds] [-C comment] [-f keyfile] [-P passphrase]
       ssh-keygen -l [-v] [-E fingerprint_hash] [-f input_keyfile]
       ssh-keygen -B [-f input_keyfile]
       ssh-keygen -D pkcs11
       ssh-keygen -F hostname [-lv] [-f known_hosts_file]
       ssh-keygen -H [-f known_hosts_file]
       ssh-keygen -K [-a rounds] [-w provider]
       ssh-keygen -R hostname [-f known_hosts_file]
       ssh-keygen -r hostname [-g] [-f input_keyfile]
       ssh-keygen -M generate [-O option] output_file
       ssh-keygen -M screen [-f input_file] [-O option] output_file
       ssh-keygen -I certificate_identity -s ca_key [-hU] [-D pkcs11_provider]
                  [-n principals] [-O option] [-V validity_interval]
                  [-z serial_number] file ...
       ssh-keygen -L [-f input_keyfile]
       ssh-keygen -A [-a rounds] [-f prefix_path]
       ssh-keygen -k -f krl_file [-u] [-s ca_public] [-z version_number]
                  file ...
       ssh-keygen -Q [-l] -f krl_file [file ...]
       ssh-keygen -Y find-principals -s signature_file -f allowed_signers_file
       ssh-keygen -Y check-novalidate -n namespace -s signature_file
       ssh-keygen -Y sign -f key_file -n namespace file ...
       ssh-keygen -Y verify -f allowed_signers_file -I signer_identity
                  -n namespace -s signature_file [-r revocation_file]

compuni@maker311 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 763

compuni@maker311 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
/c/Users/Compuni/.ssh/id_rsa: No such file or directory

compuni@maker311 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "leoranli@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Compuni/.ssh/id_rsa):
Created directory '/c/Users/Compuni/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/Compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/Compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:etwT2Fmd6rVrJMOS4Bd34z4dqvpR/vyde/LBL3yXc1o leoranli@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
|                 |
|             . . |
|            . o  |
|        .o.o..o  |
|       .S.+=.+.. |
|       o..+o*.+o |
|      . o.oo.Bo+E|
|       .   ...X=@|
|         .oo..o%%|
+----[SHA256]-----+

compuni@maker311 MINGW64 ~
$

compuni@maker311 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 779

compuni@maker311 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/Compuni/.ssh/id_rsa (leoranli@edu.unifil.br)

compuni@maker311 MINGW64 ~
$ clip <~/.ssh/id_rsa.pub

compuni@maker311 MINGW64 ~
$ ssh -T git@github.com
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])?
Host key verification failed.

compuni@maker311 MINGW64 ~
$ clip <~/.ssh/id_rsa.pub

compuni@maker311 MINGW64 ~
$ ssh -T git@github.com
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])?
Host key verification failed.

compuni@maker311 MINGW64 ~
$ ssh -t git@github.com
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])?
Host key verification failed.

compuni@maker311 MINGW64 ~
$ git clone git@github.com:andrerusso-jpg/SCCP.git
Cloning into 'SCCP'...
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])?
Host key verification failed.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

compuni@maker311 MINGW64 ~
$ cd repositotio SCCP
bash: cd: too many arguments

compuni@maker311 MINGW64 ~
$ git push
fatal: not a git repository (or any of the parent directories): .git

compuni@maker311 MINGW64 ~
$ git pull
fatal: not a git repository (or any of the parent directories): .git

compuni@maker311 MINGW64 ~
$ cd SCCP
bash: cd: SCCP: No such file or directory

compuni@maker311 MINGW64 ~
$ git clone git@github.com:andrerusso-jpg/SCCP.git
Cloning into 'SCCP'...
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])?
Host key verification failed.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

compuni@maker311 MINGW64 ~
$ git clone git@github.com:andrerusso-jpg/SCCP.git
Cloning into 'SCCP'...
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])?
Host key verification failed.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

compuni@maker311 MINGW64 ~
$ git clone git@github.com:andrerusso-jpg/SCCP.git
Cloning into 'SCCP'...
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

compuni@maker311 MINGW64 ~
$ code .


compuni@maker311 MINGW64 ~
$

compuni@maker311 MINGW64 ~
$ cd SCCP

compuni@maker311 MINGW64 ~/SCCP (main)
$ GIT PULL
fatal: cannot handle PULL as a builtin

compuni@maker311 MINGW64 ~/SCCP (main)
$ git pull

remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (6/6), done.
Unpacking objects: 100% (8/8), 2.00 KiB | 51.00 KiB/s, done.
remote: Total 8 (delta 1), reused 2 (delta 0), pack-reused 0 (from 0)
From github.com:andrerusso-jpg/SCCP
   a3998d7..950e658  main       -> origin/main
Updating a3998d7..950e658
Fast-forward
 PORTUGOL | 1 +
 Portugol | 1 +
 2 files changed, 2 insertions(+)
 create mode 100644 PORTUGOL

compuni@maker311 MINGW64 ~/SCCP (main)
$

compuni@maker311 MINGW64 ~/SCCP (main)
$ git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 3.01 KiB | 118.00 KiB/s, done.
From github.com:andrerusso-jpg/SCCP
   950e658..e0f37b7  main       -> origin/main
Updating 950e658..e0f37b7
Fast-forward
 README.md | 387 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 387 insertions(+)
 create mode 100644 README.md

compuni@maker311 MINGW64 ~/SCCP (main)
$ code .

compuni@maker311 MINGW64 ~/SCCP (main)
$



## OBSERVAÇÕES
nenhuma.

