Règles de Bon Usage - Documentation GitHub(function(){
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

Scroll breadcrumbs right

[Site policy](/fr/site-policy)
----------

Règles de Bon Usage
==========

[Politiques d’utilisation acceptable de GitHub](/fr/site-policy/acceptable-use-policies/github-acceptable-use-policies)
----------

[GitHub Active Malware ou Exploits](/fr/site-policy/acceptable-use-policies/github-active-malware-or-exploits)
----------

[GitHub Intimidation et Harcèlement](/fr/site-policy/acceptable-use-policies/github-bullying-and-harassment)
----------

[GitHub perturbe l'expérience des autres utilisateurs](/fr/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)
----------

[GitHub Doxxing et invasion de la vie privée](/fr/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)
----------

[GitHub Discours de haine et discrimination](/fr/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)
----------

[Usurpation d'identité GitHub](/fr/site-policy/acceptable-use-policies/github-impersonation)
----------

[Désinformation et désinformation GitHub](/fr/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)
----------

[Contenu sexuellement obscène de GitHub](/fr/site-policy/acceptable-use-policies/github-sexually-obscene-content)
----------

[GitHub Menaces de violence et contenu gratuitement violent](/fr/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)
----------

[Terrorisme et extrémisme violent sur GitHub](/fr/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
----------

[Exploitation ou abus sexuels d’enfants sur GitHub](/fr/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)
----------

[Images intimes non consensuelles sur GitHub](/fr/site-policy/acceptable-use-policies/github-non-consensual-intimate-imagery)
----------

[Outils multimédias et IA synthétiques GitHub](/fr/site-policy/acceptable-use-policies/github-synthetic-media-and-ai-tools)
----------

[Appel et rétablissement de GitHub](/fr/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)
----------
