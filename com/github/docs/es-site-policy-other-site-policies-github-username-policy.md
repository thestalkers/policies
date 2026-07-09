Política de nombre de usuario de GitHub - Documentación de GitHub(function(){
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
2. [Otras políticas del sitio](/es/site-policy/other-site-policies)
3. [Política de nombre de usuario de GitHub](/es/site-policy/other-site-policies/github-username-policy)

Política de nombre de usuario de GitHub
==========

Copiar como Markdown

En este artículo
----------

* [¿Qué pasa si el nombre de usuario que quiero ya está en uso?](#what-if-the-username-i-want-is-already-taken)
* [Política de marcas registradas](#trademark-policy)
* [Nombre Política de ocupación ilegal](#name-squatting-policy)

Los nombres de cuenta de GitHub están disponibles por orden de llegada y están destinados a un uso inmediato y activo.

[¿Qué pasa si el nombre de usuario que quiero ya está en uso?](#what-if-the-username-i-want-is-already-taken)
----------

Tenga en cuenta que no toda la actividad en GitHub es públicamente visible; las cuentas sin actividad visible pueden estar en uso activo.

No aceptamos solicitudes para liberar, transferir ni reclamar nombres de usuario sobre la base de que parecen inactivos o que parece que no se utilizan. Si el nombre de usuario que desea ya está reclamado, deberá seleccionar otro nombre disponible distinto a menos que envíe una queja como marca comercial tal como se describe a continuación.

Si el nombre de usuario que desea ya ha sido reclamado, considere otros nombres o variaciones únicas. Puede usar un número, un guion o una forma alternativa de escribir ese nombre para encontrar un nombre de usuario de su preferencia que aún esté disponible.

[Política de marcas registradas](#trademark-policy)
----------

Si cree que la cuenta de alguien está infringiendo sus derechos de marca comercial, encontrará más información sobre cómo presentar una queja sobre marca comercial en nuestra página [TÍTULO AUTOMÁTICO](/es/site-policy/content-removal-policies/github-trademark-policy). Las quejas válidas sobre marcas comerciales son las únicas solicitudes que revisamos para una posible liberación de un nombre de usuario ya reclamado.

[Nombre Política de ocupación ilegal](#name-squatting-policy)
----------

GitHub prohíbe la usurpación de nombres de cuenta, y los nombres de cuenta no pueden reservarse ni mantenerse inactivamente para uso futuro. Las cuentas que infrinjan esta política de usurpación de nombres pueden eliminarse o cambiarse de nombre sin previo aviso. Los intentos de vender, comprar o solicitar otras formas de pago a cambio de nombres de cuenta están prohibidos y pueden resultar en la suspensión permanente de la cuenta.
