GitHub 上的欺凌和骚扰 - GitHub 文档(function(){
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

* [站点政策](/zh/site-policy)/
* [可接受使用政策](/zh/site-policy/acceptable-use-policies)/
* [欺凌和骚扰](/zh/site-policy/acceptable-use-policies/github-bullying-and-harassment)

GitHub 上的欺凌和骚扰
==========

复制为 Markdown 格式

我们不容忍任何形式的骚扰、欺凌或虐待，无论是直接还是鼓励他人参与违禁行为。 其中包括：

* 针对性的人身攻击
* 以近乎于虐待的方式实施或策划[破坏性](/zh/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)活动
* 以一种会导致威胁的方式关注平台上的其他用户
* 发出针对他人的性骚扰或性评论
* 以煽动冲突或破坏真诚讨论的方式虚伪地参与对话
* 创建专门用于逃避 GitHub 员工或用户采取的审核操作的备用帐户

请注意，并非所有不受欢迎的行为都一定被视为骚扰。 例如，与其他用户意见不一致或对他们的评论投反对票可能不会上升到我们平台上的骚扰级别。 此外，分享对公众人物或公共项目或公众感兴趣的话题的批评，并不一定受此政策约束。 然而，我们建议您注意您与其他用户和平台的互动方式，因为此活动仍可能违反我们对破坏其他用户体验的限制。
