DMCA Takedown-Richtlinie - GitHub-Dokumentation

[Skip to main content](#main-content)

[Home](/de)

[Site policy](/de/site-policy)

* [Websiterichtlinie](/de/site-policy)/
* [Richtlinien zum Entfernen von Inhalten](/de/site-policy/content-removal-policies)/
* [DMCA Takedown-Richtlinie](/de/site-policy/content-removal-policies/dmca-takedown-policy)

DMCA Takedown-Richtlinie
==========

In diesem Artikel
----------

* [Was sind die Produktbenutzungsrechte (DMCA)?](#what-is-the-dmca)
* [DMCA-Hinweise in Kürze](#dmca-notices-in-a-nutshell)
* [A. Wie funktioniert das eigentlich?](#a-how-does-this-actually-work)
* [B. Was ist mit Gabeln? (oder Was ist eine Gabel?)](#b-what-about-forks-or-whats-a-fork)
* [C. Was ist mit Umgehungsansprüchen?](#c-what-about-circumvention-claims)
* [D. Was passiert, wenn ich versehentlich das Fenster zum Vornehmen von Änderungen verpasst habe?](#d-what-if-i-inadvertently-missed-the-window-to-make-changes)
* [E. Transparenz](#e-transparency)
* [F. Wiederholte Verletzung](#f-repeated-infringement)
* [G. Übermittlung von Mitteilungen](#g-submitting-notices)
* [Erfahren Sie mehr und sprechen Sie es an](#learn-more-and-speak-up)

Willkommen beim GitHub-Leitfaden zum Digital Millennium Copyright Act, allgemein bekannt als „DMCA“. Diese Seite ist nicht als umfassende Einführung in das Gesetz gedacht. Wenn Sie jedoch eine DMCA-Entfernungsmitteilung erhalten haben, die auf Inhalte abzielt, die Sie auf GitHub gepostet haben, oder wenn Sie ein Rechteinhaber sind, der eine solche Mitteilung herausgeben möchte, wird diese Seite hoffentlich dazu beitragen, das Gesetz ein wenig zu entmystifizieren, ebenso wie unsere Richtlinien für deren Einhaltung.

(Wenn Sie nur eine Mitteilung übermitteln möchten, können Sie zu „[G. Senden von Mitteilungen](#g-submitting-notices)“ springen.)

Wie bei allen rechtlichen Angelegenheiten ist es immer am besten, sich zu Ihren spezifischen Fragen oder Ihrer Situation an einen Fachmann zu wenden. Wir empfehlen Ihnen dringend, dies zu tun, bevor Sie Maßnahmen ergreifen, die Ihre Rechte beeinträchtigen könnten. Dieser Leitfaden ist keine Rechtsberatung und sollte auch nicht als solche verstanden werden.

[Was sind die Produktbenutzungsrechte (DMCA)?](#what-is-the-dmca)
----------

Um den DMCA und einige der politischen Linien, die er zieht, zu verstehen, ist es vielleicht hilfreich, das Leben vor seiner Verabschiedung zu betrachten.

Der DMCA bietet Dienstanbietern, die nutzergenerierte Inhalte hosten, einen sicheren Hafen. Da selbst eine einzige Klage wegen Urheberrechtsverletzung einen gesetzlichen Schadenersatz von bis zu $150,000 nach sich ziehen kann, könnte die Möglichkeit, für nutzergenerierte Inhalte haftbar gemacht zu werden, für Dienstanbieter sehr schädlich sein. Bei potenziellen Schäden, die sich über Millionen von Nutzer vervielfältigen, hätte es Cloud-Computing-Sites und Sites mit nutzergenerierte Inhalten wie YouTube, Facebook oder GitHub ohne DMCA wahrscheinlich [niemals gegeben](https://arstechnica.com/tech-policy/2015/04/how-the-dmca-made-youtube/) (oder zumindest nicht, ohne einen Teil dieser Kosten an ihre Nutzer weiterzugeben).

Der DMCA geht dieses Problem an, indem er einen [urheberrechtlichen Haftungsschutz](https://www.copyright.gov/title17/92chap5.html#512) für Internetdienstanbieter schafft, die mutmaßlich rechtsverletzende nutzergenerierte Inhalte hosten. Solange sich ein Dienstanbieter an die Notice-and-Takedown-Regeln des DMCA hält, haftet er im Wesentlichen nicht für Urheberrechtsverletzungen auf der Grundlage von nutzergenerierten Inhalten. Aus diesem Grund ist es für GitHub wichtig, seinen DMCA-Safe-Harbor-Status beizubehalten.

Der DMCA verbietet auch die [Umgehung technischer Maßnahmen](https://www.copyright.gov/title17/92chap12.html), die den Zugang zu urheberrechtlich geschützten Werken wirksam kontrollieren.

[DMCA-Hinweise in Kürze](#dmca-notices-in-a-nutshell)
----------

Der DMCA bietet zwei einfache, unkomplizierte Verfahren, die alle GitHub-Nutzer kennen sollten: (i) ein [Takedown Notice](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)-Verfahren für Urheberrechtsinhaber, um die Entfernung von Inhalten zu beantragen; und (ii) ein [Counter Notice](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)-Verfahren, mit dem Nutzer Inhalte wieder aktivieren können, wenn Inhalte versehentlich oder durch fälschliche Identifizierung entfernt wurden.

DMCA [Takedown Notices](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) werden von Urheberrechtsinhabern verwendet, um GitHub zu bitten, Inhalte zu entfernen, von denen sie glauben, dass sie eine Verletzung darstellen. Als Softwaredesigner oder -entwickler erstellen Sie jeden Tag urheberrechtlich geschützte Inhalte. Wenn jemand anderes Ihre urheberrechtlich geschützten Inhalte auf GitHub auf nicht autorisierte Weise verwendet, können Sie uns eine DMCA-Entfernungsmitteilung senden, um zu verlangen, dass die verletzenden Inhalte geändert oder entfernt werden.

Auf der anderen Seite können mit [Counter Notices](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice) Fehler korrigiert werden. Möglicherweise besitzt die Person, die die Deaktivierungsmitteilung sendet, keine Urheberrechte oder hat nicht bemerkt, dass Sie eine Lizenz besitzen, oder hat einen anderen Fehler in ihrer Deaktivierungsmitteilung gemacht. Da GitHub normalerweise nicht wissen kann, ob ein Fehler vorliegt, können Sie uns die DMCA-Gegendarstellung mitteilen und darum bitten, dass wir den Inhalt wieder einstellen.

Der DMCA-Benachrichtigungs- und Deaktivierungsprozess sollte nur für Beschwerden über Urheberrechtsverletzungen verwendet werden. Mitteilungen, die über unseren DMCA-Prozess gesendet werden, müssen urheberrechtlich geschützte Werke oder Werke, die angeblich verletzt werden, identifizieren. Das Verfahren kann nicht für andere Beschwerden verwendet werden, z. B. Beschwerden über mutmaßliche [Markenrechtsverletzung](/de/site-policy/content-removal-policies/github-trademark-policy) oder [sensible Daten](/de/site-policy/content-removal-policies/github-private-information-removal-policy); für diese Situationen bieten wir separate Prozesse an.

[A. Wie funktioniert das eigentlich?](#a-how-does-this-actually-work)
----------

Das DMCA-Framework ist ein bisschen wie das Verteilen von Notizen im Unterricht. Der Urheberrechtsinhaber reicht GitHub eine Beschwerde über einen Benutzer ein. Wenn es richtig geschrieben ist, leiten wir die Beschwerde an den Benutzer weiter. Wenn der Benutzer die Beschwerde bestreitet, kann er dies in einer Notiz zurückgeben. GitHub übt in diesem Prozess wenig Ermessensspielraum aus, außer zu bestimmen, ob die Mitteilungen die Mindestanforderungen des DMCA erfüllen. Es ist Sache der Parteien (und ihrer Anwälte), die Begründetheit ihrer Ansprüche zu beurteilen, wobei zu beachten ist, dass Mitteilungen unter Strafe des Meineids erfolgen müssen.

Hier sind die grundlegenden Schritte des Prozesses.

1. **Urheberrechtsinhaber untersucht die Angelegenheit.** Ein Urheberrechtsinhaber sollte immer eine erste Untersuchung durchführen, um sowohl (a) zu bestätigen, dass er das Urheberrecht an einem Originalwerk besitzt, als auch (b), dass der Inhalt auf GitHub nicht autorisiert ist und eine Verletzung darstellt. Dazu gehört die Bestätigung, dass die Verwendung nicht als geschützt im Rahmen der [angemessenen Verwendung](https://www.lumendatabase.org/topics/22) gilt. Eine bestimmte Verwendung kann fair sein, wenn sie nur eine kleine Menge urheberrechtlich geschützter Inhalte verwendet, diese Inhalte auf transformative Weise verwendet, sie für Bildungszwecke verwendet oder eine Kombination der oben genannten. Da sich Code natürlich für solche Anwendungen anbietet, ist jeder Anwendungsfall anders und muss separat betrachtet werden.

   >
   >
   > **Beispiel:** Ein Beschäftigter der Acme Web Company findet Code des Unternehmens in einem GitHub-Repository. Die Acme Web Company lizenziert ihren Quellcode an mehrere vertrauenswürdige Partner. Vor dem Einsenden einer Take-down-Benachrichtigung sollte Acme diese Lizenzen und seine Vereinbarungen überprüfen, um zu bestätigen, dass der Code auf GitHub unter keiner von ihnen autorisiert ist.
   >
   >

2. **Urheberrechtsinhaber sendet eine Mitteilung.** Im Anschluss an eine Untersuchung erstellt und sendet ein Urheberrechtsinhaber eine [Takedown Notice](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) an GitHub. Unter der Annahme, dass die Takedown Notice gemäß den gesetzlichen Anforderungen ausreichend detailliert ist (wie in der [Anleitung](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) erläutert), werden wir [die Mitteilung](#d-transparency) in unserem [öffentlichen Repository](https://github.com/github/dmca) veröffentlichen und den Link an den betroffenen Nutzer weitergeben.

3. **GitHub fordert den Benutzer auf, Änderungen vorzunehmen.** Wenn in der Mitteilung behauptet wird, dass der gesamte Inhalt eines Repositorys oder ein Paket eine Verletzung darstellt, werden wir mit Schritt 6 fortfahren und das gesamte Repository oder Paket umgehend deaktivieren. Da GitHub den Zugriff auf bestimmte Dateien innerhalb eines Repositorys nicht deaktivieren kann, werden wir andernfalls den Benutzer kontaktieren, der das Repository erstellt hat, und ihm ungefähr einen Werktag geben, um den in der Mitteilung angegebenen Inhalt zu löschen oder zu ändern. Wir benachrichtigen den Urheberrechtsinhaber, wenn wir dem Benutzer die Möglichkeit geben, Änderungen vorzunehmen. Da Pakete unveränderlich sind, müsste GitHub das gesamte Paket deaktivieren, wenn nur ein Teil eines Pakets eine Verletzung darstellt, aber wir erlauben die Wiederherstellung, sobald der verletzende Teil entfernt wurde.

4. **Benutzer benachrichtigt GitHub über Änderungen.** Wenn der Nutzer die angegebenen Änderungen vornimmt, ist er *verpflichtet*, uns dies innerhalb eines Zeitfensters von etwa einem Werktag mitzuteilen. Wenn dies nicht der Fall ist, deaktivieren wir das Repository (wie in Schritt 6 beschrieben). Wenn der Benutzer uns mitteilt, dass er Änderungen vorgenommen hat, werden wir überprüfen, ob die Änderungen vorgenommen wurden, und dann den Urheberrechtsinhaber benachrichtigen.

5. **Der Urheberrechtsinhaber ändert die Mitteilung oder zieht sie zurück.** Wenn der Nutzer Änderungen vornimmt, muss der Urheberrechtsinhaber diese überprüfen und seine Entfernungsmitteilung erneuern oder überarbeiten, wenn die Änderungen nicht ausreichen. GitHub wird keine weiteren Maßnahmen ergreifen, es sei denn, der Urheberrechtsinhaber kontaktiert uns, um entweder die ursprüngliche Deaktivierungsmitteilung zu erneuern oder eine überarbeitete einzureichen. Wenn der Urheberrechtsinhaber mit den Änderungen zufrieden ist, kann er entweder einen formellen Widerruf einreichen oder nichts unternehmen. GitHub interpretiert Stillschweigen von mehr als zwei Wochen als stillschweigende Rücknahme der Deaktivierungsmitteilung.

6. **GitHub kann den Zugriff auf den Inhalt deaktivieren.** GitHub deaktiviert den Inhalt eines Nutzers, wenn: (i) der Inhaber des Urheberrechts behauptet, das Urheberrecht am gesamten Repository oder Paket des Nutzers zu besitzen (wie in Schritt 3 angegeben); (ii) der Nutzer keine Änderungen vorgenommen hat, nachdem ihm Gelegenheit dazu gegeben wurde (wie in Schritt 4 angegeben); oder (iii) der Urheberrechtsinhaber seine Takedown Notice erneuert hat, nachdem der Nutzer die Möglichkeit hatte, Änderungen vorzunehmen. Wenn der Urheberrechtsinhaber sich stattdessen dafür entscheidet, die Mitteilung zu *überarbeiten*, kehren wir zu Schritt 2 zurück und wiederholen den Vorgang, als ob die überarbeitete Mitteilung eine neue Mitteilung wäre.

7. **Der Nutzer kann eine Counter Notice senden.** Wir empfehlen Benutzern, deren Inhalte deaktiviert wurden, sich mit einem Anwalt über ihre Optionen zu beraten. Wenn ein Nutzer glaubt, dass sein Inhalt aufgrund eines Fehlers oder durch fälschliche Identifizierung deaktiviert wurde, kann er uns eine [Counter Notice](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice) senden. Wie bei der ursprünglichen Mitteilung werden wir sicherstellen, dass die Counter Notice ausreichend detailliert ist (wie in der [Anleitung](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice) erläutert). In diesem Fall [veröffentlichen](#d-transparency) wir sie in unserem [öffentlichen Repository](https://github.com/github/dmca) und geben die Mitteilung an den Urheberrechtsinhaber zurück, indem wir diesem den Link senden.

8. **Der Urheberrechtsinhaber kann rechtliche Schritte einleiten.** Wenn ein Urheberrechtsinhaber den Inhalt nach Erhalt einer Gegendarstellung deaktiviert lassen möchte, muss er eine rechtliche Klage einleiten, um einen Gerichtsbeschluss zu erwirken, um den Benutzer daran zu hindern, sich an rechtsverletzenden Aktivitäten in Bezug auf den Inhalt auf GitHub zu beteiligen. Mit anderen Worten, Sie könnten verklagt werden. Wenn der Urheberrechtsinhaber GitHub nicht innerhalb von 10 bis 14 Tagen benachrichtigt, indem er eine Kopie einer gültigen Rechtsbeschwerde sendet, die bei einem zuständigen Gericht eingereicht wurde, wird GitHub den deaktivierten Inhalt wieder aktivieren.

[B. Was ist mit Gabeln? (oder Was ist eine Gabel?)](#b-what-about-forks-or-whats-a-fork)
----------

Eines der besten Features von GitHub ist die Möglichkeit für Benutzer, die Repositories der anderen zu „forken“. Was bedeutet das? Im Wesentlichen bedeutet dies, dass Benutzer eine Kopie eines Projekts auf GitHub in ihren eigenen Repositories erstellen können. Wenn die Lizenz oder das Gesetz es zulässt, können Benutzer dann Änderungen an diesem Fork vornehmen, um entweder zum Hauptprojekt zurückzukehren oder einfach ihre eigene Variante eines Projekts zu behalten. Jedes dieser Exemplare ist ein „[GitHub-Glossar](/de/get-started/quickstart/github-glossary#fork)“ des ursprünglichen Repositorys, das wiederum auch als „übergeordnetes Element“ der Fork bezeichnet werden kann.

GitHub wird Forks *nicht* automatisch deaktivieren, wenn ein übergeordnetes Repository deaktiviert wird. Dies liegt daran, dass Forks verschiedenen Benutzern gehören, möglicherweise erheblich verändert wurden und möglicherweise lizenziert oder auf andere Weise verwendet werden, die durch die Fair-Use-Doktrin geschützt ist. GitHub führt keine unabhängigen Untersuchungen zu Forks durch. Wir erwarten von Urheberrechtsinhabern, dass sie diese Untersuchung durchführen und, wenn sie der Meinung sind, dass die Forks ebenfalls eine Verletzung darstellen, Forks ausdrücklich in ihre Deaktivierungsmitteilung aufnehmen.

In seltenen Fällen können Sie eine Urheberrechtsverletzung in einem vollständigen Repository geltend machen, das aktiv gegabelt wird. Wenn Sie zu dem Zeitpunkt, an dem Sie Ihre Mitteilung eingereicht haben, alle bestehenden Forks dieses Repositorys als mutmaßlich verletzend identifiziert haben, würden wir zum Zeitpunkt der Bearbeitung der Mitteilung einen gültigen Anspruch gegen alle Forks in diesem Netzwerk bearbeiten. Wir würden dies angesichts der Wahrscheinlichkeit tun, dass alle neu erstellten Forks denselben Inhalt enthalten würden. Wenn das gemeldete Netzwerk, das die mutmaßlich verletzenden Inhalte enthält, größer als einhundert (100) Repositories ist und es daher schwierig wäre, es in seiner Gesamtheit zu überprüfen, können wir außerdem in Betracht ziehen, das gesamte Netzwerk zu deaktivieren, wenn Sie in Ihrer Mitteilung angeben, dass „Basierend Bei der repräsentativen Anzahl von Forks, die ich überprüft habe, glaube ich, dass alle oder die meisten Forks im gleichen Maße wie das übergeordnete Repository verletzen. Ihre eidesstattliche Erklärung würde für diese Erklärung gelten.

[C. Was ist mit Umgehungsansprüchen?](#c-what-about-circumvention-claims)
----------

Der DMCA verbietet die [Umgehung technischer Maßnahmen](https://www.copyright.gov/title17/92chap12.html), die den Zugang zu urheberrechtlich geschützten Werken wirksam kontrollieren. Angesichts der Tatsache, dass diese Arten von Ansprüchen oft sehr technischer Natur sind, verlangt GitHub von den Anspruchsstellern die Bereitstellung [detaillierter Informationen zu diesen Forderungen](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice#complaints-about-anti-circumvention-technology), und wir nehmen eine umfassendere Prüfung vor.

Eine Umgehungsklage muss die folgenden Angaben zu den eingesetzten technischen Maßnahmen und der Art und Weise, wie sie durch das beschuldigte Projekt umgangen werden, enthalten. Insbesondere muss die Mitteilung an GitHub detaillierte Erklärungen enthalten, die Folgendes beschreiben:

1. Was sind die technischen Maßnahmen?
2. Wie sie den Zugriff auf das urheberrechtlich geschützte Material effektiv kontrollieren; und
3. Wie das beschuldigte Projekt darauf abzielt, ihre zuvor beschriebenen technischen Schutzmaßnahmen zu umgehen.

GitHub wird Umgehungsansprüche genau prüfen, auch von technischen und rechtlichen Experten. In der technischen Überprüfung werden wir versuchen, die Details über die Funktionsweise der technischen Schutzmaßnahmen und die Art und Weise, wie das Projekt sie angeblich umgeht, zu validieren. Bei der rechtlichen Prüfung werden wir versuchen sicherzustellen, dass die Ansprüche nicht über die Grenzen des DMCA hinausgehen. In Fällen, in denen wir nicht feststellen können, ob ein Anspruch gültig ist, werden wir auf der Seite des Entwicklers irren und den Inhalt offen lassen. Wenn der Antragsteller weitere Einzelheiten nachverfolgen möchte, würden wir den Überprüfungsprozess erneut starten, um die überarbeiteten Ansprüche zu bewerten.

Wenn unsere Experten feststellen, dass ein Anspruch vollständig, rechtmäßig und technisch legitim ist, werden wir den Eigentümer des Repositorys kontaktieren und ihm die Möglichkeit geben, auf den Anspruch zu reagieren oder Änderungen am Repo vorzunehmen, um eine Deaktivierung zu vermeiden. Wenn sie nicht antworten, werden wir versuchen, den Eigentümer des Repositorys erneut zu kontaktieren, bevor wir weitere Schritte unternehmen. Mit anderen Worten, wir werden ein Repository nicht auf der Grundlage des mutmaßlichen Einsatzes von Technologie zur Umgehung von Maßnahmen deaktivieren, ohne zu versuchen, einen Repository-Eigentümer zu kontaktieren, um ihm die Möglichkeit zu geben, darauf zu antworten oder Änderungen vorzunehmen. Wenn wir das Problem nicht lösen können, indem wir uns zuerst an den Eigentümer des Repositorys wenden, prüfen wir immer gerne eine Antwort des Eigentümers des Repositorys, auch nachdem der Inhalt deaktiviert wurde, wenn er die Möglichkeit haben möchte, den Anspruch anzufechten, uns zusätzliche Fakten vorzulegen, oder nehmen Sie Änderungen vor, um den Inhalt wiederherzustellen. Wenn wir Inhalte deaktivieren müssen, stellen wir sicher, dass Repository-Eigentümer ihre Issues und Pull-Requests und andere Repository-Daten, die den mutmaßlichen Umgehungscode nicht enthalten, im rechtlich möglichen Umfang exportieren können.

Bitte beachten Sie, dass unser Überprüfungsprozess für Umgehungstechnologie nicht für Inhalte gilt, die andernfalls gegen unsere Richtlinien zur akzeptablen Nutzung verstoßen würden, was die Weitergabe nicht autorisierter Produktlizenzschlüssel betrifft, Software zur Generierung nicht autorisierter Produktlizenzschlüssel oder Software zur Umgehung von Prüfungen auf Produktlizenzschlüssel. Obwohl diese Art von Ansprüchen auch gegen die DMCA-Bestimmungen zur Umgehungstechnologie verstoßen können, sind diese in der Regel unkompliziert und rechtfertigen keine zusätzliche technische und rechtliche Überprüfung. Wenn ein Anspruch jedoch nicht einfach ist, z. B. im Fall von Jailbreaks, würde das Verfahren zur Überprüfung des Anspruchs auf Umgehung von Technologien angewendet.

Wenn GitHub eine DMCA Takedown Notice im Rahmen unseres Prozesses zur Überprüfung von Ansprüchen wegen Umgehungstechnologie verarbeitet, bieten wir dem Repository-Eigentümer eine Empfehlung an, um eine unabhängige Rechtsberatung über [GitHubs Developer Defense Fund](https://github.blog/2021-07-27-github-developer-rights-fellowship-stanford-law-school/) zu erhalten, die für ihn kostenlos ist.

[D. Was passiert, wenn ich versehentlich das Fenster zum Vornehmen von Änderungen verpasst habe?](#d-what-if-i-inadvertently-missed-the-window-to-make-changes)
----------

Uns ist bewusst, dass es viele triftige Gründe gibt, warum Sie möglicherweise keine Änderungen innerhalb des von uns bereitgestellten Zeitfensters von etwa einem Werktag vornehmen können, bevor Ihr Repository deaktiviert wird. Vielleicht wurde unsere Nachricht als Spam markiert, vielleicht waren Sie im Urlaub, vielleicht checken Sie Ihr E-Mail-Konto nicht regelmäßig oder vielleicht waren Sie einfach nur beschäftigt. Wir verstehen es. Wenn Sie antworten, um uns mitzuteilen, dass Sie die Änderungen gerne vorgenommen hätten, aber irgendwie die erste Gelegenheit verpasst haben, werden wir das Repository ein weiteres Mal für etwa einen Werktag erneut aktivieren, damit Sie die Änderungen vornehmen können. Auch hier müssen Sie uns benachrichtigen, dass Sie die Änderungen vorgenommen haben, damit das Repository nach diesem Zeitfenster von etwa einem Werktag aktiviert bleibt, wie oben unter [Schritt A.4](#a-how-does-this-actually-work) angegeben. Bitte beachten Sie, dass wir nur diese eine zusätzliche Chance anbieten.

[E. Transparenz](#e-transparency)
----------

Wir glauben, dass Transparenz eine Tugend ist. Die Öffentlichkeit sollte wissen, welche Inhalte von GitHub entfernt werden und warum. Eine informierte Öffentlichkeit kann potenzielle Probleme erkennen und aufdecken, die sonst in einem undurchsichtigen System unbemerkt bleiben würden. Wir veröffentlichen redigierte Kopien aller rechtlichen Mitteilungen, die wir erhalten (einschließlich Originalmitteilungen, Counter Notices oder Widerrufen), unter <https://github.com/github/dmca>. Wir werden Ihre persönlichen Kontaktinformationen nicht öffentlich veröffentlichen; Wir werden persönliche Informationen (mit Ausnahme von Benutzernamen in URLs) entfernen, bevor wir Mitteilungen veröffentlichen. Wir werden jedoch keine anderen Informationen aus Ihrer Mitteilung unkenntlich machen, es sei denn, Sie bitten uns ausdrücklich darum. Hier sind einige Beispiele für eine veröffentlichte [Takedown Notice](https://github.com/github/dmca/blob/master/2014/2014-05-28-Delicious-Brains.md) und[Counter Notice](https://github.com/github/dmca/blob/master/2014/2014-05-01-Pushwoosh-SDK-counternotice.md), damit Sie sich eine Vorstellung davon machen können. Wenn wir Inhalte entfernen, werden wir an ihrer Stelle einen Link zu dem entsprechenden Hinweis veröffentlichen.

Bitte beachten Sie auch, dass wir, obwohl wir nicht redigierte Mitteilungen nicht öffentlich veröffentlichen, eine vollständige nicht redigierte Kopie aller Mitteilungen, die wir erhalten, direkt an jede Partei weitergeben können, deren Rechte davon betroffen wären.

[F. Wiederholte Verletzung](#f-repeated-infringement)
----------

Es ist die Richtlinie von GitHub, unter geeigneten Umständen und nach eigenem Ermessen die Konten von Benutzern zu deaktivieren und zu kündigen, die möglicherweise die Urheberrechte oder andere geistige Eigentumsrechte von GitHub oder anderen verletzen.

[G. Übermittlung von Mitteilungen](#g-submitting-notices)
----------

Wenn Sie bereit sind, eine Mitteilung oder Gegendarstellung einzureichen:

* [So reichen Sie eine DMCA Takedown Notice ein](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)
* [So reichen Sie eine DMCA Counter Notice ein](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)

[Erfahren Sie mehr und sprechen Sie es an](#learn-more-and-speak-up)
----------

Wenn Sie im Internet stöbern, ist es nicht allzu schwer, Kommentare und Kritik zum Urheberrechtssystem im Allgemeinen und zum DMCA im Besonderen zu finden. Während GitHub die wichtige Rolle, die der DMCA bei der Förderung von Innovationen im Internet gespielt hat, anerkennt und schätzt, glauben wir, dass die Urheberrechtsgesetze wahrscheinlich ein oder zwei Patches gebrauchen könnten – wenn nicht eine ganz neue Version. Bei der Software verbessern und aktualisieren wir unseren Code ständig. Denken Sie darüber nach, wie sehr sich die Technologie seit 1998, als der DMCA geschrieben wurde, verändert hat. Macht es nicht einfach Sinn, diese Gesetze, die für Software gelten, zu aktualisieren?

Wir maßen uns nicht an, alle Antworten zu haben. Aber wenn Sie neugierig sind, hier sind ein paar Links zu wissenschaftlichen Artikeln und Blogbeiträgen, die wir mit Meinungen und Reformvorschlägen gefunden haben:

* [Unbeabsichtigte Konsequenzen: Zwölf Jahre unter dem DMCA](https://www.eff.org/wp/unintended-consequences-under-dmca) (Electronic Frontier Foundation)
* [Gesetzlicher Schadensersatz im Urheberrecht: Ein reformbedürftiges Rechtsmittel](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1375604) (William & Mary Law Review)
* [Ist die Schutzdauer des Urheberrechts zu lang?](https://the1709blog.blogspot.com/2012/11/is-term-of-protection-of-copyright-too.html) (Der 1709-Blog)
* [Wenn wir das „Notice & Takedown“-Verfahren des DMCA ändern wollen, konzentrieren wir uns darauf, in welchem Umfang es missbraucht wird](https://www.techdirt.com/articles/20140314/11350426579/if-were-going-to-change-dmcas-notice-takedown-lets-focus-how-widely-its-abused.shtml) (TechDirt)
* [Möglichkeiten der Urheberrechtsreform](https://www.cato-unbound.org/issues/january-2013/opportunities-copyright-reform) (Cato Unbound)
* [Der Grundsatz der angemessenen Verwendung und der Digital Millennium Copyright Act: Gibt es im Internet eine angemessene Verwendung im Rahmen des DMCA?](https://digitalcommons.law.scu.edu/lawreview/vol42/iss1/6/) (Santa Clara Law Review)

GitHub unterstützt nicht unbedingt einen der Standpunkte in diesen Artikeln. Wir stellen die Links zur Verfügung, um Sie dazu zu ermutigen, sich zu informieren, sich eine eigene Meinung zu bilden und dann mit Ihren gewählten Vertretern in Kontakt zu treten (z. B. im [US Kongress](https://www.govtrack.us/congress/members) oder dem [EU- Parlament](https://www.europarl.europa.eu/meps/en/home)), um Änderungen anzustoßen, die Ihrer Meinung nach erforderlich sind.
