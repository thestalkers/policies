GitHub Doxxing e invasão de privacidade - Documentos do GitHub(function(){
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

[Página Inicial](/pt)

[Site policy](/pt/site-policy)
----------

* [Política do site](/pt/site-policy)/
* [Políticas de Uso Aceitável](/pt/site-policy/acceptable-use-policies)/
* [Vazamento e invasão de privacidade](/pt/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)

GitHub Doxxing e invasão de privacidade
==========

Copiar como Markdown

Não publique informações pessoais de outras pessoas. Isso inclui:

* Endereços de e-mail pessoais e privados
* Telefones
* Endereços físicos ou outras informações de localização privada
* Informações da conta bancária ou números de cartão de crédito
* Números do Seguro Social/Identidade Nacional
* Senhas
* Informações do eleitor
* Informações médicas e dados biométricos pessoais
* Outras informações privadas que podem representar um risco de segurança

Podemos considerar outras informações, como fotos ou vídeos que foram feitos ou distribuídos sem o consentimento do sujeito, como uma invasão de privacidade, especialmente quando tal material representa um risco à segurança do sujeito, como no caso de intimidação ou assédio.

O GitHub levará em consideração o contexto, bem como se o conteúdo relatado está disponível publicamente em outro lugar. Observe, no entanto, que, embora o compartilhamento de conteúdo disponível publicamente possa não ser uma violação desta política, se as informações forem compartilhadas com a intenção de assediar ou incitar outro comportamento abusivo, ele poderá violar nossa proibição de [bullying e assédio](/pt/site-policy/acceptable-use-policies/github-bullying-and-harassment).

Para obter mais informações ou saber como denunciar uma violação, consulte a [Política de Remoção de Informações Privadas](/pt/site-policy/content-removal-policies/github-private-information-removal-policy) e nossas instruções para [Denunciar Abuso](/pt/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam).
