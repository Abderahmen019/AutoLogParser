# AutoLogParser
Étape 1 – Création du dépôt GitHub

    Va sur github.com/new

    Nomme ton dépôt : AutoLogParser

    Coche :

        ✅ "Add a README file"

        ✅ "Add .gitignore" → Choisis "Python"

    Clique sur Create repository

🧱 Étape 2 – Cloner ton dépôt et structurer ton projet

Dans ton terminal :

```git clone https://github.com/Abderahmen019/AutoLogParser.git```
voila le resultat de la commande: 

```
abdel@abdel-XPS-13-7390:~$ ls
Desktop    Downloads  Music     Public  Templates  yocto-lab
Documents  Kyma       Pictures  snap    Videos
abdel@abdel-XPS-13-7390:~$ git clone https://github.com/Abderahmen019/AutoLogParser.git
Cloning into 'AutoLogParser'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (4/4), 2.39 KiB | 816.00 KiB/s, done.
abdel@abdel-XPS-13-7390:~$ ls
AutoLogParser  Documents  Kyma   Pictures  snap       Videos
Desktop        Downloads  Music  Public    Templates  yocto-lab
abdel@abdel-XPS-13-7390:~$
```
2.2 Etape 2 ok:
```abdel@abdel-XPS-13-7390:~$ cd AutoLogParser/
abdel@abdel-XPS-13-7390:~/AutoLogParser$ ls
README.md
abdel@abdel-XPS-13-7390:~/AutoLogParser$ cat README.md 
# AutoLogParserabdel@abdel-XPS-13-7390:~/AutoLogParser$ mkdir autologparser logs reports
abdel@abdel-XPS-13-7390:~/AutoLogParser$ ls
autologparser  logs  README.md  reports
abdel@abdel-XPS-13-7390:~/AutoLogParser$ touch main.py requirements.txt
abdel@abdel-XPS-13-7390:~/AutoLogParser$ touch logs/test_log.txt
abdel@abdel-XPS-13-7390:~/AutoLogParser$ touch autologparser/__init__.py autologparser/parser.py autologparser/report.py
abdel@abdel-XPS-13-7390:~/AutoLogParser$ 
abdel@abdel-XPS-13-7390:~/AutoLogParser$ ls
autologparser  logs  main.py  README.md  reports  requirements.txt
abdel@abdel-XPS-13-7390:~/AutoLogParser$ 

```
