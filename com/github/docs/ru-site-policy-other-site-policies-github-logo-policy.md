Политика логотипа GitHub - Документация GitHub(function(){
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
var q=window.matchMedia?window.matchMedia('(prefers-color-scheme: dark)'):null;
var apply=function(){
var night=css.colorMode==='auto'?!!(q&&q.matches):css.colorMode==='dark';
var theme=night?css.darkTheme:css.lightTheme;
var mode=theme.indexOf('dark')===0?'dark':'light';
h.setAttribute('data-color-mode',mode);
h.setAttribute('data-'+mode+'-theme',theme);
};
h.setAttribute('data-color-mode-preference',css.colorMode);
h.setAttribute('data-light-theme',css.lightTheme);
h.setAttribute('data-dark-theme',css.darkTheme);
apply();
if(css.colorMode==='auto'&&q){
if(q.addEventListener)q.addEventListener('change',apply);
else if(q.addListener)q.addListener(apply);
}
}catch(e){}
})();

[Skip to main content](#main-content)

[Skip to content](#main-content)

Свернуть боковую панельРазвернуть боковую панель

Прокрутите панели навигации слева

1. [Домашняя страница](/ru)
2. [Политика сайта](/ru/site-policy)
3. [Другие правила сайта](/ru/site-policy/other-site-policies)
4. Политика логотипа GitHub

Прокрутите страницы вправо

[Site policy](/ru/site-policy)
----------

Политика логотипа GitHub
==========

Копирование markdown

Вы можете добавить GitHub логотипы на ваш веб-сайт или стороннее приложение в некоторых сценариях. Для получения дополнительной информации и конкретных рекомендаций по использованию логотипа см. Страницу логотипов и использования [GitHub](https://github.com/logos).

Вы также можете использовать осьминога в качестве своего личного аватара или на своем веб-сайте для ссылки на вашу GitHub учетную запись, но не для вашей компании или продукта, который вы создаете. GitHub имеет обширную коллекцию кошконогов в [Octodex](https://octodex.github.com/). Для получения дополнительной информации об использовании осьминогов из Octodex см. [Часто задаваемые вопросы по Octodex](https://octodex.github.com/faq/).
