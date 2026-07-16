GitHub 上的错误信息和虚假信息 - GitHub 文档(function(){
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
3. [可接受使用政策](/zh/site-policy/acceptable-use-policies)
4. [虚假信息政策](/zh/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)

向右滚动痕迹导航

[Site policy](/zh/site-policy)
----------

GitHub 上的错误信息和虚假信息
==========

复制为 Markdown 格式

您不得发布歪曲事实的内容，包括不准确或不实内容（错误信息）或故意造成假象的内容（虚假信息），导致可能危害公共利益或妨碍所有人获得享受自由和开放社会的公平和平等机会。 这可能包括：

* 危害公共健康或安全的不准确或无科学依据的医疗宣传
* 操纵媒体（无论是音频还是视频），导致可能引起误导或欺骗并因此而有可能危害公共利益
* 可能妨碍个人参与公民活动之能力的虚假或误导性内容
* 可能煽动对于特定群体的仇恨或针对性骚扰的未经证实的宣传

我们鼓励人们积极参与表达意见、观点和经历，并且无权对个人陈述或言论提出争议。 一般情况下，我们允许在符合我们的[可接受使用政策](/zh/site-policy/acceptable-use-policies/github-acceptable-use-policies)的前提下发表嘲弄和讽刺，并且我们认为背景信息在人们对信息的接受和理解中扮演着重要角色。 在根据本政策审查内容时，GitHub 将考虑可能有助于引导浏览者的各种因素的影响，例如，在提供内容时是否作出了明确的免责声明，是否引用了可信来源，或者是否包括其他详细信息以澄清所共享的信息的准确性。
