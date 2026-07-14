GitHub Mobbing und Belästigung - GitHub Dokumente(function(){
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
4. [Mobbing und Belästigung](/de/site-policy/acceptable-use-policies/github-bullying-and-harassment)

Scroll breadcrumbs right

[Site policy](/de/site-policy)
----------

GitHub Mobbing und Belästigung
==========

Als Markdown kopieren

Wir tolerieren keinerlei Belästigung, Mobbing oder Missbrauch, sei es direkt oder durch Ermutigung anderer, sich an den verbotenen Verhaltensweisen zu beteiligen. Dies umfasst:

* Gezielte persönliche Angriffe
* Anhäufen oder Orchestrieren [störender](/de/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users) Aktivitäten in einer Weise, die Missbrauch gleichkommt
* Verfolgen eines anderen Benutzers auf der Plattform auf eine Weise, die Einschüchterung hervorruft
* An eine andere Person gerichtete sexuelle Annäherungsversuche oder Kommentare machen
* Unaufrichtige Teilnahme an Gesprächen in einer Weise, die Konflikte auslöst oder eine aufrichtige Diskussion untergräbt
* Erstellen alternativer Konten speziell zum Umgehen von Moderationsmaßnahmen durch GitHub-Mitarbeiter oder -Benutzer

Bitte beachten Sie, dass nicht jedes unerwünschte Verhalten unbedingt als Belästigung angesehen wird. Wenn Sie beispielsweise einem anderen Benutzer nicht zustimmen oder seine Kommentare ablehnen, kann dies auf unserer Plattform möglicherweise nicht als Belästigung empfunden werden. Darüber hinaus fällt das Teilen von Kritik an Persönlichkeiten des öffentlichen Lebens oder Projekten oder Themen von öffentlichem Interesse nicht unbedingt unter diese Richtlinie. Wir empfehlen Ihnen jedoch, darauf zu achten, wie Sie mit anderen Benutzern und der Plattform interagieren, da diese Aktivität immer noch gegen unsere Beschränkung verstoßen kann, die Erfahrung anderer Benutzer zu stören.
