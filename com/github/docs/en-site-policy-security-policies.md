Security Policies - GitHub Docs(function(){
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
3. [Security Policies](/en/site-policy/security-policies)

Scroll breadcrumbs right

[Site policy](/en/site-policy)
----------

Security Policies
==========

* [Coordinated Disclosure of Security Vulnerabilities, 1 of 3](/en/site-policy/security-policies/coordinated-disclosure-of-security-vulnerabilities)
* [GitHub Bug Bounty Program Legal Safe Harbor, 2 of 3](/en/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor)
* [GitHub SIRT description RFC 2350, 3 of 3](/en/site-policy/security-policies/github-sirt-description-rfc-2350)
