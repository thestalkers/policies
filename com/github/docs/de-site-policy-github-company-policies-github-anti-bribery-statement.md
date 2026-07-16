GitHub-Erklärung zur Bestechungsbekämpfung - GitHub Dokumente(function(){
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
3. [GitHub-Unternehmensrichtlinien](/de/site-policy/github-company-policies)
4. [GitHub-Erklärung zur Bestechungsbekämpfung](/de/site-policy/github-company-policies/github-anti-bribery-statement)

Breadcrumbs nach rechts scrollen

[Site policy](/de/site-policy)
----------

GitHub-Erklärung zur Bestechungsbekämpfung
==========

Als Markdown kopieren

In diesem Artikel
----------

* [GitHub-Richtlinien, die Bestechung verbieten](#github-policies-prohibiting-bribery)
* [Schulungen für unsere Mitarbeiter](#training-for-our-employees)
* [Einbindung unserer Partner](#engaging-our-partners)

GitHub hält an unserer Verpflichtung zu ethischen Geschäftspraktiken fest, unter anderem durch das Verbot von Bestechung und Korruption. Wie [Transparency International](https://www.transparency.org/what-is-corruption) erklärt, verursacht Korruption folgende Arten von Kosten:

* **politische**, weil sie ein großes Hindernis für Demokratie und Rechtsstaatlichkeit darstellt
* **wirtschaftliche** durch die Erschöpfung des Volksvermögens
* **soziale**, weil das Vertrauen der Menschen in die politische Gesellschaft, Institutionen und Anführer untergraben wird
* **umweltbezogene**, weil die Nichtdurchsetzung von Umweltgesetzen und -vorschriften erleichtert wird.

[GitHub-Richtlinien, die Bestechung verbieten](#github-policies-prohibiting-bribery)
----------

GitHub macht unser Engagement gegen Bestechung in einer Reihe von Unternehmensrichtlinien deutlich. Als Teil der Microsoft-Familie bekennt sich GitHub zusätzlich zu den hier beschriebenen Richtlinien auch zur Antikorruptionsrichtlinie von Microsoft, die für alle Mitarbeiter und Auftragnehmer von GitHub gilt.

Der **Ethikkodex** von GitHub verbietet es Mitarbeitern und Auftragnehmern, sich an Bestechung oder Korruption zu beteiligen oder dazu beizutragen, und legt Vorschriften für die Aufbewahrung von Aufzeichnungen fest:

>
>
> Sie dürfen niemals etwas anderes von Wert zahlen, anbieten, versprechen, versprechen, veranlassen, annehmen oder autorisieren, an irgendjemanden – einschließlich an Personen in einer Macht- oder Autoritätsposition, wie z. B. Regierungsbeamte oder bei kommerziellen Transaktionen – um ein Geschäft zu erhalten oder aufrechtzuerhalten oder um sich einen anderen unangemessenen Vorteil für GitHub oder Microsoft zu sichern. Sie dürfen auch keine Bestechungsgelder, Schmiergelder oder andere unzulässige Barzahlungen erbitten oder annehmen. ... [GitHub Mitarbeiter] sind verpflichtet, genaue und faire Aufzeichnungen über alle Transaktionen zu führen, die Ausgaben beinhalten, die im Namen von GitHub getätigt wurden – beispielsweise durch das Aufbewahren von Quittungen und das Bereitstellen genauer Beschreibungen Ihrer Ausgaben – sowie alle anderen Transaktionen, die die Veräußerung oder Übertragung von GitHub-Vermögenswerten beinhalten. Solche Maßnahmen werden vom US Foreign Corrupt Practices Act, dem Vereinigten Königreich, verlangt Bribery Act of 2010 und Antikorruptionsgesetze anderer Jurisdiktionen, in denen GitHub geschäftlich tätig ist, und sind ebenfalls einfach das Richtige.
>
>

Der Ethikkodex von GitHub geht auf bestimmte Situationen ein, darunter Geschenke, Reisen und Bewirtung; Erleichterung von Zahlungen; Spenden für wohltätige Zwecke; Arbeitsplätze; und die Zusammenarbeit mit Vertretern sowie darüber, wer als Regierungsbeamter gilt.

Die Verhaltensstandards von GitHub verbieten:

>
>
> Bestechung von Regierungsbeamten oder anderen Personen, um sich einen unfairen Vorteil zu verschaffen, und Annahme von Bestechungsgeldern von irgendjemandem.
>
>

In der **Richtlinie zu Geschenken und Bewirtung** von GitHub wird erläutert, dass Bestechung im Zusammenhang mit Reisen oder Bewirtungen nicht gestattet ist, und gibt Beispiele zur Veranschaulichung unangemessenen Verhaltens. Die Richtlinie beschreibt angemessene und unangemessene Geschenke, Reise- und Bewirtungskosten; Unternehmensprozesse für das Schenken von Geschenken durch die Direktoren, leitenden Angestellten, Mitarbeiter und Vertreter von GitHub und Anforderungen für die Aufbewahrung von Aufzeichnungen, Strafen; und Meldung von Verstößen. Es enthält klare monetäre Schwellenwerte für Geschenke sowie jährliche Beschränkungen, mit begrenzten Ausnahmen für Geschenke, die von der entsprechenden Geschäftsleitung genehmigt wurden. Die Richtlinie ist klar und für GitHub-Mitarbeiter und Auftragnehmer leicht zugänglich.

[Schulungen für unsere Mitarbeiter](#training-for-our-employees)
----------

GitHub-Mitarbeiter müssen an Schulungen zum Thema Korruption, einschließlich Bestechung, teilnehmen. Darüber hinaus bieten wir zusätzliche Schulungen für besonders relevante Personen und Teams, wie z. B. unser Vertriebsteam, an. Das Training erklärt relevante Elemente des US Foreign Corrupt Practices Act und des U.K. Bribery Act of 2010. Beispiel:

* Definition und strukturelle Auswirkungen von Korruption
* Wer versichert ist, inkl
  * Beamte oder andere in einer Machtposition
  * Dritte

* Welche Art von Aktivität abgedeckt ist, einschließlich
  * Bargeld, Geschenke, Reisen und Unterhaltung
  * Erleichterungszahlungen
  * Wohltätigkeitsbeiträge und Sponsoring

* Zu welchem Zweck, inkl
  * Absicht
  * Unangemessener Vorteil oder Einfluss

* Due Diligence und rote Fahnen
* Aufzeichnungspflichten

Darüber hinaus behandelt die Schulung die internen Richtlinien von GitHub zur Bekämpfung von Korruption und Bestechung, einschließlich unserer Richtlinie zum Verzicht auf Vergeltungsmaßnahmen (Whistleblower).

Während sich der US-FCPA auf Interaktionen mit Regierungsbeamten konzentriert, ist das Vereinigte Königreich Das Bestechungsgesetz ist umfassender und erstreckt sich auf die Bestechung von Personen, unabhängig davon, ob es sich um einen Regierungsbeamten handelt. Beide Gesetze können sich auf die Handlungen von GitHub in anderen Teilen der Welt erstrecken. Die Richtlinien von GitHub verbieten die Bestechung von Personen überall auf der Welt.

[Einbindung unserer Partner](#engaging-our-partners)
----------

* Die standardmäßigen **Wiederverkaufsvereinbarungen mit Channel-Partnern** enthalten verbindliche Antikorruptionsklauseln. In Zukunft verlangt GitHub von unseren Vertriebspartnern, sich zur Einhaltung dieser Anti-Korruptions-Erklärung zu verpflichten.
* Künftig verlangen die **Anbieterverträge** von GitHub nun eine Verpflichtung zur Einhaltung des Verhaltenskodex für Lieferanten von Microsoft oder dieser Erklärung zur Bestechungsbekämpfung.
