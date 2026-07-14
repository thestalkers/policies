GitHub Menaces de violence et contenu gratuitement violent - Documentation GitHub(function(){
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

Collapse sidebarExpand sidebar

Scroll breadcrumbs left

1. [Accueil](/fr)
2. [Politique du site](/fr/site-policy)
3. [Règles de Bon Usage](/fr/site-policy/acceptable-use-policies)
4. [Menaces de Violence et Contenu de Violence gratuite](/fr/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)

Scroll breadcrumbs right

[Site policy](/fr/site-policy)
----------

GitHub Menaces de violence et contenu gratuitement violent
==========

Copier en tant que Markdown

Vous ne pouvez pas utiliser GitHub pour organiser, promouvoir, encourager, menacer ou inciter à des actes de violence. Vous ne pouvez pas publier de contenu qui représente ou glorifie la violence ou les atteintes physiques contre des êtres humains ou des animaux. Cela inclut :

* Menacer une autre personne ou un groupe d'abus, de préjudice, de violence sexuelle ou de mort
* Publier du texte, des images ou du contenu audio glorifiant ou contenant une représentation graphique de la violence envers soi-même, une autre personne, un groupe ou un animal
* Encourager une autre personne à s'automutiler

Nous n'autorisons pas la publication de contenu violent sans discrimination ou d'une manière difficile à éviter pour les autres utilisateurs, comme un avatar de profil ou un commentaire sur un problème. Cependant, nous comprenons qu'il peut y avoir des raisons légitimes de publier du contenu violent, par exemple à des fins éducatives ou documentaires, des œuvres créatives ou des représentations d'événements historiques. Dans ces cas, un avertissement clair ou une clause de non-responsabilité peut aider les utilisateurs à prendre une décision éclairée quant à savoir s'ils souhaitent ou non interagir avec un tel contenu. Néanmoins, GitHub peut décider de limiter la visibilité de ce contenu à ceux qui choisissent de s'y inscrire.
