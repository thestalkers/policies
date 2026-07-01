Políticas de Uso Aceitável - Documentos do GitHub(function(){
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

* [Política do site](/pt/site-policy)/
* [Políticas de Uso Aceitável](/pt/site-policy/acceptable-use-policies)

Políticas de Uso Aceitável
==========

[Políticas de uso aceitável do GitHub](/pt/site-policy/acceptable-use-policies/github-acceptable-use-policies)
----------

[Malware ou exploits ativos do GitHub](/pt/site-policy/acceptable-use-policies/github-active-malware-or-exploits)
----------

[Bullying e Assédio no GitHub](/pt/site-policy/acceptable-use-policies/github-bullying-and-harassment)
----------

[GitHub interrompendo a experiência de outros usuários](/pt/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)
----------

[GitHub Doxxing e invasão de privacidade](/pt/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)
----------

[Discurso de ódio e discriminação do GitHub](/pt/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)
----------

[Representação do GitHub](/pt/site-policy/acceptable-use-policies/github-impersonation)
----------

[Informação falsa e desinformação no GitHub](/pt/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)
----------

[Conteúdo sexualmente obsceno do GitHub](/pt/site-policy/acceptable-use-policies/github-sexually-obscene-content)
----------

[Ameaças do GitHub de violência e conteúdo violento gratuito](/pt/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)
----------

[Terrorismo e extremismo violento – GitHub](/pt/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
----------

[Abuso ou exploração sexual infantil – GitHub](/pt/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)
----------

[Imagens íntimas não consensuais – GitHub](/pt/site-policy/acceptable-use-policies/github-non-consensual-intimate-imagery)
----------

[Ferramentas de IA e mídia sintética – GitHub](/pt/site-policy/acceptable-use-policies/github-synthetic-media-and-ai-tools)
----------

[Contestação e reintegração do GitHub](/pt/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)
----------
