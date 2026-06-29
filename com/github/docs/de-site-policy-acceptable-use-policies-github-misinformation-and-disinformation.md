GitHub Fehlinformationen und Desinformationen - GitHub Dokumente(function(){
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

[Startseite](/de)

[Site policy](/de/site-policy)
----------

* [Websiterichtlinie](/de/site-policy)/
* [Richtlinien zur akzeptablen Nutzung](/de/site-policy/acceptable-use-policies)/
* [Richtlinie zu Desinformation](/de/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)

GitHub Fehlinformationen und Desinformationen
==========

Als Markdown kopieren

Sie dürfen keine Inhalte veröffentlichen, die ein verzerrtes Bild der Realität vermitteln, unabhängig davon, ob sie ungenau oder falsch (Fehlinformation) oder absichtlich irreführend (Desinformation) sind, wenn diese Inhalte geeignet sind, der Öffentlichkeit Schaden zuzufügen oder faire und gleiche Chancen zu beeinträchtigen dass alle an einer freien und offenen Gesellschaft teilhaben können. Dies kann beinhalten:

* Ungenaue oder wissenschaftlich nicht belegte medizinische Behauptungen, die die öffentliche Gesundheit oder Sicherheit gefährden
* Manipulierte Medien, ob audiovisuell oder visuell, die wahrscheinlich auf eine Weise irreführen oder täuschen, die dem öffentlichen Interesse schaden kann
* Falsche oder irreführende Inhalte, die wahrscheinlich die Fähigkeit einer Person beeinträchtigen, an bürgerlichen Aktivitäten teilzunehmen
* Unbegründete Behauptungen, die Hass oder gezielte Belästigung bestimmter Personengruppen fördern könnten

Wir fördern die aktive Teilnahme am Ausdruck von Ideen, Perspektiven und Erfahrungen und sind möglicherweise nicht in der Lage, persönliche Berichte oder Beobachtungen zu bestreiten. Wir erlauben grundsätzlich Parodien und Satire, solange unsere [Acceptable Use Policy](/de/site-policy/acceptable-use-policies/github-acceptable-use-policies) dabei eingehalten wird. Wir halten den Kontext für wichtig, wenn es darum geht, wie Informationen aufgenommen und verstanden werden. Bei der Überprüfung von Inhalten gemäß dieser Richtlinie berücksichtigt GitHub die Auswirkungen verschiedener Faktoren, die bei der Orientierung des Betrachters hilfreich sein können, z Informationen geteilt werden.
