Richtlinien zur akzeptablen Nutzung - GitHub Dokumente(function(){
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
2. [Richtlinien zur akzeptablen Nutzung](/de/site-policy/acceptable-use-policies)

Richtlinien zur akzeptablen Nutzung
==========

[GitHub-Richtlinien zur akzeptablen Nutzung](/de/site-policy/acceptable-use-policies/github-acceptable-use-policies)
----------

[GitHub Aktive Malware oder Exploits](/de/site-policy/acceptable-use-policies/github-active-malware-or-exploits)
----------

[GitHub Mobbing und Belästigung](/de/site-policy/acceptable-use-policies/github-bullying-and-harassment)
----------

[GitHub stört die Erfahrung anderer Benutzer](/de/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users)
----------

[GitHub Doxxing und Verletzung der Privatsphäre](/de/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)
----------

[GitHub Hassreden und Diskriminierung](/de/site-policy/acceptable-use-policies/github-hate-speech-and-discrimination)
----------

[GitHub-Identitätswechsel](/de/site-policy/acceptable-use-policies/github-impersonation)
----------

[GitHub Fehlinformationen und Desinformationen](/de/site-policy/acceptable-use-policies/github-misinformation-and-disinformation)
----------

[GitHub Sexuell obszöner Inhalt](/de/site-policy/acceptable-use-policies/github-sexually-obscene-content)
----------

[GitHub Androhungen von Gewalt und unentgeltlich gewalttätigen Inhalten](/de/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)
----------

[Terrorismus und gewalttätiger Extremismus auf GitHub](/de/site-policy/acceptable-use-policies/github-terrorism-and-violent-extremism)
----------

[Sexuelle Ausbeutung oder Missbrauch von Kindern auf GitHub](/de/site-policy/acceptable-use-policies/github-child-sexual-exploitation-or-abuse)
----------

[Nicht einvernehmliche intime Bilder auf GitHub](/de/site-policy/acceptable-use-policies/github-non-consensual-intimate-imagery)
----------

[Synthetische Medien und KI-Tools auf GitHub](/de/site-policy/acceptable-use-policies/github-synthetic-media-and-ai-tools)
----------

[GitHub-Einspruch und Wiedereinsetzung](/de/site-policy/acceptable-use-policies/github-appeal-and-reinstatement)
----------
