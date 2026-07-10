GitHub Bullying and Harassment - GitHub Docs(function(){
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

1. [Site policy](/en/site-policy)
2. [Acceptable Use Policies](/en/site-policy/acceptable-use-policies)
3. [Bullying and Harassment](/en/site-policy/acceptable-use-policies/github-bullying-and-harassment)

GitHub Bullying and Harassment
==========

Copy as Markdown

We do not tolerate harassment, bullying, or abuse of any kind, whether directly or by encouraging others to take part in the prohibited conduct. This includes:

* Targeted personal attacks
* Piling on to or orchestrating [disruptive](/en/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users) activity in a way that amounts to abuse
* Following another user around the platform in a manner that causes intimidation
* Making sexual advances or comments directed at another individual
* Disingenuously participating in conversation in a way that instigates conflict or undermines sincere discussion
* Creating alternative accounts specifically to evade moderation action taken by GitHub staff or users

Please note, not all unwelcome conduct is necessarily considered harassment. For example, disagreeing with another user or downvoting their comments may not rise to the level of harassment on our platform. In addition, sharing criticism of public figures or projects, or topics of public interest, does not necessarily fall under this policy. However, we encourage you to be mindful in how you engage with other users and the platform, as this activity may still violate our restriction on disrupting the experience of other users.
