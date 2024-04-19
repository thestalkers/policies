Lignes directrices pour les demandes légales de données utilisateur - Documentation GitHub

[Skip to main content](#main-content)

[Accueil](/fr)

[Site policy](/fr/site-policy)

* [Politique du site](/fr/site-policy)/
* [Autres politiques du site](/fr/site-policy/other-site-policies)/
* [Lignes directrices pour les demandes légales de données utilisateur](/fr/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)

Lignes directrices pour les demandes légales de données utilisateur
==========

Dans cet article
----------

* [À propos de ces lignes directrices](#about-these-guidelines)
* [Terminologie GitHub](#github-terminology)
* [Données utilisateur sur GitHub.com](#user-data-on-githubcom)
* [Nous aviserons tous les titulaires de compte concernés](#we-will-notify-any-affected-account-owners)
* [Divulgation d'informations non publiques](#divulgation-dinformations-non-publiques)
* [Remboursement des frais](#cost-reimbursement)
* [Conservation des données](#data-preservation)
* [Soumettre des demandes](#submitting-requests)
* [Demandes des forces de l'ordre étrangères](#demandes-des-forces-de-lordre-étrangères)
* [Questions](#questions)

Êtes-vous un agent des forces de l'ordre menant une enquête pouvant impliquer du contenu utilisateur hébergé sur GitHub ?
Ou peut-être êtes-vous une personne soucieuse de sa vie privée qui aimerait savoir quelles informations nous partageons avec les forces de l'ordre et dans quelles circonstances.
Dans tous les cas, vous êtes sur la bonne page.

Dans ces directives, nous fournissons un aperçu de ce qu'est GitHub, des types de données dont nous disposons et des conditions dans lesquelles nous divulguerons les informations privées des utilisateurs.
Avant d'entrer dans les détails, cependant, voici quelques détails importants que vous voudrez peut-être connaître :

* Nous [**aviserons les utilisateurs concernés**](#we-will-notify-any-affected-account-owners) de toute demande d'informations sur leur compte, à moins qu'il ne soit interdit de le faire par la loi ou une ordonnance du tribunal.
* Nous ne divulguerons pas **les données de suivi de localisation**, comme les journaux d'adresses IP, sans une [ordonnance judiciaire ou un mandat de perquisition valable](#with-a-court-order-or-a-search-warrant).
* Nous ne divulguerons aucun **contenu utilisateur privé**, y compris le contenu des dépôts privés, sans un [mandat de perquisition](#only-with-a-search-warrant).

[À propos de ces lignes directrices](#about-these-guidelines)
----------

Nos utilisateurs nous font confiance pour leurs projets logiciels et leur code, qui font souvent partie de leurs actifs professionnels ou personnels les plus précieux.
Maintenir cette confiance est essentiel pour nous, ce qui signifie que les données des utilisateurs sont sûres, sécurisées et privées.

Alors que l'écrasante majorité de nos utilisateurs utilisent les services de GitHub pour créer de nouvelles entreprises, développer de nouvelles technologies et pour l'amélioration générale de l'humanité, nous reconnaissons qu'avec des millions d'utilisateurs répartis dans le monde entier, il y a forcément quelques brebis galeuses dans le peloton.
Dans ces cas, nous voulons aider les forces de l'ordre à servir leur intérêt légitime à protéger le public.

En fournissant des directives aux forces de l'ordre, nous espérons trouver un équilibre entre les intérêts souvent opposés de la vie privée des utilisateurs et de la justice.
Nous espérons que ces directives aideront à définir les attentes des deux côtés, ainsi qu'à ajouter de la transparence aux processus internes de GitHub.
Nos utilisateurs doivent savoir que nous apprécions leurs informations privées et que nous faisons tout notre possible pour les protéger.
Au minimum, cela signifie ne divulguer des données à des tiers que lorsque les exigences légales appropriées ont été satisfaites.
De la même manière, nous espérons également éduquer les professionnels de l'application de la loi sur les systèmes de GitHub afin qu'ils puissent adapter plus efficacement leurs demandes de données et cibler uniquement les informations nécessaires pour mener leur enquête.

[Terminologie GitHub](#github-terminology)
----------

Avant de nous demander de divulguer des données, il peut être utile de comprendre comment notre système est mis en œuvre.
GitHub héberge des millions de référentiels de données utilisant le [système de gestion de versions Git](https://git-scm.com/video/what-is-version-control).
Les référentiels sur GitHub, qui peuvent être publics ou privés, sont le plus souvent utilisés pour les projets de développement de logiciels, mais sont également souvent utilisés pour travailler sur des contenus de toutes sortes.

* [**Utilisateurs**](/fr/get-started/learning-about-github/github-glossary#user) : les utilisateurs sont représentés dans notre système en tant que comptes GitHub personnels.
  Chaque utilisateur a un profil personnel et peut posséder plusieurs référentiels.
  Les utilisateurs peuvent créer ou être invités à rejoindre des organisations ou à collaborer sur le référentiel d'un autre utilisateur.

* [**Collaborateurs**](/fr/get-started/learning-about-github/github-glossary#collaborator) : un collaborateur est un utilisateur ayant un accès en lecture et écriture à un référentiel qui a été invité à contribuer par le propriétaire du référentiel.

* [**Organisations**](/fr/get-started/learning-about-github/github-glossary#organization) : les organisations sont un groupe de deux utilisateurs ou plus qui reflètent généralement des organisations du monde réel, comme des entreprises ou des projets.
  Ils sont administrés par les utilisateurs et peuvent contenir à la fois des référentiels et des équipes d'utilisateurs.

* [**Référentiel**](/fr/get-started/learning-about-github/github-glossary#repository) : un référentiel est l'un des éléments GitHub les plus basiques.
  Ils peuvent être plus faciles à imaginer en tant que dossier de projet.
  Un référentiel contient tous les fichiers du projet (y compris la documentation) et stocke l'historique des révisions de chaque fichier.
  Les référentiels peuvent avoir plusieurs collaborateurs et, à la discrétion de ses administrateurs, peuvent être accessibles au public ou non.

* [**Pages**](/fr/pages/getting-started-with-github-pages/about-github-pages) : les GitHub Pages sont des pages Web publiques hébergées gratuitement par GitHub que les utilisateurs peuvent facilement publier grâce au code stocké dans leurs référentiels.
  Si un utilisateur ou une organisation a une Page GitHub, elle se trouve généralement à une URL telle que `https://username.github.io` ou la page Web peut être mappée à son propre nom de domaine personnalisé.

* [**Gists**](/fr/get-started/writing-on-github/editing-and-sharing-content-with-gists/creating-gists) : les gists sont des extraits de code source ou d'autres textes que les utilisateurs peuvent utiliser pour stocker des idées ou partager avec des amis.
  Comme les référentiels GitHub classiques, les Gists sont créés avec Git, ils sont donc automatiquement versionnés, forkables et téléchargeables.
  Les Gists peuvent être publics ou secrets (accessibles uniquement via une URL connue). Les Gists publics ne peuvent pas être convertis en Gists secrets.

[Données utilisateur sur GitHub.com](#user-data-on-githubcom)
----------

Voici une liste non exhaustive des types de données que nous conservons sur les utilisateurs et les projets sur GitHub.

* []()**Données de compte public** : il existe une variété d'informations accessibles au public sur GitHub concernant les utilisateurs et leurs référentiels.
  Les profils utilisateur sont disponibles en utilisant une URL, par exemple `https://github.com/username`.
  Les profils d'utilisateurs affichent des informations sur le moment où l'utilisateur a créé son compte ainsi que son activité publique sur GitHub.com et ses interactions sociales.
  Les profils d'utilisateurs publics peuvent également inclure des informations supplémentaires qu'un utilisateur peut avoir choisi de partager publiquement.
  Tous les profils publics d'utilisateurs affichent :

  * Nom d'utilisateur

  * Les référentiels que l'utilisateur a marqués d'une étoile

  * Les autres utilisateurs GitHub que l'utilisateur suit

  * Les utilisateurs qui les suivent

    Facultativement, un utilisateur peut également choisir de partager publiquement les informations suivantes :

  * Leur vrai nom

  * Un avatar

  * Une société affiliée

  * Leur emplacement

  * Une adresse e-mail publique

  * Leur page web personnelle

  * Les organisations auxquelles l'utilisateur est membre (*selon les préférences de l'organisation ou de l'utilisateur*)

* []()**Données de compte privé** : GitHub collecte et conserve également certaines informations privées sur les utilisateurs, comme indiqué dans notre [Politique de Confidentialité](/fr/site-policy/privacy-policies/github-privacy-statement).
  Cela peut inclure :

  * Adresses e-mail privées

  * Détails de paiement

  * Journaux d'accès de sécurité

  * Données sur les interactions avec les référentiels privés

    Pour avoir une idée du type d'informations privées sur le compte que GitHub collecte, vous pouvez visiter votre [tableau de bord personnel](https://github.com/dashboard) et parcourir les sections de la barre de menus de gauche.

* []()\*\* Données de compte d'organisation\*\* : les informations sur les organisations, leurs utilisateurs administratifs et leurs référentiels sont accessibles au public sur GitHub.
  Les profils d'organisation sont disponibles en utilisant une URL, par exemple `https://github.com/organization`.
  Les profils d'organisations publiques peuvent également inclure des informations supplémentaires que les propriétaires ont choisi de partager publiquement.
  Tous les profils publics d'organisation affichent :

  * Le nom de l’organisation

  * Les référentiels que les propriétaires ont mis en vedette

  * Tous les utilisateurs de GitHub qui sont propriétaires de l'organisation

    Facultativement, les utilisateurs administratifs peuvent également choisir de partager publiquement les informations suivantes :

  * Un avatar

  * Une société affiliée

  * Leur emplacement

  * Membres directs et équipes

  * Collaborateurs

* []()**Données de référentiel public** : GitHub héberge des millions de projets logiciels publics, open source.
  Vous pouvez parcourir presque tous les référentiels publics (par exemple, [GitHub Docs](https://github.com/github/docs)) pour avoir une idée des informations que GitHub collecte et conserve sur les référentiels.
  Cela peut inclure :

  * Le code lui-même
  * Versions précédentes du code
  * Versions stables du projet
  * Informations sur les collaborateurs, les contributeurs et les membres du référentiel
  * Journaux des opérations Git telles que les commits, les branchements, le push, le pull, le forking et le clonage
  * Conversations liées aux opérations Git telles que les commentaires sur les pull requests ou les commits
  * Documentation du projet telle que les pages Problèmes et Wiki
  * Statistiques et graphiques montrant les contributions au projet et le réseau de contributeurs

* []()**Données de référentiel privé** : GitHub collecte et conserve le même type de données pour les dépôts privés que celles visibles pour les dépôts publics, sauf que seuls les utilisateurs spécifiquement invités peuvent accéder aux Données de référentiel privé.

* []()**Autres données** : en outre, GitHub collecte des données d'analyse telles que les visites de pages et les informations fournies occasionnellement par nos utilisateurs (comme les communications avec notre équipe de support, les informations d'enquête et/ou les inscriptions au site).

[Nous aviserons tous les titulaires de compte concernés](#we-will-notify-any-affected-account-owners)
----------

Notre politique est d'informer les utilisateurs de toute demande en attente concernant leurs comptes ou référentiels, à moins que la loi ou une ordonnance du tribunal ne nous interdise de le faire. Avant de divulguer des informations sur l'utilisateur, nous ferons un effort raisonnable pour informer les propriétaires de compte concernés en envoyant un message à leur adresse e-mail vérifiée en leur fournissant une copie de l'assignation à comparaître, de l'ordonnance du tribunal ou du mandat afin qu'ils puissent avoir la possibilité de contester le procédure judiciaire s'ils le souhaitent. Dans des circonstances d'urgence (rares), nous pouvons retarder la notification si nous déterminons qu'un délai est nécessaire pour éviter la mort ou un préjudice grave ou en raison d'une enquête en cours.

[Divulgation d'informations non publiques](#divulgation-dinformations-non-publiques)
----------

Notre politique est de divulguer les informations non publiques des utilisateurs dans le cadre d'une enquête civile ou pénale uniquement avec le consentement de l'utilisateur ou à la réception d'une citation à comparaître valide, d'une demande d'enquête civile, d'une ordonnance du tribunal, d'un mandat de perquisition ou de toute autre procédure judiciaire valide similaire. Dans certaines circonstances urgentes (voir ci-dessous), nous pouvons également partager des informations limitées mais correspondant uniquement à la nature des circonstances, et nécessiterions une procédure judiciaire pour tout ce qui va au-delà.
GitHub se réserve le droit de s'opposer à toute demande d'informations non publiques.
Lorsque GitHub accepte de produire des informations non publiques en réponse à une demande légale, nous effectuerons une recherche raisonnable des informations demandées.
Voici les types d'informations que nous accepterons de produire, selon le type de procédure judiciaire qui nous est signifiée :

* []()**Avec le consentement de l'utilisateur** : GitHub fournira des informations privées sur le compte, si demandé, directement à l'utilisateur (ou à un propriétaire, dans le cas d'un compte d'organisation), ou à un tiers désigné avec le consentement écrit de l'utilisateur une fois que GitHub est convaincu que l'utilisateur a vérifié son identité.

* []()**Avec une citation à comparaître** : si nous recevons une citation à comparaître valable, une demande d'enquête civile ou un processus légal similaire émis dans le cadre d'une enquête criminelle ou civile officielle, nous pouvons fournir certaines informations sur le compte non publiques, qui peuvent inclure :

  * Noms associés au compte
  * Adresse(s) e-mail(s) associée(s) au compte
  * Les informations de facturation
  * Date d'inscription et date de résiliation
  * Adresse IP, date et heure au moment de l'enregistrement du compte
  * Adresse(s) IP utilisée(s) pour accéder au compte à un moment précis ou lors d'un événement pertinent pour l'enquête

Dans le cas de comptes d'organisation, nous pouvons fournir les noms et adresse(s) e-mail(s) des titulaires du compte ainsi que la date et l'adresse IP au moment de la création du compte d'organisation. Nous ne produirons pas d'informations sur d'autres membres ou contributeurs, le cas échéant, au compte de l'organisation ni aucune information supplémentaire concernant les propriétaires de compte identifiés sans une demande de suivi pour ces utilisateurs spécifiques.

Veuillez noter que les informations disponibles varient d'un cas à l'autre. Certaines des informations sont facultatives pour les utilisateurs. Dans d'autres cas, il se peut que nous n'ayons pas collecté ou conservé les informations.

* []()**Avec une ordonnance du tribunal *ou* un mandat de perquisition** : nous ne divulguerons pas les journaux d'accès aux comptes à moins d'y être contraints par (i) une ordonnance du tribunal rendue en vertu de l'article 18 U.S.C. Section 2703(d), sur présentation de faits précis et articulés montrant qu'il existe des motifs raisonnables de croire que les informations recherchées sont pertinentes et importantes pour une enquête criminelle en cours ; ou (ii) un mandat de perquisition émis selon les procédures décrites dans les Règles fédérales de procédure pénale ou des procédures de mandat d'État équivalentes, sur présentation d'une cause probable.
  Outre les informations de compte non publiques répertoriées ci-dessus, nous pouvons fournir des journaux d'accès au compte en réponse à une ordonnance du tribunal ou à un mandat de perquisition, qui peuvent inclure :

  * Tous les journaux qui révéleraient les mouvements d'un utilisateur sur une période donnée
  * Paramètres du compte ou du référentiel privé (par exemple, quels utilisateurs disposent de certaines autorisations, etc.)
  * Données analytiques spécifiques à l'utilisateur ou à l'IP telles que l'historique de navigation
  * Journaux d'accès de sécurité autres que la création de compte ou pour une heure et une date spécifiques

* []()**Uniquement avec un mandat de perquisition** : nous ne divulguerons pas le contenu privé d'un compte à moins d'y être contraints par un mandat de perquisition délivré conformément aux procédures décrites dans les Règles fédérales de Procédure pénale des États-Unis ou à des procédures équivalentes d'autres États sur présentation d'une cause probable.
  En plus des informations de compte non publiques et des journaux d'accès au compte mentionnés ci-dessus, nous fournirons également le contenu du compte privé en réponse à un mandat de perquisition, qui peut inclure :

  * Contenu des Gists secrets
  * Code source ou autre contenu dans des référentiels privés
  * Enregistrements de contribution et de collaboration pour les référentiels privés
  * Communications ou documentation (telles que les problèmes ou les wikis) dans des référentiels privés
  * Toutes les clés de sécurité utilisées pour l'authentification ou le chiffrement

* []()**Dans des circonstances urgentes** : si nous recevons une demande d'informations dans certaines circonstances exceptionnelles (lorsque nous pensons que la divulgation est nécessaire pour prévenir une urgence impliquant un danger de mort ou de blessure physique grave pour une personne), nous pouvons divulguer des informations limitées que nous jugeons nécessaires pour pouvoir répondre à l'urgence par la mise en œuvre des principes de protection des informations personnelles. Pour toute information au-delà de cela, nous aurions besoin d'une citation à comparaître, d'un mandat de perquisition ou d'une ordonnance du tribunal, comme décrit ci-dessus. Par exemple, nous ne divulguerons pas le contenu de dépôts privés sans mandat de perquisition. Avant de divulguer des informations, nous confirmons que la demande provient d'un organisme chargé de l'application de la loi, une autorité a envoyé un avis officiel résumant l'urgence et comment les informations demandées aideront à faire face à l'urgence.

[Remboursement des frais](#cost-reimbursement)
----------

En vertu des lois étatiques et fédérales, GitHub peut demander le remboursement des coûts associés au respect d'une demande légale valide, telle qu'une assignation à comparaître, une ordonnance d'un tribunal ou un mandat de perquisition. Nous ne facturons que le recouvrement de certains coûts, et ces remboursements ne couvrent qu'une partie des coûts que nous engageons réellement pour nous conformer aux ordonnances légales.

Bien que nous ne facturions pas dans les situations d'urgence ou dans d'autres circonstances urgentes, nous demandons le remboursement de toutes les autres demandes légales conformément au calendrier suivant, sauf disposition contraire de la loi :

* Recherche initiale d'un maximum de 25 identifiants : gratuit
* Production d'informations / de données sur les abonnés pour un maximum de 5 comptes : gratuit
* Production d'informations / de données sur les abonnés pour plus de 5 comptes : 20 USD par compte
* Recherches secondaires : 10 USD par recherche

[Conservation des données](#data-preservation)
----------

Nous prendrons des mesures pour conserver les dossiers de compte jusqu'à 90 jours sur demande formelle des forces de l'ordre américaines dans le cadre d'enquêtes criminelles officielles et dans l'attente de l'émission d'une ordonnance du tribunal ou d'une autre procédure.

[Soumettre des demandes](#submitting-requests)
----------

Veuillez adresser vos demandes à :

```
GitHub, Inc.
c/o Corporation Service Company
2710 Gateway Oaks Drive, Suite 150N
Sacramento, CA 95833-3505

```

Des copies carbone peuvent être envoyées par courrier électronique à [legal-support@github.com](mailto:legal-support@github.com).

Veuillez formuler vos demandes aussi spécifiques et précises que possible, en incluant les informations suivantes :

* Informations complètes sur l'autorité émettrice de la demande d'informations
* Le nom et le badge/ID de l'agent responsable
* Une adresse e-mail et un numéro de téléphone officiels
* Les noms d'utilisateur, d'organisation et de référentiel d'intérêt
* Les URL de toutes les pages, points essentiels ou fichiers d'intérêt
* La description des types d'enregistrements dont vous avez besoin

Veuillez prévoir au moins deux semaines pour que nous puissions étudier votre demande.

### [Avis relatif au projet de loi 1242 de l'Assemblée de l'État de Californie](#avis-relatif-au-projet-de-loi1242-de-lassemblée-de-létat-de-californie) ###

En soumettant une procédure légale à GitHub, vous attestez que la procédure légale n'est pas liée à la violation d'une loi qui crée une responsabilité pour les comportements liés à l'avortement qui sont légaux en Californie.

[Demandes des forces de l'ordre étrangères](#demandes-des-forces-de-lordre-étrangères)
----------

En tant que société américaine basée en Californie, GitHub n'est pas tenue de fournir des données aux gouvernements étrangers en réponse à une procédure judiciaire émise par des autorités étrangères.
Les responsables de l'application des lois étrangers souhaitant demander des informations à GitHub doivent contacter le bureau des affaires internationales de la division pénale du ministère de la Justice des États-Unis.
GitHub répondra rapidement aux demandes émises par l'intermédiaire d'un tribunal américain au moyen d'un traité d'entraide judiciaire ("MLAT ») ou d'une commission rogatoire.

[Questions](#questions)
----------

Avez-vous d'autres questions, commentaires ou suggestions ? Veuillez contacter .

{"resolvedServerColorMode":"day"}
