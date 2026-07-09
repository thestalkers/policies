Termos do GitHub - Documentos do GitHub(function(){
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
2. [Termos do GitHub](/pt/site-policy/github-terms)

Termos do GitHub
==========

[Termos de Serviço do GitHub](/pt/site-policy/github-terms/github-terms-of-service)
----------

[Termos de serviço corporativos do GitHub](/pt/site-policy/github-terms/github-corporate-terms-of-service)
----------

[Termos do GitHub para produtos e recursos adicionais](/pt/site-policy/github-terms/github-terms-for-additional-products-and-features)
----------

[Diretrizes da comunidade do GitHub](/pt/site-policy/github-terms/github-community-guidelines)
----------

[Código de conduta da comunidade do GitHub](/pt/site-policy/github-terms/github-community-code-of-conduct)
----------

[Termos de licença de pré-lançamento do GitHub](/pt/site-policy/github-terms/github-pre-release-license-terms)
----------

[Versões prévias cobertas pelo DPA (Contrato de Proteção de Dados) do GitHub](/pt/site-policy/github-terms/github-dpa-previews)
----------

[Termos adicionais dos patrocinadores do GitHub](/pt/site-policy/github-terms/github-sponsors-additional-terms)
----------

[Contrato de desenvolvedor registrado do GitHub](/pt/site-policy/github-terms/github-registered-developer-agreement)
----------

[Termos de Serviço do GitHub Marketplace](/pt/site-policy/github-terms/github-marketplace-terms-of-service)
----------

[Contrato de desenvolvedor do GitHub Marketplace](/pt/site-policy/github-terms/github-marketplace-developer-agreement)
----------

[Termos do Programa de Pesquisa GitHub](/pt/site-policy/github-terms/github-research-program-terms)
----------

[Termos e condições de aplicativos de código aberto do GitHub](/pt/site-policy/github-terms/github-open-source-applications-terms-and-conditions)
----------

[Termos do evento do GitHub](/pt/site-policy/github-terms/github-event-terms)
----------

[Código de conduta do evento GitHub](/pt/site-policy/github-terms/github-event-code-of-conduct)
----------

[Contrato de Uso Educacional do GitHub](/pt/site-policy/github-terms/github-educational-use-agreement)
----------

[Política de Desenvolvedor de Extensão do GitHub Copilot](/pt/site-policy/github-terms/github-copilot-extension-developer-policy)
----------

[Contrato do Programa de Parceiros de Verificação de Segredos do GitHub](/pt/site-policy/github-terms/github-secret-scanning-partner-program-agreement)
----------
