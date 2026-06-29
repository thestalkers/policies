Información errónea y desinformación de GitHub - Documentación de GitHub(function(){
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
* [Directiva de desinformación](/es/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)

Información errónea y desinformación de GitHub
==========

Copiar como Markdown

No puede publicar contenido que presente una visión distorsionada de la realidad, ya sea inexacto o falso (información errónea) o intencionalmente engañoso (desinformación), cuando dicho contenido pueda causar daño al público o interferir con oportunidades justas e equitativas. para que todos participen en una sociedad libre y abierta. Esto puede incluir:

* Afirmaciones médicas inexactas o sin respaldo científico que ponen en peligro la salud o la seguridad pública
* Medios manipulados, ya sean de audio o visuales, que puedan inducir a error o engañar de una manera que pueda dañar el interés público
* Contenido falso o engañoso que probablemente interfiera con la capacidad de una persona para participar en actividades cívicas
* Afirmaciones sin fundamento que podrían promover el odio o el acoso dirigido a grupos específicos de personas

Fomentamos la participación activa en la expresión de ideas, perspectivas y experiencias y es posible que no estemos en posición de disputar relatos u observaciones personales. Por lo general, permitimos la parodia y la sátira siempre que sean acordes con nuestras [Directivas de uso aceptable](/es/site-policy/acceptable-use-policies/github-acceptable-use-policies) y consideramos que el contexto es importante en la forma en que se recibe y entiende la información. Al revisar el contenido bajo esta política, GitHub considerará el impacto de varios factores que pueden ayudar a orientar al espectador, como si el contenido se ha proporcionado con descargos de responsabilidad claros, citas de fuentes creíbles o incluye otros detalles que aclaran la precisión de la información que se comparte.
