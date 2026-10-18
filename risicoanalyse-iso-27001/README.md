# Risicoanalyse ISO 27001

Een risicoregister voor de risicobeoordeling en risicobehandeling van ISO 27001: per risico de dreiging, de kans en de impact, het risiconiveau (rekent de Excel zelf uit), de behandeling, de maatregelen uit bijlage A en het restrisico, met  kolommen.

- **Excel:** [maasiso-risicoanalyse-iso-27001.xlsx](maasiso-risicoanalyse-iso-27001.xlsx)
- **Uitleg en toelichting:** https://www.maasiso.nl/gratis-tools/risicoanalyse-iso-27001/
- **Versie:** 1.0, 18 oktober 2026
- **Licentie:** [CC BY 4.0](../LICENSE): vrij te gebruiken, aan te passen en te delen, ook commercieel, met vermelding van MaasISO en een link naar de pagina hierboven.

De schalen en niveaus zijn een voorstel van MaasISO: ISO 27001 laat de criteria aan de organisatie (6.1.2 a).

## Kans

| Score | Naam | Omschrijving |
| --- | --- | --- |
| 1 | Zeer klein | Nog nooit gebeurd en niet te verwachten; minder dan eens in de tien jaar. |
| 2 | Klein | Kan gebeuren, maar zelden; eens in de vijf tot tien jaar. |
| 3 | Mogelijk | Komt bij vergelijkbare organisaties voor; eens in de één tot vijf jaar. |
| 4 | Waarschijnlijk | Gebeurt naar verwachting elk jaar. |
| 5 | Bijna zeker | Gebeurt meerdere keren per jaar of gebeurt nu al. |

## Impact

| Score | Naam | Omschrijving |
| --- | --- | --- |
| 1 | Verwaarloosbaar | Geen merkbare gevolgen voor klanten of werk; binnen een uur opgelost. |
| 2 | Klein | Kleine verstoring of schade, binnen een dag hersteld; geen persoonsgegevens of vertrouwelijke informatie naar buiten. |
| 3 | Merkbaar | Werk ligt deels stil of een klant merkt het; beperkte financiële schade of een melding nodig. |
| 4 | Ernstig | Belangrijke dienst dagen niet beschikbaar, vertrouwelijke gegevens gelekt, forse schade of boete mogelijk. |
| 5 | Zeer ernstig | Voortbestaan van de organisatie of veiligheid van mensen in gevaar; langdurige uitval of grootschalig datalek. |

## Niveaus (kans × impact)

| Niveau | Score | Actie |
| --- | --- | --- |
| ✓ Laag | 1-4 | Accepteren mag; vastleggen en bij de volgende beoordeling opnieuw bekijken. |
| ! Midden | 5-9 | Maatregelen overwegen; accepteren alleen met reden en akkoord van de risico-eigenaar. |
| ! Hoog | 10-15 | Behandelen met maatregelen en een plan met eigenaar en datum. |
| ✕ Zeer hoog | 16-25 | Direct behandelen; directie informeren en het risico niet accepteren zonder besluit van de directie. |

## Behandelopties (6.1.3 a)

- **Verminderen:** Maatregelen nemen die de kans of de impact verkleinen, bijvoorbeeld uit bijlage A.
- **Vermijden:** Stoppen met de activiteit of het systeem waar het risico uit voortkomt.
- **Delen:** Een deel van het risico bij een ander leggen, bijvoorbeeld via een verzekering of een contract met een leverancier.
- **Accepteren:** Het risico bewust dragen, met akkoord van de risico-eigenaar (6.1.3 f).

## Kolommen van het risicoregister

| Kolom | Uitleg | ISO/IEC 27001:2022 |
| --- | --- | --- |
| Nr. | Vast nummer per risico, zodat u in het behandelplan en de verklaring van toepasselijkheid ernaar kunt verwijzen. | – |
| Bedrijfsmiddel of proces | Waarop het risico betrekking heeft: een systeem, een proces, informatie of een locatie binnen de reikwijdte. | 4.3 |
| Dreiging | Wat er kan gebeuren, bijvoorbeeld phishing, uitval van de leverancier of verlies van een laptop. | 6.1.2 c |
| Kwetsbaarheid of oorzaak | Waardoor de dreiging kan slagen, bijvoorbeeld geen meerfactorauthenticatie of geen back-up buiten het netwerk. | 6.1.2 c |
| Gevolg voor V, I of B | Of het risico de vertrouwelijkheid, de integriteit of de beschikbaarheid van informatie raakt. | 6.1.2 c |
| Risico-eigenaar | De persoon die over het risico beslist en het restrisico accepteert. | 6.1.2 c, 6.1.3 f |
| Kans (1-5) | Hoe waarschijnlijk het is, volgens de schaal op het blad Criteria. | 6.1.2 d |
| Impact (1-5) | Hoe ernstig de gevolgen zijn, volgens de schaal op het blad Criteria. | 6.1.2 d |
| Risico | Kans maal impact; rekent de Excel zelf uit. | 6.1.2 d |
| Niveau | Laag, midden, hoog of zeer hoog volgens de grenzen op het blad Criteria; rekent de Excel zelf uit. | 6.1.2 e |
| Behandeling | Verminderen, vermijden, delen of accepteren. | 6.1.3 a |
| Maatregelen | Welke maatregelen u neemt, met het nummer uit bijlage A (bijvoorbeeld A.8.13 back-up). Neem ze over in de verklaring van toepasselijkheid. | 6.1.3 b, c, d |
| Actie en datum | Wat er nog moet gebeuren, door wie en wanneer: het risicobehandelplan. | 6.1.3 e, 8.3 |
| Restkans | De kans na de maatregelen. | 6.1.3 |
| Restimpact | De impact na de maatregelen. | 6.1.3 |
| Restrisico | Restkans maal restimpact, met het niveau; rekent de Excel zelf uit. | 6.1.3 |
| Restrisico geaccepteerd | Akkoord van de risico-eigenaar op het plan en het restrisico, met datum. | 6.1.3 f |
| Volgende beoordeling | Wanneer u het risico opnieuw bekijkt, en in elk geval bij een grote wijziging. | 8.2 |

## Goed om te weten

- **Clausules:** De risicobeoordeling staat in 6.1.2 van ISO/IEC 27001:2022, de risicobehandeling in 6.1.3; uitvoeren doet u volgens 8.2 en 8.3, met geplande tussenpozen en bij grote wijzigingen.
- **Eigen criteria:** De norm schrijft geen schaal voor: u legt zelf vast hoe u kans en impact beoordeelt en welk risico u accepteert (6.1.2 a). De schalen op het blad Criteria zijn een voorstel; pas ze aan en houd ze daarna vast, zodat de uitkomsten vergelijkbaar blijven (6.1.2 b).
- **Voorbeelden:** De eerste vijf regels op het blad Risicoregister zijn fictieve voorbeelden. Overschrijf of verwijder ze.
- **Geen normtekst:** Alle teksten zijn eigen woorden van MaasISO en geen normtekst; de norm zelf is te koop bij NEN.

De [ISO 27001 Toolkit](https://www.maasiso.nl/toolkits/iso-27001/) bevat ISB-P01 Procedure risicomanagement, RSK-002 Risicoregister en behandelplan, ISB-001 Verklaring van toepasselijkheid.
