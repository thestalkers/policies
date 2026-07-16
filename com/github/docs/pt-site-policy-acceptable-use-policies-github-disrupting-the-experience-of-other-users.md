GitHub interrompendo a experiência de outros usuários - Documentos do GitHub(function(){
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
4. [Interrupção da experiência de outros usuários](/pt/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)

Deslizar o caminho de navegação para a direita

[Site policy](/pt/site-policy)
----------

GitHub interrompendo a experiência de outros usuários
==========

Copiar como Markdown

Fazer parte de uma comunidade inclui reconhecer como seu comportamento afeta os outros e se envolver em interações significativas e produtivas com as pessoas e a plataforma em que elas confiam.

Não permitimos comportamentos que interrompam significativa ou continuamente a experiência de outros usuários. Isso inclui:

* Postar comentários fora do tópico
* Abrindo problemas vazios ou sem sentido ou pull requests
* Marcar e/ou seguir contas ou repositórios em grande volume em um curto período de tempo
* Criando revisões de código sem sentido ou irrelevantes
* Envolver-se com os recursos da plataforma de forma que cause notificações excessivas para outros usuários
* Usar qualquer outro recurso da plataforma de uma maneira que crie disrupção

Embora encorajemos os mantenedores a moderar seus próprios projetos individualmente, a equipe do GitHub pode tomar medidas restritivas adicionais contra contas que estão engajadas nesses tipos de comportamento.

Observe que a conduta acima também pode violar outras restrições em nossas [Políticas de Uso Aceitável](/pt/site-policy/acceptable-use-policies/github-acceptable-use-policies). Por exemplo, dependendo da natureza e gravidade da atividade, pode chegar ao nível de [bullying e assédio](/pt/site-policy/acceptable-use-policies/github-bullying-and-harassment).
