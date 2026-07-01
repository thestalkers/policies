Other Site Policies - GitHub Docs(function(){
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
* [Other Site Policies](/en/site-policy/other-site-policies)

Other Site Policies
==========

* [GitHub and Trade Controls, 1 of 7](/en/site-policy/other-site-policies/github-and-trade-controls)
* [GitHub Deceased User Policy, 2 of 7](/en/site-policy/other-site-policies/github-deceased-user-policy)
* [GitHub Logo Policy, 3 of 7](/en/site-policy/other-site-policies/github-logo-policy)
* [GitHub Government Takedown Policy, 4 of 7](/en/site-policy/other-site-policies/github-government-takedown-policy)
* [GitHub Username Policy, 5 of 7](/en/site-policy/other-site-policies/github-username-policy)
* [Guidelines for Legal Requests of User Data, 6 of 7](/en/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)
* [GitHub Account Recovery Policy, 7 of 7](/en/site-policy/other-site-policies/github-account-recovery-policy)
