Otras políticas del sitio - Documentación de GitHub(function(){
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
3. [Otras políticas del sitio](/es/site-policy/other-site-policies)

Desplazar las migas de pan hacia la derecha

[Site policy](/es/site-policy)
----------

Otras políticas del sitio
==========

[GitHub y controles comerciales](/es/site-policy/other-site-policies/github-and-trade-controls)
----------

[Política de usuarios fallecidos de GitHub](/es/site-policy/other-site-policies/github-deceased-user-policy)
----------

[Política del logotipo de GitHub](/es/site-policy/other-site-policies/github-logo-policy)
----------

[Política de eliminación del gobierno de GitHub](/es/site-policy/other-site-policies/github-government-takedown-policy)
----------

[Política de nombre de usuario de GitHub](/es/site-policy/other-site-policies/github-username-policy)
----------

[Directrices para solicitudes legales de datos de usuario](/es/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)
----------

[Directiva de recuperación de cuentas de GitHub](/es/site-policy/other-site-policies/github-account-recovery-policy)
----------
