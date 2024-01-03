Leitfaden zum Einreichen einer DMCA-Takedown-Mitteilung - GitHub-Dokumentation

[Skip to main content](#main-content)

[Startseite](/de)

[Site policy](/de/site-policy)

* [Websiterichtlinie](/de/site-policy)/
* [Richtlinien zum Entfernen von Inhalten](/de/site-policy/content-removal-policies)/
* [Leitfaden zum Einreichen einer DMCA-Takedown-Mitteilung](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)

Leitfaden zum Einreichen einer DMCA-Takedown-Mitteilung
==========

In diesem Artikel
----------

* [Bevor du anfängst](#before-you-start)
* [Ihre Beschwerde muss...](#your-complaint-must-)
* [Beschwerden über Antiumgehungstechnologie](#complaints-about-anti-circumvention-technology)
* [So reichen Sie Ihre Beschwerde ein](#how-to-submit-your-complaint)

Dieser Leitfaden beschreibt die Informationen, die GitHub benötigt, um eine DMCA-Takedown-Anfrage zu bearbeiten. Wenn Sie allgemeinere Fragen dazu haben, was der DMCA ist oder wie GitHub DMCA-Takedown-Anträge bearbeitet, lesen Sie bitte unsere [Richtlinie zu DMCA-Takedowns](/de/site-policy/content-removal-policies/dmca-takedown-policy).

Aufgrund der Art der Inhalte, die GitHub hostet (hauptsächlich Softwarecode) und der Art und Weise, wie die Inhalte verwaltet werden (mit Git), müssen Beschwerden so spezifisch wie möglich sein. Diese Richtlinien sollen die Bearbeitung mutmaßlicher Verstoßmeldungen so einfach wie möglich gestalten. Unser unten stehendes Meldeformular entspricht dem im DMCA vorgeschlagenen Formular, das auf der offiziellen Website des U.S. Copyright Office zu finden ist: <https://www.copyright.gov>.

Wie bei allen rechtlichen Angelegenheiten ist es immer am besten, sich zu Ihren spezifischen Fragen oder Ihrer Situation an einen Fachmann zu wenden. Wir empfehlen Ihnen dringend, dies zu tun, bevor Sie Maßnahmen ergreifen, die Ihre Rechte beeinträchtigen könnten. Dieser Leitfaden ist keine Rechtsberatung und sollte auch nicht als solche verstanden werden.

[Bevor du anfängst](#before-you-start)
----------

***Sagen Sie stets die Wahrheit.*** Der DMCA verlangt, dass Sie in Ihrer Urheberrechtsbeschwerde *unter Strafe des Meineids* auf die Tatsachen schwören. Es ist ein Bundesverbrechen, in einer eidesstattlichen Erklärung vorsätzlich zu lügen. (*Siehe* [United States Code, Titel 18, Abschnitt 1621](https://www.gpo.gov/fdsys/pkg/USCODE-2011-title18/html/USCODE-2011-title18-partI-chap79-sec1621.htm).) Das Einreichen falscher Informationen kann auch zu einer zivilrechtlichen Haftung führen – das heißt, Sie könnten auf Schadensersatz in Geld verklagt werden. Gemäß den Bestimmungen des DMCA ist jede Person, die vorsätzlich falsch aussagt, dass Material oder Aktivitäten eine Verletzung darstellen, [schadensersatzpflichtig](https://en.wikipedia.org/wiki/Online_Copyright_Infringement_Liability_Limitation_Act#%C2%A7_512(f)_Misrepresentations).

***Stellen Sie Untersuchungen an.*** Millionen von Benutzern und Organisationen stecken ihr Herz und ihre Seele in die Projekte, die sie auf GitHub erstellen und zu denen sie beitragen. Das Einreichen einer DMCA-Beschwerde gegen ein solches Projekt ist ein schwerwiegender Rechtsvorwurf, der echte Konsequenzen für echte Menschen hat. Aus diesem Grund bitten wir Sie, eine gründliche Untersuchung durchzuführen und einen Anwalt zu konsultieren, bevor Sie eine Deaktivierung einreichen, um sicherzustellen, dass die Verwendung tatsächlich nicht zulässig ist.

***Fragen Sie zunächst höflich nach.*** Ein guter erster Schritt, bevor Sie uns eine Deaktivierungsmitteilung senden, besteht darin, zu versuchen, den Benutzer direkt zu kontaktieren. Sie haben möglicherweise Kontaktinformationen auf ihrer öffentlichen Profilseite oder in der README-Datei des Repositorys aufgeführt, oder Sie können sich mit ihnen in Verbindung setzen, indem Sie ein Problem oder eine Pull-Anfrage im Repository öffnen. Dies ist nicht unbedingt erforderlich, aber es ist stilvoll.

***Reichen Sie den richtigen Antrag ein.*** Wir können DMCA-Deaktivierungsmitteilungen nur für Werke akzeptieren, die urheberrechtlich geschützt sind und die ein bestimmtes urheberrechtlich geschütztes Werk identifizieren. Wenn Sie eine Beschwerde über Markenmissbrauch einreichen möchten, lesen Sie bitte unsere [Markenrichtlinie](/de/site-policy/content-removal-policies/github-trademark-policy). Wenn Sie sensible Daten wie Kennwörter entfernen möchten, lesen Sie bitte unsere [Richtlinie zu sensiblen Daten](/de/site-policy/content-removal-policies/github-private-information-removal-policy). Wenn Sie einen Fall von Verleumdung oder anderem missbräuchlichem Verhalten melden möchten, lesen Sie bitte unsere [Community-Richtlinien](/de/site-policy/github-terms/github-community-guidelines).

***Code unterscheidet sich von anderen kreativen Inhalten.*** GitHub wurde für die Zusammenarbeit an Softwarecode entwickelt. Dies macht die Identifizierung einer gültigen Urheberrechtsverletzung komplizierter, als dies beispielsweise bei Fotos, Musik oder Videos der Fall wäre.

Es gibt eine Reihe von Gründen, warum sich Code von anderen kreativen Inhalten unterscheidet. Zum Beispiel:

* Ein Repository kann Bits und Teile von Code von vielen verschiedenen Personen enthalten, aber nur eine Datei oder sogar eine Unterroutine innerhalb einer Datei verletzt Ihre Urheberrechte.
* Code mischt Funktionalität mit kreativem Ausdruck, aber das Urheberrecht schützt nur die ausdrucksstarken Elemente, nicht die funktionalen Teile.
* Oft sind Lizenzen zu berücksichtigen. Nur weil ein Codeabschnitt einen Urheberrechtsvermerk enthält, bedeutet dies nicht unbedingt, dass er eine Urheberrechtsverletzung darstellt. Es ist möglich, dass der Code gemäß einer Open-Source-Lizenz verwendet wird.
* Eine bestimmte Verwendung kann [angemessen](https://www.lumendatabase.org/topics/22) sein, wenn nur wenige urheberrechtlich geschützte Inhalte verwendet werden, diese Inhalte auf transformative Weise verwendet werden, wenn die Inhalte für Bildungszwecke verwendet werden, oder wenn eine Kombination der oben genannten Bedingungen vorliegt. Da sich Code natürlich für solche Anwendungen anbietet, ist jeder Anwendungsfall anders und muss separat betrachtet werden.
* Der Code kann auf viele verschiedene Arten verletzt werden, was detaillierte Erklärungen und Identifizierungen von Werken erfordert.

Diese Liste ist nicht vollständig, weshalb es beim Umgang mit Code doppelt wichtig ist, mit einem Rechtsexperten über Ihre vorgeschlagene Beschwerde zu sprechen.

***Keine Bots.*** Sie sollten die Fakten jeder Deaktivierungsmitteilung, die Sie senden, von einem geschulten Fachmann auswerten lassen. Wenn Sie Ihre Bemühungen an Dritte auslagern, stellen Sie sicher, dass Sie wissen, wie sie arbeiten, und stellen Sie sicher, dass sie keine automatisierten Bots verwenden, um Beschwerden in großen Mengen einzureichen. Diese Beschwerden sind oft ungültig und ihre Bearbeitung führt dazu, dass Projekte unnötigerweise abgebrochen werden!

***Urheberrechtsfragen sind komplex.*** Es kann sehr schwierig sein festzustellen, ob ein bestimmtes Werk urheberrechtlich geschützt ist oder nicht. Beispielsweise sind Tatsachen (einschließlich Daten) im Allgemeinen nicht urheberrechtlich geschützt. Wörter und kurze Sätze sind im Allgemeinen nicht urheberrechtlich geschützt. URLs und Domainnamen sind im Allgemeinen nicht urheberrechtlich geschützt. Da Sie mit dem DMCA-Verfahren nur auf urheberrechtlich geschützte Inhalte abzielen können, sollten Sie bei Fragen zur Schutzfähigkeit Ihrer Inhalte mit einem Anwalt sprechen.

***Möglicherweise erhalten Sie eine Counter Notice.*** Jeder Benutzer, der von Ihrer Takedown Notice betroffen ist, kann eine [Counter Notice](/de/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice) einreichen. Wenn dies der Fall ist, werden wir ihre Inhalte innerhalb von 10 bis 14 Tagen wieder aktivieren, es sei denn, Sie teilen uns mit, dass Sie rechtliche Schritte eingeleitet haben, um den Benutzer daran zu hindern, sich an rechtsverletzenden Aktivitäten in Bezug auf die Inhalte auf GitHub zu beteiligen.

***Ihre Beschwerde wird veröffentlicht.*** Wie in unserer [Richtlinie zu DMCA-Takedowns](/de/site-policy/content-removal-policies/dmca-takedown-policy#d-transparency) dargelegt, veröffentlichen wir alle vollständigen und durchsetzbaren Takedown Notices, nachdem wir jegliche personenbezogenen Daten unkenntlich gemacht haben, unter <https://github.com/github/dmca>.

***GitHub tritt nicht als Richter auf.***GitHub übt in diesem Prozess wenig Ermessensspielraum aus, außer zu bestimmen, ob die Mitteilungen die Mindestanforderungen des DMCA erfüllen. Es ist Sache der Parteien (und ihrer Anwälte), die Begründetheit ihrer Ansprüche zu beurteilen, wobei zu beachten ist, dass Mitteilungen unter Strafe des Meineids erfolgen müssen.

[Ihre Beschwerde muss...](#your-complaint-must-)
----------

1. **die folgende Erklärung beinhalten: „I have read and understand GitHub's Guide to Filing a DMCA Notice.”** („Ich habe den Leitfaden von GitHub zur Einreichung einer DMCA-Notice gelesen und verstanden.”) Wir werden die Bearbeitung einer ansonsten vollständigen Beschwerde nicht ablehnen, wenn Sie diese Erklärung nicht beifügen. Aber wir wissen, dass Sie diese Richtlinien nicht gelesen haben, und bitten Sie möglicherweise, zurückzugehen und dies zu tun.

2. **Benennen Sie das urheberrechtlich geschützte Werk, bei dem Sie glauben, dass eine Urheberrechtsverletzung stattgefunden hat.** Diese Informationen sind wichtig, da sie dem betroffenen Benutzer helfen, Ihren Anspruch zu bewerten und ihm die Möglichkeit geben, Ihre Arbeit mit seiner zu vergleichen. Die Spezifität Ihrer Identifizierung hängt von der Art des Werks ab, von dem Sie glauben, dass es verletzt wurde. Wenn Sie Ihre Arbeit veröffentlicht haben, können Sie möglicherweise einfach auf eine Webseite verlinken, auf der sie sich befindet. Wenn es urheberrechtlich geschützt und nicht veröffentlicht ist, können Sie es beschreiben und erklären, dass es urheberrechtlich geschützt ist. Wenn Sie es beim Copyright Office registriert haben, sollten Sie die Registrierungsnummer angeben. Wenn Sie behaupten, dass der gehostete Inhalt eine direkte, wörtliche Kopie Ihrer Arbeit ist, können Sie diese Tatsache auch einfach erklären.

3. **Identifizieren Sie das Material, von dem Sie meinen, dass es die Urheberrechte des in Punkt 2 genannten Werks verletzt.** Es ist wichtig, bei Ihrer Identifizierung so genau wie möglich zu sein. Diese Identifizierung muss ausreichend sein, damit GitHub das Material finden kann. Dies bedeutet zumindest, dass Sie die URL zu dem Material angeben sollten, das angeblich Ihr Urheberrecht verletzt. Wenn Sie behaupten, dass weniger als ein ganzes Repository eine Verletzung darstellt, identifizieren Sie die spezifischen Dateien oder Zeilennummern innerhalb einer Datei, die Ihrer Meinung nach eine Verletzung darstellen. Wenn Sie behaupten, dass der gesamte Inhalt einer URL eine Verletzung darstellt, machen Sie dies bitte auch ausdrücklich.

   * Bitte beachten Sie, dass GitHub *keine* [Forks](/de/site-policy/content-removal-policies/dmca-takedown-policy#b-what-about-forks-or-whats-a-fork) automatisch deaktivieren wird, wenn ein Parent-Repository deaktiviert wird. Wenn Sie die Forks eines Repositorys untersucht und analysiert haben und der Meinung sind, dass sie ebenfalls eine Verletzung darstellen, geben Sie bitte jede mutmaßlich verletzende Fork explizit an. Bitte bestätigen Sie auch, dass Sie jeden Einzelfall untersucht haben und dass Ihre eidesstattlichen Erklärungen für jeden identifizierten Fork gelten. In seltenen Fällen können Sie eine Urheberrechtsverletzung in einem vollständigen Repository geltend machen, das aktiv gegabelt wird. Wenn Sie zu dem Zeitpunkt, an dem Sie Ihre Mitteilung eingereicht haben, alle bestehenden Forks dieses Repositorys als mutmaßlich verletzend identifiziert haben, würden wir zum Zeitpunkt der Bearbeitung der Mitteilung einen gültigen Anspruch gegen alle Forks in diesem Netzwerk bearbeiten. Wir würden dies angesichts der Wahrscheinlichkeit tun, dass alle neu erstellten Forks denselben Inhalt enthalten würden. Wenn das gemeldete Netzwerk, das die mutmaßlich verletzenden Inhalte enthält, größer als einhundert (100) Repositories ist und es daher schwierig wäre, es in seiner Gesamtheit zu überprüfen, können wir außerdem in Erwägung ziehen, das gesamte Netzwerk zu deaktivieren, wenn Sie in Ihrer Mitteilung angeben, dass „Basierend Bei der repräsentativen Anzahl von Forks, die Sie überprüft haben, glaube ich, dass alle oder die meisten Forks im gleichen Maße wie das übergeordnete Repository verletzen." Ihre eidesstattliche Erklärung würde für diese Erklärung gelten.

4. **Erklären Sie, was der betroffene Benutzer tun müsste, um den Verstoß zu beheben.** Auch hier ist die Spezifität wichtig. Wenn wir Ihre Beschwerde an den Benutzer weiterleiten, wird ihm mitgeteilt, was er tun muss, um zu vermeiden, dass der Rest seiner Inhalte deaktiviert wird. Muss der Benutzer nur eine Erklärung zur Namensnennung hinzufügen? Müssen sie bestimmte Zeilen in ihrem Code oder ganze Dateien löschen? Natürlich verstehen wir, dass in manchen Fällen der gesamte Inhalt eines Benutzers mutmaßlich rechtsverletzend ist und er nichts tun kann, außer alles zu löschen. Wenn dem so ist, machen Sie das bitte auch deutlich.

5. **Geben Sie Ihre Kontaktdaten an.** Geben Sie Ihre E-Mail-Adresse, Ihren Namen, Ihre Telefonnummer und Ihre physische Adresse an.

6. **Geben Sie die Kontaktinformationen der Person an, die Ihr Urheberrecht verletzt hat, falls Sie sie haben.** Normalerweise genügt dies, indem der GitHub-Benutzername angegeben wird, der mit dem mutmaßlich rechtsverletzenden Inhalt verknüpft ist. Es kann jedoch Fälle geben, in denen Sie zusätzliche Kenntnisse über den mutmaßlichen Rechtsverletzer haben. Wenn ja, teilen Sie uns diese Informationen bitte mit.

7. **Nehmen Sie die folgende Erklärung auf: „Ich bin nach Treu und Glauben der Ansicht, dass die Verwendung der oben beschriebenen Marke nicht vom Markeninhaber, seinem Vertreter oder dem Gesetz autorisiert wurde. Ich habe das Fair-Use-Prinzip bei meiner Bewertung berücksichtigt.”**

8. **Fügen Sie außerdem bitte folgende Erklärung ein: „Ich erkläre, dass die Informationen in dieser Mitteilung richtig sind, und ich erkläre ferner an Eides statt, dass ich befugt bin, im Namen des Inhabers des exklusiven und mutmaßlich verletzten Rechts aufzutreten.”**

9. **Setzen Sie Ihre physische oder elektronische Unterschrift darunter.**

[Beschwerden über Antiumgehungstechnologie](#complaints-about-anti-circumvention-technology)
----------

Das Urheberrechtsgesetz verbietet auch die Umgehung technischer Maßnahmen, die den Zugang zu urheberrechtlich geschützten Werken wirksam kontrollieren. Wenn Sie glauben, dass auf GitHub gehostete Inhalte gegen dieses Verbot verstoßen, senden Sie uns bitte einen Bericht über unseren [Formular für Urheberrechtsansprüche](https://github.com/contact/dmca). Eine Umgehungsklage muss die folgenden Angaben zu den eingesetzten technischen Maßnahmen und der Art und Weise, wie sie durch das beschuldigte Projekt umgangen werden, enthalten. Insbesondere muss die Mitteilung an GitHub detaillierte Erklärungen enthalten, die Folgendes beschreiben:

1. Was sind die technischen Maßnahmen?
2. Wie sie den Zugriff auf das urheberrechtlich geschützte Material effektiv kontrollieren; und
3. Wie das beschuldigte Projekt darauf abzielt, ihre zuvor beschriebenen technischen Schutzmaßnahmen zu umgehen.

[So reichen Sie Ihre Beschwerde ein](#how-to-submit-your-complaint)
----------

Sie erhalten am schnellsten eine Antwort, wenn Sie Ihre Informationen auf unserem [Formular für Urheberrechtsansprüche](https://github.com/contact/dmca) eingeben und dort alle Fragen beantworten.

Sie können auch eine E-Mail-Benachrichtigung an [copyright@github.com](mailto:copyright@github.com) senden. Sie können einen Anhang hinzufügen, wenn Sie möchten, aber bitte fügen Sie auch eine Nur-Text-Version Ihres Briefes in den Text Ihrer Nachricht ein.

Sie können Ihre Notice auch per Post senden, aber es dauert *sehr viel länger*, bis wir sie erhalten und darauf reagieren können. Mitteilungen, die wir per Klartext-E-Mail erhalten, werden viel schneller bearbeitet als PDF-Anhänge oder physische Post. Wenn Sie uns Ihre Mitteilung dennoch per Post zusenden möchten, lautet unsere physische Adresse:

```
GitHub, Inc
Attn: DMCA Agent
88 Colin P Kelly Jr St
San Francisco, CA. 94107

```
