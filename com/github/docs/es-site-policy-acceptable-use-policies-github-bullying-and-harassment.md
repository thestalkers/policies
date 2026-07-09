Intimidación y acoso de GitHub - Documentación de GitHub(function(){
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
3. [Intimidación y Acoso](/es/site-policy/acceptable-use-policies/github-bullying-and-harassment)

Intimidación y acoso de GitHub
==========

Copiar como Markdown

No toleramos el acoso, la intimidación o el abuso de ningún tipo, ya sea directamente o animando a otros a participar en la conducta prohibida. Esto incluye:

* Ataques personales dirigidos
* la acumulación o la organización de actividades [perturbadoras](/es/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users) de cualquier modo que pueda ser constitutivo de abuso
* Seguir a otro usuario por la plataforma de una manera que provoque intimidación
* Hacer insinuaciones o comentarios sexuales dirigidos a otra persona
* Participar falsamente en una conversación de una manera que instiga el conflicto o socava la discusión sincera
* Crear cuentas alternativas específicamente para evadir la acción de moderación tomada por el personal o los usuarios de GitHub

Tenga en cuenta que no todas las conductas no deseadas se consideran necesariamente acoso. Por ejemplo, no estar de acuerdo con otro usuario o rechazar sus comentarios puede no alcanzar el nivel de acoso en nuestra plataforma. Además, compartir críticas de figuras o proyectos públicos, o temas de interés público, no necesariamente se incluye en esta política. Sin embargo, lo alentamos a que tenga en cuenta cómo interactúa con otros usuarios y la plataforma, ya que esta actividad aún puede violar nuestra restricción sobre la interrupción de la experiencia de otros usuarios.
