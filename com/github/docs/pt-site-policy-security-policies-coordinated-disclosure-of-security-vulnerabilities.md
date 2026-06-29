Divulgação coordenada de vulnerabilidades de segurança - Documentos do GitHub(function(){
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
* [Políticas de Segurança](/pt/site-policy/security-policies)/
* [Divulgação coordenada de vulnerabilidades de segurança](/pt/site-policy/security-policies/coordinated-disclosure-of-security-vulnerabilities)

Divulgação coordenada de vulnerabilidades de segurança
==========

Copiar como Markdown

Queremos manter o GitHub seguro para todos. Se você descobriu uma vulnerabilidade de segurança no GitHub, agradecemos sua ajuda em divulgá-la para nós de maneira coordenada.

[Programa de recompensas](#bounty-program)
----------

Como várias outras grandes empresas de software, o GitHub oferece uma recompensa de bugs para melhor se envolver com pesquisadores de segurança. A ideia é simples: hackers e pesquisadores de segurança (como você) descobrem e relatam vulnerabilidades por meio de nosso processo de divulgação coordenado. Então, para reconhecer o esforço significativo que esses pesquisadores costumam fazer ao caçar insetos, nós os recompensamos com algum dinheiro vivo.

Consulte o site [Recompensa por Bugs do GitHub](https://bounty.github.com) para obter detalhes de recompensas, além dos termos abrangentes da [Política Legal de Safe Harbor](/pt/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor) e ache os bugs!
