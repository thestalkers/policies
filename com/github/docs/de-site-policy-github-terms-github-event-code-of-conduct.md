GitHub-Verhaltenskodex für Veranstaltungen - GitHub Dokumente(function(){
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
3. [GitHub-Bedingungen](/de/site-policy/github-terms)
4. [GitHub-Verhaltenskodex für Veranstaltungen](/de/site-policy/github-terms/github-event-code-of-conduct)

Scroll breadcrumbs right

[Site policy](/de/site-policy)
----------

GitHub-Verhaltenskodex für Veranstaltungen
==========

Als Markdown kopieren

In diesem Artikel
----------

* [Verhaltenskodex](#code-of-conduct)
* [Einen Vorfall melden](#reporting-an-incident)
* [Kredit](#credit)

[Verhaltenskodex](#code-of-conduct)
----------

Durch die Teilnahme an einer GitHub-Veranstaltung, einschließlich der von GitHub in Verbindung mit der Veranstaltung organisierten Veranstaltungen oder Aktivitäten (zusammenfassend als "Veranstaltung" bezeichnet), erklären Sie, dass Sie die folgenden Verhaltensregeln für GitHub-Veranstaltungen (im Folgenden "Verhaltenstegeln") gelesen und verstanden haben und ihnen zustimmen. Diese Verhaltensregeln gelten für alle Teilnehmer, Referenten, Aussteller, Sponsoren, Organisatoren, Mitarbeiter und Freiwilligen (zusammen als „Veranstaltungsteilnehmer“ bezeichnet) bei der Veranstaltung.

GitHub weiß die Teilnahme aller Veranstaltungsteilnehmer zu schätzen und möchte eine Veranstaltung abhalten, die allen Veranstaltungsteilnehmern eine angenehme und bereichernde Erfahrung bietet. Von allen Veranstaltungsteilnehmern wird daher erwartet, dass sie den anderen Veranstaltungsteilnehmern während der gesamten Veranstaltung mit Respekt und Höflichkeit begegnen.

GitHub hat sich zum Ziel gesetzt, eine positive und belästigungsfreie Erfahrung für jeden zu bieten, unabhängig von Alter, Geschlecht, Geschlechtsidentität und -ausdruck, sexueller Orientierung, Behinderung, persönlichem Erscheinungsbild, Körpergröße, ethnischer Zugehörigkeit, Rasse, Religion, Nationalität oder Erfahrungsniveau.

Wir tolerieren keine Form der Belästigung von Veranstaltungsteilnehmern und auch kein Verhalten, das in irgendeiner Weise dazu führen könnte, dass sich ein Veranstaltungsteilnehmer unsicher fühlt oder Angst um sein körperliches oder seelisches Wohlbefinden hat. Die gesamte Kommunikation und das Verhalten sollten für ein professionelles Umfeld geeignet sein, zu dem Menschen mit vielen unterschiedlichen Hintergründen gehören.

Beispiele für ermutigtes Verhalten, das zu einem positiven Umfeld beiträgt, sind:

* Umgang mit einladender und inklusiver Sprache
* Respektieren Sie unterschiedliche Sichtweisen und Erfahrungen
* Konstruktive Kritik anmutig annehmen
* Den Schwerpunkt auf das legen, was für alle Teilnehmer der Veranstaltung am besten ist
* Zeigen Sie Empathie gegenüber anderen und den Veranstaltungsteilnehmern

Als inakzeptables Verhalten gilt unter anderem:

* Die Verwendung von sexualisierter Sprache oder Bildern
* Unangemessene körperliche Kontakte, sexuelle Aufmerksamkeit oder Annäherungsversuche
* Trolling, beleidigende oder abwertende Kommentare oder Verhaltensweisen
* Persönliche oder politische Angriffe auf Veranstaltungsteilnehmer
* Anhaltende Unterbrechung von Gesprächen oder anderen Veranstaltungen oder Aktivitäten, die von GitHub in Verbindung mit der Veranstaltung organisiert werden
* Einschüchterung, Stalking, Verfolgung oder Belästigung von Veranstaltungsteilnehmern
* Fotografieren oder Aufnehmen von Veranstaltungsteilnehmern ohne deren Zustimmung
* Belästigungen jeglicher Art, auch in scherzhafter oder ironischer Weise
* Verhalten, das in einem beruflichen Umfeld vernünftigerweise als unangemessen angesehen werden könnte

Jeder Veranstaltungsteilnehmer ist für sein Handeln vollumfänglich selbst verantwortlich.

Vielen Dank, dass Sie dazu beigetragen haben, dies zu einem einladenden, freundlichen Ort für alle zu machen.

[Einen Vorfall melden](#reporting-an-incident)
----------

Wenn Sie belästigt werden, bemerken, dass eine andere Person belästigt wird, andere Anliegen haben oder der Meinung sind, dass ein Veranstaltungsteilnehmer sich nicht an diese Verhaltensregeln hält, sprechen Sie in dringenden Fällen bitte direkt mit einem Sicherheitsbeauftragten oder GitHub-Mitarbeiter vor Ort oder senden Sie uns in weniger dringenden Fällen eine E-Mail an [events@github.com](mailto:events@github.com). Wählen Sie in lebensbedrohlichen Situationen bitte sofort die 911.

GitHub-Mitarbeiter helfen den Veranstaltungsteilnehmern gerne dabei, den Sicherheitsdienst oder die örtlichen Strafverfolgungsbehörden zu kontaktieren, und werden diejenigen, die Belästigungen ausgesetzt sind, schützen oder auf andere Weise unterstützen, damit sie sich für die Dauer der Veranstaltung sicher fühlen.

[Kredit](#credit)
----------

Teile dieses Verhaltenskodex basieren auf der Vorlage example anti-harassment policy aus dem Geek Feminism Wiki, erstellt von der Ada Initiative und anderen Ehrenamtlichen unter einer Creative Commons Zero Lizenz.
