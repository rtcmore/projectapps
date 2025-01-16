# projectapps

iq-13@iq13:~/Documents/pelindo_apps$ git init
Reinitialized existing Git repository in /home/iq-13/Documents/pelindo_apps/.git/
iq-13@iq13:~/Documents/pelindo_apps$ git add .
iq-13@iq13:~/Documents/pelindo_apps$ git commit -m "Inisialisasi proyek Flutter pelindo_apps"
On branch main
nothing to commit, working tree clean
iq-13@iq13:~/Documents/pelindo_apps$ git status
On branch main
nothing to commit, working tree clean
iq-13@iq13:~/Documents/pelindo_apps$ git remote -v
origin  git@github.com:rtcmore/repo.git (fetch)
origin  git@github.com:rtcmore/repo.git (push)
iq-13@iq13:~/Documents/pelindo_apps$ git init
Reinitialized existing Git repository in /home/iq-13/Documents/pelindo_apps/.git/
iq-13@iq13:~/Documents/pelindo_apps$ git init
Reinitialized existing Git repository in /home/iq-13/Documents/pelindo_apps/.git/
iq-13@iq13:~/Documents/pelindo_apps$ git add .
iq-13@iq13:~/Documents/pelindo_apps$ git commit -m "Inisialisasi proyek Flutter pelindo_apps"
On branch main
nothing to commit, working tree clean
iq-13@iq13:~/Documents/pelindo_apps$ git remote add origin https://github.com/rtcmore/pelindo_apps.git
error: remote origin already exists.
iq-13@iq13:~/Documents/pelindo_apps$ git remote -v
origin  git@github.com:rtcmore/repo.git (fetch)
origin  git@github.com:rtcmore/repo.git (push)
iq-13@iq13:~/Documents/pelindo_apps$ origin  https://github.com/rtcmore/pelindo_apps.git (fetch)
origin  https://github.com/rtcmore/pelindo_apps.git (push)
bash: syntax error near unexpected token `('
bash: syntax error near unexpected token `('
iq-13@iq13:~/Documents/pelindo_apps$ git status
On branch main
nothing to commit, working tree clean
iq-13@iq13:~/Documents/pelindo_apps$ origin  https://github.com/rtcmore/pelindo_apps.git (fetch)
bash: syntax error near unexpected token `('
iq-13@iq13:~/Documents/pelindo_apps$ git status
On branch main
nothing to commit, working tree clean
iq-13@iq13:~/Documents/pelindo_apps$ git remote -v
origin  git@github.com:rtcmore/repo.git (fetch)
origin  git@github.com:rtcmore/repo.git (push)
iq-13@iq13:~/Documents/pelindo_apps$ git push -u origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
iq-13@iq13:~/Documents/pelindo_apps$ ls -al ~/.ssh
total 12
drwx------  2 iq-13 iq-13 4096 Jan 16 12:30 .
drwxr-x--- 26 iq-13 iq-13 4096 Jan 16 12:34 ..
-rw-r--r--  1 iq-13 iq-13  142 Jan 16 12:30 known_hosts
iq-13@iq13:~/Documents/pelindo_apps$ ssh-keygen -t rsa -b 4096 -C "robitbackmore@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/home/iq-13/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/iq-13/.ssh/id_rsa
Your public key has been saved in /home/iq-13/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:dgaZmziJOCcd/4ZFg+vJyV7r7MHsTOl3wUgfnh1AjJ0 robitbackmore@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|           =..   |
|       . o. E    |
|    . . *    .   |
|   o + = =. . .  |
|  + + * S.o= + . |
|   + + @ +. * .  |
|      B X    .   |
|     . O o. .    |
|      .oO. .     |
+----[SHA256]-----+
iq-13@iq13:~/Documents/pelindo_apps$ eval "$(ssh-agent -s)"
Agent pid 27556
iq-13@iq13:~/Documents/pelindo_apps$ ssh-add ~/.ssh/id_rsa
Identity added: /home/iq-13/.ssh/id_rsa (robitbackmore@gmail.com)
iq-13@iq13:~/Documents/pelindo_apps$ cat ~/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC1xx1YhhZwQxGvIHJnU8uduvX5QJtHim+5mU6TE9KvUHmfX2ElG6U7fsL0d/HpnfdcBsK7rc2XPdYESvTLYZjnZ4MRyPO1uCqQAbTFPU8m04ggJVL140FermmtTnFVy2HZdxJ+yI+y2ePLhL2kMCPx3mqbJto7aqRhwE1FqSidllVcxKnqba1CAIWqilmh8XqUzeAOYm/y7TG7DOxtlaoKM1reofFubqeb5yp0I68FENTntaB3Q7KlaLJFQRYMuVL5hC39QhPM4CNG7RYg2H96Ww+OQLJPbFZZMeiB/U2TZAyi4CCP/m5r94vaP3j/tW/HwLjEuy5h+FRG1lqpn7QqqnKLKXKf7vMXfi+tyBrkH7hXfPXoZ1eBr8ogrI18ZaR/i18UNetcO64eUKlmjspWP9TjrffQv2XYxNrPKsi5LFGkmZwweikmj5m4R545ANc0hSA7CHRD1Np9BwZzsjXBkwoFjdXvwQ2agVL4mFPWdUd66+Jj9Qdm/xTamdmXOMBndkh+7hblwHU624WNcSSS9E2cMVXiKTpZfRs2A1aIeQCVLC2GlOUTsRmIVP8U/w6WHJ/bE65MCYcnUJy5bMP6Hdsy1Zn2wZzF4TBQNE8LU2HKo6ztT9SW1IP5KowQr92/Qco2ZtXf8Zl5hEPnxmu19oJfzqrJHDLthVx1bf9ZBw== robitbackmore@gmail.com
iq-13@iq13:~/Documents/pelindo_apps$ git remote set-url origin https://github.com/rtcmore/pelindo_apps.git
iq-13@iq13:~/Documents/pelindo_apps$ git push -u origin main
Enumerating objects: 176, done.
Counting objects: 100% (176/176), done.
Delta compression using up to 2 threads
Compressing objects: 100% (154/154), done.
Writing objects: 100% (176/176), 1.01 MiB | 5.82 MiB/s, done.
Total 176 (delta 20), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (20/20), done.
To https://github.com/rtcmore/pelindo_apps.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
iq-13@iq13:~/Documents/pelindo_apps$ 
