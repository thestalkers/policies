Политики конфиденциальности - GitHub Docs(function(){
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

1. [Домашняя страница](/ru)
2. [Политика сайта](/ru/site-policy)
3. [Политики конфиденциальности](/ru/site-policy/privacy-policies)

Scroll breadcrumbs right

[Site policy](/ru/site-policy)
----------

Политики конфиденциальности
==========

[Общие заявления о конфиденциальности GitHub](/ru/site-policy/privacy-policies/github-general-privacy-statement)
----------

[Дополнительные обработчики данных GitHub](/ru/site-policy/privacy-policies/github-subprocessors)
----------

[Cookie-файлы GitHub](/ru/site-policy/privacy-policies/github-cookies)
----------

[Глобальное уведомление о конфиденциальности данных для кандидатов на GitHub](/ru/site-policy/privacy-policies/github-candidate-privacy-policy)
----------
