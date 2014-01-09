# Constitution d'un livre {#core-ref:74c0b7b2-4e50-4e74-8e16-b0642a83d3ab}

![](fbook-icon.png)

Le livre est un famille qui permet de construire un documents en rassemblant
un ensemble de chapitres. Ces chapitres contiennent un texte formaté que le
livre devra assembler suivant l'ordre choisi.

![](fbook-create.png)

## Mise en page du livre {#core-ref:fbd3435f-4dfd-48d7-9936-11046594cfd6}

Le livre permet deux façons de réaliser votre mise en pages. La première
consiste a renseigner les paramètres d'entêtes défini dans le cadre "mise en
pages". Pour les entêtes et les pieds de pages vous pouvez utiliser les mots-
clés `##PAGE##` pour désigner la page courante et `##PAGES##` pour désigner le
nombre total de pages.

Si vous choisissez de mettre une table des matières cette-ci sera inséré après
la page de garde. Cette table des matières ne sera visible que sur le fichier
PDF produit.

La deuxième méthode de mise en page consiste à fournir un fichier au format
openDocument Text pour définir les différents styles (style des titres, des
entêtes, etc.). Si le fichier est présent les autres informations de mise en
pages sont ignorées.

## Le chapitre

Pour créer un chapitre, il faut cliquer sur le menu "Insérer un nouveau
chapitre".

![](fbook1.png)

Cela va associer un nouveau chapitre aux livre. La numérotation permet
d'ordonner le chapitre dans le livre. Le chapitre un devra avoir le numéro 1. Le
numéro zéro est réservé à la page de garde. Vous pouvez aussi définir des sous-
chapitres ; mettez 1.2 pour désigner le sous chapitre deux du chapitre un. Dans
le cas de sous chapitre, il ne faut pas mettre de style de titre de niveau
supérieur. Par exemple pour un chapitre de niveau deux il ne faut pas mettre de
style "titre 1".

Grâce à l'éditeur intégré vous pouvez écrire directement votre texte et ajouter
des images.

Il est aussi possible de renseigner des valeurs d'attributs du livre en
utilisant les noms d'attributs en majuscules et entre crochets.

Pour voir l'ensemble des chapitres constitués vous cliquez sur le menu “Ouvrir”
du livre. Vous pouvez ensuite cliquer sur les liens à droite pour voir les
chapitres. Si vous cliquez sur l'icône vous ouvrez directement le chapitre en
édition. Vous pouvez éditer plusieurs chapitres en même temps; si vous cliquez
sur un autre chapitre vous pouvez revenir au précédent sans perdre votre
édition.

![](fbook2.png)

## Production du fichier assemblé {#core-ref:759d9ab0-b9d5-4e06-855e-0a608f2c8c66}

Une fois vos chapitres écrit vous pouvez voir une pré-assemblage en cliquant sur
le menu "Visualisation" du livre. Cela vous donne un aperçu HTML de l'assemblage
des chapitres.

Pour construire la version PDF, le serveur de transformation doit être installé
et configuré. Cliquer sur le menu "Génération PDF" pour lancer l'assemblage.

![](fbook4.png)

## Pour aller plus loin {#core-ref:57f720b7-94d9-4083-b52d-955c5df537fa}

Le livre fournit par le module est la base pour l'assemblage de texte. Il peut
être dérivé pour vos besoins spécifiques en ajoutant vos propres attributs. Les
chapitres peuvent aussi êtres soumis à des cycles de vies. Vous pouvez aussi
autoriser certains groupes d'utilisateur à modifier des chapitres de tel type et
pas à d'autre. A vous d'imaginer ce que vous pouvez en faire pour l'adapter à
votre besoin.
