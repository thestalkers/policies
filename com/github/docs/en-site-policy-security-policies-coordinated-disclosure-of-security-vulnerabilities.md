Coordinated Disclosure of Security Vulnerabilities - GitHub Docs(function(){
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
var q=window.matchMedia?window.matchMedia('(prefers-color-scheme: dark)'):null;
var apply=function(){
var night=css.colorMode==='auto'?!!(q&&q.matches):css.colorMode==='dark';
var theme=night?css.darkTheme:css.lightTheme;
var mode=theme.indexOf('dark')===0?'dark':'light';
h.setAttribute('data-color-mode',mode);
h.setAttribute('data-'+mode+'-theme',theme);
};
h.setAttribute('data-color-mode-preference',css.colorMode);
h.setAttribute('data-light-theme',css.lightTheme);
h.setAttribute('data-dark-theme',css.darkTheme);
apply();
if(css.colorMode==='auto'&&q){
if(q.addEventListener)q.addEventListener('change',apply);
else if(q.addListener)q.addListener(apply);
}
}catch(e){}
})();

[Skip to main content](#main-content)

[Skip to content](#main-content)

Collapse sidebarExpand sidebar

Scroll breadcrumbs left

1. [Home](/en)
2. [Site policy](/en/site-policy)
3. [Security Policies](/en/site-policy/security-policies)
4. Coordinated Disclosure of Security Vulnerabilities

Scroll breadcrumbs right

[Site policy](/en/site-policy)
----------

Coordinated Disclosure of Security Vulnerabilities
==========

Copy markdown

We want to keep GitHub safe for everyone. If you've discovered a security vulnerability in GitHub, we appreciate your help in disclosing it to us in a coordinated manner.

[Bounty Program](#bounty-program)
----------

Like several other large software companies, GitHub provides a bug bounty to better engage with security researchers. The idea is simple: hackers and security researchers (like you) find and report vulnerabilities through our coordinated disclosure process. Then, to recognize the significant effort that these researchers often put forth when hunting down bugs, we reward them with some cold hard cash.

Check out the [GitHub Bug Bounty](https://bounty.github.com) site for bounty details, review our comprehensive [Legal Safe Harbor Policy](/en/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor) terms as well, and happy hunting!
