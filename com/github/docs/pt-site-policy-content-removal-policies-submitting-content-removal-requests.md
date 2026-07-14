Como enviar solicitações de remoção de conteúdo - Documentos do GitHub(function(){
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
3. [Políticas de remoção de conteúdo](/pt/site-policy/content-removal-policies)
4. [Como enviar solicitações de remoção de conteúdo](/pt/site-policy/content-removal-policies/submitting-content-removal-requests)

Scroll breadcrumbs right

[Site policy](/pt/site-policy)
----------

Como enviar solicitações de remoção de conteúdo
==========

Copiar como Markdown

Neste artigo
----------

* [Política de remoção de DMCA](#dmca-takedown-policy)
* [Política de marca registrada do GitHub](#github-trademark-policy)
* [Política de remoção de informações privadas do GitHub](#github-private-information-removal-policy)

Entendemos que conteúdo protegido por direitos autorais, marca registrada ou privado pode ser publicado no GitHub – acidentalmente ou de propósito – às vezes em repositórios que você não possui. Como a natureza desse conteúdo varia e devido às diferentes leis aplicáveis, cada categoria tem seus próprios requisitos de relatórios distintos descritos em nossas políticas.

Se você quiser solicitar que o conteúdo seja removido do GitHub, reserve um tempo para se familiarizar com cada uma dessas políticas e seus respectivos requisitos de relatório antes de enviar um relatório. Se recebermos um relatório incompleto, precisaremos solicitar esclarecimentos ou revisões e você precisará reenviar um relatório revisado.

Observe que não podemos ajudá-lo a determinar qual política é apropriada para sua situação específica. Se você revisou as políticas abaixo e ainda tem dúvidas sobre se o conteúdo deve ou não ser denunciado como copyright, marca registrada ou informação privada, recomendamos consultar um advogado independente.

[Política de remoção de DMCA](#dmca-takedown-policy)
----------

A [Política de remoção da DMCA](/pt/site-policy/content-removal-policies/dmca-takedown-policy) pode ser usada para denunciar conteúdo que você acredita que viola direitos autorais de sua propriedade ou de sua organização. Depois de analisar a política, você também pode analisar nosso [Guia para Enviar uma Notificação de Remoção da DMCA](/pt/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) antes de enviar uma denúncia.

[Política de marca registrada do GitHub](#github-trademark-policy)
----------

A [Política de marcas registradas do GitHub](/pt/site-policy/content-removal-policies/github-trademark-policy) pode ser usada para denunciar conteúdo que pareça usar sua empresa ou nome comercial, o logotipo ou outros materiais protegidos por marca de maneira que possa enganar ou confundir outras pessoas em relação à marca ou à afiliação comercial.

[Política de remoção de informações privadas do GitHub](#github-private-information-removal-policy)
----------

A [Política de remoção de informações privadas do GitHub](/pt/site-policy/content-removal-policies/github-private-information-removal-policy) pode ser usada para denunciar dados privados (confidenciais e que representam um risco de segurança), mas que não são necessariamente protegidos por direitos autorais ou marcas.

Usuários na Índia podem [entrar em contato com o Oficial de Reclamações do GitHub](https://support.github.com/contact/india-grievance-officer).
