Politiques de Confidentialité - Documentation GitHub(function(){
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
2. [Politiques de Confidentialité](/fr/site-policy/privacy-policies)

Politiques de Confidentialité
==========

[Déclaration de confidentialité générale GitHub](/fr/site-policy/privacy-policies/github-general-privacy-statement)
----------

[Sous-processeurs GitHub](/fr/site-policy/privacy-policies/github-subprocessors)
----------

[Cookies sur GitHub](/fr/site-policy/privacy-policies/github-cookies)
----------

[Notification de confidentialité des données globales GitHub pour les candidats](/fr/site-policy/privacy-policies/github-candidate-privacy-policy)
----------
