# 2. Groupes et courbes elliptiques

ark-ec distingue les représentations affines et projectives des points. Les coordonnées projectives évitent certains inverses coûteux pendant les calculs répétés, puis une conversion ramène le résultat vers une forme affine.

Les traits CurveGroup, AffineRepr et AdditiveGroup définissent l’addition, la multiplication scalaire, l’identité et les conversions. La structure exacte dépend du modèle de courbe.

Les courbes Short Weierstrass et Twisted Edwards n’utilisent pas les mêmes coordonnées ni les mêmes formules. Le type choisi doit donc suivre les paramètres cryptographiques attendus.

La validation des points et des sous-groupes est une condition de sécurité à la frontière des entrées externes.

Suite : [Pairings et cryptographie](03-pairings-cryptographie.md).
