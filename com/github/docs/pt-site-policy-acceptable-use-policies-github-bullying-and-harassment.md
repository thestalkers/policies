Bullying e Assédio no GitHub - Documentos do GitHub(function(){
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

[Página Inicial](/pt)

[Site policy](/pt/site-policy)
----------

1. [Política do site](/pt/site-policy)
2. [Políticas de Uso Aceitável](/pt/site-policy/acceptable-use-policies)
3. [Bullying e assédio](/pt/site-policy/acceptable-use-policies/github-bullying-and-harassment)

Bullying e Assédio no GitHub
==========

Copiar como Markdown

Não toleramos assédio, intimidação ou abuso de qualquer tipo, seja diretamente ou incentivando outras pessoas a participar da conduta proibida. Isso inclui:

* Ataques pessoais direcionados
* Acumular ou orquestrar atividades [perturbadoras](/pt/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users) de uma forma que equivale a abuso
* Seguir outro usuário pela plataforma de maneira que cause intimidação
* Fazer avanços ou comentários sexuais dirigidos a outro indivíduo
* Participar de forma dissimulada de uma conversa de uma forma que instigue conflito ou prejudique a discussão sincera
* Criação de contas alternativas especificamente para evitar ações de moderação tomadas pela equipe ou usuários do GitHub

Observe que nem toda conduta indesejada é necessariamente considerada assédio. Por exemplo, discordar de outro usuário ou rejeitar seus comentários pode não atingir o nível de assédio em nossa plataforma. Além disso, compartilhar críticas a figuras públicas ou projetos, ou temas de interesse público, não necessariamente se enquadra nesta política. No entanto, recomendamos que você esteja atento ao modo como se envolve com outros usuários e a plataforma, pois essa atividade ainda pode violar nossa restrição de interromper a experiência de outros usuários.
