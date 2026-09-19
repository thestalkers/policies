Andere Website-Richtlinien - GitHub Dokumente(function(){
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

Randleiste reduzierenRandleiste erweitern

Breadcrumbs nach links scrollen

1. [Startseite](/de)
2. [Websiterichtlinie](/de/site-policy)
3. Andere Website-Richtlinien

Breadcrumbs nach rechts scrollen

[Site policy](/de/site-policy)
----------

Andere Website-Richtlinien
==========

[GitHub und Handelskontrollen](/de/site-policy/other-site-policies/github-and-trade-controls)
----------

[GitHub-Richtlinie für verstorbene Benutzer](/de/site-policy/other-site-policies/github-deceased-user-policy)
----------

[GitHub-Logo-Richtlinie](/de/site-policy/other-site-policies/github-logo-policy)
----------

[GitHub Government Takedown-Richtlinie](/de/site-policy/other-site-policies/github-government-takedown-policy)
----------

[GitHub-Richtlinie für Benutzernamen](/de/site-policy/other-site-policies/github-username-policy)
----------

[Richtlinien für rechtliche Anfragen von Benutzerdaten](/de/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)
----------

[Wiederherstellungsrichtlinie für GitHub-Konten](/de/site-policy/other-site-policies/github-account-recovery-policy)
----------
