可接受使用政策 - GitHub 文档(function(){
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

[主](/zh)

[Site policy](/zh/site-policy)
----------

1. [站点政策](/zh/site-policy)
2. [可接受使用政策](/zh/site-policy/acceptable-use-policies)

可接受使用政策
==========

[GitHub 可接受使用政策](/zh/site-policy/acceptable-use-policies/github-acceptable-use-policies)
----------

[GitHub 上的活跃恶意软件或攻击](/zh/site-policy/acceptable-use-policies/github-active-malware-or-exploits)
----------

[GitHub 上的欺凌和骚扰](/zh/site-policy/acceptable-use-policies/github-bullying-and-harassment)
----------

[在 GitHub 上扰乱其他用户的体验](/zh/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)
----------

[在 GitHub 上进行人肉搜索和侵犯隐私](/zh/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)
----------

[GitHub 仇恨言论和歧视](/zh/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)
----------

[在 GitHub 上冒充他人](/zh/site-policy/acceptable-use-policies/github-impersonation)
----------

[GitHub 上的错误信息和虚假信息](/zh/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)
----------

[GitHub 上的性淫秽内容](/zh/site-policy/acceptable-use-policies/github-sexually-obscene-content)
----------

[GitHub 上的暴力威胁和无端暴力内容](/zh/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)
----------

[GitHub 恐怖主义和暴力极端主义](/zh/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
----------

[GitHub 儿童性剥削或虐待](/zh/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)
----------

[GitHub 非自愿私密图像](/zh/site-policy/acceptable-use-policies/github-non-consensual-intimate-imagery)
----------

[GitHub 合成媒体和 AI 工具](/zh/site-policy/acceptable-use-policies/github-synthetic-media-and-ai-tools)
----------

[GitHub 申诉和恢复](/zh/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)
----------
