GitHub-Richtlinie für verstorbene Benutzer - GitHub Dokumente(function(){
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
3. [Andere Website-Richtlinien](/de/site-policy/other-site-policies)
4. [GitHub-Richtlinie für verstorbene Benutzer](/de/site-policy/other-site-policies/github-deceased-user-policy)

Scroll breadcrumbs right

[Site policy](/de/site-policy)
----------

GitHub-Richtlinie für verstorbene Benutzer
==========

Als Markdown kopieren

Falls ein GitHub-Benutzer stirbt, können wir mit einer autorisierten Person zusammenarbeiten, um festzustellen, was mit dem Inhalt des Kontos passiert.

Wenn Sie Angehöriger, ein [vorab bestimmter Nachfolger](/de/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/maintaining-ownership-continuity-of-your-personal-accounts-repositories) oder eine andere autorisierte Person (einschließlich eines Mitarbeiters oder Geschäftspartners) eines verstorbenen Benutzers sind, der bzw. die eine Anfrage bezüglich des Kontos der verstorbenen Person stellen möchte, können Sie sich über das [GitHub-Support-Portal](https://support.github.com/) an uns wenden. Klicken Sie im Portal auf **Kontaktieren Sie uns**, und geben Sie die folgenden Informationen in Ihrer Nachricht an:

* Name
* Kontaktinformationen
* Name des verstorbenen Kontoinhabers
* GitHub-Benutzername des verstorbenen Kontoinhabers
* Ihre Beziehung zum verstorbenen Kontoinhaber (bitte geben Sie an, ob Sie als Kontonachfolger auf GitHub.com bestimmt wurden)
* Falls als Kontonachfolger bestimmt, der Benutzername Ihres GitHub-Kontos
* Welche Aktion Sie anstreben (z. B. öffentliche Repositories übertragen, Abrechnung über das Konto kündigen)

Sobald wir Ihre Anfrage erhalten haben, können wir weitere Informationen anfordern, z. B. eine Kopie Ihres Lichtbildausweises, eine Kopie der Sterbeurkunde und Unterlagen, die bestätigen, dass Sie berechtigt sind, in Bezug auf das Konto des verstorbenen Benutzers zu handeln überprüfen, ob wir ordnungsgemäß autorisiert sind, Ihre Anfrage zu bearbeiten.

Bitte beachten Sie, dass die Informationen, die Sie in Ihrer Anfrage angeben, in Übereinstimmung mit unserer [Datenschutzerklärung](/de/site-policy/privacy-policies/github-privacy-statement) erfasst werden, und wir werden die Informationen nur so lange aufbewahren, wie es zur Erfüllung unserer gesetzlichen Verpflichtungen und zur Beilegung von Streitigkeiten erforderlich ist.
