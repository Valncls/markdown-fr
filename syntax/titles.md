# Titre

Comme nous avons commencé à écrire un documents Markdown, nous devons ajouter un titre et quelque sous-titres.

Markdown propose deux types d'en-tetes, Setext et atx.

Les styles d'en-tete Setext sont "soulignés" en utilisant le signe égal (pour les premier niveaux d'en-tete) et les tirets (pour les deuxieme niveaux d'en-tete )
Par exemple :

```
Ceci est un H1
=============

Ceci est un H2
-------------
```

Peu importe le nombre de = ou - le soulignement fonctionnera.


Le style Atx utilise de 1 à 6 caractères diez (#) au début de la ligne, cela correspond au niveaux d'en-tete. Par exemple :
```
# Ceci est un H1

## Ceci est un H2

###### Ceci est un H6
```



Il est possible de fermer les styles d'en-tete Atx. C'est simplement esthetique - vous pouvez l'utiliser sivous pensez que cela rend mieux. Le nombre de diez de fermeture n'a pas besoin de correspondre au nombre de diez de départ. (Le nombre de diez de départ détermine le niveau de l'en-tete.) :
```
# Ceci est un H1 #

## Ceci est un H2 ##

### Ceci est un H3 ######
```


---


Voici un quizz sur les en-tete Markdown

Selectionne le bon en-tete:

- [x] `# hello`
- [ ] `#hello`

> Les en-tetes ont besoin d'un espace entre le diez et le texte.

Selectionne le bon en-tete
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seul '=' et '-' sont acceptés pour souligner un en-tete.
---
