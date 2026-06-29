Política de logotipo do GitHub - Documentos do GitHub(function(){
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
* [Outras políticas do site](/pt/site-policy/other-site-policies)/
* [Política de logotipo do GitHub](/pt/site-policy/other-site-policies/github-logo-policy)

Política de logotipo do GitHub
==========

Copiar como Markdown

Você pode adicionar logotipos GitHub em seu site ou aplicativo de terceiros em alguns cenários. Para obter mais informações e diretrizes específicas sobre o uso do logotipo, consulte [GitHub página Logotipos e Uso](https://github.com/logos).

Você também pode usar um octogato como avatar pessoal ou no site para vincular à sua conta do GitHub, mas não para sua empresa ou um produto que você está criando. GitHub tem uma extensa coleção de octogatos no [Octodex](https://octodex.github.com/). Para obter mais informações sobre como usar os octogatos do Octodex, consulte as [Perguntas frequentes sobre Octodex](https://octodex.github.com/faq/).
