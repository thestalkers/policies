Envío de solicitudes de eliminación de contenido - Documentación de GitHub(function(){
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
3. [Políticas de eliminación de contenido](/es/site-policy/content-removal-policies)
4. [Envío de solicitudes de eliminación de contenido](/es/site-policy/content-removal-policies/submitting-content-removal-requests)

Desplazar las migas de pan hacia la derecha

[Site policy](/es/site-policy)
----------

Envío de solicitudes de eliminación de contenido
==========

Copiar como Markdown

En este artículo
----------

* [Política de eliminación de DMCA](#dmca-takedown-policy)
* [Política de marcas registradas de GitHub](#github-trademark-policy)
* [Política de eliminación de información privada de GitHub](#github-private-information-removal-policy)

Entendemos que el contenido con derechos de autor, marca registrada o privado puede publicarse en GitHub, ya sea accidentalmente o a propósito, a veces en repositorios que no son de su propiedad. Debido a que la naturaleza de este contenido varía y debido a las diferentes leyes aplicables, cada categoría tiene sus propios requisitos de informes distintos descritos en nuestras políticas.

Si desea solicitar que se elimine contenido de GitHub, tómese un tiempo para familiarizarse con cada una de estas políticas y sus respectivos requisitos de informes antes de enviar un informe. Si recibimos un informe incompleto, tendremos que solicitar aclaraciones o revisiones y deberá volver a enviar un informe revisado.

Tenga en cuenta que no podemos ayudarlo a determinar qué política es adecuada para su situación específica. Si revisó las políticas a continuación y todavía tiene preguntas sobre si el contenido debe informarse o no como derechos de autor, marca comercial o información privada, le recomendamos consultar con un asesor legal independiente.

[Política de eliminación de DMCA](#dmca-takedown-policy)
----------

La [directiva de eliminación de contenidos de DMCA](/es/site-policy/content-removal-policies/dmca-takedown-policy) se puede usar para denunciar contenido que crea que infringe un derecho de autor que le pertenece a usted o a su organización. Una vez que haya revisado la directiva, es posible que también desee revisar nuestra [Guía para enviar una notificación de eliminación de la DMCA](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) antes de enviar una denuncia.

[Política de marcas registradas de GitHub](#github-trademark-policy)
----------

La [directiva de marcas comerciales de GitHub](/es/site-policy/content-removal-policies/github-trademark-policy) puede usarse para denunciar contenido que parezca que usa el nombre de su empresa o negocio, su logotipo u otros materiales protegidos por marcas comerciales de una manera que pueda inducir a error o confundir a otras personas con respecto a su marca o afiliación empresarial.

[Política de eliminación de información privada de GitHub](#github-private-information-removal-policy)
----------

La [directiva de eliminación de información privada de GitHub](/es/site-policy/content-removal-policies/github-private-information-removal-policy) se puede usar para denunciar datos que son privados (confidenciales y que presentan un riesgo de seguridad), pero que no están necesariamente protegidos por derechos de autor o marcas comerciales.

Los usuarios de la India pueden [ponerse en contacto con el oficial de quejas de GitHub](https://support.github.com/contact/india-grievance-officer).
