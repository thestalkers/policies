GitHub Hassreden und Diskriminierung - GitHub Dokumente(function(){
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
3. [Richtlinien zur akzeptablen Nutzung](/de/site-policy/acceptable-use-policies)
4. [Hassreden und Diskriminierung](/de/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)

Scroll breadcrumbs right

[Site policy](/de/site-policy)
----------

GitHub Hassreden und Diskriminierung
==========

Als Markdown kopieren

GitHub toleriert keine Äußerungen, die Hass gegen eine Einzelperson oder eine Gruppe von Menschen aufgrund ihrer Person angreifen oder fördern, einschließlich Alter, Körpergröße, Fähigkeiten, ethnische Zugehörigkeit, Geschlechtsidentität und -ausdruck, Erfahrungsniveau, Nationalität, persönliches Aussehen, Rasse, Religion, sexuelle Identität oder sexuelle Orientierung. Dies schließt Folgendes ein:

* Eine Person oder Gruppe aufgrund ihrer Überzeugungen oder der oben aufgeführten Eigenschaften verspotten, angreifen oder ausgrenzen
* Anzeigen einer eindeutigen Zugehörigkeit oder Identifikation mit bekannten [terroristischen oder gewaltbereiten extremistischen Organisationen](/de/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
* Unterstützung oder Förderung von Hassgruppen oder auf Hass basierenden Verschwörungstheorien
* Das Teilen von Symbolen oder Bildern, die gleichbedeutend mit Hass sind
* Verwendung schädlicher Stereotypen, Beleidigungen oder entmenschlichender Sprache
* Angriff auf eine Person aufgrund ihres wahrgenommenen Geschlechts
* Hundepfeifen; oder die Verwendung verschlüsselter oder anzüglicher Sprache und/oder Symbole, um Missbrauch oder Hass zu fördern

Während GitHub alle Fälle von Missbrauch und Belästigung auf der Plattform ernst nimmt, setzen wir uns besonders dafür ein, auf Hass basierenden Missbrauch zu bekämpfen, wenn er überproportional Communitys betrifft, die in der Vergangenheit von solchem Missbrauch betroffen waren. Unser Ziel ist es, GitHub zu einem Ort zu machen, an dem sich alle Menschen willkommen und sicher fühlen.
