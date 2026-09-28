# Lire ta note

Ta note va de F à A, comme l'étiquette énergie d'un logement (le DPE). Elle répond à une
seule question : **à quel point ce produit est-il solide aujourd'hui ?**

## Ce que la note mesure exactement

La note porte sur une version précise de ton code, sur une branche précise. Ce n'est pas
une note sur toi, ni sur ton prestataire, ni sur la valeur commerciale du produit. Deux
projets utiles peuvent avoir des notes très différentes.

Elle est calculée à partir de cinq axes : sécurité, dépendances, structure, tests et
dette. Chacun a sa propre lettre, et la note globale les combine. Voir
[Les cinq axes](les-cinq-axes.md).

Le calcul ne fait appel à aucune intelligence artificielle : c'est un enchaînement de
règles fixes, publiées, et les mêmes pour tout le monde.

## La note n'apparaît jamais seule

Sous la lettre, Tenko affiche toujours les **trois causes** qui pèsent le plus. Une cause
regroupe des constats de même nature, par exemple « trois mots de passe écrits en clair »
ou « douze briques logicielles avec une faille connue ». Chaque cause indique les fichiers
concernés et l'effet estimé sur la note si elle disparaît.

C'est voulu : une lettre sans explication ne te permet de rien décider.

## Un axe peut être « non mesuré »

Si ton projet ne contient rien qui permette de juger un axe, Tenko l'affiche « non
mesuré » et le retire du calcul plutôt que d'inventer une note. La note globale indique
alors sur combien d'axes elle porte.

## Pourquoi la note bouge

Trois raisons possibles :

- ton code a changé, en mieux ou en moins bien ;
- une faille vient d'être publiée sur une brique que tu utilises, sans que tu aies rien
  touché ;
- les règles de calcul ont changé de version. Ce changement est marqué sur la courbe
  d'évolution, pour que tu ne confondes pas les deux.

## Si un constat te paraît faux

Ça arrive. Tu peux le contester, et il cesse de peser sur ta note le temps de la revue :
voir [Contester un signal](contester-un-signal.md).

---

[← Retour au wiki](../README.md)
