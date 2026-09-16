# 5. Hash-to-curve et sérialisation

Hash-to-curve transforme un message en point d’une courbe selon une suite de hachage et de mapping spécifiée. Le trait HashToCurve sépare le champ, le hash-to-field et la fonction de mapping.

Les paramètres de domaine et les conventions de suite doivent être identiques entre producteurs et vérificateurs. Une différence d’encodage produit un point différent sans nécessairement déclencher une erreur évidente.

La sérialisation canonique représente les éléments de manière déterministe et peut inclure une validation à la désérialisation. Elle est indispensable pour les preuves, les clés et les vecteurs interopérables.

Les entrées externes doivent être rejetées lorsqu’elles ne respectent pas les invariants de la courbe ou du champ.

Suite : [Composition ZK et limites](06-composition-zk-limites.md).
