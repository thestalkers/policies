Richtlinien zum Entfernen von Inhalten - GitHub Dokumente(function(){
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

Randleiste reduzierenRandleiste erweitern

Breadcrumbs nach links scrollen

1. [Startseite](/de)
2. [Websiterichtlinie](/de/site-policy)
3. [Richtlinien zum Entfernen von Inhalten](/de/site-policy/content-removal-policies)

Breadcrumbs nach rechts scrollen

[Site policy](/de/site-policy)
----------

Richtlinien zum Entfernen von Inhalten
==========

[Einreichen von Anträgen auf Entfernung von Inhalten](/de/site-policy/content-removal-policies/submitting-content-removal-requests)
----------

[DMCA Takedown-Richtlinie](/de/site-policy/content-removal-policies/dmca-takedown-policy)
----------

[Richtlinie zum Entfernen privater Informationen von GitHub](/de/site-policy/content-removal-policies/github-private-information-removal-policy)
----------

[GitHub-Markenrichtlinie](/de/site-policy/content-removal-policies/github-trademark-policy)
----------

[Anleitung zum Einreichen einer DMCA-Gegendarstellung](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)
----------

[Leitfaden zum Einreichen einer DMCA-Takedown-Mitteilung](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)
----------
