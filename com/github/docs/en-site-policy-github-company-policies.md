GitHub Company Policies - GitHub Docs(function(){
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
* [GitHub Company Policies](/en/site-policy/github-company-policies)

GitHub Company Policies
==========

* [GitHub Statement Against Modern Slavery and Child Labor, 1 of 4](/en/site-policy/github-company-policies/github-statement-against-modern-slavery-and-child-labor)
* [GitHub Anti-Bribery Statement, 2 of 4](/en/site-policy/github-company-policies/github-anti-bribery-statement)
* [GitHub GPL Cooperation Commitment, 3 of 4](/en/site-policy/github-company-policies/github-gpl-cooperation-commitment)
* [GitHub Gifts and Entertainment Policy, 4 of 4](/en/site-policy/github-company-policies/github-gifts-and-entertainment-policy)
