Politiques de l'entreprise GitHub - Documentation GitHub(function(){
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
3. [Politiques de l'entreprise GitHub](/fr/site-policy/github-company-policies)

Faire défiler les barres de navigation vers la droite

[Site policy](/fr/site-policy)
----------

Politiques de l'entreprise GitHub
==========

[Déclaration de GitHub contre l'esclavage moderne et le travail des enfants](/fr/site-policy/github-company-policies/github-statement-against-modern-slavery-and-child-labor)
----------

[Déclaration anti-corruption GitHub](/fr/site-policy/github-company-policies/github-anti-bribery-statement)
----------

[Engagement de coopération GitHub GPL](/fr/site-policy/github-company-policies/github-gpl-cooperation-commitment)
----------

[Politique relative aux cadeaux et aux divertissements de GitHub](/fr/site-policy/github-company-policies/github-gifts-and-entertainment-policy)
----------
