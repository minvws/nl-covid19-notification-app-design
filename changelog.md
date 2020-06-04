**Design Release 0.5 - Week 23**

Ons doel van deze week was om een zo compleet mogelijk overzicht te bieden van de verschillende schermen/flows, en een framework op te zetten waarbinnen we allen kunnen werken.

Mede met dank aan de community op Slack, GitHub en Twitter hebben we voor deze versie (0.5) een aantal belangrijke besluiten genomen. We verwachten dat deze besluiten een framework bieden waarbinnen we tot de release aan kunnen werken. Enkel bij grote veranderingen in het Plan van Eisen zullen hier mogelijk veranderingen in komen. De belangrijkste veranderingen willen we hier toelichten.

**Navigatie structuur**

We hebben verschillende navigatie structuren overwogen, zoals bijvoorbeeld een subtiel menu rechtsboven, een zeer zichtbaar opties menu knop onderaan, en een thuis scherm met scrollview met daarop content-kaarten. Uiteindelijk hebben we ervoor gekozen om de statuspagina scrollbaar te maken en hier de verschillende opties te tonen. De voornaamste overwegingen waren:

1. Deze optie is zeer toegankelijk, het is immers allemaal al aanwezig en zichtbaar te maken met 1 keer scrollen.
2. Het geeft direct een extra indruk van de werking van de applicatie.
3. Het is zeer schaalbaar mochten er in de toekomst extra items bij komen.

We hebben hierbij veel gehad aan de voorbeelden en input van o.a. Edwin van Bospoort, Aldert Greijdanus, Revi Kornmann, Stefan de Weijer Bart van de Biezen, Benjamin Broersma, Arian van Putten, Bas van Dorst, Rob Voets en Patrick Vos.

**Blootstelling Notificatie**

We moeten ten alle tijden voorkomen dat de applicatie gebruikt kan worden als een &#39;corona paspoort&#39; om aan te tonen dat iemand corona-vrij is. Dit zou bedrijven en instellingen ertoe kunnen bewegen om aan mensen te vragen om de app te tonen als bewijs dat zij niet in de buurt zijn geweest van iemand die positief getest is, of dat ze zelf positief zijn getest. Wanneer iemand een blootstelling notificatie heeft gehad, of zelf positief is getest, dan moeten zij de optie hebben om dit &quot;bericht&quot; te &quot;wissen&quot;. Tegelijkertijd is een blootstelling notificatie erg belangrijk, en kunnen we situaties bedenken (i.e. slaapdronken uit automatisme weg tappen) waarbij iemand de app al wel weer in een neutrale status heeft. We hebben grofweg 2 varianten overwogen.

1. Bij het ontvangen van een notificatie wordt een modal-view (scherm) geopend met het bericht en enige uitleg.
2. De statuspagina wordt aangepast, met een knop om de vervolgacties te lezen.

We hebben uiteindelijk gekozen voor optie B. De belangrijkste overwegingen hierbij waren dat

1. Deze optie voorkomt dat iemand uit automatisme het bericht sluit. Het wordt een zeer bewuste actie. We gaan er ook van uit dat het merendeel van de mensen het bericht niet zal willen sluiten omdat ze niet verwachten dat anderen naar hun telefoon zullen kijken. Dus het mogelijk maken het bericht te laten staan is belangrijk.
2. Dit houdt de belangrijkste informatie, maar ook de overige informatie in de app, voor hun beschikbaar. -- Wanneer iemand besluit om de app weer in de &#39;neutrale status&#39; te zetten dan is de essentiële informatie nog steeds beschikbaar, daar deze voor alle gebruikers altijd beschikbaar is.

We hebben hierbij wederom veel gehad aan de input van o.a. Edwin van de Bospoort, Michel de Meere, Amin Kadhim, Kevin Mol, Aldert Greijdanus, Revi Kornmann, Max de Froe, Matthijs Blaauw, Bas van Dorst, Ron van den Berg, Teun Hompe en Reyber Turgut.

Bovenstaand zijn de grote wijzigingen, daarnaast er ook vele kleinere wijzigingen. Je kunt de verschillende versies naast elkaar bekijken om deze te evalueren. Onderstaand een selectie van andere belangrijke stappen die we hebben kunnen zetten. We verwachten dat de rest van de wijzigingen zonder uitleg hier redelijk duidelijk zijn, maar beantwoorden graag alle vragen die je hebt op het slack kanaal!

- Er zijn nieuwe illustraties en teksten, op basis van community feedback en de user tests, in de schermen geplaatst.
- De verschillende staten van het statuspagina zijn nu toegevoegd. De belangrijkste zijn:
  - App is niet actief
  - Bluetooth staat niet aan
  - Bericht ontvangen
  - OS updaten om deze app te gebruiken.
- Er is een eerste tekstuele versie van het &quot;Hoe werkt de app&quot; scherm toegevoegd.
- Er is een eerste versie van de &quot;bevestigingscode&quot; flow toegevoegd.
- Er is een los instellingen scherm gemaakt waar daadwerkelijk secundaire functionaliteit staat zoals de privacy policy, en de terms of use.
- De optie om de app te delen is in de onboarding en onderaan het statuspagina toegevoegd om adoptie te helpen.

Nog een extra shoutout naar Maarten Janssen voor zijn ideeën m.b.t. de testknop, en naar Sebastian Wachholz, Ryan Barret en Lennert Dorman voor het vertalen van de documentatie in het Engels en Duits!

---

We hopen dat we niemand zijn vergeten in de credits. Naarmate er meer mensen meedoen zal het lastiger worden om bij te houden wie er heeft bijgedragen. We waarderen alle input enorm, en geloven dat deze ook essentieel is voor zowel de ontwikkeling als de uiteindelijke acceptatie en adoptie. Alleen samen kunnen we deze app tot een succes maken. Uiteindelijk willen we iedereen die heeft bijgedragen meenemen in een lijst in de app (subtiel verstopt).

Een eerste versie staat hier: https://github.com/minvws/nl-covid19-notification-app-design/pull/28
