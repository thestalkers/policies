Koordinierte Offenlegung von Sicherheitslücken - GitHub Dokumente(function(){
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
3. [Sicherheitsrichtlinien](/de/site-policy/security-policies)
4. [Koordinierte Offenlegung von Sicherheitslücken](/de/site-policy/security-policies/coordinated-disclosure-of-security-vulnerabilities)

Breadcrumbs nach rechts scrollen

[Site policy](/de/site-policy)
----------

Koordinierte Offenlegung von Sicherheitslücken
==========

Als Markdown kopieren

Wir möchten GitHub für alle sicher halten. Wenn Sie eine Sicherheitslücke in GitHub entdeckt haben, schätzen wir Ihre Hilfe, indem Sie uns diese auf koordinierte Weise mitteilen.

[Bounty-Programm](#bounty-program)
----------

Wie mehrere andere große Softwareunternehmen bietet GitHub eine Prämie für Fehler, um besser mit Sicherheitsforschern in Kontakt zu treten. Die Idee ist einfach: Hacker und Sicherheitsexperten (wie Sie) finden und melden Schwachstellen durch unseren koordinierten Offenlegungsprozess. Um den erheblichen Aufwand zu würdigen, den diese Forscher oft bei der Suche nach Fehlern aufwenden, belohnen wir sie mit etwas barem Geld.

Auf der [GitHub Bug Bounty](https://bounty.github.com)-Seite sind ausführlichere Angaben zu finden. Außerdem sollten Sie sich auch die umfassende [Richtlinie zum Safe-Harbor-Verfahren](/de/site-policy/security-policies/github-bug-bounty-program-legal-safe-harbor) durchlesen. Viel Glück bei der Jagd nach Sicherheitslücken!
