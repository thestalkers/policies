GitHub Terms - GitHub Docs(function(){
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
3. GitHub Terms

Scroll breadcrumbs right

[Site policy](/en/site-policy)
----------

GitHub Terms
==========

* [GitHub Terms of Service, 1 of 18](/en/site-policy/github-terms/github-terms-of-service)
* [GitHub Corporate Terms of Service, 2 of 18](/en/site-policy/github-terms/github-corporate-terms-of-service)
* [GitHub Terms for Additional Products and Features, 3 of 18](/en/site-policy/github-terms/github-terms-for-additional-products-and-features)
* [GitHub Community Guidelines, 4 of 18](/en/site-policy/github-terms/github-community-guidelines)
* [GitHub Community Code of Conduct, 5 of 18](/en/site-policy/github-terms/github-community-code-of-conduct)
* [GitHub Pre-release License Terms, 6 of 18](/en/site-policy/github-terms/github-pre-release-license-terms)
* [GitHub DPA-Covered Previews, 7 of 18](/en/site-policy/github-terms/github-dpa-previews)
* [GitHub Sponsors Additional Terms, 8 of 18](/en/site-policy/github-terms/github-sponsors-additional-terms)
* [GitHub Registered Developer Agreement, 9 of 18](/en/site-policy/github-terms/github-registered-developer-agreement)
* [GitHub Marketplace Terms of Service, 10 of 18](/en/site-policy/github-terms/github-marketplace-terms-of-service)
* [GitHub Marketplace Developer Agreement, 11 of 18](/en/site-policy/github-terms/github-marketplace-developer-agreement)
* [GitHub Research Program Terms, 12 of 18](/en/site-policy/github-terms/github-research-program-terms)
* [GitHub Open Source Applications Terms and Conditions, 13 of 18](/en/site-policy/github-terms/github-open-source-applications-terms-and-conditions)
* [GitHub Event Terms, 14 of 18](/en/site-policy/github-terms/github-event-terms)
* [GitHub Event Code of Conduct, 15 of 18](/en/site-policy/github-terms/github-event-code-of-conduct)
* [GitHub Educational Use Agreement, 16 of 18](/en/site-policy/github-terms/github-educational-use-agreement)
* [GitHub Copilot Extension Developer Policy, 17 of 18](/en/site-policy/github-terms/github-copilot-extension-developer-policy)
* [GitHub Secret Scanning Partner Program Agreement, 18 of 18](/en/site-policy/github-terms/github-secret-scanning-partner-program-agreement)
