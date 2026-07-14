GitHub Intimidation et Harcèlement - Documentation GitHub(function(){
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
4. [Intimidation et harcèlement](/fr/site-policy/acceptable-use-policies/github-bullying-and-harassment)

Scroll breadcrumbs right

[Site policy](/fr/site-policy)
----------

GitHub Intimidation et Harcèlement
==========

Copier en tant que Markdown

Nous ne tolérons pas le harcèlement, l'intimidation ou l'abus de quelque nature que ce soit, que ce soit directement ou en encourageant les autres à prendre part à la conduite interdite. Cela inclut :

* Attaques personnelles ciblées
* Participer à des activités [perturbatrices](/fr/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users) ou les orchestrer d'une manière qui équivaut à un abus
* Suivre un autre utilisateur autour de la plate-forme d'une manière qui provoque l'intimidation
* Faire des avances sexuelles ou des commentaires adressés à une autre personne
* Participer de manière malhonnête à une conversation d'une manière qui provoque un conflit ou sape une discussion sincère
* Créer des comptes alternatifs spécifiquement pour échapper aux actions de modération prises par le personnel ou les utilisateurs de GitHub

Veuillez noter que tous les comportements importuns ne sont pas nécessairement considérés comme du harcèlement. Par exemple, être en désaccord avec un autre utilisateur ou rejeter ses commentaires peut ne pas atteindre le niveau de harcèlement sur notre plateforme. De plus, le partage de critiques de personnalités ou de projets publics, ou de sujets d'intérêt public, ne relève pas nécessairement de cette politique. Cependant, nous vous encourageons à faire attention à la façon dont vous interagissez avec les autres utilisateurs et la plate-forme, car cette activité peut toujours enfreindre notre restriction sur la perturbation de l'expérience des autres utilisateurs.
