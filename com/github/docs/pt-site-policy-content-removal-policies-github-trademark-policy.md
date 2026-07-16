Política de marca registrada do GitHub - Documentos do GitHub(function(){
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
4. [Política de marca registrada do GitHub](/pt/site-policy/content-removal-policies/github-trademark-policy)

Deslizar o caminho de navegação para a direita

[Site policy](/pt/site-policy)
----------

Política de marca registrada do GitHub
==========

Copiar como Markdown

Neste artigo
----------

* [O que é uma violação da política de marca registrada do GitHub?](#what-is-a-github-trademark-policy-violation)
* [O que não é uma violação da política de marca registrada do GitHub?](#what-is-not-a-github-trademark-policy-violation)
* [Como o GitHub responde a violações de política de marca registrada relatadas?](#how-does-github-respond-to-reported-trademark-policy-violations)
* [Como faço para denunciar uma violação da política de marca registrada?](#how-do-i-report-a-trademark-policy-violation)
* [Quais informações são necessárias ao relatar violações da política de marcas registradas?](#what-information-is-required-when-reporting-trademark-policy-violations)

[O que é uma violação da política de marca registrada do GitHub?](#what-is-a-github-trademark-policy-violation)
----------

Usar uma empresa ou nome comercial, logotipo ou outros materiais protegidos por marca registrada de maneira que possa enganar ou confundir outras pessoas em relação à sua marca ou afiliação comercial pode ser considerado uma violação da política de marca registrada.

[O que não é uma violação da política de marca registrada do GitHub?](#what-is-not-a-github-trademark-policy-violation)
----------

Usar a marca registrada de outra pessoa de forma que não tenha nada a ver com o produto ou serviço para o qual a marca registrada foi concedida não é uma violação da política de marcas registradas. Os nomes de usuário do GitHub estão disponíveis por ordem de chegada e não podem ser reservados. Uma conta do GitHub com um nome de usuário que seja o mesmo que uma marca registrada não é, por si só, necessariamente uma violação de nossa política de marcas registradas.

[Como o GitHub responde a violações de política de marca registrada relatadas?](#how-does-github-respond-to-reported-trademark-policy-violations)
----------

Quando recebemos denúncias de violações da política de marcas registradas de titulares de registros federais ou internacionais de marcas registradas, analisamos a conta e podemos tomar as seguintes medidas:

* Quando houver uma intenção clara de enganar outras pessoas por meio do uso não autorizado de uma marca registrada, o GitHub suspenderá a conta e notificará o titular da conta.
* Quando determinamos que uma conta parece confundir os usuários, mas não está se passando propositalmente como produto ou serviço de marca registrada, damos ao titular da conta a oportunidade de esclarecer qualquer possível confusão. Também podemos liberar um nome de usuário para uso ativo do titular da marca registrada.

[Como faço para denunciar uma violação da política de marca registrada?](#how-do-i-report-a-trademark-policy-violation)
----------

Os titulares de marcas registradas podem denunciar possíveis violações da política de marca registrada ao GitHub por meio de [Enviar Relatório de Violação da Política de Marcas Registradas](https://support.github.com/contact/trademark-policy). Use o formulário de contato e envie solicitações relacionadas a marcas registradas usando o endereço de e-mail de sua empresa e inclua todas as informações solicitadas abaixo para ajudar a agilizar nossa resposta. Certifique-se também de nos descrever claramente por que a conta pode causar confusão com sua marca ou como a conta pode diluir ou manchar sua marca.

[Quais informações são necessárias ao relatar violações da política de marcas registradas?](#what-information-is-required-when-reporting-trademark-policy-violations)
----------

Para investigar violações da política de marcas registradas, forneça todas as informações a seguir:

* Nome de usuário da conta denunciada

* Nome da empresa

* A conta GitHub da sua empresa (se houver)

* Site da Empresa

* Sua palavra de marca registrada, símbolo, etc.

* Número de registro da marca

* Escritório de registro de marcas (por exemplo, USPTO)

* Descrição da confusão (por exemplo, passar por sua empresa, incluindo descrições específicas de conteúdo ou comportamento)

* Ação solicitada (por exemplo, remoção de conta em violação ou transferência de nome de usuário de marca registrada para uma conta corporativa existente)

* Inclua a seguinte declaração: “Acredito de boa-fé que o uso da marca registrada descrita acima não é autorizado pelo proprietário da marca registrada, nem por seu agente, nem pela lei. Levei em consideração os usos nominativos e outros usos justos."

* Além disso, inclua a seguinte declaração: “Juro, sob pena de perjúrio, que as informações nesta notificação são precisas e que sou o proprietário da marca registrada, ou estou autorizado a agir em nome do proprietário, de um direito exclusivo que supostamente foi infringido”.

* Incluir sua assinatura física ou eletrônica.

* Observação: É necessário um número de registro de marca federal ou internacional. Se o nome que você informar **não** for uma marca registrada (por exemplo, uma agência governamental ou organização sem fins lucrativos), informe:

  * Seu nome e sobrenome
  * Título
  * Endere輟
  * Telefone
  * E-mail (deve ser do domínio da empresa)
