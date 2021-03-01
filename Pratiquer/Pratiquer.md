# Pratiquer

Mettez dans ce dossier tout le code source produit dans les exercices proposés pour la partie "Pratiquer" de la fiche Level up


BUBBLE SORT EXEMPLE :

liste = [1,4,5,7,6,8,1,35,46,4,55,12,14,23,7,34,25,21,22,36]

def tri_a_bulles(liste):
	n = len(liste)
	fin="N"
	parcours = 0
	permut = 0
	while fin=="N":
		fin = "O"
		for i in range (n-1):
			if liste [i] > liste [i+1]
			fin = "N"
			liste [i], liste [i+1] = liste [i+1],liste [i]
			print(liste)
			permut = permut + 1
			parcours = parcours + 1
return (liste,parcours,permut)
