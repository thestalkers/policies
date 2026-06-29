Documentação da Política do Site - Documentos do GitHub(function(){
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

Documentação da Política do Site
==========

Consulte os termos de serviço, as políticas de uso aceitável, as práticas de privacidade, os procedimentos de remoção de conteúdo e outras políticas do site do GitHub.

[Visão geral](/site-policy/github-terms/github-terms-of-service)

Recomendada
----------

[### Termos de Serviço do GitHub ###](/pt/free-pro-team@latest/site-policy/github-terms/github-terms-of-service)[### Declaração Geral de Privacidade do GitHub ###](/pt/free-pro-team@latest/site-policy/privacy-policies/github-general-privacy-statement)[### Políticas de uso aceitável do GitHub ###](/pt/free-pro-team@latest/site-policy/acceptable-use-policies/github-acceptable-use-policies)

Artigos
----------

Categoria: Todas as categorias

[Follow acceptable use policies ### Abuso ou exploração sexual infantil – GitHub ###](/pt/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)[Follow acceptable use policies ### Ameaças do GitHub de violência e conteúdo violento gratuito ###](/pt/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)[Review privacy and security policies ### Aviso de Privacidade de Dados Global do GitHub para Candidatos ###](/pt/site-policy/privacy-policies/github-candidate-privacy-policy)[Follow acceptable use policies ### Bullying e Assédio no GitHub ###](/pt/site-policy/acceptable-use-policies/github-bullying-and-harassment)[Review product and program terms ### Código de conduta da comunidade do GitHub ###](/pt/site-policy/github-terms/github-community-code-of-conduct)[Review product and program terms ### Código de conduta do evento GitHub ###](/pt/site-policy/github-terms/github-event-code-of-conduct)[Request content removal ### Como enviar solicitações de remoção de conteúdo ###](/pt/site-policy/content-removal-policies/submitting-content-removal-requests)[Review company and general policies ### Compromisso de Cooperação GitHub GPL ###](/pt/site-policy/github-company-policies/github-gpl-cooperation-commitment)[Follow acceptable use policies ### Contestação e reintegração do GitHub ###](/pt/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)

Mostrando 1-9 de 57

[Previous]()[1](#1)[2](#2)[3](#3)[4](#4)[5](#5)[6](#6)[7](#7)[Next](#2)
