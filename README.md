# Evaluation diagnostique

## Durée à disposition

```text
//     ___ _____  __  __  __ ___ _  _ _   _ _____ ___ ___   __  __   _   __  __
//    |   \_ _\ \/ / |  \/  |_ _| \| | | | |_   _| __/ __| |  \/  | /_\  \ \/ /
//    | |) | | >  <  | |\/| || || .` | |_| | | | | _|\__ \ | |\/| |/ _ \  >  < 
//    |___/___/_/\_\ |_|  |_|___|_|\_|\___/  |_| |___|___/ |_|  |_/_/ \_\/_/\_\
//                                                                             
```

## Consigne

**`IMPORTANT`**, ce travail est à faire :

- Sans RP
- Sans ChatGPT
- Sans rien de rien => **juste votre mémoire !**

## Travail à réaliser



1) Créez une interface `ISaitProgrammer` n'ayant qu'une seule méthode  
  
    ```java
    void coder(int dureeEnMinutes)
    ```  

    chaque fois que ce sera nécessaire, vous lui donnerez le code suivant :  

    ```java
    System.out.println("Je code pendant " + dureeEnMinutes + " minutes...");
    ```

2) Créez une classe `Personne` ayant deux caractéristiques nom et prénom qu'on ne pourra plus modifier ensuite.
3) Créez une classe `Apprenti` qui sera également une `Personne` et qui aura une caractéristique supplémentaire `anneeDebut` représentant l'année de début de son apprentissage qu'on ne pourra plus modifier ensuite.
4) Créez une classe `Informaticien` qui sera également un `Apprenti` sans aucune autre caractéristique supplémentaire.
5) Créez une classe `Mecanicien` qui sera également un `Apprenti` sans aucune autre caractéristique supplémentaire.
6) Créez une classe `Autodidacte` qui sera également une `Personne` sans aucune autre caractéristique supplémentaire mais ayant appris à programmer par elle-même, et donc implémentant l'interface `ISaitProgrammer`.
7) Dans le `main()` déjà fourni, créez un tableau dynamique permettant de contenir des `Personne`.
8) Ajoutez-y les deux apprentis informaticiens jumeaux ("Alain", "Terrieur", 2022) et son frère ("Alex", "Terrieur", 2022), deux apprentis mécaniciens ("Mac", "Haroni", 2021) et ("John", "D'Oeuf", 2023) ainsi qu'un autodidacte ("Genius", "Master").
9) Dans une boucle, afficher le nom et prenom de chaque personne de la collection.
10) Affichez un séparateur "------------" sur la console.
11) Dans une boucle, afficher le nom et prenom des personnes mais uniquement celles sachant programmer (c-à-d celles qui implémentent bien l'interface `ISaitProgrammer`).  chaque apprenti.
12) On vous fait remarquer que ça n'a pas de sens de pouvoir créer des objets directement issus de la classe Personne. Faites le nécessaire afin d'empêcher qu'on puisse créer un objet de cette classe-là (sans casser tout ce qui précède).
13) Triez votre liste de Personne par ordre alphabétique du nom en utilisant l'implémentation de l'interface Comparable. Afficher votre liste (nom et prénom) triée dans la console.
14) Faites un push/commit pour rendre votre travail.

> Bon travail !