GitHub Threats of Violence and Gratuitously Violent Content - GitHub Docs(function(){
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
* [Threats of Violence and Gratuitously Violent Content](/en/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)

GitHub Threats of Violence and Gratuitously Violent Content
==========

Copy as Markdown

You may not use GitHub to organize, promote, encourage, threaten, or incite acts of violence. You may not post content that depicts or glorifies violence or physical harm against human beings or animals. This includes:

* Threatening another individual or group with abuse, harm, sexual violence, or death
* Posting text, imagery, or audio content glorifying or containing a graphic depiction of violence toward oneself, another individual, group, or animal
* Encouraging another individual to engage in self harm

We do not allow violent content to be posted indiscriminately or in a way that is difficult for other users to avoid, such as a profile avatar or an issue comment. However, we understand there may be legitimate reasons to post violent content, such as for educational or documentary purposes, creative works, or depictions of historical events. In those cases, a clear warning or disclaimer can help users make an educated decision as to whether or not they want to engage with such content. Still, GitHub may decide to limit the visibility of such content to those who choose to opt in.
