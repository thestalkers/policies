Suplantación de GitHub - Documentación de GitHub(function(){
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
* [Directivas de Uso Aceptable](/es/site-policy/acceptable-use-policies)/
* [Suplantación](/es/site-policy/acceptable-use-policies/github-impersonation)

Suplantación de GitHub
==========

Copiar como Markdown

No puede tergiversar su identidad o su asociación con otra persona u organización. Esto incluye hacer cualquiera de las siguientes cosas de una manera que induzca a error o engañe a otros:

* Copiar el avatar de otro usuario u otra información de perfil personal
* Publicar contenido bajo la dirección de correo electrónico de otro usuario
* Usar un nombre de usuario, nombre de organización u otro espacio de nombres engañosamente similar
* Acceso a una cuenta u organización con el token o las credenciales de otro usuario
* De lo contrario, haciéndose pasar por otra persona u organización.

La suplantación de identidad es una forma de acoso y la violación de esta política puede dar lugar a la pérdida de acceso a su cuenta.

Tenga en cuenta que tener un nombre de usuario similar a otro no es necesariamente una suplantación de identidad. GitHub tendrá en cuenta el contexto. Por ejemplo, como en los casos que implican reclamaciones de [información falsa o desinformación](/es/site-policy/acceptable-use-policies/github-misinformation-and-disinformation), generalmente permitimos la parodia y la sátira que esté en línea con nuestras [Directivas de uso aceptable](/es/site-policy/acceptable-use-policies/github-acceptable-use-policies).
