Contestação e Reintegração do GitHub - Documentos do GitHub(function(){
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
4. [Contestação e Reintegração do GitHub](/pt/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)

Deslizar o caminho de navegação para a direita

[Site policy](/pt/site-policy)
----------

Contestação e Reintegração do GitHub
==========

Copiar como Markdown

Neste artigo
----------

* [Contestação e Reintegração](#appeal-and-reinstatement)
* [O que são Contestações e Reintegrações?](#what-are-appeals-and-reinstatements)
* [Como isso funciona](#how-this-works)
* [Transparência](#transparency)

[Contestação e Reintegração](#appeal-and-reinstatement)
----------

Embora a maioria das interações entre os membros das comunidades do GitHub e do npm esteja dentro das nossas Políticas de Uso Aceitável, Diretrizes da Comunidade e Termos de Código Aberto, às vezes ocorrem violações dessas políticas. Quando isso acontece, a equipe do GitHub pode precisar tomar medidas de fiscalização para resolver as violações. No entanto, entendemos que, às vezes, podemos cometer erros. Em alguns casos, pode haver uma base para reverter uma ação de moderação tomada (ou não tomada) pela equipe do GitHub. Para garantir que nossas políticas e resultados sejam aplicados uniformemente, o GitHub oferece um processo interno de processamento de reclamações onde os usuários podem enviar solicitações de reintegração ou fornecer informações adicionais para contestar de uma decisão de moderação.

[O que são Contestações e Reintegrações?](#what-are-appeals-and-reinstatements)
----------

Tanto as Contestações quanto as Reintegrações podem surgir em relação a decisões de impedir a publicação de conteúdo ou de desativar ou limitar o acesso a conteúdo ou a uma conta, incluindo decisões sobre se deve ou não:

* Remover, desabilitar o acesso ou restringir a visibilidade do conteúdo
* Suspender ou terminar o acesso a uma conta
* Suspender ou terminar o acesso ao serviço, no todo ou em parte
* Suspender, terminar ou restringir a capacidade de monetizar conteúdo
* Bloquear a publicação de conteúdo no npm

A “Reintegração” é quando o usuário deseja recuperar o acesso à sua conta ou conteúdo, está disposto a fazer as alterações necessárias para solucionar a violação e deve concordar em não violar nossos termos daqui por diante.

Uma “Contestação” é quando o usuário contesta que ocorreu uma violação e pode fornecer informações adicionais para mostrar que uma decisão diferente deveria ter sido tomada.

[Como isso funciona](#how-this-works)
----------

Se você deseja obter a Reintegração ou fazer uma Contestação de uma medida coercitiva no GitHub ou no npm, preencha o formulário aplicável:

* [Formulário de Contestação e Reintegração do GitHub](https://support.github.com/contact/reinstatement)
* [Formulário de Contestação e Reintegração do npm](https://support.github.com/support/contact/product-selection/reinstatement-requests/npm-reinstatement-request)

No GitHub, é possível solicitar a Reintegração ou Contestação de uma decisão de moderação em até seis meses após a decisão. O GitHub pode, a seu critério, recusar-se a considerar quaisquer solicitações enviadas mais de seis meses após a decisão.

A equipe do GitHub revisará as informações fornecidas no formulário para determinar se há informações suficientes para garantir a Reintegração ou a concessão de uma Contestação.

### [Reintegrações](#reinstatements) ###

Quando um usuário concordar em cumprir nossas Políticas de Uso Aceitável no futuro e tiver feito as alterações necessárias para resolver as violações, poderemos optar por reintegrar sua conta ou conteúdo dependendo das circunstâncias e da gravidade da violação inicial.

Todas as solicitações legítimas de Reintegração serão analisadas inicialmente pela equipe do GitHub e serão respondidas com uma decisão.

### [Contestações](#appeals) ###

Quando um usuário busca contestar uma decisão, ele pode usar o formulário para explicar sua base para contestar a decisão e fornecer qualquer informação adicional sobre a suposta violação que ele acredita que deveria ter levado a uma decisão diferente.

Se as informações fornecidas demonstrarem que uma conclusão diferente deveria ter sido alcançada, poderemos conceder uma Contestação. O GitHub reverterá ou modificará sua decisão quando a Contestação contiver motivos suficientes para determinarmos que (i) nossa decisão de agir ou não agir foi equivocada; (ii) que o conteúdo ou conduta não foi ilegal e não estava incompatível com os nossos Termos; ou (iii) que o conteúdo ou a conduta justifique uma ação de menor gravidade do que a medida tomada.

Todas as decisões da Contestação serão tomadas por seres humanos e não por qualquer meio automatizado. Se o revisor da Contestação for a mesma pessoa que fez a determinação inicial e esse membro da equipe acreditar que sua conclusão inicial estava correta (e, portanto, estaria inclinado a negar a Contestação), um membro diferente da equipe do GitHub revisará a Contestação de forma independente.

Todas as Contestações legítimas serão respondidas com uma decisão final.

[Transparência](#transparency)
----------

Acompanhamos as Contestações e as Reintegrações por meio da [Central de transparência](https://transparencycenter.github.com/appeals/).

### [Direitos legais](#legal-rights) ###

Se você acreditar que uma decisão final tomada sobre uma Contestação ainda está incorreta, será possível, em determinadas circunstâncias, ter direitos adicionais para buscar a revisão da decisão de acordo com a lei local. Por exemplo, se você estiver na União Europeia, talvez seja possível acessar um processo de resolução extrajudicial de litígios em conformidade com o [Regulamento dos Serviços Digitais](https://eur-lex.europa.eu/eli/reg/2022/2065/oj#d1e2819-1-1). Esse processo reflete o compromisso do GitHub com os direitos humanos reconhecidos internacionalmente, estabelecidos nos Princípios Orientadores das Nações Unidas sobre Negócios e Direitos Humanos (UNGPs), com a privacidade e com a liberdade de expressão.
