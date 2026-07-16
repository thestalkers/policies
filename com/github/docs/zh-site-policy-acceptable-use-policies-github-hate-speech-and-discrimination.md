GitHub 仇恨言论和歧视 - GitHub 文档(function(){
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
4. [仇恨言论和歧视](/zh/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)

向右滚动痕迹导航

[Site policy](/zh/site-policy)
----------

GitHub 仇恨言论和歧视
==========

复制为 Markdown 格式

GitHub 不容忍基于个人或群体的特征（包括年龄、体型、能力、民族、性别认同和表达、经验水平、国籍、个人外表、种族、宗教、性身份或性取向）攻击或宣扬对个人或群体的仇恨言论。 其中包括：

* 基于个人或团体的信仰或上述特征，嘲笑、攻击或排斥他们
* 与已知的[恐怖主义组织或暴力极端主义组织](/zh/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)有明确的隶属关系或相关身份
* 支持或宣扬仇恨团体或基于仇恨的阴谋论
* 分享与仇恨同义的符号或图像
* 使用有害的刻板印象、诽谤或非人性化言论
* 以个人的感知性别为依据攻击他们
* 吹狗哨；或使用编码或暗示性语言和/或符号来宣扬虐待或仇恨

虽然 GitHub 会认真对待平台上的所有滥用和骚扰事件，但我们特别致力于打击基于仇恨的滥用行为，因为它会不当地影响社区，以往，社区一直是此类滥用行为的目标。 我们的目标是让 GitHub 成为一个让所有人都感到受欢迎和安全的地方。
