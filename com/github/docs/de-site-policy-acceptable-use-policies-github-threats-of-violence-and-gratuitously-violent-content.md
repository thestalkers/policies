GitHub Androhungen von Gewalt und unentgeltlich gewalttätigen Inhalten - GitHub Dokumente(function(){
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
3. [Richtlinien zur akzeptablen Nutzung](/de/site-policy/acceptable-use-policies)
4. [Androhung von Gewalt und gewalttätige Inhalte](/de/site-policy/acceptable-use-policies/github-threats-of-violence-and-gratuitously-violent-content)

Breadcrumbs nach rechts scrollen

[Site policy](/de/site-policy)
----------

GitHub Androhungen von Gewalt und unentgeltlich gewalttätigen Inhalten
==========

Als Markdown kopieren

Sie dürfen GitHub nicht verwenden, um Gewalttaten zu organisieren, zu fördern, zu ermutigen, zu bedrohen oder anzustiften. Sie dürfen keine Inhalte posten, die Gewalt oder körperliche Gewalt gegen Menschen oder Tiere darstellen oder verherrlichen. Dies umfasst:

* Eine andere Person oder Gruppe mit Missbrauch, Schaden, sexueller Gewalt oder dem Tod zu bedrohen
* Posten von Texten, Bildern oder Audioinhalten, die Gewalt gegen sich selbst, eine andere Person, Gruppe oder ein Tier verherrlichen oder eine grafische Darstellung davon enthalten
* Ermutigung einer anderen Person, sich selbst zu verletzen

Wir gestatten nicht, dass gewalttätige Inhalte wahllos oder auf eine Weise gepostet werden, die für andere Benutzer schwer zu vermeiden ist, wie z. B. ein Profil-Avatar oder ein Kommentar zu einem Problem. Wir verstehen jedoch, dass es legitime Gründe geben kann, gewalttätige Inhalte zu posten, wie z. B. für Bildungs- oder Dokumentationszwecke, kreative Werke oder Darstellungen historischer Ereignisse. In diesen Fällen kann eine klare Warnung oder ein Haftungsausschluss den Benutzern helfen, eine fundierte Entscheidung darüber zu treffen, ob sie sich mit solchen Inhalten beschäftigen möchten oder nicht. Dennoch kann GitHub beschließen, die Sichtbarkeit solcher Inhalte auf diejenigen zu beschränken, die sich dafür entscheiden.
