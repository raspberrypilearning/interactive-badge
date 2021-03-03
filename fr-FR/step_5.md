## Créer une animation simple

Créons une animation (très) simple pour tes visages heureux et tristes.

+ Ajoute un deuxième bloc `montrer LEDs` dans ton bloc `lorsque le bouton A est pressé`, avec un visage neutre.

![capture d'écran](images/badge-neutral.png)

+ Si tu exécutes ce code pour le tester, tu remarqueras que le motif change rapidement. Pour que le changement soit plus lent, tu devras ajouter un bloc `pause` entre les 2 images affichées.

![capture d’écran](images/badge-pause.png)

Pour choisir le nombre de millisecondes à attendre, clique sur la flèche vers le bas et entre un nombre. 1000 millisecondes équivaut à 1 seconde, donc 250 millisecondes équivaut à un quart de seconde.

+ Tu devras aussi animer ton visage triste. La façon la plus simple d'y arriver est de dupliquer les blocs que tu viens juste de créer. Fais un clic droit sur un bloc pour le dupliquer. Tu remarqueras que l'éditeur PXT duplique juste un bloc à la fois (pas plusieurs blocs comme dans Scratch.)

+ Tu peux ensuite faire glisser ces blocs dans ton bloc `lorsque le bouton B est pressé`. Voici à quoi ton code devrait ressembler :

![capture d'écran](images/badge-on-b-pressed.png)

+ Teste ton code, et tu devrais voir un visage souriant ou triste animé quand tu appuies sur le bouton A et B.

![capture d'écran](images/badge-final.gif)