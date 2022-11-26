# Durée de vie du muon

Des données brutes sont fournies avec un code pour les extraire et les transformer en 299845 évènements, chacun sous forme d'une tension (mV) en fonction du temps (ns). 
Dans ces milliers de tableaux de 5000 points (un point toutes les 5ns) figurent un ou deux pics. 
Le but est de ne conserver que les évènements à deux pics et de faire un histogramme de la durée séparant ces deux pics ; selon une définition arbitraire (entre le maximum des deux pics, ou la première valeur, ou la moyenne).

Pour cela, les données d'intérêt (nombre pics, amplitude, durée selon une définition...) seront calculées puis stockées dans un fichier data.txt. Notons que la durée de vie aura pour valeur -99 s'il n'y a qu'un seul pic.
