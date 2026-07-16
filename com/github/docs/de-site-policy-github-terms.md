GitHub-Bedingungen - GitHub Dokumente(function(){
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
3. [GitHub-Bedingungen](/de/site-policy/github-terms)

Breadcrumbs nach rechts scrollen

[Site policy](/de/site-policy)
----------

GitHub-Bedingungen
==========

[GitHub-Nutzungsbedingungen](/de/site-policy/github-terms/github-terms-of-service)
----------

[GitHub-Vertragsbedingungen für Unternehmen](/de/site-policy/github-terms/github-corporate-terms-of-service)
----------

[GitHub-Nutzungsbedingungen für zusätzliche Produkte und Funktionen](/de/site-policy/github-terms/github-terms-for-additional-products-and-features)
----------

[GitHub-Community-Richtlinien](/de/site-policy/github-terms/github-community-guidelines)
----------

[Verhaltenskodex für die GitHub-Community](/de/site-policy/github-terms/github-community-code-of-conduct)
----------

[Lizenzbestimmungen für die Vorabversion von GitHub](/de/site-policy/github-terms/github-pre-release-license-terms)
----------

[Durch DPA abgedeckte Vorschauversionen auf GitHub](/de/site-policy/github-terms/github-dpa-previews)
----------

[GitHub sponsert zusätzliche Bedingungen](/de/site-policy/github-terms/github-sponsors-additional-terms)
----------

[Vereinbarung für registrierte GitHub-Entwickler](/de/site-policy/github-terms/github-registered-developer-agreement)
----------

[GitHub Marketplace-Nutzungsbedingungen](/de/site-policy/github-terms/github-marketplace-terms-of-service)
----------

[GitHub Marketplace-Entwicklervereinbarung](/de/site-policy/github-terms/github-marketplace-developer-agreement)
----------

[Bedingungen des GitHub-Forschungsprogramms](/de/site-policy/github-terms/github-research-program-terms)
----------

[Allgemeine Geschäftsbedingungen für GitHub-Open-Source-Anwendungen](/de/site-policy/github-terms/github-open-source-applications-terms-and-conditions)
----------

[Bedingungen für GitHub-Events](/de/site-policy/github-terms/github-event-terms)
----------

[GitHub-Verhaltenskodex für Veranstaltungen](/de/site-policy/github-terms/github-event-code-of-conduct)
----------

[GitHub-Vereinbarung zur Nutzung für Bildungszwecke](/de/site-policy/github-terms/github-educational-use-agreement)
----------

[GitHub Copilot Extension Developer Policy](/de/site-policy/github-terms/github-copilot-extension-developer-policy)
----------

[Vereinbarung über das GitHub-Partnerprogramm zur Geheimnisüberprüfung](/de/site-policy/github-terms/github-secret-scanning-partner-program-agreement)
----------
