+++
title = "test notebook"
type = "post"
categories = []
tags = []
date = "2017-03-08T18:22:44Z"

+++

### Perfect CdTe (444 supercell)

- Tested for convergence of thermal props and DOS on 48 48 48 and 60 60 60 k-mesh

![CdTe bandstructure](../images/test-notebook/band.png)


#### Animation
Thanks to Adam, it's super easy to generate lovely .gif files of the phonon modes

1) Generate .ascii file in phonopy (choosing the phonon q):

    phonopy anime.conf

2) Call `ascii-phonons` to do it's magic:

    ~/Applications/ascii-phonons/scripts/ascii-phonons anime.ascii -m 0 --gif -d 4 4 4  -o pretty0


