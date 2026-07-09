Politiques de suppression de contenu - Documentation GitHub(function(){
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

1. [Politique du site](/fr/site-policy)
2. [Politiques de suppression de contenu](/fr/site-policy/content-removal-policies)

Politiques de suppression de contenu
==========

[Envoi de demandes de suppression de contenu](/fr/site-policy/content-removal-policies/submitting-content-removal-requests)
----------

[Politique de retrait DMCA](/fr/site-policy/content-removal-policies/dmca-takedown-policy)
----------

[Politique de suppression des informations privées de GitHub](/fr/site-policy/content-removal-policies/github-private-information-removal-policy)
----------

[Politique de marque GitHub](/fr/site-policy/content-removal-policies/github-trademark-policy)
----------

[Guide de soumission d'un avis de contestation DMCA](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)
----------

[Guide de soumission d'un avis de retrait DMCA](/fr/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)
----------
