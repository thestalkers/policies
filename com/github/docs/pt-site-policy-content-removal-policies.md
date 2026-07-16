Políticas de remoção de conteúdo - Documentos do GitHub(function(){
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

Barra lateral do recolhimentoExpandir barra lateral

Deslocar a trilha de navegação para a esquerda

1. [Página Inicial](/pt)
2. [Política do site](/pt/site-policy)
3. [Políticas de remoção de conteúdo](/pt/site-policy/content-removal-policies)

Deslizar o caminho de navegação para a direita

[Site policy](/pt/site-policy)
----------

Políticas de remoção de conteúdo
==========

[Como enviar solicitações de remoção de conteúdo](/pt/site-policy/content-removal-policies/submitting-content-removal-requests)
----------

[Política de remoção de DMCA](/pt/site-policy/content-removal-policies/dmca-takedown-policy)
----------

[Política de remoção de informações privadas do GitHub](/pt/site-policy/content-removal-policies/github-private-information-removal-policy)
----------

[Política de marca registrada do GitHub](/pt/site-policy/content-removal-policies/github-trademark-policy)
----------

[Guia para enviar uma contranotificação da DMCA](/pt/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)
----------

[Guia para enviar um aviso de remoção da DMCA](/pt/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)
----------
