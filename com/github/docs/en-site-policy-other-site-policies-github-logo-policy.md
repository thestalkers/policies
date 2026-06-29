GitHub Logo Policy - GitHub Docs(function(){
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
* [Other Site Policies](/en/site-policy/other-site-policies)/
* [GitHub Logo Policy](/en/site-policy/other-site-policies/github-logo-policy)

GitHub Logo Policy
==========

Copy as Markdown

You can add GitHub logos to your website or third-party application in some scenarios. For more information and specific guidelines on logo usage, see the [GitHub Logos and Usage page](https://github.com/logos).

You can also use an octocat as your personal avatar or on your website to link to your GitHub account, but not for your company or a product you're building. GitHub has an extensive collection of octocats in the [Octodex](https://octodex.github.com/). For more information on using the octocats from the Octodex, see the [Octodex FAQ](https://octodex.github.com/faq/).
