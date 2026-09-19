协调披露安全漏洞 - GitHub 文档(function(){
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

折叠边栏展开侧边栏

向左滚动痕迹导航

1. [主](/zh)
2. [站点政策](/zh/site-policy)
3. [安全政策](/zh/site-policy/security-policies)
4. 协调披露安全漏洞

向右滚动痕迹导航

[Site policy](/zh/site-policy)
----------

协调披露安全漏洞
==========

复制 markdown

我们希望每个人都能安全地使用 GitHub。 当您发现 GitHub 中的安全漏洞时，如果您能以协调一致的方式向我们披露，我们将深表感谢。

[赏金计划](#bounty-program)
----------

为更好地吸引安全研究人员参与，GitHub 也像其他一些大型软件公司一样提供 Bug 赏金。 我们的思路很简单：黑客和安全研究人员（像您一样）发现漏洞并通过我们的协调披露流程报告漏洞。 然后，为了认可这些研究人员在寻找 Bug 时付出的巨大努力，我们用一些真金白银奖励他们。

请查看 [GitHub Bug 赏金](https://bounty.github.com)站点了解赏金详情，并阅读我们全面的[法律安全港政策](/zh/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor)条款，我们期待您大展身手！
