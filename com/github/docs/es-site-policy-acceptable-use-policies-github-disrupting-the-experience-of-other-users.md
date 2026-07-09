GitHub interrumpiendo la experiencia de otros usuarios - Documentación de GitHub(function(){
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
3. [Alteración de la experiencia de otros usuarios](/es/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)

GitHub interrumpiendo la experiencia de otros usuarios
==========

Copiar como Markdown

Ser parte de una comunidad incluye reconocer cómo su comportamiento afecta a los demás y participar en interacciones significativas y productivas con las personas y la plataforma en la que confían.

No permitimos comportamientos que interrumpan significativa o continuamente la experiencia de otros usuarios. Esto incluye:

* Publicar comentarios fuera de tema
* Abrir propuestas vacías o sin sentido o solicitudes de incorporación de cambios
* Protagonizar y/o seguir cuentas o repositorios en gran volumen en un corto periodo de tiempo
* Crear revisiones de código sin sentido o irrelevantes
* Interactuar con las funciones de la plataforma de una manera que genera notificaciones excesivas para otros usuarios
* Usar cualquier otra característica de la plataforma de una manera que genere interrupciones

Si bien alentamos a los mantenedores a moderar sus propios proyectos de forma individual, el personal de GitHub puede tomar medidas restrictivas adicionales contra las cuentas que se involucran en este tipo de comportamientos.

Tenga en cuenta que la conducta anterior también puede infringir otras restricciones de nuestras [Directivas de uso aceptable](/es/site-policy/acceptable-use-policies/github-acceptable-use-policies). Por ejemplo, según la naturaleza y la gravedad de la actividad, puede llegar al nivel de [acoso y agresión](/es/site-policy/acceptable-use-policies/github-bullying-and-harassment).
