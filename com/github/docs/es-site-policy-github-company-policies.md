Políticas de empresa de GitHub - Documentación de GitHub(function(){
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

[Inicio](/es)

[Site policy](/es/site-policy)
----------

* [Política del sitio](/es/site-policy)/
* [Políticas de empresa de GitHub](/es/site-policy/github-company-policies)

Políticas de empresa de GitHub
==========

[Declaración de GitHub contra la esclavitud moderna y el trabajo infantil](/es/site-policy/github-company-policies/github-statement-against-modern-slavery-and-child-labor)
----------

[Declaración contra el soborno de GitHub](/es/site-policy/github-company-policies/github-anti-bribery-statement)
----------

[Compromiso de cooperación de GitHub GPL](/es/site-policy/github-company-policies/github-gpl-cooperation-commitment)
----------

[Política de obsequios y entretenimiento de GitHub](/es/site-policy/github-company-policies/github-gifts-and-entertainment-policy)
----------
