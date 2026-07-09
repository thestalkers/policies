GitHub-Logo-Richtlinie - GitHub Dokumente(function(){
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

[Startseite](/de)

[Site policy](/de/site-policy)
----------

1. [Websiterichtlinie](/de/site-policy)
2. [Andere Website-Richtlinien](/de/site-policy/other-site-policies)
3. [GitHub-Logo-Richtlinie](/de/site-policy/other-site-policies/github-logo-policy)

GitHub-Logo-Richtlinie
==========

Als Markdown kopieren

Sie können GitHub-Logos auf Ihrer Website oder in einigen Anwendungen von Drittanbietern hinzufügen. Weitere Informationen und spezifische Richtlinien zur Verwendung von Logos finden Sie auf der Seite [GitHub-Logos und Verwendung](https://github.com/logos).

Sie können Octocat auch als Ihren persönlichen Avatar oder auf Ihrer Website verwenden, um auf Ihr GitHub-Konto zu verlinken, aber nicht als Logo für Ihr Unternehmen oder ein Produkt, das Sie entwickeln. GitHub hat eine umfangreiche Sammlung von Octocats im [Octodex](https://octodex.github.com/). Weitere Informationen zur Verwendung der Octocats aus dem Octodex finden Sie unter [Octodex FAQ](https://octodex.github.com/faq/).
