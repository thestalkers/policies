Documentation sur la politique du site - Documentation GitHub(function(){
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
2. Politique du site

Faire défiler les barres de navigation vers la droite

[Site policy](/fr/site-policy)
----------

Documentation sur la politique du site
==========

Consultez les conditions d’utilisation du service, les stratégies d’utilisation acceptables, les pratiques de confidentialité, les procédures de suppression de contenu et d’autres stratégies de site de GitHub.

[Vue d’ensemble](/site-policy/github-terms/github-terms-of-service)

Recommandé
----------

### [Conditions Générales d’Utilisation de GitHub](/fr/free-pro-team@latest/site-policy/github-terms/github-terms-of-service) ###

### [Déclaration de confidentialité générale GitHub](/fr/free-pro-team@latest/site-policy/privacy-policies/github-general-privacy-statement) ###

### [Politiques d’utilisation acceptable de GitHub](/fr/free-pro-team@latest/site-policy/acceptable-use-policies/github-acceptable-use-policies) ###

Articles
----------

Catégorie: Toutes les catégories

Review product and program terms

### [Accord d'utilisation pédagogique de GitHub](/fr/site-policy/github-terms/github-educational-use-agreement) ###

Follow acceptable use policies

### [Appel et rétablissement de GitHub](/fr/site-policy/acceptable-use-policies/github-appeal-and-reinstatement) ###

Review product and program terms

### [Code de Conduite de la Communauté GitHub](/fr/site-policy/github-terms/github-community-code-of-conduct) ###

Review product and program terms

### [Code de conduite des événements GitHub](/fr/site-policy/github-terms/github-event-code-of-conduct) ###

Review product and program terms

### [Conditions d'utilisation de GitHub Corporate](/fr/site-policy/github-terms/github-corporate-terms-of-service) ###

Review product and program terms

### [Conditions d'utilisation de la place de marché GitHub](/fr/site-policy/github-terms/github-marketplace-terms-of-service) ###

Review product and program terms

### [Conditions de l'événement GitHub](/fr/site-policy/github-terms/github-event-terms) ###

Review product and program terms

### [Conditions du programme de recherche GitHub](/fr/site-policy/github-terms/github-research-program-terms) ###

Review product and program terms

### [Conditions Générales d’Utilisation de GitHub](/fr/site-policy/github-terms/github-terms-of-service) ###

Affichage de 1-9 de 57

[Previous]()[1](#1)[2](#2)[3](#3)[4](#4)[5](#5)[6](#6)[7](#7)[Next](#2)
