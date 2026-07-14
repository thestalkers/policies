Representação do GitHub - Documentos do GitHub(function(){
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
4. [Representação](/pt/site-policy/acceptable-use-policies/github-impersonation)

Scroll breadcrumbs right

[Site policy](/pt/site-policy)
----------

Representação do GitHub
==========

Copiar como Markdown

Você não pode deturpar sua identidade ou sua associação com outra pessoa ou organização. Isso inclui fazer qualquer uma das ações a seguir de forma a enganar ou enganar os outros:

* Copiar o avatar de outro usuário ou outras informações de perfil pessoal
* Postar conteúdo com o endereço de e-mail de outro usuário
* Usar um nome de usuário, nome de organização ou outro namespace enganosamente semelhante
* Acessar uma conta ou organização com o token ou as credenciais de outro usuário
* Caso contrário, posando como outro indivíduo ou organização

A falsificação de identidade é uma forma de assédio e a violação desta política pode levar à perda de acesso à sua conta.

Observe que ter um nome de usuário semelhante a outro não é necessariamente falsificação de identidade. O GitHub levará o contexto em consideração. Por exemplo, como nos casos que envolvem requerimentos judiciais ou extrajudiciais de [informações incorretas ou desinformação](/pt/site-policy/acceptable-use-policies/github-misinformation-and-disinformation), geralmente permitimos paródias e sátiras que estejam de acordo com as [Políticas de Uso Aceitável](/pt/site-policy/acceptable-use-policies/github-acceptable-use-policies).
