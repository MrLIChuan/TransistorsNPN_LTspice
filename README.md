# TransistorsNPN_LTspice
L'objectif de ce TP est de réaliser le circuit d'un traceur de courbes automatique pour transistors NPN. Ce circuit est soumis à un cahier des charges. Afin de répondre à ces critères, nous allons suivre un protocole bien précis, qui mènera à la simulation, sur LT SPICE IV, du traçage des courbes.

	La méthode de travail consiste à diviser la fonction « traceur de courbes » en plusieurs fonctions simples, qui, assemblées, réaliseront la fonction cherchée. Pour chacune de ces fonctions, on définit un nouveau cahier des charges, qui mènera à un schéma structurel, puis au choix des composants utilisés. Ce travail est réalisé sur papier, et constitue la conception du circuit électronique, que l’on réalise étape par étape, fonction par fonction. Ces fonctions simples seront ensuite simulées sur LT SPICE, indépendamment des autres.
	
	Cela permet tout simplement de s'assurer du bon fonctionnement de chaque bloc fonctionnel. Une simulation complète et prématurée du circuit global complexifie la localisation des erreurs de conception. En effet les fonctions électroniques sont inter-dépendantes, si un résultat affiché par LT SPICE est différent de celui attendu, il est difficile de trouver la localisation du problème parmi toutes les fonctions, qui s’influencent toutes entre elles.
	
	De plus, l’ajustement de chaque fonction demeure relativement simple quand celles-ci sont étudiées une à une. Grâce à la simulation, on peut ajuster la valeur des composants et se rapprocher du résultat souhaité.
	
	Une fois que les fonctions sont simulées et correctement labellisées, il suffit de copier les schémas de ces dernières dans une nouvelle feuille, de les relier entre elles pour obtenir le schéma structurel du circuit demandé. On réalise alors une simulation et on obtient normalement les courbes souhaitées, réalisées par le traceur, et affichables sur un oscilloscope.
	
	Je vais donc, dans ce compte rendu de TP, détailler l’ensemble du travail effectué, analyser les erreurs commises et réaliser une étude critique afin de ne pas les reproduire.
