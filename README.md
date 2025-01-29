1- Clonar el dipòsit:

	git clone https://github.com/dacomo2021daw2/prjava02.git
	cd prjava02
	ls

	
5- Canviar a main i comparar l’historial:

	git checkout main
	git status
	git log --oneline --graph --all
	02

7-Canviar a branca00 i comprovar canvis:
	
	git checkout branca00
	geany Prjava02.java &

10b-Fer merge de branca00 a main:

	git checkout main
	git merge branca00

12-Fer push de main a GitHub:

	git push origin main

14a- Fer push de branca01 a GitHub:

	git push origin branca01



6-No veuràs la línia afegida en branca00 perquè main encara no té aquests canvis.

7-ara sí que es veu la línia afegida perque estic en branca00.

12c-perquè no hem fet push de branca00.

14c-branca01 està 1 commit per davant de main.
