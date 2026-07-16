Directivas de Privacidad - Documentación de GitHub(function(){
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

Contraer barra lateralExpandir barra lateral

Desplazar las migas de pan a la izquierda

1. [Inicio](/es)
2. [Política del sitio](/es/site-policy)
3. [Directivas de Privacidad](/es/site-policy/privacy-policies)

Desplazar las migas de pan hacia la derecha

[Site policy](/es/site-policy)
----------

Directivas de Privacidad
==========

[Declaración de privacidad general de GitHub](/es/site-policy/privacy-policies/github-general-privacy-statement)
----------

[Subprocesadores de GitHub](/es/site-policy/privacy-policies/github-subprocessors)
----------

[Cookies de GitHub](/es/site-policy/privacy-policies/github-cookies)
----------

[Aviso de privacidad de datos de GitHub global para candidatos](/es/site-policy/privacy-policies/github-candidate-privacy-policy)
----------
