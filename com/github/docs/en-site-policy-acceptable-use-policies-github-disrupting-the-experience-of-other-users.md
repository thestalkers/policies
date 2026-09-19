GitHub Disrupting the Experience of Other Users - GitHub Docs(function(){
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
4. Disrupting the Experience of Other Users

Scroll breadcrumbs right

[Site policy](/en/site-policy)
----------

GitHub Disrupting the Experience of Other Users
==========

Copy markdown

Being part of a community includes recognizing how your behavior affects others and engaging in meaningful and productive interactions with people and the platform they rely on.

We do not allow behavior that significantly or continually disrupts the experience of other users. This includes:

* Posting off-topic comments
* Opening empty or meaningless issues or pull requests
* Starring and/or following accounts or repositories in large volume in a short period of time
* Creating nonsensical or irrelevant code reviews
* Engaging with platform features in a way that causes excessive notifications for other users
* Using any other platform feature in a way that creates disruption

While we encourage maintainers to moderate their own projects on an individual basis, GitHub staff may take further restrictive action against accounts that are engaging in these types of behaviors.

Please note that the above conduct may also violate other restrictions in our [Acceptable Use Policies](/en/site-policy/acceptable-use-policies/github-acceptable-use-policies). For example, depending on the nature and severity of the activity, it may rise to the level of [bullying and harassment](/en/site-policy/acceptable-use-policies/github-bullying-and-harassment).
