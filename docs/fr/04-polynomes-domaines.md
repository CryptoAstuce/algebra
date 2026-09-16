# 4. Polynômes et domaines d’évaluation

Les polynômes représentent les relations que les systèmes de preuve veulent vérifier. ark-poly fournit des polynômes denses, creux et des domaines d’évaluation adaptés aux FFT.

Un domaine d’évaluation choisit des points structurés, souvent des racines de l’unité, pour passer efficacement entre coefficients et évaluations. La taille du domaine doit couvrir le degré demandé.

Les opérations d’interpolation, d’évaluation et de FFT sont sensibles aux paramètres du corps. Les contraintes de puissance et de taille sont donc des propriétés cryptographiques autant que des détails de performance.

Cette couche relie l’algèbre abstraite aux constructions de preuve concrètes.

Suite : [Hash-to-curve et sérialisation](05-hash-serialization.md).
