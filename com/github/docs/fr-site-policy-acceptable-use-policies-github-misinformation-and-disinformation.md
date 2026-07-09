Désinformation et désinformation GitHub - Documentation GitHub(function(){
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
2. [Règles de Bon Usage](/fr/site-policy/acceptable-use-policies)
3. [Stratégie de désinformation](/fr/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)

Désinformation et désinformation GitHub
==========

Copier en tant que Markdown

Vous ne pouvez pas publier de contenu qui présente une vision déformée de la réalité, qu'il soit inexact ou faux (désinformation) ou intentionnellement trompeur (désinformation), lorsque ce contenu est susceptible de porter préjudice au public ou d'interférer avec des opportunités justes et égales. pour tous de participer à une société libre et ouverte. Cela peut inclure :

* Allégations médicales inexactes ou scientifiquement non étayées qui mettent en danger la santé ou la sécurité publiques
* Médias manipulés, qu'ils soient audio ou visuels, susceptibles d'induire en erreur ou de tromper d'une manière susceptible de nuire à l'intérêt public
* Contenu faux ou trompeur susceptible d'interférer avec la capacité d'un individu à participer à des activités civiques
* Allégations non fondées susceptibles de promouvoir la haine ou le harcèlement ciblé de groupes de personnes spécifiques

Nous encourageons la participation active à l'expression d'idées, de points de vue et d'expériences et ne sommes peut-être pas en mesure de contester des récits ou des observations personnelles. Nous autorisons généralement la parodie et la satire qui sont conformes à nos [règles de bon usage](/fr/site-policy/acceptable-use-policies/github-acceptable-use-policies) et nous considérons que le contexte est important dans la façon dont l'information est reçue et comprise. Lors de l'examen du contenu dans le cadre de cette politique, GitHub prendra en compte l'impact de divers facteurs susceptibles d'aider à orienter le spectateur, par exemple si le contenu a été fourni avec des clauses de non-responsabilité claires, des citations de sources crédibles ou inclut d'autres détails qui clarifient l'exactitude du informations partagées.
