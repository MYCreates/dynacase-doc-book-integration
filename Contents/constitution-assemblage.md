# Constitution d'un assemblage de fichiers  {#book-integration:beb70ace-1c95-452b-88e9-bc5911e555cf}

![](assemblage-icon.png)

L'assemblage de fichiers permets de constituer un fichier PDF unique qui
rassemble un ensemble de fichiers. Cet assemblage de fichier est réalisé avec la
famille Assemblage. Cette famille va définir un ensemble de fichiers qui seront
une succession de chapitre de niveau un. Au contraire du livre, avec cette
famille l'assemblage de sous-chapitres n'est pas possible. Chacun des fichiers
chapitre est un fichier au format openDocument Text ou Microsoft Word. Si vous
voulez insérer des feuilles de tableurs, il faudra les insérer par copier/coller
(sans faire de liens) dans un fichier texte.

![](collating-edit.png)

La sélection des fichiers à insérer comme chapitre se fait par une sélection de
documents qui contiennent au moins un fichier. Pour cela dans le tableau
"chapitres", vous sélectionnez d'abord la famille dans la première colonne,
ensuite vous sélectionnez le document de la famille voulu. Ensuite, de manière
optionnelle vous pouvez choisir l'attribut fichier dans le cas ou le document en
possède plusieurs. :!: Attention, les tableaux de fichiers ne sont pas supportés
par l'assembleur. Ensuite si votre document chapitre est contraint par un cycle
de vie vous pouvez sélectionner l'état dans lequel vous voulez votre chapitre.
Si un état est sélectionné, l'assembleur choisira le dernier fichier dans l'état
désigné. Cet état est forcément figé, cela signifie que le fichier n'est pas
modifiable. Si vous faite une modification au document chapitre (forcément dans
l'état courant) il faudra ré-appliquer un changement d'état pour que le fichier
soit pris en compte par l'assembleur. Si le document n'est pas disponible dans
l'état souhaité, le fichier n'apparaîtra pas. S'il n'y as pas d'état, par défaut
c'est la révision du document utilisé lors de son insertion qui sera utilisé. Si
le document chapitre est révisé après son insertion, les modifications ne seront
pas prise en compte par l'assembleur. Si vous voulez toujours la dernière
révision, il faut alors choisir "La plus récente".

![](collating-view.png)

Une fois les documents choisis, l'assembleur vous affiche des liens pour
consulter les fichiers et les documents dont sont issus les fichiers qui vont
être utilisés pour l'assemblage.

Afin d'assembler les chapitres, il est nécessaire aussi de renseigner le fichier
principal au format openDocument Text, qui contiendra le style général du
fichier assemblé. Il peut être utilisé pour définir les entêtes et les pieds de
pages ainsi que la table des matières.

Pour la tables des matières, il est nécessaire d'avoir utilisé des textes avec
les styles "titre 1", "titre 2" et "titre 3" pour que cette table soit
correctement produite. Une fois utilisé, vous pouvez effacer les textes si vous
n'en avez pas usage dans le fichier de garde.

Pour lancer l'assemblage, le serveur de transformation doit être installé et
configuré. Lorsqu'il est configuré il faut cliquer sur le menu “Assembler” pour
lancer la procédure d'assemblage. Cette procédure se déroule en deux temps. Vous
verrez d'abord apparaître le fichier assemblé dans le format "openDocument Text"
puis dans un second temps la version PDF sera disponible. Voici un exemple du
PDF produit avec la table des matières et les entêtes de pages.

![](collating-toc.png)

![](collating-pdf.png)
