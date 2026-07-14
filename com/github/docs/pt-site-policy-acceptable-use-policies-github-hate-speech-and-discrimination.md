Discurso de ódio e discriminação do GitHub - Documentos do GitHub(function(){
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
4. [Discriminação e discurso de ódio](/pt/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)

Scroll breadcrumbs right

[Site policy](/pt/site-policy)
----------

Discurso de ódio e discriminação do GitHub
==========

Copiar como Markdown

O GitHub não tolera discursos que ataquem ou promovam ódio contra um indivíduo ou grupo de pessoas com base em quem são, incluindo idade, tamanho corporal, habilidade, etnia, identidade e expressão de gênero, nível de experiência, nacionalidade, aparência pessoal, raça, religião, identidade sexual ou orientação sexual. Isso inclui:

* Zombar, atacar ou excluir uma pessoa ou grupo com base em suas crenças ou nas características listadas acima
* Exibir clara afiliação ou identificação com [organizações extremistas violentas ou terroristas conhecidas](/pt/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
* Apoiar ou promover grupos de ódio ou teorias da conspiração baseadas no ódio
* Compartilhar símbolos ou imagens sinônimo de ódio
* Usar estereótipos prejudiciais, insultos ou discurso desumanizante
* Atacar um indivíduo com base em seu gênero percebido
* Cachorro assobiando; ou usando linguagem e/ou símbolos codificados ou sugestivos para promover abuso ou ódio

Embora o GitHub leve a sério todos os casos de abuso e assédio na plataforma, estamos especialmente comprometidos em combater o abuso baseado em ódio, onde afeta desproporcionalmente as comunidades que historicamente foram alvo de tal abuso. Nosso objetivo é tornar o GitHub um lugar onde todos os indivíduos se sintam bem-vindos e seguros.
