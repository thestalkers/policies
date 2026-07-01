Política de usuarios fallecidos de GitHub - Documentación de GitHub(function(){
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
* [Otras políticas del sitio](/es/site-policy/other-site-policies)/
* [Política de usuarios fallecidos de GitHub](/es/site-policy/other-site-policies/github-deceased-user-policy)

Política de usuarios fallecidos de GitHub
==========

Copiar como Markdown

En caso de que fallezca un usuario de GitHub, podemos trabajar con una persona autorizada para determinar qué sucede con el contenido de la cuenta.

Si usted es un pariente cercano, un [sucesor previamente designado](/es/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/maintaining-ownership-continuity-of-your-personal-accounts-repositories) u otra persona autorizada (que podría incluir un colaborador o socio comercial) de un usuario fallecido y desea realizar una solicitud con respecto a su cuenta, puede ponerse en contacto con nosotros mediante el [Portal de soporte técnico de GitHub](https://support.github.com/). En el portal, haga clic en **Ponerse en contacto con nosotros** y proporcione la siguiente información en el mensaje:

* Denominación
* Información de Contacto
* Nombre del titular de la cuenta fallecido
* Nombre de usuario de GitHub del titular de la cuenta fallecido
* Su relación con el titular de la cuenta fallecido (incluya si ha sido designado como sucesor de la cuenta en GitHub.com)
* Si se designa como sucesor de la cuenta, el nombre de usuario de su cuenta de GitHub
* Qué acción está buscando (por ejemplo, transferir repositorios públicos, cancelar la facturación a cuenta)

Una vez que hayamos recibido su solicitud, podemos realizar un seguimiento con una solicitud de información adicional, como una copia de su identificación con foto, una copia del certificado de defunción y documentación que confirme que está autorizado para actuar en relación con la cuenta del usuario fallecido, para verificar que estamos debidamente autorizados para procesar su solicitud.

Tenga en cuenta que la información que proporciona en su solicitud se recopila de acuerdo con nuestra [Declaración de Privacidad](/es/site-policy/privacy-policies/github-privacy-statement) y conservaremos la información solo según sea necesario para cumplir nuestras obligaciones legales y resolver litigios.
