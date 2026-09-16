# 1. Corps finis et arithmétique

Les corps finis fournissent les opérations de base des circuits et des preuves : addition, multiplication, inverse, racine carrée et exponentiation. ark-ff formalise ces opérations avec les traits Field et PrimeField.

Un corps premier est défini par son modulus. Les représentations internes peuvent utiliser plusieurs mots machine, mais la sérialisation canonique doit rester indépendante de cette disposition.

Les éléments doivent respecter les invariants du corps lors du décodage. Une donnée mal formée ne doit pas être acceptée comme un élément valide.

Ces abstractions permettent de réutiliser les mêmes algorithmes avec différentes courbes et configurations de preuve.

Suite : [Groupes et courbes elliptiques](02-groupes-courbes.md).
