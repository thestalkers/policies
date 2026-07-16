GitHub perturbe l'expérience des autres utilisateurs - Documentation GitHub(function(){
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
3. [Règles de Bon Usage](/fr/site-policy/acceptable-use-policies)
4. [Perturber l'expérience des autres utilisateurs](/fr/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)

Faire défiler les barres de navigation vers la droite

[Site policy](/fr/site-policy)
----------

GitHub perturbe l'expérience des autres utilisateurs
==========

Copier en tant que Markdown

Faire partie d'une communauté implique de reconnaître comment votre comportement affecte les autres et de s'engager dans des interactions significatives et productives avec les gens et la plate-forme sur laquelle ils s'appuient.

Nous n'autorisons pas les comportements qui perturbent de manière significative ou continue l'expérience des autres utilisateurs. Cela inclut :

* Publier des commentaires hors sujet
* Ouvrir des problèmes vides ou sans signification ou des demandes d'extraction
* Mettre en vedette et/ou suivre des comptes ou des référentiels en grand volume en peu de temps
* Créer des revues de code absurdes ou non pertinentes
* Interagir avec les fonctionnalités de la plate-forme d'une manière qui provoque des notifications excessives pour les autres utilisateurs
* Utiliser toute autre fonctionnalité de la plateforme d'une manière qui crée des perturbations

Bien que nous encourageons les mainteneurs à modérer leurs propres projets sur une base individuelle, le personnel de GitHub peut prendre des mesures restrictives supplémentaires contre les comptes qui se livrent à ces types de comportements.

Veuillez noter que la conduite ci-dessus peut également violer d'autres restrictions de nos [Règles de Bon Usage](/fr/site-policy/acceptable-use-policies/github-acceptable-use-policies). Par exemple, selon la nature et la gravité de l'activité, elle peut s'apparenter à de l'[intimidation et du harcèlement](/fr/site-policy/acceptable-use-policies/github-bullying-and-harassment).
