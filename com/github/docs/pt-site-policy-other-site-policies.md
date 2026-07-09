Outras políticas do site - Documentos do GitHub(function(){
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

1. [Política do site](/pt/site-policy)
2. [Outras políticas do site](/pt/site-policy/other-site-policies)

Outras políticas do site
==========

[GitHub e controles de comércio](/pt/site-policy/other-site-policies/github-and-trade-controls)
----------

[Política de usuário falecido do GitHub](/pt/site-policy/other-site-policies/github-deceased-user-policy)
----------

[Política de logotipo do GitHub](/pt/site-policy/other-site-policies/github-logo-policy)
----------

[Política de remoção governamental do GitHub](/pt/site-policy/other-site-policies/github-government-takedown-policy)
----------

[Política de nome de usuário do GitHub](/pt/site-policy/other-site-policies/github-username-policy)
----------

[Diretrizes para Solicitações Legais de Dados do Usuário](/pt/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)
----------

[Política de Recuperação de Conta do GitHub](/pt/site-policy/other-site-policies/github-account-recovery-policy)
----------
