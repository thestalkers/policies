GitHub Misinformation and Disinformation - GitHub Docs(function(){
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
3. [Acceptable Use Policies](/en/site-policy/acceptable-use-policies)
4. Disinformation Policy

Scroll breadcrumbs right

[Site policy](/en/site-policy)
----------

GitHub Misinformation and Disinformation
==========

Copy markdown

You may not post content that presents a distorted view of reality, whether it is inaccurate or false (misinformation) or is intentionally deceptive (disinformation), where such content is likely to result in harm to the public or to interfere with fair and equal opportunities for all to take part in a free and open society. This may include:

* Inaccurate or scientifically unsupported medical claims that endanger public health or safety
* Manipulated media, whether audio or visual, likely to mislead or deceive in a way that may harm the public interest
* False or misleading content likely to interfere with an individual's ability to participate in civic activities
* Unsubstantiated claims that could promote hate or targeted harassment of specific groups of people

We encourage active participation in the expression of ideas, perspectives, and experiences and may not be in a position to dispute personal accounts or observations. We generally allow parody and satire that is in line with our [Acceptable Use Policies](/en/site-policy/acceptable-use-policies/github-acceptable-use-policies), and we consider context to be important in how information is received and understood. When reviewing content under this policy, GitHub will consider the impact of various factors that may help to orient the viewer, such as whether the content has been provided with clear disclaimers, citations to credible sources, or includes other details that clarify the accuracy of the information being shared.
