# Amara-Ouail-Said-Zakaria-Taleb-Houssem-Eddine
projet système d'exploitation

On veut effectuer en parallèle(En utilisant le modèle producteurs/consommateur) le produit de deux matrices: B (n1* m1) et C (n2 * m2) ⇒ la matrice résultante A=B*C ;

Les matrices sont remplis par des valeurs aléatoires

Les résultats intermédiaires seront placés dans un tampon de taille “T[N]”.

Chaque threads producteurs calcule une ligne de la matrice résultante A et range les résultat dans le tampon T

Les threads consommateurs consomment l'élément T[y] le place dans la matrice résultante A au bon emplacement!

q1: Quelles sont les structures de données à utiliser ?
r: Pour ce problème, vous pouvez utiliser une structure de données telle qu'un tableau à deux dimensions pour représenter les matrices B, C et A. De plus, un tampon de taille T[N] peut être utilisé pour stocker les résultats intermédiaires.
q2: Comment allez-vous protéger l'accès à ces données?
r: Vous pouvez protéger l'accès aux données en utilisant des verrous (locks) ou des sémaphores pour synchroniser l'accès concurrent aux structures de données partagées, comme les tampons et les matrices.
q3: Quels sont les risques?
r: Les principaux risques incluent les conditions de concurrence, les problèmes de synchronisation et les erreurs de gestion de la mémoire. Il est important de concevoir soigneusement la logique de synchronisation pour éviter les conditions de concurrence et les incohérences dans les données partagées.

!

