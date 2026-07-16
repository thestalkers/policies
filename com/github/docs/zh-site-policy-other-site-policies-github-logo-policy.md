GitHub 徽标政策 - GitHub 文档(function(){
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
3. [其他站点政策](/zh/site-policy/other-site-policies)
4. [GitHub 徽标政策](/zh/site-policy/other-site-policies/github-logo-policy)

向右滚动痕迹导航

[Site policy](/zh/site-policy)
----------

GitHub 徽标政策
==========

复制为 Markdown 格式

在某些情况下，您可以将 GitHub 徽标添加到您的网站或第三方应用程序中。 有关徽标使用的更多信息和具体指南，请参阅 [GitHub 徽标和使用页面](https://github.com/logos)。

您还可以将章鱼猫用作个人头像或放在网站上作为您的 GitHub 帐户的链接，但不能用于您的公司或您构建的产品。 GitHub 的 [Octodex](https://octodex.github.com/) 中有各种造型的章鱼猫。 有关使用 Octodex 中的章鱼猫的更多信息，请参阅 [Octodex 常见问题解答](https://octodex.github.com/faq/)。
