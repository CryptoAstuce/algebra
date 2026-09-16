# 3. Pairings et cryptographie

Un pairing bilinéaire transforme deux points de groupes elliptiques en un élément d’un groupe multiplicatif. Cette propriété permet de vérifier des relations algébriques utilisées par Groth16, KZG et d’autres constructions.

Le trait Pairing décrit les groupes, le champ cible et l’opération de pairing sans imposer une courbe unique. Les familles BLS12 et BN disposent d’instanciations spécialisées.

La sécurité dépend des paramètres, des cofactors, des sous-groupes et des conventions d’encodage. Une formule correcte sur une mauvaise courbe ne fournit pas la sécurité attendue.

Les opérations de pairing sont coûteuses : les bibliothèques optimisent les multiplications et les multi-pairings, mais l’intégrateur doit toujours maîtriser les tailles d’entrée.

Suite : [Polynômes et domaines d’évaluation](04-polynomes-domaines.md).
