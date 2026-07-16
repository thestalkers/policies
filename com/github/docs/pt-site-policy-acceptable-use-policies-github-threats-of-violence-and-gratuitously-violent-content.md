Ameaças do GitHub de violência e conteúdo violento gratuito - Documentos do GitHub(function(){
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
4. [Ameaças de violência e conteúdo injustificadamente violento](/pt/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)

Deslizar o caminho de navegação para a direita

[Site policy](/pt/site-policy)
----------

Ameaças do GitHub de violência e conteúdo violento gratuito
==========

Copiar como Markdown

Você não pode usar o GitHub para organizar, promover, encorajar, ameaçar ou incitar atos de violência. Você não pode postar conteúdo que descreva ou glorifique violência ou dano físico contra seres humanos ou animais. Isso inclui:

* Ameaçar outro indivíduo ou grupo com abuso, dano, violência sexual ou morte
* Postar texto, imagens ou conteúdo de áudio glorificando ou contendo uma representação gráfica de violência contra si mesmo, outro indivíduo, grupo ou animal
* Incentivar outro indivíduo a se envolver em automutilação

Não permitimos que conteúdo violento seja postado indiscriminadamente ou de forma difícil para outros usuários evitarem, como um avatar de perfil ou um comentário de problema. No entanto, entendemos que pode haver motivos legítimos para postar conteúdo violento, como para fins educacionais ou documentais, trabalhos criativos ou representações de eventos históricos. Nesses casos, um aviso claro ou isenção de responsabilidade pode ajudar os usuários a tomar uma decisão informada sobre se desejam ou não se envolver com esse conteúdo. Ainda assim, o GitHub pode decidir limitar a visibilidade de tal conteúdo àqueles que optarem por participar.
