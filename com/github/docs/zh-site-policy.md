站点政策文档 - GitHub 文档(function(){
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

向右滚动痕迹导航

[Site policy](/zh/site-policy)
----------

站点政策文档
==========

查看 GitHub 的服务条款、可接受使用政策、隐私做法、内容删除流程及其他站点政策。

[概述](/site-policy/github-terms/github-terms-of-service)

建议
----------

[### GitHub 服务条款 ###](/zh/free-pro-team@latest/site-policy/github-terms/github-terms-of-service)[### GitHub 一般隐私声明 ###](/zh/free-pro-team@latest/site-policy/privacy-policies/github-general-privacy-statement)[### GitHub 可接受使用政策 ###](/zh/free-pro-team@latest/site-policy/acceptable-use-policies/github-acceptable-use-policies)

文章
----------

类别: 所有类别

[Request content removal ### DMCA 下架政策 ###](/zh/site-policy/content-removal-policies/dmca-takedown-policy)[Request content removal ### DMCA 下架通知提交指南 ###](/zh/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)[Request content removal ### DMCA 抗辩通知提交指南 ###](/zh/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)[Review privacy and security policies ### GitHub Bug 赏金计划法律安全港 ###](/zh/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor)[Review privacy and security policies ### GitHub Cookie ###](/zh/site-policy/privacy-policies/github-cookies)[Review product and program terms ### GitHub Copilot 扩展开发人员策略 ###](/zh/site-policy/github-terms/github-copilot-extension-developer-policy)[Review product and program terms ### GitHub DPA 约束的预览版 ###](/zh/site-policy/github-terms/github-dpa-previews)[Review company and general policies ### GitHub GPL 合作承诺 ###](/zh/site-policy/github-company-policies/github-gpl-cooperation-commitment)[Review product and program terms ### GitHub Marketplace 开发人员协议 ###](/zh/site-policy/github-terms/github-marketplace-developer-agreement)

显示 57 的 1-9

[Previous]()[1](#1)[2](#2)[3](#3)[4](#4)[5](#5)[6](#6)[7](#7)[Next](#2)
