# ABC du langage C sur Fun par Rémi Sharrock

**Votre mission**

Rémi vous a expliqué comment afficher du texte à l'écran et notamment comment afficher plusieurs lignes de texte ! Dans cette activité, votre but est d'écrire une liste des compétences que vous maitrisez.

**La liste des compétences est la suivante :**


    A ce stade, je sais :  
    - Afficher du texte  
    - Sauter des lignes  
    - Corriger des erreurs   


Attention en tant que développeur C, vous allez devoir respecter certaines règles ! Vous devez respecter strictement ce qui est dans l’encadré !  


**afficher_text1.c**  
[code](./afficher_text1.c)
```c
 #include <stdio.h>
    int main() {
      printf ("A ce stade, je sais :\n- Afficher du texte\n- Sauter des lignes\n- Corriger des erreurs");
      return 0;
}  
```


**Votre mission**

Vous savez afficher des caractères ? Vous savez retourner à la ligne ? Alors faites de l'art avec les lettres !

**Votre but est d'afficher le tableau ci-dessous, en utilisant un seul printf.**

```
   ()_()
 =( °w° )=
   )   (  //
  (__ __)//

```
Attention ! L'artiste qui a créé cette oeuvre tient à ce que son tableau soit reproduit fidèlement, aussi vous ne devez surtout pas le modifier !

Notez en particulier :

    Qu'il n'y a aucun caractère espace à la fin des lignes.
    Qu'il y a une colonne d'espaces à gauche du chat, donc entre 1 et 3 espaces au début de chaque ligne.

Si vous avez des espaces en trop ou en moins, votre programme ne sera pas validé. 

**afficher_chat.c**  
[code](./afficher_chat.c)
```c
 
 #include <stdio.h>

int main() {
    printf ("   ()_()\n =( °w° )=\n   )   (  //\n  (__ __)//");
    return 0;
}
```
**Votre mission**

Youpi ! Vous êtes devenu-e maître des caractères spéciaux. Vous savez donc les insérer dans votre code. Mais savez-vous vraiment les utiliser ? Faisons-en votre spécialité. Nous avons déjà évoqué dans une vidéo précédente la fameuse phrase de Dennis Ritchie, mais elle n'a pas encore suffisamment été mise en valeur dans ce cours. C'est l'heure de remédier à cet oubli et de rendre hommage à cet homme !

Votre but est d'utiliser ces caractères dans votre code, mais en tant que développeur-se C, vous allez devoir les utiliser correctement. Vous ne voulez pas salir la mémoire de ce grand homme !

Nous vous demandons d'afficher le texte suivant :
```
Dennis Ritchie a dit un jour : 
"La meilleure façon d'apprendre à programmer, c'est de programmer."
```
Mais ce serait trop facile comme ça ! Vous n'avez droit ici qu'à un seul printf.

Attention ! Vous devez respecter strictement ce qui est écrit au dessus ! 

**afficher_text2.c**  
[code](./afficher_text2.c)
```c
 #include <stdio.h>

int main() {
    printf ("Dennis Ritchie a dit un jour :\n\"La meilleure façon d'apprendre à programmer, c'est de programmer.\"");
    return 0;
}
}  
```