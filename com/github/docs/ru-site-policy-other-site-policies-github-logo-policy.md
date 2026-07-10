Политика логотипа GitHub - GitHub Docs(function(){
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

[Домашняя страница](/ru)

[Site policy](/ru/site-policy)
----------

1. [Политика сайта](/ru/site-policy)
2. [Другие правила сайта](/ru/site-policy/other-site-policies)
3. [Политика логотипа GitHub](/ru/site-policy/other-site-policies/github-logo-policy)

Политика логотипа GitHub
==========

Копировать как Markdown

Вы можете добавить GitHub логотипы на ваш веб-сайт или стороннее приложение в некоторых сценариях. Для получения дополнительной информации и конкретных рекомендаций по использованию логотипа см. Страницу логотипов и использования [GitHub](https://github.com/logos).

Вы также можете использовать осьминога в качестве своего личного аватара или на своем веб-сайте для ссылки на вашу GitHub учетную запись, но не для вашей компании или продукта, который вы создаете. GitHub имеет обширную коллекцию кошконогов в [Octodex](https://octodex.github.com/). Для получения дополнительной информации об использовании осьминогов из Octodex см. [Часто задаваемые вопросы по Octodex](https://octodex.github.com/faq/).
