Политика компании #REF! - GitHub Docs(function(){
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
2. [Политика компании #REF!](/ru/site-policy/github-company-policies)

Политика компании #REF!
==========

[Заявление GitHub против современного рабства и детского труда](/ru/site-policy/github-company-policies/github-statement-against-modern-slavery-and-child-labor)
----------

[Заявление GitHub о борьбе со взяточничеством](/ru/site-policy/github-company-policies/github-anti-bribery-statement)
----------

[Обязательство сотрудничества с GitHub GPL](/ru/site-policy/github-company-policies/github-gpl-cooperation-commitment)
----------

[Политика GitHub в отношении подарков и развлечений](/ru/site-policy/github-company-policies/github-gifts-and-entertainment-policy)
----------
