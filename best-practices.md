# Maximiser la qualité de ton aide

Lorsqu’on intervient auprès d’une personne pour l’aider, il est facile de nuire à la qualité de cette aide par des réflexes inappropriés. Voici quelques recommandations pour optimiser le résultat.

## Personnaliser la relation

Si tu n’a pas encore discuté avec cette personne, commence par personnaliser, du genre : _« salut, moi c’est … Et toi, tu t’appelles…? »_

## Se placer à niveau verticalement

- Ne prends pas sa chaise
- Ne reste pas debout à côté, même penché·e
- Prends une chaise à côté, ou agenouille-toi, pour être à niveau
- Ne reste pas le regard figé·e sur l’écran, multiplie les contacts visuels avec la personne en la regardant pendant que tu lui expliques quelque chose

## Sonder le bagage de la personne

Pour que tes explications soient adaptées, il est important de savoir à quel degré de débutant·e on a affaire. Jamais codé ? Jamais codé en JS ? Jamais fait de Node ? Déjà fait du Node mais pas sur le sujet de l’atelier…?

Tu auras parfois besoin d’expliquer les bases de la ligne de commande (CLI), ou ce qu’est une variable, un tableau, une boucle… Et c’est OK ! C’est cool ! On est là pour mettre aux gens le pied à l’étrier, et leur donner confiance !

Voir aussi plus bas « Rester constructifs ».

## Repasser par l’énoncé si besoin

Si tu n’es plus sûr·e de l’énoncé (ou que tu ne connais pas cet exo), ou simplement parce que tu veux t’assurer que la personne a bien compris les données et n’a pas lu en diagonale, pour amorcer votre réflexion, n’hésite pas à remontrer l’énoncé.

Sur la plupart des exos, ça se fait avec un simple `commande-de-l-atelier print`, par exemple `learnyounode print`. Si ça ne marche pas, lance la commande et resélectionne l’énoncé.

Il arrive aussi que des gens relisent **un autre énoncé** après avoir démarré un exo, ce qui change l’exo actif pour l’atelier, et fait que les sous-commandes `run` et `verify` n’envoient plus les bons environnements d’exécution. Re-sélectionner l’énoncé manuellement permet de remettre les choses d’aplomb.

## Vérifier les versions de Node et npm

Ça peut toujours servir si tu as un doute de compatibilité, etc.

```bash
node -v
npm -v
```

Viser des versions encore maintenues, donc pour Node au moins la dernière 6 (Maintenance LTS jusqu’en avril 2019, viser la 6.11 au minimum, en juin 2018 on est à la 6.14.3), en préférant la 8.x voire la 10.x (qui sera maintenue jusqu’en avril 2021), ne serait-ce que parce que chaque version est plus rapide que la précédente.

Avec nvm, c’est juste une histoire de `nvm install 10` par exemple.

Pour npm, préférer la 6.x. Si tu as une version antérieure, un `npm install --global npm` fera la mise à jour, qui marche dès Node 6.x.

## Ne pas s’approprier le clavier

Tu ne devrais que très rarement avoir un vrai besoin de prendre la main sur le clavier et/ou la souris / le trackpad de la personne. Autant que possible, guide ses manipulations et laisse-la faire, même si c’est plus lent. On n’est pas dans un concours de vitesse !

Si tu dois absolument prendre le clavier, par exemple pour attaquer une session de débogage potentiellement velue (voir ci-dessous), demande toujours la permission avant (« tu permets que j’utilise ton clavier ? »), et attends une réponse claire pour y aller. Si besoin, déplace le laptop face à toi pour ne gêner ni l’espace personnel de l’autre ni sa visibilité de l’écran.

## Exprimer son processus de décision / débgogage

Si la connaissance technique est précieuse, l’acquisition d’un processus de débogage efficace est encore plus utile pour nos participant·e·s. C’est un des savoir-faire les plus précieux que tu puisses leur transmettre.

Du coup, que tu aies ou non la main sur le clavier / la souris, vocalise systématiquement tes réflexions, questionnements, raisons pour tes actions et manip’s lors d’un débogage. Il faut permettre aux gens que tu aides d’entrer dans ta tête, en quelque sorte, de bien voir les questions que tu te poses, les pistes que tu explores et élimines, tout l’arbre de décision en fait. Fais-les participer autant que possible, explique tout en détail.

## Interroger, faire réfléchir

Même quand tu as identifié le problème, ne fournis pas, autant que possible, la solution toute faite, sauf si c’est une faute de frappe ultra-basique (et même là, explique pourquoi c’est une erreur de syntaxe, le cas échéant).

Au contraire, essaie de faire retrouver le problème à la personne en la questionnant, en orientant sa réflexion, façon [maïeutique socratienne](http://bit.ly/2t7L0p1) (plus d’infos sur [son utilisation en pédagogie](http://www.pedagogie-active.fr/lecture_suivie/2-50.html)).

C’est un vrai plaisir de voir le regard des gens s’illuminer quand ils comprennent « par eux-mêmes » le souci et comment y remédier, et ça ancre beaucoup mieux les savoirs. Ça les aide aussi énormément à prendre confiance.

## Rester constructifs et positifs

Proscris absolument toute remarque négative, tout langage corporel négatif. Pas de soupirs, de roulements d’yeux / d’yeux au ciel, de moue énervée, pas de « tout le monde sait ça »…

**Rien n’est évident quand on débute**. Et ne confonds pas **rapide** et **simple**, ou **simple** et **facile**. Donc attention aux tournures du genre de _« tout simplement »_, _« c’est tout bête »_, _« évidemment »_, etc.

On peut bien sûr chercher à démystifier l’apparente complexité, mais des tournures comme _« tu vas voir, c’est nettement moins compliqué que tu ne le penses »_, ou _« ça peut surprendre au début, mais tu vas vite comprendre… »_ sont préférables. De même, _« pas très compliqué »_ ou _« pas très avancé »_ sont mieux que _« simple »_ et _« facile »_.

Et n’oublie pas d’encourager les gens et de les féliciter quand ils arrivent au bout de leur problème. Ça ne coûte rien et ça aide énormément.
