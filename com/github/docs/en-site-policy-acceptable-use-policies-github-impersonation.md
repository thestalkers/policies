GitHub Impersonation - GitHub Docs(function(){
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

Collapse sidebarExpand sidebar

Scroll breadcrumbs left

1. [Home](/en)
2. [Site policy](/en/site-policy)
3. [Acceptable Use Policies](/en/site-policy/acceptable-use-policies)
4. [Impersonation](/en/site-policy/acceptable-use-policies/github-impersonation)

Scroll breadcrumbs right

[Site policy](/en/site-policy)
----------

GitHub Impersonation
==========

Copy as Markdown

You may not misrepresent your identity or your association with another person or organization. This includes doing any of the following in a way that misleads or deceives others:

* Copying another user's avatar or other personal profile information
* Posting content under another user's email address
* Using a deceptively similar username, organization name, or other namespace
* Accessing an account or organization with another user's token or credentials
* Otherwise posing as another individual or organization

Impersonation is a form of harassment and violation of this policy may lead to loss of access to your account.

Please note, having a username similar to another is not necessarily impersonation. GitHub will take context into account. For example, as in cases involving claims of [misinformation or disinformation](/en/site-policy/acceptable-use-policies/github-misinformation-and-disinformation), we generally allow parody and satire that is in line with our [Acceptable Use Policies](/en/site-policy/acceptable-use-policies/github-acceptable-use-policies).
