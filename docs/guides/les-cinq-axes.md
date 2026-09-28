# Les cinq axes

Ta note globale combine cinq jugements séparés. Chacun a sa propre lettre, de F à A, pour
que tu saches quoi corriger en premier.

| Axe | Ce que c'est | Pourquoi ça compte |
| --- | --- | --- |
| **Sécurité** | Ce qui peut être retourné contre toi : un mot de passe laissé en clair dans le code, une page d'administration sans verrou. | Une porte ouverte est trouvée par des robots, souvent avant tes premiers clients. |
| **Dépendances** | Les briques toutes faites que ton produit utilise et que d'autres équipes entretiennent à ta place. | Une brique trop ancienne ou connue comme percée fragilise ton produit sans que rien ne change à l'écran. |
| **Structure** | La façon dont le code est rangé : des fichiers de taille raisonnable, des noms clairs, chaque chose à un seul endroit. | Un code mal rangé rend chaque modification plus longue, donc plus chère, y compris pour une IA. |
| **Tests** | Des vérifications automatiques qui relancent ton produit et disent si quelque chose vient de casser. | Sans elles, tu découvres les pannes en même temps que tes utilisateurs. |
| **Dette** | Les raccourcis pris pour aller vite : du code recopié, du code mort, des morceaux laissés à finir. | La dette ne bloque rien aujourd'hui et ralentit tout dans six mois. |

## Lequel regarder en premier

**Sécurité et dépendances d'abord** : ce sont les deux axes où un problème peut te coûter
quelque chose sans prévenir. Structure, tests et dette se corrigent plus lentement et se
voient sur la durée. Tenko applique cet ordre pour classer tes trois causes : voir
[Lire ta note](lire-ta-note.md).

---

[← Retour au wiki](../README.md)
