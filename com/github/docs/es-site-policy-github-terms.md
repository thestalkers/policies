Términos de GitHub - Documentación de GitHub(function(){
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

1. [Política del sitio](/es/site-policy)
2. [Términos de GitHub](/es/site-policy/github-terms)

Términos de GitHub
==========

[Términos de Servicio de GitHub](/es/site-policy/github-terms/github-terms-of-service)
----------

[Condiciones de servicio corporativas de GitHub](/es/site-policy/github-terms/github-corporate-terms-of-service)
----------

[Términos de GitHub para productos y funciones adicionales](/es/site-policy/github-terms/github-terms-for-additional-products-and-features)
----------

[Directrices de la comunidad de GitHub](/es/site-policy/github-terms/github-community-guidelines)
----------

[Código de conducta de la comunidad de GitHub](/es/site-policy/github-terms/github-community-code-of-conduct)
----------

[Términos de licencia de la versión preliminar de GitHub](/es/site-policy/github-terms/github-pre-release-license-terms)
----------

[Versiones preliminares sujetas al acuerdo de protección de datos en GitHub](/es/site-policy/github-terms/github-dpa-previews)
----------

[Patrocinadores de GitHub Términos adicionales](/es/site-policy/github-terms/github-sponsors-additional-terms)
----------

[Acuerdo de desarrollador registrado de GitHub](/es/site-policy/github-terms/github-registered-developer-agreement)
----------

[Condiciones de servicio del Mercado GitHub](/es/site-policy/github-terms/github-marketplace-terms-of-service)
----------

[Acuerdo para desarrolladores del Mercado GitHub](/es/site-policy/github-terms/github-marketplace-developer-agreement)
----------

[Términos del programa de investigación de GitHub](/es/site-policy/github-terms/github-research-program-terms)
----------

[Términos y condiciones de las aplicaciones de código abierto de GitHub](/es/site-policy/github-terms/github-open-source-applications-terms-and-conditions)
----------

[Términos del evento de GitHub](/es/site-policy/github-terms/github-event-terms)
----------

[Código de conducta de eventos de GitHub](/es/site-policy/github-terms/github-event-code-of-conduct)
----------

[Acuerdo de uso educativo de GitHub](/es/site-policy/github-terms/github-educational-use-agreement)
----------

[Directiva para desarrolladores de extensiones de GitHub Copilot](/es/site-policy/github-terms/github-copilot-extension-developer-policy)
----------

[Contrato del Programa de análisis de secretos de GitHub para Partners](/es/site-policy/github-terms/github-secret-scanning-partner-program-agreement)
----------
