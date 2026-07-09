Políticas de eliminación de contenido - Documentación de GitHub(function(){
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
2. [Políticas de eliminación de contenido](/es/site-policy/content-removal-policies)

Políticas de eliminación de contenido
==========

[Envío de solicitudes de eliminación de contenido](/es/site-policy/content-removal-policies/submitting-content-removal-requests)
----------

[Política de eliminación de DMCA](/es/site-policy/content-removal-policies/dmca-takedown-policy)
----------

[Política de eliminación de información privada de GitHub](/es/site-policy/content-removal-policies/github-private-information-removal-policy)
----------

[Política de marcas registradas de GitHub](/es/site-policy/content-removal-policies/github-trademark-policy)
----------

[Guía para enviar una contranotificación de DMCA](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)
----------

[Guía para enviar un aviso de eliminación de DMCA](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)
----------
