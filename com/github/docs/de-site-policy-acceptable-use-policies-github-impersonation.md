GitHub-Identitätswechsel - GitHub Dokumente(function(){
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
3. [Identitätswechsel](/de/site-policy/acceptable-use-policies/github-impersonation)

GitHub-Identitätswechsel
==========

Als Markdown kopieren

Sie dürfen Ihre Identität oder Ihre Verbindung zu einer anderen Person oder Organisation nicht falsch darstellen. Dies schließt Folgendes ein, um andere irrezuführen oder zu täuschen:

* Kopieren des Avatars oder anderer persönlicher Profilinformationen eines anderen Benutzers
* Posten von Inhalten unter der E-Mail-Adresse eines anderen Benutzers
* Verwendung eines täuschend ähnlichen Benutzernamens, Organisationsnamens oder anderen Namensraums
* Zugreifen auf ein Konto oder eine Organisation mit dem Token oder den Anmeldeinformationen eines anderen Benutzers
* Sich anderweitig als eine andere Person oder Organisation auszugeben

Identitätsdiebstahl ist eine Form der Belästigung und ein Verstoß gegen diese Richtlinie kann zum Verlust des Zugriffs auf Ihr Konto führen.

Bitte beachten Sie, dass ein Benutzername, der einem anderen ähnlich ist, nicht unbedingt ein Identitätsdiebstahl ist. GitHub berücksichtigt den Kontext. In Fällen, in denen Ansprüche von [Falschinformation oder Desinformation](/de/site-policy/acceptable-use-policies/github-misinformation-and-disinformation) geltend gemacht werden, erlauben wir beispielsweise im Allgemeinen Parodie und Satire, die mit unseren [Richtlinien zur akzeptablen Nutzung](/de/site-policy/acceptable-use-policies/github-acceptable-use-policies) in Einklang stehen.
