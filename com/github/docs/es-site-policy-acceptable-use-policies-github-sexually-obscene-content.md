Contenido sexualmente obsceno de GitHub - Documentación de GitHub(function(){
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
2. [Directivas de Uso Aceptable](/es/site-policy/acceptable-use-policies)
3. [Contenido Sexualmente Obsceno](/es/site-policy/acceptable-use-policies/github-sexually-obscene-content)

Contenido sexualmente obsceno de GitHub
==========

Copiar como Markdown

No toleramos el contenido asociado con la explotación o el abuso sexual de otra persona, incluso cuando [se trata de menores](/es/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse). No permitimos contenido sugerente o de temática sexual que tenga poco o ningún propósito que no sea el de solicitar una respuesta erótica o impactante, particularmente cuando ese contenido se amplifica por su ubicación en perfiles u otros contextos sociales. Esto incluye:

* Contenido pornográfico
* Imágenes íntimas no consentidas
* Representaciones gráficas de actos sexuales, incluidas fotografías, videos, animaciones, dibujos, imágenes generadas por computadora o contenido basado en texto

Reconocemos que no toda la desnudez o el contenido relacionado con la sexualidad es obsceno. Podemos permitir representaciones visuales y/o textuales en contextos artísticos, educativos, históricos o periodísticos, o en relación con la defensa de las víctimas. En algunos casos, un descargo de responsabilidad puede ayudar a comunicar el contexto del proyecto. Sin embargo, comprenda que podemos optar por limitar el contenido dando a los usuarios la opción de participar antes de verlo.
