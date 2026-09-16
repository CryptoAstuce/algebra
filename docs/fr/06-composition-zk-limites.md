# 6. Composition ZK et limites

arkworks algebra fournit les briques mathématiques, pas un système de preuve complet. Les crates de SNARK choisissent ensuite une courbe, un champ scalaire, un circuit et une relation de vérification.

La généricité facilite la recherche et la composition, mais elle augmente le risque de mauvais paramètres : courbe incompatible, mauvais sous-groupe, domaine trop petit ou encodage divergent.

Les performances dépendent du matériel, du choix de coordonnées, de la taille des domaines et de la stratégie de batch. Elles ne sont pas déductibles uniquement des traits publics.

Périmètre : ce parcours traduit les composants Field, PrimeField, CurveGroup, Pairing, polynomial, hashing et serialization du dépôt. Aucune installation, compilation ou exécution de test n’a été effectuée. Consulter les suites officielles pour une validation concrète.

Retour : [sommaire du parcours](README.md).
