Compromiso de cooperación de GitHub GPL - Documentación de GitHub(function(){
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
3. [Políticas de empresa de GitHub](/es/site-policy/github-company-policies)
4. [Compromiso de cooperación de GitHub GPL](/es/site-policy/github-company-policies/github-gpl-cooperation-commitment)

Desplazar las migas de pan hacia la derecha

[Site policy](/es/site-policy)
----------

Compromiso de cooperación de GitHub GPL
==========

Copiar como Markdown

Este compromiso se refiere a las contribuciones de GitHub a Git, el kernel de Linux y otros programas bajo licencias cubiertas (desplácese hasta el final para ver las definiciones).

Basamos nuestra declaración en la [plantilla](https://github.com/gplcc/gplcc/blob/master/Company/GPL%20Cooperation%20Commitment-Company-Template.md) para empresas. Consulte el [sitio de compromiso de cooperación con GPL](https://gplcc.github.io/gplcc/) para saber cómo otras empresas, personas y proyectos pueden adoptar este compromiso.

[Nuestro compromiso](#our-commitment)
----------

Antes de presentar o continuar procesando cualquier procedimiento legal o reclamo (que no sea una Acción defensiva) que surja de la rescisión de una Licencia cubierta, GitHub se compromete a extender a la persona o entidad ("usted") acusada de violar la Licencia cubierta las siguientes disposiciones con respecto a cura y restablecimiento, tomado de GPL versión 3. Como se usa aquí, el término 'esta Licencia' se refiere a la Licencia cubierta específica que se está aplicando.

Sin embargo, si deja de violar esta Licencia, su licencia de un titular de derechos de autor en particular se restablece (a) provisionalmente, a menos y hasta que el titular de los derechos de autor rescinda su licencia de manera explícita y definitiva, y (b) permanentemente, si el titular de los derechos de autor no cumple. para notificarle de la violación por algún medio razonable antes de 60 días después del cese.

Además, su licencia de un titular de derechos de autor en particular se restablece permanentemente si el titular de derechos de autor le notifica la violación por algún medio razonable, esta es la primera vez que recibe un aviso de violación de esta Licencia (para cualquier trabajo) de ese titular de derechos de autor, y subsana la infracción antes de los 30 días posteriores a la recepción de la notificación.

GitHub pretende que este Compromiso sea irrevocable, vinculante y ejecutable contra GitHub y los cesionarios o sucesores de los derechos de autor de GitHub.

GitHub puede modificar este Compromiso mediante la publicación de una nueva edición en esta página o en una ubicación posterior.

Definiciones

'Licencia amparada' hace referencia a la Licencia pública general de GNU, versión 2 (GPLv2), la Licencia pública general reducida de GNU, versión 2.1 (LGPLv2.1) o la Licencia pública general de biblioteca de GNU, versión 2 (LGPLv2), todas publicadas por la Fundación de Software Libre.

'Acción defensiva' se refiere a un procedimiento legal o reclamo que GitHub presenta contra usted en respuesta a un procedimiento o reclamo anterior iniciado por usted o su afiliado.

'GitHub' significa GitHub, Inc. y sus subsidiarias.

Este trabajo está disponible bajo una licencia Creative Commons Attribution-ShareAlike 4.0 International.
