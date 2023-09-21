Politique de suppression des informations privées de GitHub - Documentation GitHub

[Skip to main content](#main-content)

[All products](/fr)

[Site policy](/site-policy)

* [Politique du site](/fr/site-policy)/
* [Politiques de suppression de contenu](/fr/site-policy/content-removal-policies)/
* [Politique de suppression des informations privées de GitHub](/fr/site-policy/content-removal-policies/github-private-information-removal-policy)

Politique de suppression des informations privées de GitHub
==========

Dans cet article
----------

* [Qu'est-ce que les informations privées ?](#quest-ce-que-les-informations-privées)
* [Choses à savoir](#things-to-know)
* [Comment cela fonctionne-t-il réellement ?](#how-does-this-actually-work)
* [Envoi d'une demande de suppression d'informations privées](#envoi-dune-demande-de-suppression-dinformations-privées)
* [Comment soumettre votre demande](#how-to-submit-your-request)
* [Litiges](#disputes)

Nous proposons ce processus de retrait des informations privées en tant que service exceptionnel, uniquement pour les contenus à haut risque qui violent les [Conditions d'utilisation du service de GitHub](/fr/site-policy/acceptable-use-policies/github-acceptable-use-policies#3-conduct-restrictions), par exemple lorsque votre sécurité est menacée par des informations d'identification d'accès exposées. Ce guide décrit les informations dont GitHub a besoin pour traiter une demande de suppression d'informations privées d'un référentiel.

[Qu'est-ce que les informations privées ?](#quest-ce-que-les-informations-privées)
----------

Aux fins du présent document, les « informations privées » désignent le contenu qui (i) aurait dû rester confidentiel, *et* (ii) dont la disponibilité publique présente un risque de sécurité spécifique ou ciblé pour vous ou votre organisation.

Le « risque de sécurité » fait référence à une situation impliquant une exposition à un danger physique, un vol d'identité ou une probabilité accrue d'accès non autorisé à des installations physiques ou réseau.

### [Les demandes de suppression d'informations privées sont appropriées pour :](#les-demandes-de-suppression-dinformations-privées-sont-appropriées-pour) ###

* Accéder aux informations d'identification, telles que les noms d'utilisateur combinés à des mots de passe, des jetons d'accès ou d'autres secrets sensibles qui peuvent accorder l'accès au serveur, au réseau ou au domaine de votre organisation.
* Jetons AWS et autres informations d'identification d'accès similaires qui accordent l'accès à un tiers en votre nom. Vous devez être en mesure de prouver que le jeton vous appartient.
* Documentation (telle que des diagrammes ou une architecture de réseau) qui pose un risque de sécurité spécifique pour une organisation.
* Des [informations](/fr/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy) relatives à vous-même en tant que personne et présentant un risque de sécurité pour vous (par exemple des numéros de sécurité sociale ou d'autres numéros d'identification administratifs).

### [Les demandes de suppression d'informations privées ne sont *pas* appropriées pour :](#les-demandes-de-suppression-dinformations-privées-ne-sont-pas-appropriées-pour) ###

* Noms de serveurs internes, adresses IP et URL, seuls. Vous devez être en mesure de prouver que leur utilisation dans un fichier ou un morceau de code particulier constitue une menace pour la sécurité.
* De simples mentions de l'identité, du nom, de la marque, du nom de domaine de votre entreprise ou d'autres références à votre entreprise dans des fichiers sur GitHub. Vous devez être en mesure d'expliquer pourquoi l'utilisation de l'identité de votre entreprise constitue une menace pour la sécurité de votre entreprise.
* Des fichiers entiers ou des référentiels qui ne présentent pas de risque de sécurité spécifique, mais que vous jugez autrement répréhensibles.
* Demandes de suppression de contenu susceptible de porter atteinte à vos droits d'auteur ou à ceux de votre organisation. Si vous avez des questions sur la manière dont GitHub traite les questions liées au droit d'auteur ou si vous souhaitez signaler un contenu potentiellement illicite, veuillez consulter notre [Politique de retrait dans le cadre de la DMCA](/fr/site-policy/content-removal-policies/dmca-takedown-policy). Le processus de retrait des informations privées n'est généralement pas destiné à supprimer des fichiers ou des référentiels complets, mais uniquement les éléments spécifiques d'informations privées contenus dans ces fichiers. Bien qu'il puisse y avoir des cas où les fichiers sont entièrement remplis d'informations privées, vous devez justifier le risque de sécurité lié à la suppression de ces fichiers, ce qui peut augmenter le temps nécessaire au traitement de votre demande.
* Litiges de marque. Si vous avez des questions sur la manière dont GitHub traite les questions relatives aux marques commerciales ou si vous souhaitez signaler un contenu contenant les marques commerciales ou de service de votre organisation, veuillez consulter notre [Politique en matière de marques commerciales](/fr/site-policy/content-removal-policies/github-trademark-policy).
* Plaintes relatives à la confidentialité. Si vous souhaitez accéder à vos informations personnelles sur GitHub, les transférer, les modifier ou les supprimer, veuillez nous contacter en utilisant [notre formulaire de contact sur la confidentialité](https://github.com/contact/privacy).
* Contenu régi par notre [Charte de la Communauté](/fr/site-policy/github-terms/github-community-guidelines), comme les logiciels malveillants ou les outils polyvalents. Si vous avez des questions sur notre Charte de la Communauté ou si vous pensez que le contenu de GitHub pourrait enfreindre nos règles, vous pouvez utiliser un [Signaler du contenu](https://github.com/contact/report-content) pour nous contacter.

[Choses à savoir](#things-to-know)
----------

**Demandez d'abord gentiment.** Une excellente première étape avant de nous envoyer une demande de suppression de données consiste à essayer de contacter directement l'utilisateur. Ils peuvent avoir répertorié les informations de contact sur leur page de profil public ou dans le fichier README ou Support du référentiel, ou vous pouvez entrer en contact en créant un problème ou une demande d'extraction dans le référentiel. Ce n'est pas strictement obligatoire, mais c'est apprécié.

**Absence de bots.** Vous devriez demander à un professionnel qualifié d'évaluer les faits de chaque demande que vous envoyez. Si vous sous-traitez vos efforts à un tiers, assurez-vous de savoir comment il fonctionne et assurez-vous qu'il n'utilise pas de robots automatisés pour soumettre des plaintes en masse. Ces plaintes incluent souvent des données qui ne présentent aucune menace pour la sécurité, et elles n'incluent pas d'explications suffisantes, nécessitant des allers-retours supplémentaires et entraînant des retards, même lorsque la plainte est fondée.

**Envoyez une demande appropriée.** Comme indiqué ci-dessus, nous proposons ce processus de suppression d'informations privées en tant que service exceptionnel uniquement pour les contenus à haut risque. Nous ne sommes pas en mesure d'utiliser ce processus pour supprimer d'autres types de contenu, tels que des contenus potentiellement contrefaits, et nous ne sommes pas en mesure de traiter d'autres types de demandes de suppression simultanément lors du traitement des demandes de suppression d'informations privées. Nous serons en mesure de vous aider plus rapidement si vous envoyez vos demandes de suppression d'informations privées séparément de toute demande de suppression de contenu potentiellement illicite. Si vous ne savez pas si votre demande concerne uniquement des informations privées ou concerne également d'autres questions juridiques, veuillez consulter un conseiller juridique.

**Temps de traitement.** Bien que nous traitions les demandes de suppression d'informations privées aussi rapidement que possible, en raison du volume de demandes que nous traitons, l'examen de votre demande peut prendre un certain temps. Des demandes supplémentaires ou des demandes multiples provenant de points de contact supplémentaires peuvent entraîner des retards.

[Comment cela fonctionne-t-il réellement ?](#how-does-this-actually-work)
----------

1. **Le plaignant enquête.** Il appartient au demandeur de mener sa propre enquête et de nous fournir les [détails dont nous avons besoin](#your-request-must-include), le plus important étant d'expliquer en quoi les données présentent un risque pour la sécurité. GitHub n'est pas en mesure de rechercher ou de prendre des décisions initiales concernant des informations privées au nom d'un individu ou d'une organisation.

2. **Le plaignant envoie une demande de retrait d'informations privées.** Après avoir mené une enquête, le plaignant prépare et [envoie une demande de retrait d'informations privées](#sending-a-private-information-removal-request) à GitHub. Si la demande n'est pas suffisamment détaillée pour démontrer le risque de sécurité et pour que GitHub localise les données, nous répondrons et demanderons plus d'informations.

3. **GitHub demande à l'utilisateur d'apporter des modifications.** Dans la plupart des cas, nous contacterons l'utilisateur qui a créé le référentiel et lui donnerons la possibilité de supprimer ou de modifier les informations privées spécifiées dans la demande ou de contester la réclamation.

4. **L'utilisateur notifie GitHub des modifications.** Si l'utilisateur choisit d'apporter les modifications spécifiées, il doit nous en informer dans le délai imparti. S'ils ne le font pas, nous désactiverons le référentiel. Si l'utilisateur nous informe qu'il a apporté des modifications, nous vérifierons que les modifications ont été apportées et informerons le plaignant.

OU

1. **L'utilisateur peut contester la demande.** Si un utilisateur estime que le contenu en question n'est pas une information privée soumise à la présente politique, il peut le contester. S'ils le font, nous laisserons généralement au plaignant le soin de contacter l'utilisateur et de régler les choses directement avec lui, dans des limites raisonnables.

2. **Le plaignant vérifie les modifications apportées**. Si l'utilisateur apporte des modifications, le plaignant doit les examiner. Si les modifications sont insuffisantes, le plaignant doit fournir à GitHub des détails expliquant pourquoi. GitHub peut désactiver le référentiel ou donner à l'utilisateur une chance supplémentaire d'apporter les modifications.

3. **L'utilisateur peut demander une fenêtre supplémentaire pour apporter des modifications.** Si l'utilisateur a raté l'occasion de supprimer les informations privées spécifiées dans l'avis, nous pouvons lui accorder une fenêtre supplémentaire d'environ 1 jour ouvrable, sur demande, pour effectuer ces modifications. Dans ce cas, GitHub informera le plaignant.

### [Qu'en est-il des fourches ? (ou Qu'est-ce qu'une fourchette ?)](#quen-est-il-des-fourches-ou-quest-ce-quune-fourchette) ###

L'une des meilleures fonctionnalités de GitHub est la possibilité pour les utilisateurs de « fourcher » les référentiels les uns des autres. Qu'est-ce que cela signifie ? Essentiellement, cela signifie que les utilisateurs peuvent faire une copie d'un projet sur GitHub dans leurs propres référentiels. Comme la licence ou la loi le permet, les utilisateurs peuvent ensuite apporter des modifications à ce fork pour soit revenir au projet principal, soit simplement conserver leur propre variante d'un projet. Chacun de ces exemplaires est un « [Glossaire GitHub](/fr/get-started/quickstart/github-glossary#fork) » du référentiel d'origine, qui à son tour peut également être appelé le « parent » du fork.

GitHub ne désactivera pas automatiquement les fourches lors de la désactivation d'un référentiel parent. En effet, les fourches appartiennent à différents utilisateurs et peuvent avoir été modifiées de manière significative. GitHub ne mène aucune enquête indépendante sur les fourches. Nous attendons de ceux qui envoient des demandes de suppression d'informations privées qu'ils mènent cette enquête et, s'ils pensent que les forks contiennent également des informations privées, incluent expressément les forks dans leur demande.

Si, au moment où vous avez soumis votre notification, vous avez identifié toutes les fourches existantes de ce référentiel, nous traiterons une réclamation valide contre toutes les fourches de ce réseau au moment où nous traiterons la notification. Nous le ferions étant donné la probabilité que toutes les fourches nouvellement créées contiendraient le même contenu. De plus, si le réseau signalé qui contient le contenu signalé est plus grand que cent (100) référentiels et serait donc difficile à examiner dans son intégralité, nous pouvons envisager de désactiver l'ensemble du réseau si vous indiquez dans votre avis que, sur la base du nombre représentatif de fourches que vous avez examinées, vous pensez que la totalité ou la plupart des fourches contiennent le contenu signalé dans le référentiel parent.

[Envoi d'une demande de suppression d'informations privées](#envoi-dune-demande-de-suppression-dinformations-privées)
----------

En raison du type de contenu hébergé par GitHub (principalement du code logiciel) et de la manière dont ce contenu est géré (avec Git), nous avons besoin que les réclamations soient aussi précises que possible. Afin que nous puissions vérifier qu'un utilisateur a complètement supprimé les informations privées signalées, nous devons savoir exactement où chercher.

Ces lignes directrices sont conçues pour rendre le traitement des demandes de suppression d'informations privées aussi simple que possible.

### [Votre demande doit inclure :](#your-request-must-include) ###

1. Un lien fonctionnel et cliquable vers chaque fichier contenant des informations privées. (Notez que nous ne pouvons pas travailler à partir de résultats de recherche, d'exemples ou de captures d'écran.)
2. Numéros de ligne spécifiques dans chaque fichier contenant les informations privées.
3. Une brève description de la façon dont chaque élément que vous avez identifié pose un risque de sécurité pour vous ou votre organisation. ***Il est important que vous fournissiez une explication de la manière dont les données posent un risque pour la sécurité au-delà de la simple déclaration de ce risque.***
4. Si vous êtes un tiers agissant en tant qu'agent pour une organisation confrontée à un risque de sécurité, incluez une déclaration indiquant que vous avez le droit légal d'agir au nom de cette organisation.
5. FACULTATIF : faites-nous savoir si votre demande est particulièrement urgente, et pourquoi. Nous répondons à toutes les demandes de suppression d'informations privées aussi rapidement que possible. Toutefois, si cette demande est particulièrement urgente, comme une exposition d'informations d'identification très récente, veuillez expliquer pourquoi.

[Comment soumettre votre demande](#how-to-submit-your-request)
----------

Vous pouvez soumettre votre demande de retrait d'informations privées en utilisant notre [formulaire de contact](https://support.github.com/contact?tags=docs-private-information). Veuillez inclure une version en texte brut de votre demande dans le corps de votre message. L'envoi de votre demande en pièce jointe peut entraîner des retards de traitement.

[Litiges](#disputes)
----------

Si vous avez reçu de notre part une demande de retrait d'informations privées, vous pouvez la contester en répondant à notre courrier électronique et en nous indiquant, de manière aussi détaillée que possible, pourquoi vous pensez que le contenu en question n'est pas une information privée soumise à la présente Politique.
