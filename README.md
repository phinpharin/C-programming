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

