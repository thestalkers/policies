Dokumentation zur Websiterichtlinie - GitHub Dokumente(function(){
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

1. [Startseite](/de)
2. [Websiterichtlinie](/de/site-policy)

Scroll breadcrumbs right

[Site policy](/de/site-policy)
----------

Dokumentation zur Websiterichtlinie
==========

Überprüfen Sie die Vertragsbedingungen von GitHub, die Richtlinien zur akzeptablen Nutzung, die Datenschutzpraktiken, die Verfahren zum Entfernen von Inhalten und andere Websiterichtlinien.

[Übersicht](/site-policy/github-terms/github-terms-of-service)

Empfohlen
----------

[### GitHub-Nutzungsbedingungen ###](/de/free-pro-team@latest/site-policy/github-terms/github-terms-of-service)[### Allgemeine Datenschutzerklärung für GitHub ###](/de/free-pro-team@latest/site-policy/privacy-policies/github-general-privacy-statement)[### GitHub-Richtlinien zur akzeptablen Nutzung ###](/de/free-pro-team@latest/site-policy/acceptable-use-policies/github-acceptable-use-policies)

Artikel
----------

Kategorie: Alle Kategorien

[Review privacy and security policies ### Allgemeine Datenschutzerklärung für GitHub ###](/de/site-policy/privacy-policies/github-general-privacy-statement)[Review product and program terms ### Allgemeine Geschäftsbedingungen für GitHub-Open-Source-Anwendungen ###](/de/site-policy/github-terms/github-open-source-applications-terms-and-conditions)[Request content removal ### Anleitung zum Einreichen einer DMCA-Gegendarstellung ###](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)[Review product and program terms ### Bedingungen des GitHub-Forschungsprogramms ###](/de/site-policy/github-terms/github-research-program-terms)[Review product and program terms ### Bedingungen für GitHub-Events ###](/de/site-policy/github-terms/github-event-terms)[Review privacy and security policies ### Beschreibung des GitHub SIRT RFC 2350 ###](/de/site-policy/security-policies/github-sirt-description-rfc-2350)[Request content removal ### DMCA Takedown-Richtlinie ###](/de/site-policy/content-removal-policies/dmca-takedown-policy)[Review product and program terms ### Durch DPA abgedeckte Vorschauversionen auf GitHub ###](/de/site-policy/github-terms/github-dpa-previews)[Request content removal ### Einreichen von Anträgen auf Entfernung von Inhalten ###](/de/site-policy/content-removal-policies/submitting-content-removal-requests)

Anzeigen 1 bis 9 von 57

[Previous]()[1](#1)[2](#2)[3](#3)[4](#4)[5](#5)[6](#6)[7](#7)[Next](#2)
