Politique de retrait DMCA - Documentation GitHub

[Skip to main content](#main-content)

[Accueil](/fr)

[Site policy](/fr/site-policy)
----------

* [Politique du site](/fr/site-policy)/
* [Politiques de suppression de contenu](/fr/site-policy/content-removal-policies)/
* [Politique de retrait DMCA](/fr/site-policy/content-removal-policies/dmca-takedown-policy)

Politique de retrait DMCA
==========

Dans cet article
----------

* [Qu’est ce que le DMCA ?](#what-is-the-dmca)
* [Avis DMCA en bref](#dmca-notices-in-a-nutshell)
* [A. Comment cela fonctionne-t-il réellement ?](#a-how-does-this-actually-work)
* [B. Qu'en est-il des fourches ? (ou Qu'est-ce qu'une fourchette ?)](#b-quen-est-il-des-fourches-ou-quest-ce-quune-fourchette)
* [C. Qu'en est-il des allégations de contournement ?](#c-quen-est-il-des-allégations-de-contournement)
* [D. Que se passe-t-il si j'ai manqué par inadvertance la fenêtre pour apporter des modifications ?](#d-que-se-passe-t-il-si-jai-manqué-par-inadvertance-la-fenêtre-pour-apporter-des-modifications)
* [E. Transparence](#e-transparency)
* [F. Infraction répétée](#f-repeated-infringement)
* [G. Soumettre des avis](#g-submitting-notices)
* [En savoir plus et parler](#learn-more-and-speak-up)

Bienvenue dans le guide de GitHub sur le Digital Millennium Copyright Act, communément appelé « DMCA ». Cette page ne se veut pas une introduction complète à la loi. Cependant, si vous avez reçu un avis de retrait DMCA ciblant le contenu que vous avez publié sur GitHub ou si vous êtes un titulaire de droits cherchant à émettre un tel avis, cette page aidera, espérons-le, à démystifier un peu la loi ainsi que notre politiques pour s'y conformer.

(Si vous souhaitez simplement envoyer une information préalable, vous pouvez passer à la section « [G. Envoi d'informations préalables](#g-submitting-notices) ».)

Comme pour toutes les questions juridiques, il est toujours préférable de consulter un professionnel au sujet de vos questions ou de votre situation spécifique. Nous vous encourageons fortement à le faire avant d'entreprendre toute action qui pourrait avoir un impact sur vos droits. Ce guide n'est pas un avis juridique et ne doit pas être considéré comme tel.

[Qu’est ce que le DMCA ?](#what-is-the-dmca)
----------

Afin de comprendre le DMCA et certaines des lignes politiques qu'il dessine, il est peut-être utile de considérer la vie avant sa promulgation.

Le DMCA offre une sphère de sécurité aux fournisseurs de services qui hébergent du contenu généré par les utilisateurs. Étant donné que même une seule réclamation pour violation du droit d'auteur peut entraîner des dommages-intérêts pouvant aller jusqu'à $150,000, la possibilité d'être tenu responsable du contenu généré par l'utilisateur pourrait être très préjudiciable pour les fournisseurs de services. Avec des dommages potentiels multipliés par des millions d'utilisateurs, les sites de cloud-computing et de contenu généré par les utilisateurs comme YouTube, Facebook ou GitHub n'auraient probablement [jamais vu le jour](https://arstechnica.com/tech-policy/2015/04/how-the-dmca-made-youtube/) sans la DMCA (ou du moins pas sans répercuter une partie de ce coût en aval sur leurs utilisateurs).

La DMCA aborde cette question en créant une [sphère de sécurité pour la responsabilité en matière de droits d'auteur](https://www.copyright.gov/title17/92chap5.html#512) pour les fournisseurs d'accès Internet qui hébergent des contenus générés par les utilisateurs présumés en infraction. Essentiellement, tant qu'un fournisseur de services respecte les règles de notification et de retrait du DMCA, il ne sera pas responsable de la violation du droit d'auteur basée sur le contenu généré par l'utilisateur. Pour cette raison, il est important que GitHub maintienne son statut de refuge DMCA.

La DMCA interdit également le [contournement des mesures techniques](https://www.copyright.gov/title17/92chap12.html) qui contrôlent efficacement l'accès aux œuvres protégées par le droit d'auteur.

[Avis DMCA en bref](#dmca-notices-in-a-nutshell)
----------

La DMCA fournit deux procédures simples que tous les utilisateurs de GitHub doivent connaître : (i) une procédure d'[avis de retrait](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) permettant aux détenteurs de droits d'auteur de demander le retrait d'un contenu ; et (ii) une procédure d'[information préalable en matière de contestation](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice) permettant aux utilisateurs de faire réactiver un contenu retiré par erreur ou après une mauvaise identification.

Les [informations préalables en matière de retrait](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) dans le cadre de la DMCA sont utilisées par les titulaires de droits d'auteur pour demander à GitHub de retirer le contenu qu'ils estiment être en infraction. Si vous êtes un concepteur ou un développeur de logiciels, vous créez chaque jour du contenu protégé par des droits d'auteur. Si quelqu'un d'autre utilise votre contenu protégé par des droits d'auteur de manière non autorisée sur GitHub, vous pouvez nous envoyer un avis de retrait DMCA pour demander que le contenu en infraction soit modifié ou supprimé.

D'autre part, des [informations préalables en matière de contestation](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice) peuvent être utilisées pour corriger des erreurs. Peut-être que la personne qui envoie l'avis de retrait ne détient pas le droit d'auteur ou n'a pas réalisé que vous avez une licence ou a fait une autre erreur dans son avis de retrait. Étant donné que GitHub ne peut généralement pas savoir s'il y a eu une erreur, l'avis de compteur DMCA vous permet de nous le faire savoir et de demander que nous remettions le contenu en place.

Le processus de notification et de retrait DMCA ne doit être utilisé que pour les plaintes concernant la violation du droit d'auteur. Les avis envoyés par le biais de notre processus DMCA doivent identifier les œuvres protégées par le droit d'auteur ou les œuvres qui auraient été enfreintes. Cette procédure ne peut pas être utilisée pour d'autres plaintes, comme les plaintes relatives à une prétendue [violation de marque commerciale](/fr/site-policy/content-removal-policies/github-trademark-policy) ou à des [données sensibles](/fr/site-policy/content-removal-policies/github-private-information-removal-policy). Nous proposons des procédures distinctes pour ces problèmes.

[A. Comment cela fonctionne-t-il réellement ?](#a-how-does-this-actually-work)
----------

Le cadre DMCA est un peu comme passer des notes en classe. Le titulaire des droits d'auteur remet à GitHub une plainte concernant un utilisateur. S'il est correctement rédigé, nous transmettons la plainte à l'utilisateur. Si l'utilisateur conteste la plainte, il peut renvoyer une note le disant. GitHub exerce peu de pouvoir discrétionnaire dans le processus autre que de déterminer si les avis répondent aux exigences minimales du DMCA. Il appartient aux parties (et à leurs avocats) d'apprécier le bien-fondé de leurs prétentions, sachant que les dénonciations doivent être faites sous peine de parjure.

Voici les étapes de base du processus.

1. **Le titulaire du droit d'auteur enquête.** Un titulaire de droits d'auteur doit toujours mener une enquête initiale pour confirmer à la fois (a) qu'il détient les droits d'auteur sur une œuvre originale et (b) que le contenu sur GitHub est non autorisé et contrefait. Il s'agit notamment de confirmer que l'utilisation n'est pas protégée en tant qu'[usage raisonnable](https://www.lumendatabase.org/topics/22). Une utilisation particulière peut être équitable si elle n'utilise qu'une petite quantité de contenu protégé par le droit d'auteur, utilise ce contenu de manière transformatrice, l'utilise à des fins éducatives ou une combinaison des éléments ci-dessus. Étant donné que le code se prête naturellement à de telles utilisations, chaque cas d'utilisation est différent et doit être considéré séparément.

   >
   >
   > **Exemple :** Un employé d'Acme Web Company trouve une partie du code de l'entreprise dans un référentiel GitHub. Acme Web Company concède sous licence son code source à plusieurs partenaires de confiance. Avant d'envoyer un avis de retrait, Acme doit examiner ces licences et ses accords pour confirmer que le code sur GitHub n'est autorisé par aucun d'entre eux.
   >
   >

2. **Le titulaire du droit d'auteur envoie une information préalable.** Après avoir mené son enquête, le titulaire du droit d'auteur prépare et envoie une [information préalable en matière de retrait](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) à GitHub. Si l'avis de retrait est suffisamment détaillé conformément aux exigences légales (comme expliqué dans le [guide pratique](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)), nous [publierons l'avis](#e-transparency) sur notre [référentiel public](https://github.com/github/dmca) et transmettrons le lien à l'utilisateur concerné.

3. **GitHub demande à l'utilisateur d'apporter des modifications.** Si l'avis allègue que tout le contenu d'un référentiel enfreint, ou qu'un package enfreint, nous passerons à l'étape 6 et désactiverons rapidement l'ensemble du référentiel ou du package. Sinon, étant donné que GitHub ne peut pas désactiver l'accès à des fichiers spécifiques dans un référentiel, nous contacterons l'utilisateur qui a créé le référentiel et lui donnerons environ 1 jour ouvrable pour supprimer ou modifier le contenu spécifié dans l'avis. Nous informerons le titulaire des droits d'auteur si et quand nous donnons à l'utilisateur la possibilité d'apporter des modifications. Étant donné que les packages sont immuables, si seule une partie d'un package est en infraction, GitHub devra désactiver l'intégralité du package, mais nous autorisons la réintégration une fois la partie en infraction supprimée.

4. **L'utilisateur notifie GitHub des modifications.** Si l'utilisateur choisit d'apporter les modifications spécifiées, il *doit* nous en informer dans un délai d'environ un jour ouvrable. Si ce n'est pas le cas, nous désactiverons le référentiel (comme décrit à l'étape 6). Si l'utilisateur nous informe qu'il a apporté des modifications, nous vérifierons que les modifications ont été apportées, puis nous en informerons le titulaire des droits d'auteur.

5. **Le titulaire du droit d'auteur révise ou retire l'information préalable.** Si l'utilisateur apporte des modifications, le titulaire des droits d'auteur doit les examiner et renouveler ou réviser son avis de retrait si les modifications sont insuffisantes. GitHub ne prendra aucune autre mesure à moins que le titulaire des droits d'auteur ne nous contacte pour soit renouveler l'avis de retrait d'origine, soit en soumettre un révisé. Si le titulaire du droit d'auteur est satisfait des modifications, il peut soit soumettre une rétractation formelle, soit ne rien faire. GitHub interprétera un silence de plus de deux semaines comme une rétractation implicite de l'avis de retrait.

6. **GitHub peut désactiver l'accès au contenu.** GitHub désactivera le contenu d'un utilisateur si : (i) le titulaire des droits d'auteur a allégué un droit d'auteur sur l'ensemble du dépôt ou du package de l'utilisateur (comme indiqué à l'étape 3) ; (ii) l'utilisateur n'a apporté aucune modification après avoir eu la possibilité de le faire (comme indiqué à l'étape 4) ; ou (iii) le titulaire du droit d'auteur a renouvelé son avis de retrait après que l'utilisateur a eu la possibilité d'apporter des modifications. Si le titulaire du droit d'auteur choisit plutôt de *réviser* l'information préalable, nous retournerons à l'étape 2 et répéterons le processus comme si l'avis révisé était une nouvelle information préalable.

7. **L'utilisateur peut envoyer une information préalable en matière de contestation.** Nous encourageons les utilisateurs dont le contenu a été désactivé à consulter un avocat pour connaître leurs options. Si un utilisateur estime que son contenu a été désactivé à la suite d'une erreur ou d'une mauvaise identification, il peut nous envoyer une [information préalable en matière de contestation](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice). Comme pour l'avis initial, nous veillerons à ce que l'information préalable en matière de contestation soit suffisamment détaillée (comme expliqué dans le [guide pratique](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)). Si c'est le cas, nous le [publierons](#e-transparency) dans notre [référentiel public](https://github.com/github/dmca) et transmettrons l'avis au titulaire du droit d'auteur en lui envoyant le lien.

8. **Le titulaire du droit d'auteur peut intenter une action en justice.** Si un titulaire de droits d'auteur souhaite garder le contenu désactivé après avoir reçu un avis de contestation, il devra engager une action en justice demandant une ordonnance du tribunal pour empêcher l'utilisateur de s'engager dans une activité de contrefaçon liée au contenu sur GitHub. En d'autres termes, vous pourriez être poursuivi. Si le titulaire des droits d'auteur ne prévient pas GitHub dans les 10 à 14 jours, en envoyant une copie d'une plainte légale valide déposée auprès d'un tribunal compétent, GitHub réactivera le contenu désactivé.

[B. Qu'en est-il des fourches ? (ou Qu'est-ce qu'une fourchette ?)](#b-quen-est-il-des-fourches-ou-quest-ce-quune-fourchette)
----------

L'une des meilleures fonctionnalités de GitHub est la possibilité pour les utilisateurs de « fourcher » les référentiels les uns des autres. Qu'est-ce que cela signifie ? Essentiellement, cela signifie que les utilisateurs peuvent faire une copie d'un projet sur GitHub dans leurs propres référentiels. Comme la licence ou la loi le permet, les utilisateurs peuvent ensuite apporter des modifications à ce fork pour soit revenir au projet principal, soit simplement conserver leur propre variante d'un projet. Chacun de ces exemplaires est un « [Glossaire GitHub](/fr/get-started/learning-about-github/github-glossary#fork) » du référentiel d'origine, qui à son tour peut également être appelé le « parent » du fork.

GitHub *ne désactive pas* automatiquement les forks lors de la désactivation d'un référentiel parent. En effet, les fourches appartiennent à différents utilisateurs, peuvent avoir été modifiées de manière significative et peuvent être autorisées ou utilisées d'une manière différente qui est protégée par la doctrine de l'utilisation équitable. GitHub ne mène aucune enquête indépendante sur les fourches. Nous attendons des titulaires de droits d'auteur qu'ils mènent cette enquête et, s'ils pensent que les fourches sont également en infraction, incluent expressément les fourches dans leur avis de retrait.

Dans de rares cas, vous pouvez alléguer une violation du droit d'auteur dans un référentiel complet qui est activement bifurqué. Si, au moment où vous avez soumis votre notification, vous avez identifié toutes les fourches existantes de ce référentiel comme étant prétendument en infraction, nous traiterons une réclamation valide contre toutes les fourches de ce réseau au moment où nous traiterons la notification. Nous le ferions étant donné la probabilité que toutes les fourches nouvellement créées contiendraient le même contenu. De plus, si le réseau signalé qui contient le contenu prétendument contrefaisant est plus grand que cent (100) référentiels et serait donc difficile à examiner dans son intégralité, nous pouvons envisager de désactiver l'ensemble du réseau si vous indiquez dans votre avis que, « Basé sur le nombre représentatif de fourches que j'ai examinées, je pense que toutes ou la plupart des fourches enfreignent dans la même mesure que le référentiel parent. » Votre déclaration sous serment s'appliquerait à cette déclaration.

[C. Qu'en est-il des allégations de contournement ?](#c-quen-est-il-des-allégations-de-contournement)
----------

La DMCA interdit le [contournement des mesures techniques](https://www.copyright.gov/title17/92chap12.html) qui contrôlent efficacement l'accès aux œuvres protégées par le droit d'auteur. Étant donné que ces types de réclamations sont souvent de nature très technique, GitHub demande aux demandeurs de fournir [des informations détaillées sur ces réclamations](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice#complaints-about-anti-circumvention-technology), et nous entreprendrons alors un examen plus approfondi.

Une allégation de contournement doit inclure les détails suivants sur les mesures techniques en place et la manière dont le projet accusé les contourne. Plus précisément, l'avis à GitHub doit inclure des déclarations détaillées décrivant :

1. Quelles sont les mesures techniques ;
2. Comment ils contrôlent efficacement l'accès au matériel protégé par le droit d'auteur ;
3. Comment le projet accusé est conçu pour contourner leurs mesures de protection technologiques décrites précédemment.

GitHub examinera de près les allégations de contournement, y compris par des experts techniques et juridiques. Dans l'examen technique, nous chercherons à valider les détails sur la manière dont les mesures techniques de protection fonctionnent et la manière dont le projet les contourne prétendument. Lors de l'examen juridique, nous chercherons à nous assurer que les réclamations ne s'étendent pas au-delà des limites du DMCA. Dans les cas où nous ne pouvons pas déterminer si une revendication est valide, nous pécherons du côté du développeur et laisserons le contenu en place. Si le demandeur souhaite donner des détails supplémentaires, nous recommencerons le processus d'examen pour évaluer les demandes révisées.

Lorsque nos experts déterminent qu'une réclamation est complète, légale et techniquement légitime, nous contacterons le propriétaire du référentiel et lui donnerons la possibilité de répondre à la réclamation ou d'apporter des modifications au référentiel pour éviter un retrait. S'il ne répond pas, nous essaierons de recontacter le propriétaire du référentiel avant de prendre d'autres mesures. En d'autres termes, nous ne désactiverons pas un référentiel sur la base d'une allégation de technologie de contournement sans essayer de contacter le propriétaire du référentiel pour lui donner une chance de répondre ou d'apporter des modifications avant. Si nous ne pouvons pas résoudre le problème en contactant d'abord le propriétaire du référentiel, nous serons toujours heureux d'envisager une réponse du propriétaire du référentiel même après la désactivation du contenu s'il souhaite avoir la possibilité de contester la réclamation, de nous présenter des faits supplémentaires, ou apportez des modifications pour que le contenu soit restauré. Lorsque nous aurons besoin de désactiver du contenu, nous veillerons à ce que les propriétaires du référentiel puissent exporter leurs problèmes et demandes d'extraction et autres données du référentiel qui ne contiennent pas le code de contournement présumé dans la mesure où cela est légalement possible.

Veuillez noter que notre processus d'examen de la technologie de contournement ne s'applique pas au contenu qui violerait autrement les restrictions de notre politique d'utilisation acceptable contre le partage de clés de licence de produit non autorisées, de logiciels permettant de générer des clés de licence de produit non autorisées ou de logiciels permettant de contourner les vérifications de clés de licence de produit. Bien que ces types de réclamations puissent également enfreindre les dispositions du DMCA sur la technologie de contournement, elles sont généralement simples et ne justifient pas un examen technique et juridique supplémentaire. Néanmoins, lorsqu'une réclamation n'est pas simple, par exemple dans le cas d'évasion, le processus d'examen des réclamations liées à la technologie de contournement s'appliquerait.

Lorsque GitHub traite une demande de retrait dans le cadre de la DMCA dans le cadre de notre processus d'examen des réclamations relatives aux technologies de contournement, nous proposons au propriétaire du référentiel de bénéficier gratuitement d'une consultation juridique indépendante par l'intermédiaire du [Fonds de Défense des Développeurs de GitHub](https://github.blog/2021-07-27-github-developer-rights-fellowship-stanford-law-school/).

[D. Que se passe-t-il si j'ai manqué par inadvertance la fenêtre pour apporter des modifications ?](#d-que-se-passe-t-il-si-jai-manqué-par-inadvertance-la-fenêtre-pour-apporter-des-modifications)
----------

Nous reconnaissons qu'il existe de nombreuses raisons valables pour lesquelles vous ne pourrez peut-être pas apporter de modifications dans la fenêtre d'environ 1 jour ouvrable que nous fournissons avant que votre référentiel ne soit désactivé. Peut-être que notre message a été signalé comme spam, peut-être que vous étiez en vacances, peut-être que vous ne consultez pas ce compte de messagerie régulièrement, ou peut-être que vous étiez juste occupé. Nous avons compris. Si vous répondez pour nous faire savoir que vous auriez aimé apporter les modifications, mais que vous avez manqué la première occasion, nous réactiverons le référentiel une fois de plus pendant environ 1 jour ouvrable pour vous permettre d'apporter les modifications. Encore une fois, vous devez nous notifier que vous avez apporté les modifications pour pouvoir conserver le référentiel après ce délai d'environ 1 jour ouvrable, comme indiqué ci-dessus à [l'étape A.4](#a-how-does-this-actually-work). Veuillez noter que nous n'offrirons qu'une seule chance supplémentaire.

[E. Transparence](#e-transparency)
----------

Nous croyons que la transparence est une vertu. Le public doit savoir quel contenu est supprimé de GitHub et pourquoi. Un public informé peut remarquer et mettre en évidence des problèmes potentiels qui passeraient autrement inaperçus dans un système opaque. Nous publions des copies expurgées de tous les avis juridiques que nous recevons (y compris les informations préalables originales, les avis de contestation ou les rétractations) à l'adresse <https://github.com/github/dmca>. Nous ne publierons pas publiquement vos coordonnées personnelles ; nous supprimerons les informations personnelles (à l'exception des noms d'utilisateur dans les URL) avant de publier les avis. Cependant, nous ne supprimerons aucune autre information de votre avis, sauf si vous nous le demandez spécifiquement. Voici quelques exemples d'un [avis](https://github.com/github/dmca/blob/master/2014/2014-05-28-Delicious-Brains.md) et d'une [information préalable en matière de contestation](https://github.com/github/dmca/blob/master/2014/2014-05-01-Pushwoosh-SDK-counternotice.md) publiés pour vous permettre de voir à quoi ils ressemblent. Lorsque nous supprimons du contenu, nous publierons à sa place un lien vers l'avis connexe.

Veuillez également noter que, bien que nous ne publierons pas publiquement les avis non expurgés, nous pouvons fournir une copie complète non expurgée de tout avis que nous recevons directement à toute partie dont les droits seraient affectés par celui-ci.

[F. Infraction répétée](#f-repeated-infringement)
----------

C'est la politique de GitHub, dans des circonstances appropriées et à sa seule discrétion, de désactiver et de résilier les comptes des utilisateurs qui pourraient enfreindre les droits d'auteur ou autres droits de propriété intellectuelle de GitHub ou d'autres.

[G. Soumettre des avis](#g-submitting-notices)
----------

Si vous êtes prêt à soumettre un avis ou un avis de contestation :

* [Comment soumettre une information préalable relative à la DMCA](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)
* [Comment soumettre une information préalable en matière de contestation DMCA](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)

[En savoir plus et parler](#learn-more-and-speak-up)
----------

Si vous fouinez sur Internet, il n'est pas trop difficile de trouver des commentaires et des critiques sur le système du droit d'auteur en général et sur le DMCA en particulier. Bien que GitHub reconnaisse et apprécie le rôle important que le DMCA a joué dans la promotion de l'innovation en ligne, nous pensons que les lois sur le droit d'auteur pourraient probablement utiliser un correctif ou deux, voire une toute nouvelle version. Dans le domaine des logiciels, nous améliorons et mettons constamment à jour notre code. Pensez à tout ce que la technologie a changé depuis 1998, date à laquelle le DMCA a été rédigé. N'est-il pas logique de mettre à jour ces lois qui s'appliquent aux logiciels ?

Nous ne prétendons pas avoir toutes les réponses. Mais si vous êtes curieux, voici quelques liens vers des articles scientifiques et des articles de blog que nous avons trouvés avec des opinions et des propositions de réforme :

* [Conséquences involontaires : 12 ans dans le cadre de la DMCA](https://www.eff.org/wp/unintended-consequences-under-dmca) (Electronic Frontier Foundation)
* [Dommages statutaires dans la loi sur le droit d'auteur : un recours qui a besoin d'être réformé](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1375604) (Évaluation juridique de William et Mary)
* [La durée de protection des droits d'auteur est-elle trop longue ?](https://the1709blog.blogspot.com/2012/11/is-term-of-protection-of-copyright-too.html) (Le Blogue 1709)
* [Si nous voulons modifier les dispositions de la DMCA relatives à la notification et au retrait, concentrons-nous sur l'ampleur des abus.](https://www.techdirt.com/articles/20140314/11350426579/if-were-going-to-change-dmcas-notice-takedown-lets-focus-how-widely-its-abused.shtml) (TechDirt)
* [Opportunités de réforme du droit d'auteur](https://www.cato-unbound.org/issues/january-2013/opportunities-copyright-reform) (Cato Unbound)
* [La doctrine de l'usage loyal et la loi sur le droit d'auteur du millénaire numérique : Existe-t-il un usage loyal sur internet conformément à ladite loi ?](https://digitalcommons.law.scu.edu/lawreview/vol42/iss1/6/) (Revue de droit de Santa Clara)

GitHub n'approuve pas nécessairement les points de vue de ces articles. Nous fournissons ces liens pour vous encourager à en savoir plus, à vous forger votre propre opinion, puis à contacter votre ou vos représentants élus (par exemple, au [Congrès américain](https://www.govtrack.us/congress/members) ou au [Parlement européen](https://www.europarl.europa.eu/meps/en/home)) pour demander les changements que vous jugez nécessaires.

{"resolvedServerColorMode":"day"}
