GitHub Amenazas de violencia y contenido violento gratuito - Documentación de GitHub(function(){
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
* [Amenazas de violencia y contenido violento gratuito](/es/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)

GitHub Amenazas de violencia y contenido violento gratuito
==========

Copiar como Markdown

No puede usar GitHub para organizar, promover, alentar, amenazar o incitar a actos de violencia. No puede publicar contenido que represente o glorifique la violencia o el daño físico contra seres humanos o animales. Esto incluye:

* Amenazar a otro individuo o grupo con abuso, daño, violencia sexual o muerte
* Publicar texto, imágenes o contenido de audio que glorifique o contenga una representación gráfica de la violencia hacia uno mismo, otra persona, grupo o animal.
* Animar a otra persona a que se autolesione

No permitimos que se publique contenido violento de manera indiscriminada o de una manera que sea difícil de evitar para otros usuarios, como un avatar de perfil o un comentario sobre un problema. Sin embargo, entendemos que puede haber razones legítimas para publicar contenido violento, como con fines educativos o documentales, trabajos creativos o representaciones de eventos históricos. En esos casos, una advertencia clara o un descargo de responsabilidad pueden ayudar a los usuarios a tomar una decisión informada sobre si desean o no interactuar con dicho contenido. Aún así, GitHub puede decidir limitar la visibilidad de dicho contenido a aquellos que opten por participar.
