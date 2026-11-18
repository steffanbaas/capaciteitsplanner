# Capaciteitsplanner

Een capaciteitsplanner in één HTML-bestand, met een Excel-bestand als database. Je ziet wie waar werkt, voor hoeveel uur en hoe lang: per medewerker, klant, klantgroep (pool), chapter en project.

Huidige versie: **v1.35**

## Gebruik

1. Open `Capaciteitsplanner.html` in Chrome of Edge.
2. Klik op **Openen** en kies je Excel-bestand. Begin je nieuw, gebruik dan `Capaciteitsplanner_template.xlsx`.
3. Wijzigingen worden automatisch in het Excel-bestand opgeslagen. Bij een volgende keer opent de planner het laatst gebruikte bestand vanzelf.

Er is geen server of account nodig. Alle gegevens blijven in je eigen Excel-bestand.

In browsers zonder schrijfrechten, zoals Firefox en Safari, sla je op met **Excel downloaden**. Op een telefoon is de planner alleen lezen.

## Mogelijkheden

- **Presentatie:** kerncijfers per chapter, en een top-down overzicht van chapter naar pools, klanten, projecten en medewerkers. Je kunt het afdrukken op A4.
- **Tijdlijn:** de inzet per maand per medewerker, klant of project, in FTE of uren. De weergave Flexruimte toont de vrije en flexibele capaciteit.
- **Medewerkers / Medewerker:** de bezetting, het werkrooster met A/B-weken, afwezigheid met opmerking, skills, certificeringen en een notitie.
- **Klant / Chapters & klanten:** per klant, per chapter en per steward, met popups die laten zien wie er betrokken is.
- **Projecten:** gegroepeerd per klant, met project manager, primair verantwoordelijken, on hold en afronden.
- **Rollen:** verantwoordelijkheden zonder inzet, zoals architect of steward.
- **Skills & certificeringen:** wie wat kan.
- **Sandbox:** simuleer inzet of het vertrek van iemand, zonder iets op te slaan.
- **Inzetvormen:** normaal, flexibel, flexibel max, vast (afgesproken uren) en automatisch.
- **Verder:** Nederlands en Engels, uren per week of per maand, en een telefoonweergave.

Een uitgebreide uitleg staat in de planner onder ⚙ → *Over deze portal*.

## Privacy

Het echte Excel-bestand bevat namen en gegevens van medewerkers. Zet dat bestand daarom **niet** in deze repository. `.gitignore` blokkeert alle `.xlsx`-bestanden, behalve de lege template.
