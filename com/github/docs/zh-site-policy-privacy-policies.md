隐私政策 - GitHub 文档(function(){
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

折叠边栏展开侧边栏

向左滚动痕迹导航

1. [主](/zh)
2. [站点政策](/zh/site-policy)
3. [隐私政策](/zh/site-policy/privacy-policies)

向右滚动痕迹导航

[Site policy](/zh/site-policy)
----------

隐私政策
==========

[GitHub 一般隐私声明](/zh/site-policy/privacy-policies/github-general-privacy-statement)
----------

[GitHub 次级处理者](/zh/site-policy/privacy-policies/github-subprocessors)
----------

[GitHub Cookie](/zh/site-policy/privacy-policies/github-cookies)
----------

[GitHub 全球候选人数据隐私声明](/zh/site-policy/privacy-policies/github-candidate-privacy-policy)
----------
