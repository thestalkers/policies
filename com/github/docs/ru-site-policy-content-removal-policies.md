Политики удаления контента - GitHub Docs(function(){
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
2. [Политики удаления контента](/ru/site-policy/content-removal-policies)

Политики удаления контента
==========

[Отправка запросов на удаление содержимого](/ru/site-policy/content-removal-policies/submitting-content-removal-requests)
----------

[Политика удаления DMCA](/ru/site-policy/content-removal-policies/dmca-takedown-policy)
----------

[Политика удаления личной информации GitHub](/ru/site-policy/content-removal-policies/github-private-information-removal-policy)
----------

[Политика GitHub в отношении товарных знаков](/ru/site-policy/content-removal-policies/github-trademark-policy)
----------

[Руководство по подаче встречного уведомления DMCA](/ru/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)
----------

[Руководство по подаче уведомления об удалении DMCA](/ru/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)
----------
