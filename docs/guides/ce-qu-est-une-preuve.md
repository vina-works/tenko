# Ce qu'est une preuve

Dans Tenko, l'état « terminé » n'existe pas. Une tâche est **prouvée**, ou elle ne l'est
pas.

C'est le principe central du produit. Partout ailleurs, on te dit qu'une correction a été
faite et tu dois le croire. Ici, la correction est constatée par une machine qui relit ton
code après coup.

## Ce que Tenko constate

Après que tu as poussé une modification, Tenko refait une analyse complète et la compare
à la précédente :

- le problème signalé a-t-il disparu ?
- la modification touche-t-elle bien les fichiers concernés ?
- la note a-t-elle bougé, de combien, et sur quel axe ?

Si les trois réponses concordent, la tâche passe en « prouvée » et Tenko enregistre ce qui
a servi de preuve : la liste des fichiers modifiés, la version avant et après, la note
avant et après.

## Les formes de preuve

- **La modification elle-même** : les lignes ajoutées et retirées, et le signal qui a
  disparu à la nouvelle analyse.
- **Un test** : une vérification automatique qui n'existait pas et qui existe maintenant.

Aucune preuve ne repose sur une déclaration, ni la tienne, ni celle d'un outil d'IA.

## Quand une tâche reste « non prouvée »

Tenko te donne le motif en une phrase, par exemple « deux des trois mots de passe sont
encore présents ». Tu corriges et tu pousses à nouveau, ou tu relances la vérification à
la main.

Cas particulier : si le problème disparaît sans qu'aucune modification identifiable ne
l'explique, la tâche reste « à vérifier ». Tenko ne déclare jamais une réussite par défaut.

## Pourquoi c'est parfois lent

La vérification attend que tu pousses ta modification. Tant que rien n'est poussé, il n'y
a rien à constater. Voir [Coller un prompt dans ton outil](coller-un-prompt.md).

La décision « prouvée » ou « non prouvée » est prise par comparaison automatique, sans
intervention humaine et sans intelligence artificielle.

---

[← Retour au wiki](../README.md)
