Politique de marque GitHub - Documentation GitHub(function(){
var MODES=["auto","light","dark"],THEMES=["light","dark","dark\_dimmed","dark\_high\_contrast"],D={"colorMode":"auto","lightTheme":"light","darkTheme":"dark"};
var css=D;
try{
var m=document.cookie.match(new RegExp('(?:^|; )'+"color\_mode"+'=([^;]\*)'));
if(m){
var p=JSON.parse(decodeURIComponent(m[1]));
var fMode=function(x){return MODES.indexOf(x)\>-1?x:null;};
var fTheme=function(t){if(!t)return null;if(THEMES.indexOf(t.name)\>-1)return t.name;if(THEMES.indexOf(t.color\_mode)\>-1)return t.color\_mode;return null;};
css={colorMode:fMode(p.color\_mode)||D.colorMode,lightTheme:fTheme(p.light\_theme)||D.lightTheme,darkTheme:fTheme(p.dark\_theme)||D.darkTheme};
}
}catch(e){}
try{
var h=document.documentElement;
h.setAttribute('data-color-mode',css.colorMode);
h.setAttribute('data-light-theme',css.lightTheme);
h.setAttribute('data-dark-theme',css.darkTheme);
}catch(e){}
})();

[Skip to main content](#main-content)

Réduire la barre latéraleDévelopper la barre latérale

Faire défiler les barres de navigation vers la gauche

1. [Accueil](/fr)
2. [Politique du site](/fr/site-policy)
3. [Politiques de suppression de contenu](/fr/site-policy/content-removal-policies)
4. [Politique de marque GitHub](/fr/site-policy/content-removal-policies/github-trademark-policy)

Faire défiler les barres de navigation vers la droite

[Site policy](/fr/site-policy)
----------

Politique de marque GitHub
==========

Copier en tant que Markdown

Dans cet article
----------

* [Qu'est-ce qu'une violation de la politique de marque GitHub ?](#quest-ce-quune-violation-de-la-politique-de-marque-github)
* [Qu'est-ce qui n'est pas une violation de la politique de marque GitHub ?](#quest-ce-qui-nest-pas-une-violation-de-la-politique-de-marque-github)
* [Comment GitHub répond-il aux violations signalées de la politique en matière de marques ?](#how-does-github-respond-to-reported-trademark-policy-violations)
* [Comment puis-je signaler une violation de la politique relative aux marques ?](#how-do-i-report-a-trademark-policy-violation)
* [Quelles informations sont requises lors du signalement de violations de la politique en matière de marques ?](#what-information-is-required-when-reporting-trademark-policy-violations)

[Qu'est-ce qu'une violation de la politique de marque GitHub ?](#quest-ce-quune-violation-de-la-politique-de-marque-github)
----------

L'utilisation d'une société ou d'un nom commercial, d'un logo ou d'autres éléments protégés par une marque d'une manière susceptible d'induire en erreur ou de confondre les autres en ce qui concerne sa marque ou son affiliation commerciale peut être considérée comme une violation de la politique en matière de marques.

[Qu'est-ce qui n'est pas une violation de la politique de marque GitHub ?](#quest-ce-qui-nest-pas-une-violation-de-la-politique-de-marque-github)
----------

L'utilisation de la marque d'un tiers d'une manière qui n'a rien à voir avec le produit ou le service pour lequel la marque a été accordée n'est pas une violation de la politique relative aux marques. Les noms d'utilisateur GitHub sont disponibles selon le principe du premier arrivé, premier servi et ne peuvent pas être réservés. Un compte GitHub avec un nom d'utilisateur qui se trouve être le même qu'une marque déposée n'est pas, en soi, nécessairement une violation de notre politique en matière de marques.

[Comment GitHub répond-il aux violations signalées de la politique en matière de marques ?](#how-does-github-respond-to-reported-trademark-policy-violations)
----------

Lorsque nous recevons des rapports de non-respect des règles en matière de marques de la part de titulaires d'enregistrements de marques fédéraux ou internationaux, nous examinons le compte et pouvons prendre les mesures suivantes :

* Lorsqu'il y a une intention claire d'induire les autres en erreur par l'utilisation non autorisée d'une marque, GitHub suspendra le compte et en informera le titulaire du compte.
* Lorsque nous déterminons qu'un compte semble semer la confusion chez les utilisateurs, mais qu'il ne se fait pas délibérément passer pour le bien ou le service de marque, nous donnons au titulaire du compte la possibilité de dissiper toute confusion potentielle. Nous pouvons également publier un nom d'utilisateur pour l'utilisation active du titulaire de la marque.

[Comment puis-je signaler une violation de la politique relative aux marques ?](#how-do-i-report-a-trademark-policy-violation)
----------

Les détenteurs de marques commerciales déposées peuvent signaler à GitHub d'éventuelles violations de la politique relative aux marques commerciales en utilisant la section [Soumettre un rapport de violation de la politique des marques commerciales](https://support.github.com/contact/trademark-policy). Veuillez utiliser le formulaire de contact et soumettre vos demandes relatives aux marques commerciales en utilisant l'adresse e-mail de votre entreprise et en incluant toutes les informations demandées ci-dessous afin d'accélérer notre réponse. Assurez-vous également de nous décrire clairement pourquoi le compte peut prêter à confusion avec votre marque ou comment le compte peut diluer ou ternir votre marque.

[Quelles informations sont requises lors du signalement de violations de la politique en matière de marques ?](#what-information-is-required-when-reporting-trademark-policy-violations)
----------

Afin d'enquêter sur les cas de non-respect des règles relatives aux marques, veuillez fournir toutes les informations suivantes :

* Nom d'utilisateur du compte signalé

* Nom de votre société

* Votre compte GitHub d'entreprise (le cas échéant)

* Site Web de la société

* Votre mot de marque, symbole, etc.

* Numéro d'enregistrement de la marque

* Bureau d'enregistrement des marques (par exemple, USPTO)

* Description de la confusion (par exemple, se faire passer pour votre entreprise, y compris des descriptions spécifiques du contenu ou du comportement)

* Action demandée (par exemple, suppression d'un compte en infraction ou transfert d'un nom d'utilisateur de marque vers un compte d'entreprise existant)

* Ajoutez la déclaration suivante : « J'ai la conviction avec bonne foi que l'utilisation de la marque commerciale décrite ci-dessus n'est pas autorisée par le propriétaire de la marque de fabrique, ou son agent, ou par la loi. » J'ai pris en considération les usages nominatifs et autres usages équitables. »

* Ajoutez également la déclaration suivante : « Je jure, sous peine de parjure, que les informations contenues dans cette notification sont exactes et que je suis le propriétaire de la marque commerciale, ou que je suis autorisé à agir au nom du propriétaire, d'un droit exclusif qui aurait été violé ».

* Ajoutez votre signature physique ou électronique.

* Remarque : vous devez fournir un numéro d'enregistrement de marque commerciale fédéral ou international. Si le nom que vous déclarez n'est **pas** une marque commerciale (par exemple, un organisme gouvernemental ou à but non lucratif), veuillez nous en informer :

  * Votre prénom et votre nom
  * Fonction
  * Adresse
  * Téléphone
  * E-mail (doit provenir du domaine de l'entreprise)
