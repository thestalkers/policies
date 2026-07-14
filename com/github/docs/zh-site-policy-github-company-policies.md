GitHub 公司政策 - GitHub 文档(function(){
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

1. [主](/zh)
2. [站点政策](/zh/site-policy)
3. [GitHub 公司政策](/zh/site-policy/github-company-policies)

Scroll breadcrumbs right

[Site policy](/zh/site-policy)
----------

GitHub 公司政策
==========

[GitHub 反对现代奴役制和童工制的声明](/zh/site-policy/github-company-policies/github-statement-against-modern-slavery-and-child-labor)
----------

[GitHub 反贿赂声明](/zh/site-policy/github-company-policies/github-anti-bribery-statement)
----------

[GitHub GPL 合作承诺](/zh/site-policy/github-company-policies/github-gpl-cooperation-commitment)
----------

[GitHub 礼品和招待政策](/zh/site-policy/github-company-policies/github-gifts-and-entertainment-policy)
----------
