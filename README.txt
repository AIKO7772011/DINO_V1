Site URL:
https://aiko7772011.github.io/DINO_V1/



#11 Уроки Git+GitHub - Бесплатный хостинг Github Pages
https://www.youtube.com/watch?v=K7m1q_-chqo

Сразу можно пойти на 3:05 минут


Идем на GitHub.com 
создаем новый репозитори





###################################################
From GitHub.com
###################################################

https://github.com/AIKO7772011/DINO_V1.git

----------------------------------------------------------------------------

…or create a new repository on the command line
echo "# DINO_V1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/AIKO7772011/DINO_V1.git
git push -u origin main

----------------------------------------------------------------------------

…or push an existing repository from the command line
git remote add origin https://github.com/AIKO7772011/DINO_V1.git
git branch -M main
git push -u origin main


----------------------------------------------------------------------------

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

----------------------------------------------------------------------------
----------------------------------------------------------------------------

https://stackoverflow.com/questions/34400272/visual-studio-code-always-asking-for-git-credentials

git remote set-url origin https://<USERNAME>:<PASSWORD>@bitbucket.org/path/to/repo.git
git remote set-url origin https://AIKO7772011:Zikirokityn11iman@github.com/AIKO7772011/DINO_V1.git
git config --get remote.origin.url
----------------------------------------------------------------------------