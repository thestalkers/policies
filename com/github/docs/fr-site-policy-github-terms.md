Termes GitHub - Documentation GitHub(function(){
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
2. [Termes GitHub](/fr/site-policy/github-terms)

Termes GitHub
==========

[Conditions Générales d’Utilisation de GitHub](/fr/site-policy/github-terms/github-terms-of-service)
----------

[Conditions d'utilisation de GitHub Corporate](/fr/site-policy/github-terms/github-corporate-terms-of-service)
----------

[Conditions GitHub pour les produits et fonctionnalités supplémentaires](/fr/site-policy/github-terms/github-terms-for-additional-products-and-features)
----------

[Directives de la communauté GitHub](/fr/site-policy/github-terms/github-community-guidelines)
----------

[Code de Conduite de la Communauté GitHub](/fr/site-policy/github-terms/github-community-code-of-conduct)
----------

[GitHub – Termes du Contrat de licence de la préversion](/fr/site-policy/github-terms/github-pre-release-license-terms)
----------

[Versions préliminaires couvertes par le DPA GitHub](/fr/site-policy/github-terms/github-dpa-previews)
----------

[Conditions supplémentaires des sponsors GitHub](/fr/site-policy/github-terms/github-sponsors-additional-terms)
----------

[Contrat de développeur enregistré GitHub](/fr/site-policy/github-terms/github-registered-developer-agreement)
----------

[Conditions d'utilisation de la place de marché GitHub](/fr/site-policy/github-terms/github-marketplace-terms-of-service)
----------

[Contrat de développement de la place de marché GitHub](/fr/site-policy/github-terms/github-marketplace-developer-agreement)
----------

[Conditions du programme de recherche GitHub](/fr/site-policy/github-terms/github-research-program-terms)
----------

[Termes et conditions des applications open source GitHub](/fr/site-policy/github-terms/github-open-source-applications-terms-and-conditions)
----------

[Conditions de l'événement GitHub](/fr/site-policy/github-terms/github-event-terms)
----------

[Code de conduite des événements GitHub](/fr/site-policy/github-terms/github-event-code-of-conduct)
----------

[Accord d'utilisation pédagogique de GitHub](/fr/site-policy/github-terms/github-educational-use-agreement)
----------

[Stratégie de développeur de l’extension GitHub Copilot](/fr/site-policy/github-terms/github-copilot-extension-developer-policy)
----------

[Contrat du Programme partenaire d’analyse de secret GitHub](/fr/site-policy/github-terms/github-secret-scanning-partner-program-agreement)
----------
