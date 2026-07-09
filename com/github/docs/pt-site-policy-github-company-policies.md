Políticas da empresa do GitHub - Documentos do GitHub(function(){
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

[Página Inicial](/pt)

[Site policy](/pt/site-policy)
----------

1. [Política do site](/pt/site-policy)
2. [Políticas da empresa do GitHub](/pt/site-policy/github-company-policies)

Políticas da empresa do GitHub
==========

[Declaração do GitHub contra a escravidão moderna e o trabalho infantil](/pt/site-policy/github-company-policies/github-statement-against-modern-slavery-and-child-labor)
----------

[Declaração antissuborno do GitHub](/pt/site-policy/github-company-policies/github-anti-bribery-statement)
----------

[Compromisso de Cooperação GitHub GPL](/pt/site-policy/github-company-policies/github-gpl-cooperation-commitment)
----------

[Política de presentes e entretenimento do GitHub](/pt/site-policy/github-company-policies/github-gifts-and-entertainment-policy)
----------
