GitHub Sexually Obscene Content - GitHub Docs(function(){
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

[Home](/en)

[Site policy](/en/site-policy)
----------

* [Site policy](/en/site-policy)/
* [Acceptable Use Policies](/en/site-policy/acceptable-use-policies)/
* [Sexually Obscene Content](/en/site-policy/acceptable-use-policies/github-sexually-obscene-content)

GitHub Sexually Obscene Content
==========

Copy as Markdown

We do not tolerate content associated with sexual exploitation or abuse of another individual, including where [minors are concerned](/en/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse). We do not allow sexually themed or suggestive content that serves little or no purpose other than to solicit an erotic or shocking response, particularly where that content is amplified by its placement in profiles or other social contexts. This includes:

* Pornographic content
* Non-consensual intimate imagery
* Graphic depictions of sexual acts including photographs, video, animation, drawings, computer-generated images, or text-based content

We recognize that not all nudity or content related to sexuality is obscene. We may allow visual and/or textual depictions in artistic, educational, historical or journalistic contexts, or as it relates to victim advocacy. In some cases a disclaimer can help communicate the context of the project. However, please understand that we may choose to limit the content by giving users the option to opt in before viewing.
