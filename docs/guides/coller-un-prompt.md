# Coller un prompt dans ton outil

Un prompt est un texte d'instructions pour un outil de développement assisté par
intelligence artificielle. Tenko en rédige un par cause, à ta place, et ne modifie jamais
ton code : il te donne le texte, tu gardes la main.

## Les quatre étapes

1. **Choisis ton outil** : Claude Code, Cursor, Lovable ou Bolt. La mise en forme suit
   l'outil, et ton choix est mémorisé pour le projet.
2. **Clique sur « Copier le prompt ».**
3. **Colle-le dans ton outil**, et relis ce qu'il propose.
4. **Enregistre la modification sur ton dépôt** — on dit « pousser ». Tenko relance une
   vérification tout seul.

## Ce que contient le prompt

Une fiche de travail complète :

- **ce que tu veux, et pourquoi**, du point de vue de ton produit ;
- **ce qui a été mesuré** : les fichiers, les lignes, les chiffres relevés ;
- **la marche à suivre**, puis **les critères d'acceptation** ;
- **le cas nominal** et **les cas d'erreur** : ce qui doit continuer de marcher, et ce qui
  doit bien se passer quand quelque chose rate ;
- **ce qu'il ne faut pas toucher**, et la vérification finale.

Les critères d'acceptation te servent le plus : « est-ce fait ? » s'y répond par oui ou
par non, sans savoir lire du code. Le prompt se termine en demandant à l'outil de les
reprendre un par un — c'est ce qui te sert à relire.

Il ne contient jamais tes mots de passe ni tes clés d'accès : les passages concernés sont
masqués. Voir [Ce que Tenko fait de ton code](ce-que-tenko-fait-de-ton-code.md).

## Si le résultat ne te convient pas

Ne pousse pas la modification. Un outil d'IA peut se tromper ou casser autre chose : c'est
pour ça que Tenko revérifie plutôt que de te croire sur parole, voir
[Ce qu'est une preuve](ce-qu-est-une-preuve.md).

Si la correction n'a pas lieu d'être, [conteste le signal](contester-un-signal.md).

## Ce que ça consomme

Rédiger un prompt consomme des crédits ; un prompt déjà rédigé est resservi sans rien
coûter. Plafond mensuel atteint, Tenko cesse d'en produire de nouveaux mais continue de
calculer ta note. Voir [Ton budget et ton plafond](budget-et-plafond.md).

Les prompts sont rédigés par un système automatisé et se terminent par une mention le
rappelant.

---

[← Retour au wiki](../README.md)
