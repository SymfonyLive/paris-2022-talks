# [Symfony Live - Paris 2022](https://live.symfony.com/2022-paris/) talks

- All talks are in **french**.
- You can send feedback and love to speakers on their twitter account

## Keynote

~~Slides~~  
~~Video~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## Comment valider dynamiquement de la donnée

<dl>
  <dt>Description</dt>
  <dd>Il arrive que sur certains endpoints d'une API, le graph d'objet attendu par l'application dépende de la donnée envoyée. Par exemple, si l'utilisateur envoie `{type:foobar, data: XXX}` le format de `XXX` dépendra du type `foobar`.
Comment peut-on valider XXX ? À travers cette présentation, nous allons voir comment valider dynamiquement des données, en ré-utilisant au maximum les fonctionnalités disponibles dans Symfony.</dd>
</dl>

[Slides](https://speakerdeck.com/marionleherisson/valider-dynamiquement-de-la-donnee-avec-symfony)  
~~Video~~  
[Example](https://github.com/MarionLeHerisson/validation)

By [Marion Hurteau](https://connect.symfony.com/profile/marionleherisson)  
![github](icon/github.png) [@MarionLeHerisson](https://github.com/MarionLeHerisson)  
![twitter](icon/twitter.png) [@MarionHerisson](https://twitter.com/MarionHerisson)

---

## Du DDD avec API Platform

<dl>
  <dt>Description</dt>
  <dd>Chez Les-Tilleuls.coop, on aime bien se servir d’API Platform. Principalement parce qu’il répond à beaucoup de questions en matière de conception d’API web, mais également pour sa simplicité d’usage.

Cette simplicité a cependant un coût qui se fait généralement sentir lorsqu’on a besoin de sortir du cadre.

Le fait est que chez Les-Tilleuls.coop on aime aussi beaucoup travailler sur des applications à fortes contraintes métier, et encore plus sortir du cadre. Et quand ça s’y prête, on le fait en s’appuyant sur les principes du DDD.

Architecture hexagonale orientée message, logique métier découplée de l’infrastructure, … Tant de préceptes qui deviennent des prérequis lorsqu’il s’agit de mettre le métier au centre de nos applications tout en assurant la bonne maintenabilité de celles-ci.

Mais est-ce que tout cela n’irait pas à l’encontre de ce que propose un framework orienté RAD tel qu’API Platform ?

Peut-on réellement découpler notre logique métier de ce framework via les techniques liées au DDD sans pour autant lui faire perdre de son intêret ?

La réponse est oui, et durant ce talk nous allons vous montrer comment.</dd>
</dl>

[Slides](http://slides.com/mathiasarlaud/sflive-apip-ddd)  
~~Video~~  
[Example](https://github.com/mtarld/apip-ddd)

By [Robin Chalas](https://connect.symfony.com/profile/chalas_r)  
![github](icon/github.png) [@chalasr](https://github.com/chalasr)  
![twitter](icon/twitter.png) [@chalas_r](https://twitter.com/chalas_r)

And [Mathias Arlaud](https://connect.symfony.com/profile/mtarld)  
![github](icon/github.png) [@mtarld](https://github.com/mtarld)  
![twitter](icon/twitter.png) [@matarld](https://twitter.com/matarld)

---

## Doctrine, objet typé, et colonne JSON

<dl>
  <dt>Description</dt>
  <dd>Les bases de données savent gérer des colonnes JSON depuis des années déjà, et ces colonnes permettent d'accélérer le développement en simplifiant le code, les migrations, et la maintenance.

Cependant, manipuler un array PHP n'est pas pratique : les analyseurs statiques de code sont perdus (a moins de spécifier énormément de chose via de la PHPDoc), PHP ne peut pas controller le type au runtime, mais surtout la lisibilité du code est réduite. En effet, à moins de lire tout le code, il est difficile de savoir quelles sont les clés obligatoires, lesquelles sont optionnelles, et enfin comment est typée la donnée.

À travers cette présentation, nous allons voir comment étendre Doctrine pour avoir le meilleur des deux mondes : des colonnes en JSON, et des objets PHP fortement typés.</dd>
</dl>

[Slides](https://speakerdeck.com/lyrixx/doctrine-objet-type-et-colonne-json)  
~~Video~~

By [Grégoire Pineau](https://connect.symfony.com/profile/lyrixx)  
![github](icon/github.png) [@lyrixx](https://github.com/lyrixx)  
![twitter](icon/twitter.png) [@lyrixx](https://twitter.com/lyrixx)

---

## Connaissez-vous vraiment JWT ?

<dl>
  <dt>Description</dt>
  <dd>Depuis quelques années déjà, beaucoup d'entre nous avons vu passer ou utiliser des jetons un peu spéciaux : les JSON Web Tokens ou JWT. Ce standard de jeton est très pratique pour faire transiter de l'information de manière fiable. Ces jetons sont souvent utilisés pour assurer l'authentication auprès de web services, de micro-services ou de SSO dans le cadre d'OpenID Connect. De plus, on voit beaucoup de JWS (des jetons signés), mais ce n'est pas la seule implémentation qui existe. En réalité, la spécification JWT est nettement plus vaste que ce que l'on peut penser. Je vous propose de découvrir des aspects de JWT moins connus que l'utilisation classique.</dd>
</dl>

[Slides](https://slides.com/kpn13/connaissez-vous-vraiment-jwt-sf-live-2022)  
~~Video~~  
[Examples](https://github.com/kpn13/jwt-attack-examples)

By [Karim Pinchon](https://connect.symfony.com/profile/kpinchon)  
![github](icon/github.png) [@kpn13](https://github.com/kpn13)  
![twitter](icon/twitter.png) [@kpn13](https://twitter.com/kpn13)

---

## Des composants Symfony méconnus qui valent le détour

<dl>
  <dt>Description</dt>
  <dd>Plus qu'un framework, Symfony est un écosystème. Les composants Symfony, véritables bibliothèques indépendantes utilisables dans n'importe quel projet PHP, proposent de régler des problématiques que nous sommes susceptibles de rencontrer quotidiennement en tant que développeurs PHP.

Manipulation de chaînes de caractères avec Unicode, concurrence, internationalisation ou encore rate-limiting sont, entre autres, tous autant de défis que les composants Symfony permettent de régler avec des solutions clé en main. Et tout ça, en profitant de la robustesse d'un code open-source et de la fameuse promesse de rétrocompatibilité.

Bien que certains composants soient connus et reconnus, il en existe au moins tout autant qui pourraient vous sauver de longues heures de développement si vous connaissiez leur existence. C'est ce que nous allons explorer ensemble.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Alexandre Daubois](https://connect.symfony.com/profile/alexandre-daubois)  
![github](icon/github.png) [@alexandre-daubois](https://github.com/alexandre-daubois)  
![twitter](icon/twitter.png) [@alexdaubois](https://twitter.com/alexdaubois)

---

## À la Recherche du Temps Perdu

<dl>
  <dt>Description</dt>
  <dd>Lorsque l’on évoque la performance de nos applications, le temps demeure un élément fondamental sur lequel nous nous appuyons. Nous utilisons volontiers ses unités de mesure pour évaluer cette performance, mais que représente-t-il au fond ?

Valeur absolue ou relative ? Corrélation ou causalité ? Que nous dit réellement le temps sur nos applications, sur notre environnement ?

Au-travers de cette présentation, je tenterai de mettre cette notion en perspective, notamment au regard de la physique, mais également de son aspect symbolique, afin de mieux comprendre les enjeux liés à la performance, et ainsi (re)devenir Maître du Temps.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Jérôme Vieilledent](https://connect.symfony.com/profile/lolautruche)  
![github](icon/github.png) [@lolautruche](https://github.com/lolautruche)  
![twitter](icon/twitter.png) [@jvieilledent](https://twitter.com/jvieilledent)

---

## Vous avez dit Symfony 6.1?

<dl>
  <dt>Description</dt>
  <dd>Alors que Symfony 5.4 et 6.0 viennent à peine de sortir, la version 6.1 est déjà quasi bouclée, en vue d'une publication à la fin du mois de mai.

Que diriez-vous de m'accompagner pour une rétrospective des 12 derniers mois de contributions qui viennent de s'écouler ? Nous ferons ensemble une revue des principaux changements apportés dans l'écosystème sur cette période, sans oublier de vous présenter en avant-première les nouveautés de la prochaine version.

Vous découvrirez, je l'espère des outils dont vous ignoriez l'existence et qui pourtant pourraient vous simplifier la vie.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## L'architecture hexagonale, fini la théorie, on passe à la pratique !

<dl>
  <dt>Description</dt>
  <dd>À l'architecture hexagonale ! Cela fait des décennies que ça existe et des années que c'est sur le devant de la scène, pourtant, nous avons encore bien du mal à la mettre en place dans nos projets.

Dans ce talk, nous allons éviter la théorie, et aller directement à la pratique avec notre framework PHP préféré : Symfony.
Nous verrons comment intégrer une architecture hexagonale dans Symfony, les différentes manières d'accéder à notre hexagone (UseCase, CQRS), de persister nos entités (ORM, Memento) et enfin quelle stratégie de test adoptée avec une architecture hexagonal (Diamond testing). Tout ça avec plein d'exemples concrets !

Sacré programme, j'espère que vous êtes bien accrochés ! Et n'oubliez pas de réviser la théorie avant de venir, car dans ce talk, on passe à la pratique !</dd>
</dl>

~~Slides~~  
~~Video~~

By [Etienne Lebarillier](https://connect.symfony.com/profile/etienneleba)  
![github](icon/github.png) [@etienneleba](https://github.com/etienneleba)  
![twitter](icon/twitter.png) [@EtienneLeba](https://twitter.com/EtienneLeba)

---

## Code asynchrone dans une application Symfony synchrone

<dl>
  <dt>Description</dt>
  <dd>Le concept de Promise et les IO non-bloquants sont fondamentaux en Javascript, ils ont été implémentés en PHP par des frameworks, dont AMPHP. Pas besoin de réimplémenter un serveur HTTP pour s'en servir, le code asynchrone peut être utilisé dans un contexte PHP synchrone. Ainsi, le site et l'API GraphQL de Télé-Loisirs ont été développés en utilisant la programmation asynchrone au sein d'une application Symfony. Les pages sont structurées en composants résolus simultanément. En plus de permettre l'amélioration des temps de réponse, l'asynchrone permet une organisation du code par domaine métier (DDD), facilitant la maintenance et la collaboration entre les développeurs frontend et backend.</dd>
</dl>

[Slides](https://jerome.tamarelle.net/slides/2022-04-08-PHP-Async-SymfonyLiveParis2022.pdf)  
~~Video~~  
[Examples](https://github.com/GromNaN/async-page-builder-demo)

By [Jérôme Tamarelle](https://connect.symfony.com/profile/gromnan)  
![github](icon/github.png) [@GromNaN](https://github.com/GromNaN)  
![twitter](icon/twitter.png) [@GromNaN](https://twitter.com/GromNaN)

---

## Gestion des permissions dans Symfony

<dl>
  <dt>Description</dt>
  <dd>La sécurité des applications est plus que jamais un élément crucial, si bien que Symfony a beaucoup évolué au fil des versions pour offrir des outils permettant de sécuriser nos sites et applications de façon souple et efficace.
Où en est-on en 2022 avec la sécurité dans Symfony, quelles sont les nouveautés dans les dernières versions du framework ? Une fois l'authentification passée, quels sont les différents moyens de gérer les autorisations et les permissions ?

Quelles sont les outils offerts par l'outil qui nous permettent d'adapter nos besoins plus ou moins complexes de sécurisation, d'accès aux ressources et données ?

Après une revue de ce qu'il est possible de faire nativement avec Symfony, nous verrons comment étendre le modèle pour définir des permissions administrables et complètement adaptables à des besoins métiers plus complexes, que ce soit dans une application classique Symfony ou une API créée avec API Platform.

Enfin, nous verrons un cas d'usage qui dépasse le cadre que l'on donne habituellement à la définition des rôles pour déterminer dynamiquement les personnes habilitées à recevoir certaines notifications dans un système d'alertes internes.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Marion Agé](https://connect.symfony.com/profile/marionage)  
![github](icon/github.png) [@K-mos](https://github.com/K-mos)  
![twitter](icon/twitter.png) [@marion_age](https://twitter.com/marion_age)

---

## Développer une application web décentralisée avec Symfony et API Platform

<dl>
  <dt>Description</dt>
  <dd>Non, cette présentation ne parle pas du web3.

Et pour cause ! Il existe une manière plus ouverte, plus interopérable, plus simple, plus écologique et même plus… décentralisée (!!) de créer des applications web décentralisées.

Les standards du web, et en particulier ceux de dernière génération (RDF, JSON-LD, N3, OpenID Connect) proposent un cadre pour réaliser de telles apps.

C’est sur cette base technique que sont établis deux nouveaux protocoles qui pourraient révolutionner le web : Solid et ActivityPub.

Le projet Solid, pour Social Linked Data, développé par Sir Tim Berners-Lee - le créateur du Web himself - redonne aux utilisateurs le contrôle de leurs données. Il leur permet de les stocker où ils le souhaitent, et de choisir finement quelle application peut accéder à quoi.

ActivityPub est quant à lui un protocole qui permet de créer des réseaux sociaux décentralisés et fédérés. C’est le protocole utilisé par Mastodon, PeerTube ou encore Mobilizon, dont les instances sont regroupées au sein du réseau que l’on nomme le Fediverse.

Encore mieux, pas besoin de smart contracts ni même de blockchain pour créer des applications web décentralisées utilisant ces technologies, un bon vieux script PHP et un Raspberry Pi suffisent. Ceci dit, utiliser Symfony et API Platform peut grandement nous faciliter la tâche, c’est ce que nous découvrirons ensemble !</dd>
</dl>

~~Slides~~  
~~Video~~  
[Solid Client PHP](https://github.com/dunglas/solid-client-php)

By [Kévin Dunglas](https://connect.symfony.com/profile/)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

---

## Un SSO avec Keycloak et Symfony

<dl>
  <dt>Description</dt>
  <dd>Les SSO (single sign-on) sont de plus en plus utilisés dans les systèmes d'information. Jusque dans les entreprises, ils présentent une solution pratique pour connecter différents logiciels internes.

Keycloak est un IAM (Identity and Access Management) populaire qui offre de nombreuses possibilités en tant que SSO (connexion via différents providers comme Facebook, 2FA, stratégie de renouvellement de mot de passe etc). Nous verrons dans ce talk quelques unes de ces fonctionnalités et comment il s'intègre avec une application Symfony.</dd>
</dl>

[Slides](https://docs.google.com/presentation/d/e/2PACX-1vRDMb0L717lkeEW8Q44EkX5UnvRtEu9xHgLSOV1FBoN6iMjfV4KrPaYlBDMhjgptIxJuxPG3aUHGY5d/pub)  
~~Video~~  
[Example](https://github.com/l-vo/sf_keycloak_example/tree/sflive)

By [Laurent Voullemier](https://connect.symfony.com/profile/lvo)  
![github](icon/github.png) [@l-vo](https://github.com/l-vo)  
![twitter](icon/twitter.png) [@lvodev](https://twitter.com/lvodev)

---

## En Première Ligne : Symfony et l'open source au service de la société

<dl>
  <dt>Description</dt>
  <dd>Le jeudi 12 mars 2020, Emmanuel Macron annonce la fermeture des écoles à partir du lundi suivant.

En 3 jours s'est alors organisé une course logistique nationale pour assurer aux personnels de première ligne (santé mais aussi supermarchés, collecte des déchets, énergie, ...) la capacité de continuer à travailler alors que leurs enfants seraient à la maison.

C'est dans ce contexte que des amis et moi avons créé enpremiereligne.fr, une plateforme d'entraide locale, gratuite et open-source basée sur Symfony. Cette expérience nous a montré la puissance de l'open-source et de Symfony pour aider la société.

Dans ce talk, nous discuterons d'en quoi Symfony a été décisif dans ce projet et comment vous aussi, vous pouvez mettre à profit vos compétences technologiques pour améliorer le monde autour de vous.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Titouan Galopin](https://connect.symfony.com/profile/tgalopin)  
![github](icon/github.png) [@tgalopin](https://github.com/tgalopin)  
![twitter](icon/twitter.png) [@titouangalopin](https://twitter.com/titouangalopin)
