Política de usuário falecido do GitHub - Documentos do GitHub(function(){
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
4. [Política de usuário falecido do GitHub](/pt/site-policy/other-site-policies/github-deceased-user-policy)

Scroll breadcrumbs right

[Site policy](/pt/site-policy)
----------

Política de usuário falecido do GitHub
==========

Copiar como Markdown

No caso de falecimento de um usuário do GitHub, podemos trabalhar com um indivíduo autorizado para determinar o que acontece com o conteúdo da conta.

Se você for o parente mais próximo, um [sucessor pré-designado](/pt/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/maintaining-ownership-continuity-of-your-personal-accounts-repositories) ou outro indivíduo autorizado (que pode incluir um colaborador ou parceiro de negócios) de um usuário falecido e gostaria de fazer uma solicitação sobre sua conta, poderá entrar em contato conosco por meio do [Portal de suporte do GitHub](https://support.github.com/). No portal, clique em **Fale conosco** e forneça as seguintes informações em sua mensagem:

* Nome
* Informações do Contato
* Nome do titular da conta falecido
* Nome de usuário do GitHub do titular da conta falecido
* Seu relacionamento com o titular da conta falecido (inclua se você foi designado como o sucessor da conta em GitHub.com)
* Se designado como sucessor da conta, o nome de usuário da sua conta do GitHub
* Que ação você está buscando (por exemplo, transferir repositórios públicos, cancelar cobrança por conta)

Assim que recebermos sua solicitação, poderemos acompanhar uma solicitação de informações adicionais, como uma cópia de sua identificação com foto, cópia da certidão de óbito e documentação confirmando que você está autorizado a agir em relação à conta do usuário falecido, para verificar se estamos devidamente autorizados a processar sua solicitação.

Observe que as informações fornecidas em sua solicitação são coletadas de acordo com nossa [Política de Privacidade](/pt/site-policy/privacy-policies/github-privacy-statement) e reteremos as informações apenas conforme necessário para cumprir nossas obrigações legais e resolver controvérsias.
