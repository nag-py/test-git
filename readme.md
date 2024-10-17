# comment bien utiliser git

### De quoi est composé git ?

- Dossier local
	- git init (repo local)
	- git status (pour voir l'état)
- Staging area
	- git add "nom du fichier" ou .
	- touch .gitignore (fichiers à ne pas mettre dans le stage)
- Dépôt local
	- git commit -m "add files"
	- git log --oneline (pour voir le commit et la réference de la version)
- Github
	- creer un repo sur github
	- git branch -M main
	- git remote add origin https://github.com/nag-py/test-git.git
	- git push -u origin main