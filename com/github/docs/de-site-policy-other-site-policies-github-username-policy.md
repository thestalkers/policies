GitHub-Richtlinie für Benutzernamen - GitHub Dokumente(function(){
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

1. [Websiterichtlinie](/de/site-policy)
2. [Andere Website-Richtlinien](/de/site-policy/other-site-policies)
3. [GitHub-Richtlinie für Benutzernamen](/de/site-policy/other-site-policies/github-username-policy)

GitHub-Richtlinie für Benutzernamen
==========

Als Markdown kopieren

In diesem Artikel
----------

* [Was ist, wenn der gewünschte Benutzername bereits vergeben ist?](#what-if-the-username-i-want-is-already-taken)
* [Markenrichtlinie](#trademark-policy)
* [Namensbesetzungsrichtlinie](#name-squatting-policy)

GitHub-Kontonamen sind nach dem Prinzip „Wer zuerst kommt, mahlt zuerst“ verfügbar und sind für die sofortige und aktive Nutzung vorgesehen.

[Was ist, wenn der gewünschte Benutzername bereits vergeben ist?](#what-if-the-username-i-want-is-already-taken)
----------

Denken Sie daran, dass nicht alle Aktivitäten auf GitHub öffentlich sichtbar sind; Konten ohne sichtbare Aktivität werden möglicherweise aktiv verwendet.

Wir akzeptieren keine Anträge auf Freigabe, Übertragung oder Rückforderung von Benutzernamen mit der Begründung, dass diese inaktiv oder ungenutzt erscheinen. Falls der von Ihnen gewünschte Benutzername bereits vergeben ist, müssen Sie einen anderen verfügbaren Namen auswählen, es sei denn, Sie reichen eine Beschwerde wegen Markenrechtsverletzung ein, wie unten beschrieben.

Wenn der gewünschte Benutzername bereits beansprucht wurde, ziehen Sie andere Namen oder eindeutige Varianten in Betracht. Wenn Sie Zahlen, Bindestriche oder alternative Schreibweisen einbauen, können Sie möglicherweise einen noch verfügbaren Benutzernamen finden.

[Markenrichtlinie](#trademark-policy)
----------

Wenn Sie der Auffassung sind, dass das Konto einer anderen Person Ihre Markenrechte verletzt, finden Sie weitere Informationen zum Einreichen einer Markenbeschwerde auf der Seite [GitHub-Markenrichtlinie](/de/site-policy/content-removal-policies/github-trademark-policy). Wir prüfen ausschließlich berechtigte Beschwerden im Zusammenhang mit Markenrechten, um zu entscheiden, ob ein bereits vergebener Benutzername freigegeben werden kann.

[Namensbesetzungsrichtlinie](#name-squatting-policy)
----------

GitHub verbietet das Squatting von Kontonamen, und Kontonamen dürfen nicht für die zukünftige Verwendung reserviert oder inaktiv gehalten werden. Konten, die gegen diese Namesquatting-Richtlinie verstoßen, können ohne Vorankündigung entfernt oder umbenannt werden. Versuche, im Austausch für Kontonamen zu verkaufen, zu kaufen oder andere Zahlungsformen zu erbitten, sind verboten und können zu einer dauerhaften Sperrung des Kontos führen.
