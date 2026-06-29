Usurpation d'identité GitHub - Documentation GitHub(function(){
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

[Accueil](/fr)

[Site policy](/fr/site-policy)
----------

* [Politique du site](/fr/site-policy)/
* [Règles de Bon Usage](/fr/site-policy/acceptable-use-policies)/
* [Usurpation d'identité](/fr/site-policy/acceptable-use-policies/github-impersonation)

Usurpation d'identité GitHub
==========

Copier en tant que Markdown

Vous ne pouvez pas déformer votre identité ou votre association avec une autre personne ou organisation. Cela comprend faire l'une des choses suivantes d'une manière qui induit en erreur ou trompe les autres :

* Copier l'avatar d'un autre utilisateur ou d'autres informations de profil personnel
* Publier du contenu sous l'adresse e-mail d'un autre utilisateur
* Utilisation d'un nom d'utilisateur, d'un nom d'organisation ou d'un autre espace de noms trompeusement similaire
* Accès à un compte ou à une organisation avec le jeton ou les informations d'identification d'un autre utilisateur
* Se faire passer pour une autre personne ou organisation

L'usurpation d'identité est une forme de harcèlement et la violation de cette politique peut entraîner la perte de l'accès à votre compte.

Veuillez noter qu'avoir un nom d'utilisateur similaire à un autre n'est pas nécessairement une usurpation d'identité. GitHub tiendra compte du contexte. Par exemple, comme dans les cas impliquant des réclamations de [désinformation](/fr/site-policy/acceptable-use-policies/github-misinformation-and-disinformation), nous autorisons généralement la parodie et la satire qui sont conformes à nos [Règles de Bon Usage](/fr/site-policy/acceptable-use-policies/github-acceptable-use-policies).
