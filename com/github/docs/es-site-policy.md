Documentación de la directiva del sitio - Documentación de GitHub(function(){
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

1. [Inicio](/es)
2. [Política del sitio](/es/site-policy)

Scroll breadcrumbs right

[Site policy](/es/site-policy)
----------

Documentación de la directiva del sitio
==========

Consulte los términos del servicio, las directivas de uso aceptable, las prácticas de privacidad, los procedimientos de eliminación de contenido y otras directivas del sitio de GitHub.

[Información general](/site-policy/github-terms/github-terms-of-service)

Recomendado
----------

[### Términos de Servicio de GitHub ###](/es/free-pro-team@latest/site-policy/github-terms/github-terms-of-service)[### Declaración de privacidad general de GitHub ###](/es/free-pro-team@latest/site-policy/privacy-policies/github-general-privacy-statement)[### Políticas de uso aceptable de GitHub ###](/es/free-pro-team@latest/site-policy/acceptable-use-policies/github-acceptable-use-policies)

Artículos
----------

Categoría: Todas las categorías

[Review product and program terms ### Acuerdo de desarrollador registrado de GitHub ###](/es/site-policy/github-terms/github-registered-developer-agreement)[Review product and program terms ### Acuerdo de uso educativo de GitHub ###](/es/site-policy/github-terms/github-educational-use-agreement)[Review product and program terms ### Acuerdo para desarrolladores del Mercado GitHub ###](/es/site-policy/github-terms/github-marketplace-developer-agreement)[Follow acceptable use policies ### Apelación y restablecimiento de GitHub ###](/es/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)[Review privacy and security policies ### Aviso de privacidad de datos de GitHub global para candidatos ###](/es/site-policy/privacy-policies/github-candidate-privacy-policy)[Review product and program terms ### Código de conducta de eventos de GitHub ###](/es/site-policy/github-terms/github-event-code-of-conduct)[Review product and program terms ### Código de conducta de la comunidad de GitHub ###](/es/site-policy/github-terms/github-community-code-of-conduct)[Review company and general policies ### Compromiso de cooperación de GitHub GPL ###](/es/site-policy/github-company-policies/github-gpl-cooperation-commitment)[Review product and program terms ### Condiciones de servicio corporativas de GitHub ###](/es/site-policy/github-terms/github-corporate-terms-of-service)

Mostrar 1-9 de 57

[Previous]()[1](#1)[2](#2)[3](#3)[4](#4)[5](#5)[6](#6)[7](#7)[Next](#2)
