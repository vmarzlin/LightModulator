# LightModulator
Jeu de lumières

Le schéma a été vérifié et semble OK maintenant (il y avait une erreur au niveau des snubbers sur le schéma initial).

## Premier diagnostic
Les TRIACs semblent HS: non dessoudés il y a une résistance de 100 Ohm entre les 2 connecteurs principaux.
À l'oscilloscope on voit bien qu'ils réagissent un peu lorsque la gâchette est excitée (via le 10V d'écart entre GND et NEUT: 3ème quadrant).
Les résistances du snubber sont noires, il se peut que les condensateurs du snubber soient HS.
