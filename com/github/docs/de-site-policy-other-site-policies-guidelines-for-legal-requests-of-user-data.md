Richtlinien für rechtliche Anfragen von Benutzerdaten - GitHub-Dokumentation

[Skip to main content](#main-content)

[Startseite](/de)

[Site policy](/de/site-policy)

* [Websiterichtlinie](/de/site-policy)/
* [Andere Website-Richtlinien](/de/site-policy/other-site-policies)/
* [Richtlinien für rechtliche Anfragen von Benutzerdaten](/de/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)

Richtlinien für rechtliche Anfragen von Benutzerdaten
==========

In diesem Artikel
----------

* [Über diese Richtlinien](#about-these-guidelines)
* [GitHub-Terminologie](#github-terminology)
* [Benutzerdaten auf GitHub.com](#user-data-on-githubcom)
* [Wir werden alle betroffenen Kontoinhaber benachrichtigen](#we-will-notify-any-affected-account-owners)
* [Offenlegung von nicht-öffentlichen Informationen](#disclosure-of-non-public-information)
* [Kostenerstattung](#cost-reimbursement)
* [Datenaufbewahrung](#data-preservation)
* [Anträge stellen](#submitting-requests)
* [Anfragen ausländischer Strafverfolgungsbehörden](#requests-from-foreign-law-enforcement)
* [Fragen](#questions)

Sind Sie ein Strafverfolgungsbeamter, der eine Untersuchung durchführt, die möglicherweise auf GitHub gehostete Benutzerinhalte betrifft?
Oder vielleicht sind Sie eine datenschutzbewusste Person, die wissen möchte, welche Informationen wir an die Strafverfolgungsbehörden weitergeben und unter welchen Umständen.
In jedem Fall sind Sie auf der richtigen Seite.

In diesen Richtlinien geben wir einen kleinen Hintergrund darüber, was GitHub ist, welche Arten von Daten wir haben und unter welchen Bedingungen wir private Benutzerinformationen offenlegen.
Bevor wir jedoch ins Detail gehen, hier ein paar wichtige Details, die Sie vielleicht wissen möchten:

* Wir [**benachrichtigen alle betroffenen Benutzer**](#we-will-notify-any-affected-account-owners) über alle Anfragen nach ihren Kontoinformationen, es sei denn, dies ist gesetzlich oder per Gerichtsbeschluss untersagt.
* Wir legen keine **Standortverfolgungsdaten** offen, wie z. B. IP-Adressprotokolle, ohne dass ein [gültiger Gerichtsbeschluss oder Durchsuchungsbefehl](#with-a-court-order-or-a-search-warrant) vorliegt.
* Wir legen keine **privaten Benutzerinhalte** offen, einschließlich der Inhalte privater Repositories, ohne dass ein gültiger [Durchsuchungsbefehl](#only-with-a-search-warrant) vorliegt.

[Über diese Richtlinien](#about-these-guidelines)
----------

Unsere Benutzer vertrauen uns ihre Softwareprojekte und ihren Code an – oft einige ihrer wertvollsten geschäftlichen oder persönlichen Vermögenswerte.
Die Aufrechterhaltung dieses Vertrauens ist für uns von entscheidender Bedeutung, was bedeutet, dass Benutzerdaten sicher, geschützt und privat bleiben.

Während die überwältigende Mehrheit unserer Benutzer die Dienste von GitHub nutzt, um neue Unternehmen zu gründen, neue Technologien aufzubauen und für die allgemeine Verbesserung der Menschheit, erkennen wir an, dass es bei Millionen von Benutzern auf der ganzen Welt zwangsläufig ein paar schlechte Äpfel geben wird der Haufen.
In diesen Fällen möchten wir die Strafverfolgungsbehörden dabei unterstützen, ihr berechtigtes Interesse am Schutz der Öffentlichkeit zu erfüllen.

Durch die Bereitstellung von Richtlinien für Strafverfolgungsbeamte hoffen wir, ein Gleichgewicht zwischen den oft konkurrierenden Interessen der Privatsphäre der Benutzer und der Gerechtigkeit herzustellen.
Wir hoffen, dass diese Richtlinien dazu beitragen, Erwartungen auf beiden Seiten zu wecken und die internen Prozesse von GitHub transparenter zu machen.
Unsere Benutzer sollten wissen, dass wir ihre privaten Informationen schätzen und alles tun, um sie zu schützen.
Dies bedeutet zumindest, dass Daten nur dann an Dritte weitergegeben werden, wenn die entsprechenden gesetzlichen Anforderungen erfüllt sind.
Aus dem gleichen Grund hoffen wir auch, Strafverfolgungsbeamte über die Systeme von GitHub aufzuklären, damit sie ihre Datenanfragen effizienter anpassen und genau auf die Informationen abzielen können, die für die Durchführung ihrer Ermittlungen erforderlich sind.

[GitHub-Terminologie](#github-terminology)
----------

Bevor Sie uns bitten, Daten offenzulegen, kann es hilfreich sein, zu verstehen, wie unser System implementiert ist.
GitHub hostet Millionen von Datenrepositories mit dem [Git-Versionskontrollsystem](https://git-scm.com/video/what-is-version-control).
Repositories auf GitHub – die öffentlich oder privat sein können – werden am häufigsten für Softwareentwicklungsprojekte verwendet, werden aber auch oft verwendet, um an Inhalten aller Art zu arbeiten.

* [**Benutzer**](/de/get-started/learning-about-github/github-glossary#user) – Benutzer werden in unserem System als persönliche GitHub-Konten dargestellt.
  Jeder Benutzer hat ein persönliches Profil und kann mehrere Repositories besitzen.
  Benutzer können Organisationen erstellen oder dazu eingeladen werden, ihnen beizutreten oder am Repository eines anderen Benutzers mitzuarbeiten.

* [**Mitarbeiter**](/de/get-started/learning-about-github/github-glossary#collaborator) – Ein Mitarbeiter ist ein Benutzer mit Lese- und Schreibzugriff auf ein Repository, der vom Eigentümer des Repository eingeladen wurde, Beiträge zu leisten.

* [**Organisationen**](/de/get-started/learning-about-github/github-glossary#organization) – Organisationen sind eine Gruppe von zwei oder mehr Benutzern, die in der Regel reale Organisationen wie Unternehmen oder Projekte widerspiegeln.
  Sie werden von Benutzern verwaltet und können sowohl Repositories als auch Teams von Benutzern enthalten.

* [**Aufbewahrungsorte**](/de/get-started/learning-about-github/github-glossary#repository) – Ein Repository ist eines der grundlegendsten GitHub-Elemente.
  Sie können sich am einfachsten als Ordner eines Projekts vorstellen.
  Ein Repository enthält alle Projektdateien (einschließlich Dokumentation) und speichert den Revisionsverlauf jeder Datei.
  Repositories können mehrere Mitarbeiter haben und können nach Ermessen ihrer Administratoren öffentlich einsehbar sein oder nicht.

* [**Pages**](/de/pages/getting-started-with-github-pages/about-github-pages) – GitHub Pages sind öffentliche Webseiten, die kostenlos von GitHub gehostet werden und die die Benutzer einfach über Code veröffentlichen können, welcher in ihren Repositories gespeichert ist.
  Wenn ein Benutzer oder eine Organisation eine GitHub Page hat, kann sie normalerweise unter einer URL wie z. B. `https://username.github.io` gefunden werden, oder die Webseite wurde dem eigenen benutzerdefinierten Domänennamen des Benutzers bzw. der Organisation zugeordnet.

* [**Gists**](/de/get-started/writing-on-github/editing-and-sharing-content-with-gists/creating-gists) – Gists sind Ausschnitte aus Quellcode oder anderem Text, die Benutzer verwenden können, um Ideen zu speichern oder mit Freunden zu teilen.
  Wie normale GitHub-Repositories werden Gists mit Git erstellt, sodass sie automatisch versioniert, verzweigt und heruntergeladen werden können.
  Gists können entweder öffentlich oder geheim sein (nur über eine bekannte URL zugänglich). Öffentliche Gists können nicht in geheime Gists umgewandelt werden.

[Benutzerdaten auf GitHub.com](#user-data-on-githubcom)
----------

Hier ist eine nicht erschöpfende Liste der Arten von Daten, die wir über Benutzer und Projekte auf GitHub pflegen.

* []()**Öffentliche Kontodaten** – Auf GitHub ist eine Vielzahl von Informationen über Benutzer und ihre Repositories öffentlich verfügbar.
  Benutzerprofile finden Sie unter einer URL wie z. B. `https://github.com/username`.
  Benutzerprofile zeigen Informationen darüber an, wann der Benutzer sein Konto erstellt hat, sowie seine öffentlichen Aktivitäten auf GitHub.com und soziale Interaktionen.
  Öffentliche Benutzerprofile können auch zusätzliche Informationen enthalten, die ein Benutzer möglicherweise öffentlich geteilt hat.
  Alle öffentlichen Benutzerprofile werden angezeigt:

  * Benutzername

  * Die Repositorys, die der Benutzer markiert hat

  * Den anderen GitHub-Benutzern folgt der Benutzer

  * Die Benutzer, die ihnen folgen

    Optional kann ein Benutzer auch die folgenden Informationen öffentlich teilen:

  * Ihr richtiger Name

  * Ein Avatar

  * Ein verbundenes Unternehmen

  * Ihr Standort

  * Eine öffentliche E-Mail-Adresse

  * Ihre persönliche Webseite

  * Organisationen, bei denen der Benutzer Mitglied ist (*abhängig von den Einstellungen der Organisation oder des Benutzers*)

* []()**Private Kontodaten** – GitHub erhebt und verwaltet auch bestimmte private Informationen über Benutzer, wie in unseren [Datenschutz-Bestimmungen](/de/site-policy/privacy-policies/github-privacy-statement) beschrieben.
  Dies kann beinhalten:

  * Private E-Mail-Adressen

  * Zahlungsdetails

  * Sicherheitszugriffsprotokolle

  * Daten über Interaktionen mit privaten Repositories

    Um sich ein Bild von der Art der privaten Kontoinformationen zu machen, die GitHub erhebt, können Sie Ihr [Persönliches Dashboard](https://github.com/dashboard) aufrufen und durch die Abschnitte auf der linken Menüleiste navigieren.

* []()**Kontodaten von Organisationen** – Informationen über Organisationen, ihre administrativen Benutzer und Repositories sind auf GitHub öffentlich zugänglich.
  Organisationsprofile finden Sie unter einer URL wie z. B. `https://github.com/organization`.
  Öffentliche Organisationsprofile können auch zusätzliche Informationen enthalten, die die Eigentümer öffentlich teilen möchten.
  Alle öffentlichen Profile der Organisation werden angezeigt:

  * Name der Organisation

  * Die Repositories, die die Besitzer markiert haben

  * Alle GitHub-Benutzer, die Eigentümer der Organisation sind

    Optional können sich Administratoren auch dafür entscheiden, die folgenden Informationen öffentlich zu teilen:

  * Ein Avatar

  * Ein verbundenes Unternehmen

  * Ihr Standort

  * Direkte Mitglieder und Teams

  * Mitarbeiter

* []()**Öffentliche Repository-Daten** – GitHub vereint Millionen von öffentlichen Open-Source-Softwareprojekten.
  Sie können fast jedes öffentliche Repository durchsuchen (z. B. die [GitHub-Dokumentationen](https://github.com/github/docs)), um ein Gefühl für die Informationen zu bekommen, die GitHub über Repositorys erhebt und verwaltet.
  Dies kann beinhalten:

  * Der Code selbst
  * Frühere Versionen des Codes
  * Stabile Release-Versionen des Projekts
  * Informationen über Mitarbeiter, Mitwirkende und Repository-Mitglieder
  * Protokolle von Git-Operationen wie Commits, Branching, Pushing, Pulling, Forking und Klonen
  * Gespräche im Zusammenhang mit Git-Operationen wie Kommentare zu Pull-Requests oder Commits
  * Projektdokumentation wie Issues und Wiki-Seiten
  * Statistiken und Grafiken, die die Beiträge zum Projekt und zum Netzwerk der Mitwirkenden zeigen

* []()**Private Repository-Daten** – GitHub erhebt und verwaltet für private Repositories dieselbe Art von Daten wie für öffentliche Repositories, mit der Ausnahme, dass nur speziell eingeladene Benutzer auf die Daten privater Repositories zugreifen können.

* []()**Andere Daten** – Darüber hinaus erhebt GitHub Analysedaten wie Seitenbesuche und Informationen, die gelegentlich freiwillig von unseren Benutzern bereitgestellt werden (z. B. Kommunikation mit unserem Support-Team, Umfrageinformationen und/oder Website-Registrierungen).

[Wir werden alle betroffenen Kontoinhaber benachrichtigen](#we-will-notify-any-affected-account-owners)
----------

Es ist unsere Richtlinie, Benutzer über alle ausstehenden Anfragen in Bezug auf ihre Konten oder Repositories zu benachrichtigen, es sei denn, uns ist dies gesetzlich oder per Gerichtsbeschluss untersagt. Bevor wir Benutzerinformationen offenlegen, werden wir angemessene Anstrengungen unternehmen, um alle betroffenen Kontoinhaber zu benachrichtigen, indem wir eine Nachricht an ihre verifizierte E-Mail-Adresse senden und ihnen eine Kopie der Vorladung, des Gerichtsbeschlusses oder des Haftbefehls zukommen lassen, damit sie die Möglichkeit haben, dies anzufechten Gerichtsverfahren, wenn sie dies wünschen. Unter (seltenen) dringenden Umständen können wir die Benachrichtigung verzögern, wenn wir feststellen, dass eine Verzögerung notwendig ist, um Tod oder ernsthaften Schaden zu verhindern, oder aufgrund einer laufenden Untersuchung.

[Offenlegung von nicht-öffentlichen Informationen](#disclosure-of-non-public-information)
----------

Es ist unsere Richtlinie, nicht-öffentliche Benutzerinformationen im Zusammenhang mit zivil- oder strafrechtlichen Ermittlungen nur mit Zustimmung des Benutzers oder nach Erhalt einer gültigen Vorladung, eines zivilrechtlichen Ermittlungsantrags, eines Gerichtsbeschlusses, eines Durchsuchungsbefehls oder eines anderen ähnlichen gültigen Rechtsverfahrens offenzulegen. Unter bestimmten dringenden Umständen (siehe unten) können wir auch begrenzte Informationen weitergeben, die jedoch nur der Art der Umstände entsprechen, und würden für alles andere ein Gerichtsverfahren erfordern.
GitHub behält sich das Recht vor, Anfragen nach nicht öffentlichen Informationen zu widersprechen.
Wenn GitHub zustimmt, nicht-öffentliche Informationen als Antwort auf eine rechtmäßige Anfrage bereitzustellen, werden wir eine angemessene Suche nach den angeforderten Informationen durchführen.
Hier sind die Arten von Informationen, zu deren Herausgabe wir uns bereit erklären, abhängig von der Art des Rechtsverfahrens, das uns zugestellt wird:

* []()**Mit Zustimmung des Benutzers** – GitHub gibt private Kontoinformationen auf Anfrage direkt an den Benutzer (oder einen Besitzer, falls es sich um ein Organisationskonto handelt oder mit schriftlicher Zustimmung des Benutzers an einen benannten Dritten weiter, sobald GitHub sicher ist, dass der Benutzer seine Identität überprüft hat.

* []()**Mit Vorladung** – Wenn uns eine gültige Vorladung, ein zivilrechtliches Ermittlungsverfahren oder ein ähnliches Gerichtsverfahren im Zusammenhang mit einer offiziellen straf- oder zivilrechtlichen Untersuchung zugestellt wird, können wir bestimmte nicht öffentliche Kontoinformationen bereitstellen, darunter:

  * Mit dem Konto verknüpfte Namen
  * Mit dem Konto verknüpfte E-Mail-Adresse(n).
  * Abrechnungsinformationen
  * Registrierungsdatum und Kündigungsdatum
  * IP-Adresse, Datum und Uhrzeit zum Zeitpunkt der Kontoregistrierung
  * IP-Adresse(n), die für den Zugriff auf das Konto zu einem bestimmten Zeitpunkt oder bei einem bestimmten Ereignis verwendet werden, das für die Untersuchung relevant ist

Bei Organisationskonten können wir die Namen und E-Mail-Adressen der Kontoinhaber sowie das Datum und die IP-Adresse zum Zeitpunkt der Erstellung des Organisationskontos angeben. Wir werden keine Informationen über andere Mitglieder oder Mitwirkende, falls vorhanden, für das Organisationskonto oder zusätzliche Informationen über die identifizierten Kontoinhaber ohne eine Folgeanfrage für diese bestimmten Benutzer herausgeben.

Bitte beachten Sie, dass die verfügbaren Informationen von Fall zu Fall variieren. Einige der Informationen können vom Benutzer optional angegeben werden. In anderen Fällen haben wir die Informationen möglicherweise nicht erfasst oder gespeichert.

* []()**Mit Gerichtsbeschluss \_oder \_Durchsuchungsbefehl** – Wir legen Kontozugriffsprotokolle nur dann offen, wenn wir dazu gezwungen werden entweder (i) durch einen Gerichtsbeschluss, der gemäß 18 U.S.C. Abschnitt 2703(d) augestellt wurde, bei Vorliegen spezifischer und artikulierbarer Tatsachen, die zeigen, dass es begründeten Anlass zu der Annahme gibt, dass die angeforderten Informationen für eine laufende strafrechtliche Untersuchung relevant und wesentlich sind; oder (ii) einen Durchsuchungsbefehl, der gemäß den in der Bundesstrafprozessordnung beschriebenen Verfahren oder gleichwertigen staatlichen Haftbefehlsverfahren ausgestellt wurde, wenn ein wahrscheinlicher Grund nachgewiesen wird.
  Zusätzlich zu den oben aufgeführten nicht öffentlichen Kontoinformationen können wir Kontozugriffsprotokolle als Reaktion auf einen Gerichtsbeschluss oder einen Durchsuchungsbefehl bereitstellen, die Folgendes beinhalten können:

  * Alle Protokolle, die die Bewegungen eines Benutzers über einen bestimmten Zeitraum hinweg offenbaren würden
  * Konto- oder private Repository-Einstellungen (z. B. welche Benutzer bestimmte Berechtigungen haben usw.)
  * Benutzer- oder IP-spezifische Analysedaten wie der Browserverlauf
  * Andere Sicherheitszugriffsprotokolle als die Kontoerstellung oder für eine bestimmte Zeit und ein bestimmtes Datum

* []()**Nur mit Durchsuchungsbefehl** – Wir legen die privaten Inhalte eines Kontos nur dann offen, wenn wir durch einen Durchsuchungsbefehl dazu gezwungen sind, der gemäß den in den Federal Rules of Criminal Procedure beschriebenen Verfahren oder gleichwertigen staatlichen Durchsuchungsbefehlsverfahren bei Vorliegen eines hinreichenden Verdachts ausgestellt wurde.
  Zusätzlich zu den oben erwähnten nicht öffentlichen Kontoinformationen und Kontozugriffsprotokollen werden wir als Reaktion auf einen Durchsuchungsbefehl auch private Kontoinhalte bereitstellen, die Folgendes umfassen können:

  * Inhalt geheimer Gists
  * Quellcode oder andere Inhalte in privaten Repositories
  * Beitrags- und Kollaborationsaufzeichnungen für private Repositories
  * Mitteilungen oder Dokumentation (z. B. Ausgaben oder Wikis) in privaten Repositories
  * Alle Sicherheitsschlüssel, die für die Authentifizierung oder Verschlüsselung verwendet werden

* []()\*\* Unter dringenden Umständen\*\* – Wenn wir eine Anfrage nach Informationen unter bestimmten dringenden Umständen erhalten (wenn wir glauben, dass die Offenlegung notwendig ist, um einen Notfall zu verhindern, bei dem die Gefahr des Todes oder einer schweren körperlichen Verletzung einer Person besteht), können wir begrenzte Informationen offenlegen, die wir als notwendig erachten, um den Strafverfolgungsbehörden die Bewältigung des Notfalls zu ermöglichen. Für darüber hinausgehende Informationen benötigen wir eine Vorladung, einen Durchsuchungsbefehl oder einen Gerichtsbeschluss, wie oben beschrieben. Beispielsweise geben wir Inhalte privater Repositories nicht ohne Durchsuchungsbefehl preis. Bevor wir Informationen offenlegen, bestätigen wir, dass die Anfrage von einer Strafverfolgungsbehörde stammt, eine Behörde eine offizielle Mitteilung verschickt hat, in der der Notfall zusammengefasst ist, und wie die angeforderten Informationen zur Bewältigung des Notfalls beitragen werden.

[Kostenerstattung](#cost-reimbursement)
----------

Nach staatlichem und bundesstaatlichem Recht kann GitHub die Erstattung von Kosten verlangen, die mit der Erfüllung einer gültigen rechtlichen Forderung verbunden sind, wie z. B. einer Vorladung, einem Gerichtsbeschluss oder einem Durchsuchungsbefehl. Wir stellen nur einen Teil der Kosten in Rechnung, und diese Erstattungen decken nur einen Teil der Kosten ab, die uns tatsächlich entstehen, um rechtlichen Anordnungen nachzukommen.

Obwohl wir in Notsituationen oder unter anderen dringenden Umständen keine Gebühren erheben, verlangen wir eine Erstattung für alle anderen rechtlichen Anfragen gemäß dem folgenden Zeitplan, sofern gesetzlich nichts anderes vorgeschrieben ist:

* Erste Suche von bis zu 25 Identifikatoren: Kostenlos
* Erstellung von Teilnehmerinformationen/Daten für bis zu 5 Konten: Kostenlos
* Erstellung von Teilnehmerinformationen/Daten für mehr als 5 Konten: 20 USD pro Konto.
* Sekundäre Suche: 10 USD pro Suche

[Datenaufbewahrung](#data-preservation)
----------

Auf formelle Anfrage der US-amerikanischen Strafverfolgungsbehörden im Zusammenhang mit offiziellen strafrechtlichen Ermittlungen und bis zur Ausstellung eines Gerichtsbeschlusses oder eines anderen Verfahrens werden wir Schritte unternehmen, um Kontounterlagen bis zu 90 Tage lang aufzubewahren.

[Anträge stellen](#submitting-requests)
----------

Anfragen bitte richten an:

```
GitHub, Inc.
c/o Corporation Service Company
2710 Gateway Oaks Drive, Suite 150N
Sacramento, CA 95833-3505

```

Anfragen für Belegexemplare von Dokumenten können per E-Mail an [legal-support@github.com](mailto:legal-support@github.com) gesendet werden.

Bitte formulieren Sie Ihre Anfragen so spezifisch und eng wie möglich, einschließlich der folgenden Informationen:

* Vollständige Angaben zur Behörde, die das Auskunftsersuchen ausstellt
* Name und Ausweis/ID des verantwortlichen Agenten
* Eine offizielle E-Mail-Adresse und Telefonnummer
* Die interessierenden Benutzer-, Organisations- und Repository-Namen
* Die URLs aller Seiten, Gists oder Dateien von Interesse
* Die Beschreibung der Arten von Aufzeichnungen, die Sie benötigen

Bitte geben Sie uns mindestens zwei Wochen Zeit, um Ihre Anfrage zu prüfen.

### [California Assembly Bill 1242 Notice](#california-assembly-bill-1242-notice) ###

Indem Sie ein rechtliches Verfahren gegen GitHub einleiten, bestätigen Sie, dass sich dieses Verfahren nicht auf den Verstoß gegen Gesetze bezieht, die eine Haftung für abtreibungsbezogenes Verhalten begründen, das in Kalifornien rechtmäßig ist.

[Anfragen ausländischer Strafverfolgungsbehörden](#requests-from-foreign-law-enforcement)
----------

Als US-amerikanisches Unternehmen mit Sitz in Kalifornien ist GitHub nicht verpflichtet, Daten an ausländische Regierungen als Reaktion auf von ausländischen Behörden erlassene Rechtsverfahren bereitzustellen.
Ausländische Strafverfolgungsbeamte, die Informationen von GitHub anfordern möchten, sollten sich an das Office of International Affairs des United States Department of Justice Criminal Division wenden.
GitHub wird unverzüglich auf Ersuchen reagieren, die über ein US-Gericht im Wege eines Rechtshilfeabkommens („MLAT“) oder eines Rechtshilfeersuchens gestellt werden.

[Fragen](#questions)
----------

Haben Sie weitere Fragen, Anmerkungen oder Anregungen? Wenden Sie sich an uns über das [GitHub-Support-Portal](https://support.github.com).
