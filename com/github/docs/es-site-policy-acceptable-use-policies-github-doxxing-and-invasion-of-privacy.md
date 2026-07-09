GitHub Doxxing e invasión de la privacidad - Documentación de GitHub(function(){
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
3. [Divulgación de información personal («doxxing») e invasión de la privacidad](/es/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)

GitHub Doxxing e invasión de la privacidad
==========

Copiar como Markdown

No publiques información personal de otras personas. Esto incluye:

* Direcciones de correo electrónico personales y privadas
* Números de teléfono
* Direcciones físicas u otra información de ubicación privada
* Información de cuenta bancaria o números de tarjeta de crédito
* Números de Seguro Social/Identidad Nacional
* contraseñas
* Información de voto
* Información médica y datos biométricos personales
* Otra información privada que pueda representar un riesgo de seguridad o protección

Podemos considerar otra información, como fotos o videos que se tomaron o distribuyeron sin el consentimiento del sujeto, como una invasión de la privacidad, especialmente cuando dicho material presenta un riesgo de seguridad para el sujeto, como en el caso de intimidación o acoso.

GitHub tendrá en cuenta el contexto y si el contenido informado está disponible públicamente en otro lugar. Tenga en cuenta, sin embargo, que aunque compartir contenido disponible públicamente puede no ser una vulneración de esta directiva, si la información se comparte con la intención de acosar o incitar a otro comportamiento abusivo, puede infringir nuestra prohibición de [acoso y agresión](/es/site-policy/acceptable-use-policies/github-bullying-and-harassment).

Para obtener más información o para saber cómo denunciar una infracción, consulte nuestra [Directiva de eliminación de información privada](/es/site-policy/content-removal-policies/github-private-information-removal-policy) y nuestras instrucciones para [denunciar casos de abuso](/es/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam).
