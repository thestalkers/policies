GitHub Doxxing und Verletzung der Privatsphäre - GitHub Dokumente(function(){
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
4. [Doxxing und Verletzung der Privatsphäre](/de/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy)

Scroll breadcrumbs right

[Site policy](/de/site-policy)
----------

GitHub Doxxing und Verletzung der Privatsphäre
==========

Als Markdown kopieren

Veröffentlichen Sie keine persönlichen Daten anderer Personen. Dies schließt Folgendes ein:

* Persönliche, private E-Mail-Adressen
* Telefonnummern
* Physische Adressen oder andere private Standortinformationen
* Bankkontoinformationen oder Kreditkartennummern
* Sozialversicherungs-/nationale Identitätsnummern
* Kennwörter
* Wählerinformationen
* Medizinische Informationen und personenbezogene biometrische Daten
* Andere private Informationen, die ein Sicherheitsrisiko darstellen können

Wir können andere Informationen wie Fotos oder Videos, die ohne Zustimmung der betroffenen Person aufgenommen oder verbreitet wurden, als Eingriff in die Privatsphäre betrachten, insbesondere wenn solches Material ein Sicherheitsrisiko für die betroffene Person darstellt, wie z. B. im Falle von Einschüchterung oder Belästigung.

GitHub berücksichtigt den Kontext und ob die gemeldeten Inhalte anderweitig öffentlich verfügbar sind. Bitte beachten Sie jedoch, dass das Teilen von öffentlich zugänglichen Inhalten zwar keinen Verstoß gegen diese Richtlinie darstellt, aber wenn die Informationen mit der Absicht weitergegeben werden, jemanden zu belästigen oder zu anderem missbräuchlichem Verhalten anzustiften, kann dies gegen unser Verbot von [Mobbing und Belästigung](/de/site-policy/acceptable-use-policies/github-bullying-and-harassment) verstoßen.

Weitere Informationen oder Informationen zum Melden eines Verstoßes finden Sie in unserer [Richtlinie zum Entfernen privater Informationen](/de/site-policy/content-removal-policies/github-private-information-removal-policy) und unseren Anweisungen zum [Melden von Missbrauch](/de/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam).
