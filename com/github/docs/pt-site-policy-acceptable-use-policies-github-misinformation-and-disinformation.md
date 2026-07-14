Informação falsa e desinformação no GitHub - Documentos do GitHub(function(){
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

1. [Página Inicial](/pt)
2. [Política do site](/pt/site-policy)
3. [Políticas de Uso Aceitável](/pt/site-policy/acceptable-use-policies)
4. [Política de desinformação](/pt/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)

Scroll breadcrumbs right

[Site policy](/pt/site-policy)
----------

Informação falsa e desinformação no GitHub
==========

Copiar como Markdown

Você não pode postar conteúdo que apresente uma visão distorcida da realidade, seja imprecisa ou falsa ou intencionalmente enganosa (desinformação), onde tal conteúdo possa resultar em danos ao público ou interferir em oportunidades justas e iguais para que todos participem de uma sociedade livre e aberta. Isso pode incluir:

* Alegações médicas imprecisas ou sem respaldo científico que ponham em risco a saúde ou a segurança pública
* Mídia manipulada, seja de áudio ou visual, suscetível de induzir ao erro ou enganar de forma que possa prejudicar o interesse público
* Conteúdo falso ou enganoso que possa interferir na capacidade de um indivíduo de participar de atividades cívicas
* Alegações infundadas que podem promover ódio ou assédio direcionado a grupos específicos de pessoas

Incentivamos a participação ativa na expressão de ideias, perspectivas e experiências e podemos não estar em posição de contestar relatos ou observações pessoais. Geralmente permitimos paródias e sátiras que estejam de acordo com nossas [Políticas de Uso Aceitável](/pt/site-policy/acceptable-use-policies/github-acceptable-use-policies) e consideramos que o contexto é importante na forma como a informação é recebida e compreendida. Ao analisar o conteúdo sob esta política, o GitHub considerará o impacto de vários fatores que podem ajudar a orientar o espectador, como se o conteúdo foi fornecido com isenções de responsabilidade claras, citações a fontes confiáveis ou inclui outros detalhes que esclarecem a precisão do informações que estão sendo compartilhadas.
