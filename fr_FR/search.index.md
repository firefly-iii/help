La recherche peut être utilisée pour trouver des transactions, des comptes, des budgets, etc.

Pour affiner votre recherche de transactions spécifiques, vous pouvez utiliser les "modificateurs" suivants. Ceux-ci sont limités aux transactions et fonctionnent ensemble: si vous recherchez des transactions avec une date spécifique ET d'un type spécifique, les deux conditions doivent être remplies.

* Utilisez ` amount:12.34 ` pour trouver des transactions avec * exactement * Cette somme. Vous devez utiliser des points (.) Comme séparateur décimal.
* Vous pouvez utiliser ` amount_less:100.00 ` et ` amount_more:15.02 ` de la même manière.
* Utilisez ` amount_less ` ensemble avec ` amount_more ` pour rechercher une plage de montants.
* Utiliser ` source: employeur ` pour rechercher des transactions qui ont un compte source spécifique.
* Utilisez ` destination:walmart ` pour rechercher des transactions qui ont un compte de destination spécifique.
* Utilisez ` categorty:épicerie ` pour rechercher des transactions avec une catégorie spécifique.
* Utilisez ` budget:factures ` pour rechercher des transactions avec un budget spécifique.
* Utilisez ` bill:assurance ` pour rechercher des transactions liées à une facture spécifique.
* Utilisez ` type:retrait ` pour rechercher des types spécifiques. Supporté: transfert, dépôt, retrait.
* Utilisez ` on:2017-02-19 ` , ` before:2016-12-10 ` ou ` after:2015-08-30 ` pour limiter la plage de dates des transactions renvoyées.

Ce que vous * ne pouvez pas * faire avec des modificateurs :

* ` source: mon employeur ` : vous ne pouvez pas utiliser d'espaces.
* ` destination: "albert heijn" ` : utiliser des guillemets n'aidera pas.
* ` amount:12,35€ ` : n'utilisez pas les dénominateurs de devise et utilisez le point comme séparateur décimal.
* ` on:today ` ou ` before:30/5/17: ` le seul format pris en charge est ` AAAA-MM-JJ ` . 

Ces extensions sont en cours de développement.