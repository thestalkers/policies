Política de nome de usuário do GitHub - Documentos do GitHub(function(){
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
3. [Outras políticas do site](/pt/site-policy/other-site-policies)
4. [Política de nome de usuário do GitHub](/pt/site-policy/other-site-policies/github-username-policy)

Scroll breadcrumbs right

[Site policy](/pt/site-policy)
----------

Política de nome de usuário do GitHub
==========

Copiar como Markdown

Neste artigo
----------

* [E se o nome de usuário que eu quero já estiver em uso?](#what-if-the-username-i-want-is-already-taken)
* [Política de marca registrada](#trademark-policy)
* [Política de apropriação de nomes](#name-squatting-policy)

Os nomes de conta do GitHub estão disponíveis por ordem de chegada e destinam-se ao uso imediato e ativo.

[E se o nome de usuário que eu quero já estiver em uso?](#what-if-the-username-i-want-is-already-taken)
----------

Lembre-se de que nem todas as atividades no GitHub são visíveis publicamente; contas sem atividade visível podem estar em uso ativo.

Não aceitamos solicitações para liberar, transferir ou recuperar nomes de usuário com base no fato de que parecem inativos ou não utilizados. Se o nome de usuário que você deseja já foi reivindicado, você precisará selecionar um nome disponível diferente, a menos que esteja apresentando uma reclamação de marca registrada, conforme descrito abaixo.

Se o nome de usuário que você deseja já foi reivindicado, considere outros nomes ou variações exclusivas. Usar um número, um hífen ou uma grafia alternativa pode ajudar você a identificar um nome de usuário desejado que ainda está disponível.

[Política de marca registrada](#trademark-policy)
----------

Se você acredita que a conta de alguém está violando seus direitos de marca registrada, encontre mais informações sobre como fazer uma reclamação de marca registrada em nossa página [Política de marca registrada do GitHub](/pt/site-policy/content-removal-policies/github-trademark-policy). Reclamações válidas relacionadas a marcas registradas são os únicos pedidos que analisamos para possível liberação de um nome de usuário já reivindicado.

[Política de apropriação de nomes](#name-squatting-policy)
----------

O GitHub proíbe o squatting de nomes de contas e os nomes de contas não podem ser reservados ou mantidos inativos para uso futuro. As contas que violam esta política de usurpação de nomes podem ser removidas ou renomeadas sem aviso prévio. Tentativas de vender, comprar ou solicitar outras formas de pagamento em troca de nomes de contas são proibidas e podem resultar na suspensão permanente da conta.
