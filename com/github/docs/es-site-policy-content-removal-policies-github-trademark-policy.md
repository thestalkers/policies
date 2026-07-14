Política de marcas registradas de GitHub - Documentación de GitHub(function(){
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

Collapse sidebarExpand sidebar

Scroll breadcrumbs left

1. [Inicio](/es)
2. [Política del sitio](/es/site-policy)
3. [Políticas de eliminación de contenido](/es/site-policy/content-removal-policies)
4. [Política de marcas registradas de GitHub](/es/site-policy/content-removal-policies/github-trademark-policy)

Scroll breadcrumbs right

[Site policy](/es/site-policy)
----------

Política de marcas registradas de GitHub
==========

Copiar como Markdown

En este artículo
----------

* [¿Qué es una infracción de la política de marcas comerciales de GitHub?](#what-is-a-github-trademark-policy-violation)
* [¿Qué no es una infracción de la política de marcas comerciales de GitHub?](#what-is-not-a-github-trademark-policy-violation)
* [¿Cómo responde GitHub a las infracciones de la política de marcas comerciales denunciadas?](#how-does-github-respond-to-reported-trademark-policy-violations)
* [¿Cómo denuncio una infracción de la política de marcas comerciales?](#how-do-i-report-a-trademark-policy-violation)
* [¿Qué información se requiere al denunciar infracciones de la política de marcas comerciales?](#what-information-is-required-when-reporting-trademark-policy-violations)

[¿Qué es una infracción de la política de marcas comerciales de GitHub?](#what-is-a-github-trademark-policy-violation)
----------

El uso de una empresa o nombre comercial, logotipo u otros materiales protegidos por marcas comerciales de una manera que pueda inducir a error o confundir a otros con respecto a su marca o afiliación comercial puede considerarse una violación de la política de marcas comerciales.

[¿Qué no es una infracción de la política de marcas comerciales de GitHub?](#what-is-not-a-github-trademark-policy-violation)
----------

El uso de la marca comercial de otra persona de una manera que no tenga nada que ver con el producto o servicio para el que se otorgó la marca comercial no constituye una infracción de la política de marcas comerciales. Los nombres de usuario de GitHub están disponibles por orden de llegada y no se pueden reservar. Una cuenta de GitHub con un nombre de usuario que resulta ser el mismo que una marca comercial registrada no es, en sí mismo, necesariamente una violación de nuestra política de marcas comerciales.

[¿Cómo responde GitHub a las infracciones de la política de marcas comerciales denunciadas?](#how-does-github-respond-to-reported-trademark-policy-violations)
----------

Cuando recibimos informes de violaciones de la política de marcas comerciales de los titulares de registros de marcas comerciales internacionales o federales, revisamos la cuenta y podemos tomar las siguientes medidas:

* Cuando exista una clara intención de engañar a otros mediante el uso no autorizado de una marca registrada, GitHub suspenderá la cuenta y notificará al titular de la cuenta.
* Cuando determinamos que una cuenta parece confundir a los usuarios, pero no se hace pasar deliberadamente como el bien o servicio de marca registrada, le damos al titular de la cuenta la oportunidad de aclarar cualquier posible confusión. También podemos publicar un nombre de usuario para el uso activo del titular de la marca.

[¿Cómo denuncio una infracción de la política de marcas comerciales?](#how-do-i-report-a-trademark-policy-violation)
----------

Los titulares de marcas registradas pueden denunciar posibles infracciones de la directiva de marcas comerciales a GitHub mediante [Enviar un informe de infracción de la directiva de marcas comerciales](https://support.github.com/contact/trademark-policy). Por favor, use el formulario de contacto y envíe solicitudes relacionadas con marcas registradas utilizando la dirección de correo electrónico de su empresa e incluya toda la información solicitada a continuación para ayudar a acelerar nuestra respuesta. También asegúrese de describirnos claramente por qué la cuenta puede causar confusión con su marca o cómo la cuenta puede diluir o empañar su marca.

[¿Qué información se requiere al denunciar infracciones de la política de marcas comerciales?](#what-information-is-required-when-reporting-trademark-policy-violations)
----------

Para investigar las infracciones de la política de marcas comerciales, proporcione toda la siguiente información:

* Nombre de usuario de la cuenta denunciada

* El nombre de su empresa

* La cuenta de GitHub de su empresa (si la hay)

* Sitio Web de la empresa

* Su palabra registrada, símbolo, etc.

* Número de registro de marca

* Oficina de registro de marcas (por ejemplo, USPTO)

* Descripción de la confusión (p. ej., hacerse pasar por su empresa, incluidas descripciones específicas de contenido o comportamiento)

* Acción solicitada (p. ej., eliminación de la cuenta infractora o transferencia del nombre de usuario registrado a una cuenta de empresa existente)

* Incluya la siguiente declaración: «Creo de buena fe que el uso de la marca comercial descrita anteriormente no está autorizado por su propietario, su representante o la ley. He tomado en consideración el nominativo y otros usos justos".

* Incluya también la siguiente declaración: «Juro, bajo pena de perjurio, que la información contenida en esta notificación es exacta y que soy el propietario de la marca comercial o estoy autorizado para actuar en nombre del propietario de un derecho exclusivo que supuestamente se infringe».

* Incluya su firma física o electrónica.

* Nota: Se requiere un número de registro de marca comercial federal o internacional. Si el nombre que está denunciando **no** es una marca registrada (p. ej., un organismo gubernamental u organización sin ánimo de lucro), facilítenos:

  * Tu nombre y apellido
  * Cargo
  * Dirección
  * Teléfono
  * Correo electrónico (debe ser del dominio de la empresa)
