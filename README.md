#Respuestas cuestionario GIT

11-  Utilicé git reset —hard HEAD~1

12 - Primero git reflog, copié el id del último commit y lo rehice con el comando git reset <id del commit>

13- Desde la rama styled utilicé el comando git merge master

19 - Me cambié a la rama styled y desde allí utilice git merge htmlify, porque es styled quien absorbe a htmlify

21 - Fui a la rama master y utilicé el comando git merge styled

25 - Primer utilicé este comando: git config alias.graph "log --graph --pretty=oneline”.
después “git log —graph”

26- Me fui a la rama master y desde allí utilicé el comando git merge —-no-ff styled

27- Hice un git reset <id de antes del merge>

28- git reset <id del último merge>

29- desde la rama master git branch -D title

30- git reflog, busqué el último merge realizado con title, copie su id y utilicé el comando git reset <id del último merge>

32- Volví al initial commit con el comando git reset HEAD~2
