Divulgación coordinada de vulnerabilidades de seguridad - Documentación de GitHub(function(){
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
3. [Políticas de seguridad](/es/site-policy/security-policies)
4. [Divulgación coordinada de vulnerabilidades de seguridad](/es/site-policy/security-policies/coordinated-disclosure-of-security-vulnerabilities)

Scroll breadcrumbs right

[Site policy](/es/site-policy)
----------

Divulgación coordinada de vulnerabilidades de seguridad
==========

Copiar como Markdown

Queremos mantener GitHub seguro para todos. Si ha descubierto una vulnerabilidad de seguridad en GitHub, apreciamos su ayuda para comunicárnosla de manera coordinada.

[Programa de recompensas](#bounty-program)
----------

Al igual que otras grandes empresas de software, GitHub ofrece una recompensa por errores para interactuar mejor con los investigadores de seguridad. La idea es sencilla: los piratas informáticos y los investigadores de seguridad (como usted) encuentran vulnerabilidades y las notifican a través de nuestro proceso de revelación coordinado. Luego, para reconocer el esfuerzo significativo que estos investigadores a menudo realizan al buscar errores, los recompensamos con algo de dinero en efectivo.

Consulte el sitio [Programa de recompensa por errores de GitHub](https://bounty.github.com) para obtener más información sobre las recompensas y también los términos del completo [Directiva legal Safe Harbor](/es/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor).
