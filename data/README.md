# Data

This dataset includes descriptions of mushroom samples corresponding to 173 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom.

Donated to UCI ML 27 April 1987

## mushroom_dataset.csv
| Variable                | Description                                                                                   |
|-------------------------|-----------------------------------------------------------------------------------------------|
| class                   | poisonous=p, edible=e (binary)                                                                |
| cap-diameter            | float number in cm (metrical)                                                                 |
| cap-shape               | bell=b, conical=c, convex=x, flat=f, sunken=s, spherical=p, others=o (nominal)                |
| cap-surface             | fibrous=i, grooves=g, scaly=y, smooth=s, shiny=h, leathery=l, silky=k, sticky=t, wrinkled=w, fleshy=e (nominal) |
| cap-color               | brown=n, buff=b, gray=g, green=r, pink=p, purple=u, red=e, white=w, yellow=y, blue=l, orange=o, black=k (nominal) |
| does-bruise-bleed       | bruises-or-bleeding=t, no=f (nominal)                                                         |
| gill-attachment         | adnate=a, adnexed=x, decurrent=d, free=e, sinuate=s, pores=p, none=f, unknown=? (nominal)     |
| gill-spacing            | close=c, distant=d, none=f (nominal)                                                          |
| gill-color              | see cap-color + none=f (nominal)                                                              |
| stem-height             | float number in cm (metrical)                                                                 |
| stem-width              | float number in mm (metrical)                                                                 |
| stem-root               | bulbous=b, swollen=s, club=c, cup=u, equal=e, rhizomorphs=z, rooted=r (nominal)               |
| stem-surface            | see cap-surface + none=f (nominal)                                                            |
| stem-color              | see cap-color + none=f (nominal)                                                              |
| veil-type               | partial=p, universal=u (nominal)                                                              |
| veil-color              | see cap-color + none=f (nominal)                                                              |
| has-ring                | ring=t, none=f (nominal)                                                                      |
| ring-type               | cobwebby=c, evanescent=e, flaring=r, grooved=g, large=l, pendant=p, sheathing=s, zone=z, scaly=y, movable=m, none=f, unknown=? (nominal) |
| spore-print-color       | see cap-color (nominal)                                                                       |
| habitat                 | grasses=g, leaves=l, meadows=m, paths=p, heaths=h, urban=u, waste=w, woods=d (nominal)        |
| season                  | spring=s, summer=u, autumn=a, winter=w (nominal)                                              |
