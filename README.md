# Extraction de la terminologie à partir des corpus Charcot et Autres à l'aide de l'outil [TermSuite](https://termsuite.github.io/) (Cram & Daille, 2016)

Le répertoire `output` contient deux sous-dossiers :

1. `orig` : tableaux originaux issus de l'extraction des termes uniques à partir des corpus Charcot et Autres, avec de diverses métriques (fréquence, TF-IDF, spécificité...) sous deux formats : 

	* `.tsv` par défaut, en revanche il ne permet la sauvegarde que d'une seule feuille active au sein d'un tableau complet (p. ex. si l'on a généré un tableau dynamique dans une 2<sup>e</sup> feuille à partir des données d'origine de la 1<sup>e</sup> feuille, on perd ces données d'origine) ;
	*  `.ods` : format généré ultérieurement pour pallier le problème de la sauvegarde incomplète.

2. `analyses` : tableaux dynamiques issus des données de départ

* `graphiques` :

	* graphique à colonnes permettant de comparer les répartitions des parties du discours constituant les termes médicaux extraits dans les corpus Charcot et Autres ;
	* nuage de points permettant d'observer la corrélation linéaire positive entre les valeurs TF-IDF et les fréquences brutes des termes.


