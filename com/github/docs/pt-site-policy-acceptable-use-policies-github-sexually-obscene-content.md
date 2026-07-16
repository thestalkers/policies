Conteúdo sexualmente obsceno do GitHub - Documentos do GitHub(function(){
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
3. [Políticas de Uso Aceitável](/pt/site-policy/acceptable-use-policies)
4. [Conteúdo sexualmente obsceno](/pt/site-policy/acceptable-use-policies/github-sexually-obscene-content)

Deslizar o caminho de navegação para a direita

[Site policy](/pt/site-policy)
----------

Conteúdo sexualmente obsceno do GitHub
==========

Copiar como Markdown

Não toleramos conteúdo associado à exploração sexual ou abuso de outro indivíduo, inclusive quando [se trata de menores](/pt/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse). Não permitimos conteúdo com temas sexuais ou sugestivos que sirvam pouco ou nenhum propósito além de solicitar uma resposta erótica ou chocante, principalmente quando esse conteúdo é amplificado por sua colocação em perfis ou outros contextos sociais. Isso inclui:

* Conteúdo pornográfico
* Imagens íntimas não consensuais
* Representações gráficas de atos sexuais, incluindo fotografias, vídeos, animações, desenhos, imagens geradas por computador ou conteúdo baseado em texto

Reconhecemos que nem toda nudez ou conteúdo relacionado à sexualidade é obsceno. Podemos permitir representações visuais e/ou textuais em contextos artísticos, educacionais, históricos ou jornalísticos, ou no que se refere à defesa de vítimas. Em alguns casos, um aviso de isenção de responsabilidade pode ajudar a comunicar o contexto do projeto. No entanto, entenda que podemos optar por limitar o conteúdo dando aos usuários a opção de ativar antes de visualizar.
