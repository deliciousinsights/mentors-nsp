# Prochainement…

Quelles évolutions prévues / souhaitables pour NSP ?

## Guide d’installation Node / nvm

Un Gist public va prochainement être publié pour faciliter l’installation de Node sur les machines, pour les principaux OS (Win8 / Win10 / Win10 WSL / Ubuntu / OSX), en favorisant le recours à [nvm](https://github.com/creationix/nvm) et [nvm-windows](https://github.com/coreybutler/nvm-windows) autant que possible, plutôt que les installeurs officiels.

En effet, les personnes de l’auditoire peuvent ainsi :

1.  Utiliser plusieurs versions de Node, ce qui sera pratique à terme mais leur permet aussi d’utiliser des vieux ateliers qui seraient devenus incompatibles avec les versions récentes.
2.  Installer sans avoir les droits administrateur sur leurs machines, notamment pour les droits Linux / OSX.

## Auto-configurateur VS Code & Fontes

On l’a vu apparaître au fil des sessions sur les laptops des participant·e·s, et 2017 a été l’année de son énorme succès : [Visual Studio Code](https://code.visualstudio.com/) est désormais partout !

Christophe est désormais un fan inconditionnel, au point qu’il sert de [base d’édition pour les formations Delicious Insights](https://installations.delicious-insights.com/software/vscode.html).

Ce qui est pratique avec Code, c’est qu’on peut le scripter pour installer des extensions, y coller de la config, etc.

Beaucoup de gens arrivent à NSP avec un Code tout fraîchement installé, encore très loin du confort qu’il peut fournir pour le travail avec JS et Node. On va mettre en place un module npm dont l’installation et l’exécution (typiquement via `npx`) auto-configurera le Code de la machine locale pour l’utilisateur courant, un peu comme le [`vscode-setup`](https://github.com/deliciousinsights/vscode-setup#readme) utilisé pour les formations Delicious Insights, mais plus ciblé, avec quelques choix interactifs (genre coloration sur fond clair ou sombre, etc.), et en auto-téléchargeant / installant des fontes comme la [Source Code Pro](https://github.com/adobe-fonts/source-code-pro#readme) si nécessaire.

## Élargir et mettre à jour les traductions

La totalité des VF d’ateliers actuellement disponibles remonte à un effort massif début 2015 par Jérémie et Christophe. Certains ateliers ont depuis été largement mis à jour, et d’autres sont arrivés, qui n’ont pas ou plus de VF qualitative.

La plupart des ateliers ont entre 2 et 5 ans maintenant 😒… Certains ne marchent même plus correctement sur Node 10 voire Node 8 !

Il faudrait notamment ajouter les VF pour les ateliers qui en manquent mais sont populaires, tels que :

- [Scopes, chains and closures]()\*
- [How to npm](https://github.com/workshopper/how-to-npm#readme) (à réviser, beaucoup de fautes)
- [ES Next Generation](https://github.com/jesstelford/esnext-generation#readme)\*
- [Currying in JavaScript](https://github.com/kishorsharma/currying-workshopper#readme)
- [How to Markdown](https://github.com/workshopper/how-to-markdown#readme)
- [Regex Adventure](https://github.com/workshopper/regex-adventure#readme)\*

_\*pas facile car basé sur `adventure` et non `workshopper` ou `workshopper-adventure`, du coup pas d’infrastructure de traduction_

Jérémie et Christophe peuvent vous briefer sur le processus de contribution, et participer à la relecture.
