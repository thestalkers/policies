Política de eliminación del gobierno de GitHub - Documentación de GitHub(function(){
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
3. [Política de eliminación del gobierno de GitHub](/es/site-policy/other-site-policies/github-government-takedown-policy)

Política de eliminación del gobierno de GitHub
==========

Copiar como Markdown

En este artículo
----------

* [¿Qué es esto?](#what-is-this)
* [Cómo presentar una solicitud gubernamental de eliminación de contenido](#how-to-submit-a-government-takedown-request)
* [¿Qué sucede cuando recibimos una solicitud de eliminación completa de un gobierno?](#what-happens-when-we-receive-a-complete-takedown-request-from-a-government)
* [¿Por qué publicamos avisos de eliminación?](#why-do-we-publicly-post-takedown-notices)
* [¿Qué significa si publicamos un aviso en nuestro repositorio de eliminaciones gubernamentales?](#what-does-it-mean-if-we-post-a-notice-in-our-gov-takedowns-repository)
* [Eliminaciones del gobierno basadas en violaciones de los Términos de servicio de GitHub](#government-takedowns-based-on-violations-of-githubs-terms-of-service)
* [Informes de transparencia](#transparency-reporting)

[¿Qué es esto?](#what-is-this)
----------

De vez en cuando, GitHub recibe solicitudes de gobiernos para eliminar contenido que ha sido declarado ilegal en su jurisdicción local. Aunque es posible que no siempre estemos de acuerdo con esas leyes, es posible que debamos bloquear contenido si recibimos una solicitud completa de un funcionario del gobierno para que nuestros usuarios en esa jurisdicción puedan continuar teniendo acceso a GitHub para colaborar y crear software.

[Cómo presentar una solicitud gubernamental de eliminación de contenido](#how-to-submit-a-government-takedown-request)
----------

Si usted es un funcionario gubernamental y desea solicitar la eliminación de contenido conforme a esta política, puede enviar su solicitud a través de nuestro [Formulario de Solicitudes de Retirada Gubernamental](https://support.github.com/contact/government-takedown).

Para que una solicitud se considere completa, esta debe

* Provenir de una agencia gubernamental oficial relevante
* Identificar contenido ilegal
* Especificar la fuente de ilegalidad en esa jurisdicción (ley u orden judicial).

[¿Qué sucede cuando recibimos una solicitud de eliminación completa de un gobierno?](#what-happens-when-we-receive-a-complete-takedown-request-from-a-government)
----------

Cuando recibimos un aviso de una agencia gubernamental oficial relevante que identifica contenido ilegal y especifica la fuente de la ilegalidad, nosotros

* Notificar a los usuarios afectados sobre el contenido específico que supuestamente infringe la ley y que se trata de una solicitud de eliminación legal
* Permitir a los usuarios afectados apelar la decisión como parte de esa notificación
* Limitar el alcance geográfico de la eliminación cuando sea posible e incluirlo como parte de la notificación
* Publicamos la solicitud oficial que condujo a la eliminación en nuestro [repositorio público de eliminaciones por parte del gobierno](https://github.com/github/gov-takedowns).

[¿Por qué publicamos avisos de eliminación?](#why-do-we-publicly-post-takedown-notices)
----------

Nos preocupa la censura en Internet y creemos que la transparencia en un nivel específico y continuo es esencial para una buena gobernanza. Al publicar los avisos, podemos informar mejor al público sobre qué contenido se retiene de GitHub y por qué. Publicamos avisos de eliminación para documentar su potencial para enfriar el discurso.

[¿Qué significa si publicamos un aviso en nuestro repositorio de eliminaciones gubernamentales?](#what-does-it-mean-if-we-post-a-notice-in-our-gov-takedowns-repository)
----------

Significa que recibimos el aviso en la fecha indicada. *No* significa que el contenido sea ilegal o incorrecto. *No* significa que el usuario identificado en el aviso haya hecho algo mal. No hacemos ni implicamos ningún juicio sobre el mérito de las afirmaciones que hacen. Publicamos estos avisos y solicitudes solo con fines informativos.

[Eliminaciones del gobierno basadas en violaciones de los Términos de servicio de GitHub](#government-takedowns-based-on-violations-of-githubs-terms-of-service)
----------

En algunos casos, GitHub recibe informes de funcionarios gubernamentales sobre violaciones de los Términos de servicio de GitHub. Procesamos esas violaciones como procesaríamos una violación de los Términos de servicio informada por cualquier otra persona. Sin embargo, notificamos a los usuarios afectados que el informe proviene de un gobierno y, como en cualquier otro caso, les damos la oportunidad de apelar.

[Informes de transparencia](#transparency-reporting)
----------

Además de publicar avisos gubernamentales de eliminación en nuestro repositorio `github/gov-takedowns`, informamos sobre ellos en nuestro informe de transparencia. También rastreamos e informamos en nuestro informe de transparencia sobre eliminaciones gubernamentales basadas en violaciones de los Términos de servicio de GitHub.
