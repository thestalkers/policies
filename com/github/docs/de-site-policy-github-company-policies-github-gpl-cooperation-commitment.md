GitHub GPL Kooperationsverpflichtung - GitHub Dokumente(function(){
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
3. [GitHub-Unternehmensrichtlinien](/de/site-policy/github-company-policies)
4. [GitHub GPL Kooperationsverpflichtung](/de/site-policy/github-company-policies/github-gpl-cooperation-commitment)

Breadcrumbs nach rechts scrollen

[Site policy](/de/site-policy)
----------

GitHub GPL Kooperationsverpflichtung
==========

Als Markdown kopieren

Diese Verpflichtung bezieht sich auf GitHub-Beiträge zu Git, dem Linux-Kernel und anderen Programmen unter abgedeckten Lizenzen (scrollen Sie bis zum Ende für Definitionen).

Wir stützen unsere Erklärung auf die [Vorlage](https://github.com/gplcc/gplcc/blob/master/Company/GPL%20Cooperation%20Commitment-Company-Template.md) für Unternehmen. Siehe die [Webseite zur GPL-Kooperationsverpflichtung](https://gplcc.github.io/gplcc/) dazu, wie andere Unternehmen, Einzelpersonen und Projekte diese Verpflichtung übernehmen können.

[Unsere Hingabe](#our-commitment)
----------

Vor der Einleitung oder Fortsetzung der Verfolgung von Gerichtsverfahren oder Ansprüchen (außer einer Abwehrmaßnahme), die sich aus der Kündigung einer abgedeckten Lizenz ergeben, verpflichtet sich GitHub, der natürlichen oder juristischen Person („Sie“), die beschuldigt wird, die abgedeckte Lizenz verletzt zu haben, die folgenden Bestimmungen zu übermitteln Heilung und Wiederherstellung, entnommen aus GPL Version 3. Wie hier verwendet, bezieht sich der Begriff „diese Lizenz“ auf die spezifische abgedeckte Lizenz, die durchgesetzt wird.

Wenn Sie jedoch jegliche Verletzung dieser Lizenz einstellen, wird Ihre Lizenz von einem bestimmten Urheberrechtsinhaber (a) vorläufig wiederhergestellt, es sei denn und bis der Urheberrechtsinhaber Ihre Lizenz ausdrücklich und endgültig kündigt, und (b) dauerhaft, wenn der Urheberrechtsinhaber versagt um Sie vor Ablauf von 60 Tagen nach Beendigung mit angemessenen Mitteln über die Verletzung zu informieren.

Darüber hinaus wird Ihre Lizenz von einem bestimmten Urheberrechtsinhaber dauerhaft wiederhergestellt, wenn der Urheberrechtsinhaber Sie auf angemessene Weise über die Verletzung informiert, dies das erste Mal ist, dass Sie von diesem Urheberrechtsinhaber eine Benachrichtigung über eine Verletzung dieser Lizenz (für ein Werk) erhalten, und Sie den Verstoß innerhalb von 30 Tagen nach Erhalt der Mitteilung beheben.

GitHub beabsichtigt, dass diese Verpflichtung unwiderruflich, bindend und durchsetzbar gegenüber GitHub und Zessionaren oder Rechtsnachfolgern von GitHubs Urheberrechten ist.

GitHub kann diese Verpflichtung ändern, indem es eine neue Ausgabe auf dieser Seite oder einem Nachfolgestandort veröffentlicht.

Definitionen

„Abgedeckte Lizenz“ bezeichnet die GNU General Public License, Version 2 (GPLv2), die GNU Lesser General Public License, Version 2.1 (LGPLv2.1), oder die GNU Library General Public License, Version 2 (LGPLv2), alle wie veröffentlicht von die Free Software Foundation.

„Abwehrmaßnahme“ bezeichnet ein Gerichtsverfahren oder einen Anspruch, den GitHub als Reaktion auf ein vorheriges Verfahren oder einen Anspruch, der von Ihnen oder Ihrem verbundenen Unternehmen eingeleitet wurde, gegen Sie erhebt.

„GitHub“ bezeichnet GitHub, Inc. und seine Tochtergesellschaften.

Dieses Werk ist unter einer Creative Commons Attribution-ShareAlike 4.0 International-Lizenz verfügbar.
