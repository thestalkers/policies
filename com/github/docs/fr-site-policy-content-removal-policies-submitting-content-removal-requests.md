Envoi de demandes de suppression de contenu - Documentation GitHub(function(){
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
var q=window.matchMedia?window.matchMedia('(prefers-color-scheme: dark)'):null;
var apply=function(){
var night=css.colorMode==='auto'?!!(q&&q.matches):css.colorMode==='dark';
var theme=night?css.darkTheme:css.lightTheme;
var mode=theme.indexOf('dark')===0?'dark':'light';
h.setAttribute('data-color-mode',mode);
h.setAttribute('data-'+mode+'-theme',theme);
};
h.setAttribute('data-color-mode-preference',css.colorMode);
h.setAttribute('data-light-theme',css.lightTheme);
h.setAttribute('data-dark-theme',css.darkTheme);
apply();
if(css.colorMode==='auto'&&q){
if(q.addEventListener)q.addEventListener('change',apply);
else if(q.addListener)q.addListener(apply);
}
}catch(e){}
})();

[Skip to main content](#main-content)

[Skip to content](#main-content)

Réduire la barre latéraleDévelopper la barre latérale

Faire défiler les barres de navigation vers la gauche

1. [Accueil](/fr)
2. [Politique du site](/fr/site-policy)
3. [Politiques de suppression de contenu](/fr/site-policy/content-removal-policies)
4. Envoi de demandes de suppression de contenu

Faire défiler les barres de navigation vers la droite

[Site policy](/fr/site-policy)
----------

Dans cet article

Envoi de demandes de suppression de contenu
==========

Copier Markdown

Dans cet article
----------

* [Politique de retrait DMCA](#dmca-takedown-policy)

* [Politique de marque GitHub](#github-trademark-policy)

* [Politique de suppression des informations privées de GitHub](#github-private-information-removal-policy)

Nous comprenons que du contenu protégé par le droit d'auteur, une marque de commerce ou privé peut être publié sur GitHub - accidentellement ou exprès - parfois dans des référentiels qui ne vous appartiennent pas. Étant donné que la nature de ce contenu varie et en raison des différentes lois applicables, chaque catégorie a ses propres exigences de déclaration distinctes décrites dans nos politiques.

Si vous souhaitez demander que le contenu soit supprimé de GitHub, veuillez prendre le temps de vous familiariser avec chacune de ces politiques et leurs exigences de rapport respectives avant de soumettre un rapport. Si nous recevons un rapport incomplet, nous devrons demander des clarifications ou des révisions et vous devrez soumettre à nouveau un rapport révisé.

Veuillez noter que nous ne sommes pas en mesure de vous aider à déterminer quelle police convient à votre situation spécifique. Si vous avez examiné les politiques ci-dessous et que vous vous demandez toujours si le contenu doit ou non être signalé en tant que droit d'auteur, marque ou information privée, nous vous recommandons de consulter un conseiller juridique indépendant.

[Politique de retrait DMCA](#dmca-takedown-policy)
----------

La [Politique de retrait dans le cadre de la DMCA](/fr/site-policy/content-removal-policies/dmca-takedown-policy) permet de signaler un contenu qui, selon vous, porte atteinte à un droit d'auteur dont vous ou votre organisation êtes titulaires. Après avoir examiné la politique, vous pouvez également consulter notre [Guide de soumission d'une information préalable en matière de retrait dans le cadre de la DMCA](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) avant de soumettre un signalement.

[Politique de marque GitHub](#github-trademark-policy)
----------

La [Politique de GitHub relative aux marques commerciales](/fr/site-policy/content-removal-policies/github-trademark-policy) peut être utilisée pour signaler un contenu qui semble utiliser le nom de votre société ou de votre entreprise, votre logo ou d'autres éléments protégés par une marque commerciale d'une manière susceptible d'induire en erreur ou de prêter à confusion quant à la marque ou à l'affiliation.

[Politique de suppression des informations privées de GitHub](#github-private-information-removal-policy)
----------

La [Politique de retrait des informations privées de GitHub](/fr/site-policy/content-removal-policies/github-private-information-removal-policy) peut être utilisée pour signaler des données privées (confidentielles et présentant un risque de sécurité), mais qui ne sont pas nécessairement protégées par des droits d'auteur ou des marques commerciales.

Les utilisateurs en Inde peuvent [contacter le responsable des griefs de GitHub](https://support.github.com/contact/india-grievance-officer).
