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

折叠边栏

展开侧边栏

1. [主](/zh)
2. 站点政策

[Site policy](/zh/site-policy)
----------

站点政策文档
==========

查看 GitHub 的服务条款、可接受使用政策、隐私做法、内容删除流程及其他站点政策。

[概述](/site-policy/github-terms/github-terms-of-service)

建议
----------

### [GitHub 服务条款](/zh/free-pro-team@latest/site-policy/github-terms/github-terms-of-service) ###

### [GitHub 一般隐私声明](/zh/free-pro-team@latest/site-policy/privacy-policies/github-general-privacy-statement) ###

### [GitHub 可接受使用政策](/zh/free-pro-team@latest/site-policy/acceptable-use-policies/github-acceptable-use-policies) ###

文章
----------

类别: 所有类别

Request content removal

### [提交内容删除请求](/zh/site-policy/content-removal-policies/submitting-content-removal-requests) ###

Review privacy and security policies

### [协调披露安全漏洞](/zh/site-policy/security-policies/coordinated-disclosure-of-security-vulnerabilities) ###

Review company and general policies

### [用户数据法律请求准则](/zh/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data) ###

Follow acceptable use policies

### [在 GitHub 上进行人肉搜索和侵犯隐私](/zh/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy) ###

Follow acceptable use policies

### [在 GitHub 上冒充他人](/zh/site-policy/acceptable-use-policies/github-impersonation) ###

Follow acceptable use policies

### [在 GitHub 上扰乱其他用户的体验](/zh/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users) ###

Request content removal

### [DMCA 抗辩通知提交指南](/zh/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice) ###

Request content removal

### [DMCA 下架通知提交指南](/zh/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) ###

Request content removal

### [DMCA 下架政策](/zh/site-policy/content-removal-policies/dmca-takedown-policy) ###

显示 57 的 1-9

[Previous]()[1](#1)[2](#2)[3](#3)[4](#4)[5](#5)[6](#6)[7](#7)[Next](#2)
