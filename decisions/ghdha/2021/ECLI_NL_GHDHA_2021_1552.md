---
ecli: "ECLI:NL:GHDHA:2021:1552"
court: "Gerechtshof Den Haag"
court_code: "GHDHA"
docket: "200.284.695"
decided: "2021-06-15"
published: "2021-08-17"
type: "uitspraak"
procedure: "Hoger beroep kort geding"
subject: "Civiel recht"
source_url: "https://uitspraken.rechtspraak.nl/details?id=ECLI:NL:GHDHA:2021:1552"
published_in: ["Rechtspraak.nl"]
relations: [["Formele relatie", "Eerste aanleg: ECLI:NL:RBDHA:2020:9568, Bekrachtiging/bevestiging"]]
---

# ECLI:NL:GHDHA:2021:1552 Gerechtshof Den Haag , 15-06-2021 / 200.284.695

## Inhoudsindicatie

Kort geding - Auteursrecht - Roostersoftware voor onderwijsinstellingen met databases - spoedeisend belang

## Uitspraak

GERECHTSHOF DEN HAAG

Afdeling Civiel recht

Zaaknummer		: 200.284.695/01

Rolnummer rechtbank		: C/09/592547 / KG ZA 20-390

Arrest in kort geding van 15 juni 2021

in de zaak van

SCIENTIA LTD,

gevestigd te Cambridge, Verenigd Koninkrijk,

appellante in principaal hoger beroep,

verweerster in incidenteel hoger beroep,

hierna te noemen: Scientia,

advocaat: mr. R. Dijkema te Hilversum, voorheen mr. W. van Angeren te Amsterdam,

tegen

1
EVEOH V.O.F.

gevestigd te Den Haag,

hierna te noemen: Eveoh,

2.	[vennoot 1],

wonende te [woonplaats] ,

hierna te noemen: [vennoot 1] ,

3. [vennoot 2],

wonende te [woonplaats] ,

hierna te noemen: [vennoot 2]

geïntimeerden in principaal hoger beroep,

appellanten in incidenteel hoger beroep,

advocaat mr. A.P. Meijboom te Amsterdam,

Eveoh, [vennoot 1] en [vennoot 2] zullen hierna tezamen Eveoh c.s. worden genoemd.

1
Het geding

1.1.

Het hof heeft kennisgenomen van de volgende processtukken:

- het procesdossier van de eerste aanleg, waaronder het op 16 september 2020 in kort geding tussen partijen gewezen vonnis van de voorzieningenrechter in de rechtbank Den Haag (hierna: het vonnis);

- de dagvaarding in hoger beroep van 14 oktober 2020, met de producties 22 tot en met 26;

- de akte aanvulling conclusie van eis van de zijde van Scientia, met productie 27;

- de memorie van antwoord tevens memorie van grieven in incidenteel appel, met de producties 42 tot en met 44;

- de memorie van antwoord in incidenteel appel.

1.2.

Partijen hebben, nadat aanvankelijk een datum was bepaald voor een mondelinge behandeling, aan het hof te kennen gegeven af te zien van het recht op een mondelinge behandeling en hebben het hof verzocht arrest te wijzen op de stukken.

2
De vaststaande feiten

De door de voorzieningenrechter in het vonnis vastgestelde feiten zijn niet in geschil. Ook het hof zal daarvan uitgaan. Het gaat in deze zaak, voor zover in hoger beroep nog van belang, om het volgende.

2.1.

Scientia is een wereldwijde leverancier van roostersoftware voor universiteiten en hogescholen (hierna: de onderwijsinstellingen). Belangrijke softwareproducten van Scientia zijn de pakketten Syllabus Plus en Exam Scheduler.

2.2.

De softwareapplicatie Exam Scheduler strekt tot het genereren van examenroosters en het optimaliseren van het gebruik van kamers, personeel en surveillanten over meerdere campussen. Exam Scheduler maakt gebruik van de Exam Scheduler database (hierna: ESDB).

2.3.

De softwareapplicatie Syllabus Plus strekt tot het genereren van lesroosters. Syllabus Plus maakt gebruik van een database waarin alle data zijn opgenomen waarmee de lesroosters gegenereerd kunnen worden: de Scientia database (hierna: de SDB).

2.4.

Om individuele lesroosters ter beschikking te stellen aan medewerkers van de onderwijsinstellingen en studenten, bijvoorbeeld via een applicatie op hun mobiele telefoon of tablet, is software nodig die geen onderdeel uitmaakt van het Syllabus Plus-pakket.

2.5.

De structuur van de SDB is niet geschikt om management rapportages te genereren of interacties met applicaties van derden te ondersteunen. Daarvoor is een vertaalslag van de (data in de) SDB nodig. Ten behoeve van die vertaalslag kan met software die onderdeel uitmaakt van het Syllabus Plus-pakket, een Syllabus Plus Enterprise Reporting Database worden aangemaakt (hierna: de RDB), of kunnen meerdere RDB’s worden aangemaakt. Een RDB (door partijen ook ERDB genoemd), is een lege database die bestaat uit vooraf gedefinieerde tabellen en op die tabellen gebaseerde, voorgeprogrammeerde ‘views’. Een view bevat zelf geen data, maar een zogenaamde ‘query’ die de data dynamisch uit een andere tabel ophaalt wanneer de view geraadpleegd wordt. Met het programma Scheduled Extract kan de vertaalslag van de data in de SDB worden uitgevoerd en opgeslagen in de aangemaakte RDB. Als de RDB gevuld is, bevat deze een set data die geschikt is om uit te lezen en te presenteren aan een eindgebruiker.

2.6.

[vennoot 1] en [vennoot 2] zijn beherend vennoten van Eveoh. Eveoh ontwikkelt, implementeert, integreert en host software ten behoeve van onderwijsinstellingen.

2.7.

Het belangrijkste product van Eveoh is de softwareapplicatie MyTimetable. Met MyTimetable kunnen onderwijsinstellingen de met Syllabus Plus (of met andere softwareprogramma’s) opgestelde roosters beschikbaar stellen aan hun medewerkers en studenten, bijvoorbeeld via hun mobiele telefoon of tablet. Eveoh biedt een ‘on premise’-versie en een ‘software as a service’-versie (hierna: de SaaS-versie) van MyTimetable aan. De ‘on premise’-versie wordt geïnstalleerd en draait op de hardware van de betreffende onderwijsinstelling. Bij de SaaS-versie draait MyTimetable niet op servers van de universiteit zelf, maar bijvoorbeeld in ‘de cloud’, zoals in een cloudversie op de servers van Eveoh. De meest recente versie van MyTimetable wordt alleen nog in de SaaS-versie geleverd.

2.8.

Bij de klanten van Eveoh die Syllabus Plus van Scientia afnemen, leest MyTimetable de data van de RDB uit. Ten behoeve van het uitlezen van de data door de SaaS-versie van MyTimetable wordt een kopie (door Eveoh replica genoemd) van de RDB op de server van Eveoh opgeslagen. Voor iedere afnemer van de SaaS-versie van MyTimetable moet een dergelijke kopie van de betreffende RDB worden aangemaakt.

2.9.

In 2013 en 2014 hebben Scientia en Eveoh gesproken over een mogelijke samenwerking. In dat kader heeft Eveoh aan Scientia onder meer informatie verschaft over MyTimetable. De besprekingen hebben niet tot resultaat geleid.

2.10.

In de tweede helft van 2013 hebben Scientia en Eveoh ook contact gehad over de migratie van Syllabus Plus voor de Universiteit van Amsterdam (hierna: de UvA) en de Hogeschool Amsterdam (hierna: de HvA) van een omgeving bij een uitbesteder naar de eigen omgeving (on premise) van de UvA en de HvA. De UvA en de HvA maakten op dat moment al gebruik van MyTimetable. Per e-mail van 6 augustus 2013 heeft Eveoh in het kader van de migratie - voor zover in hoger beroep van belang - het volgende aan Scientia geschreven, waarbij het hof het antwoord dat vervolgens op 13 augustus 2013 door Scientia is gegeven, onderstreept heeft opgenomen:

“(…)

- Are you aware of any customer that uses SQL Server replication to do (one-way read only) replication of the ERDB to a different location?

It’s one of the options to get the data to Eveoh MyTimetable that we are considering for the new architecture.

RP – we are not aware of any clients that use replication, but see no reason why it would not be successful.

(…)”

2.11.

In een systeemontwerp dat is gemaakt ten behoeve van de UvA en de HvA, en is gedateerd 15 augustus 2013, heeft Eveoh - voor zover hier van belang - het volgende geschreven:

“(…)

2.6

Connections to other systems

(…) MyTimetable is hosted externally and needs a copy of the reporting database, which we will now discuss in more detail. (…).

2.6.1

Replication to Eveoh MyTimetable

At the moment, the MyTimetable servers fetch a copy of the RDB every night, after the Scheduled Extract has finished. This concerns 4 servers in total: UvA prod, UvA acc, HvA prod, HvA acc. The copy is made using a T-SQL script on the MyTimetable servers and a MS SQL linked server connection. This solution is error-prone and suboptimal: data is only updated once a day, network errors can cause the copy action to fail, and all data is transferred every day.

For the current RDB version (2.x in the case of the UvA, and 3.1.x in the case of the HvA), this is not a big issue. The Scheduled Extract cannot run in incremental mode and only runs once a day anyway. But in order to upgrade to the new reporting solution - featuring incremental and more rapid updating - a better solution is necessary.

In order to create a more robust and real-time solution, push-based replication can be used. After creating the RDB, transaction replication is set up from the source RDB to the MyTimetable SQL servers. This provides MyTimetable with semi real-time updates and a more robust connection.

It still has to be determined if the RDB can be replicated this way. Scientia is not aware of any clients using such a replication set up, but cannot find a reason why it would not work. There may be certain reasons we cannot use replication though: missing primary keys and truncate or alter table statements being used by the Scheduled Extract. Authentication and encryption requirements for this scenario still have to be determined. Once of the options could be to create a VPN connection between the MyTimetable servers and the UvA SQL servers. Another option would be to use encrypted/SSL SQL Server connections.

(…)”

Scientia heeft dit systeemontwerp van Eveoh ontvangen en heeft hierop input geleverd.

2.12.

Bij e-mail van 4 november 2013 heeft de UvA het volgende aan [ consultant Scientia] (hierna: [ consultant Scientia] ), senior technisch consultant van Scientia geschreven:

“(…)

The replication step to copy the databases to MyTimetable does not alter the data in the source RDBs.

(…)”

2.13.

Eveoh levert sinds 2015 de SaaS-versie van MyTimetable voor Syllabus Plus aan de Erasmus Universiteit Rotterdam (hierna: de Erasmus Universiteit), waarvoor met toestemming van Scientia een kopie van de RDB op de servers van Eveoh wordt opgeslagen.

2.14.

Sinds 2015 biedt Scientia onderwijsinstellingen de softwareapplicatie Scientia Publish aan, waarmee onderwijsinstellingen roosters beschikbaar kunnen stellen aan hun medewerkers en studenten, bijvoorbeeld via hun mobiele telefoon of tablet. Scientia Publish en MyTimetable zijn in zoverre dus concurrerende producten.

2.15.

Bij e-mail van 19 oktober 2017 heeft een medewerker van de Universiteit Utrecht over de koppeling tussen Syllabus Plus en MyTimetable het volgende geschreven aan [ consultant Scientia] (hierna: [ consultant Scientia] ), senior technisch consultant van Scientia, met cc aan onder meer accountmanager [accountmanager Scientia] van Scientia:

“We don’t use Publish. We use https://mytimetable.uu.nl to publish our timetables. MyTimetable is connected to S+ via scheduled extract. On the new test environment Scheduled Extract will have to be configured such that not only the local RDB’s are filled by Scheduled Extract, but also the MyTimetable RDb’s which are located in the MyTimetable datacenter.

(…)”

2.16.

Bij brief van 9 april 2020 heeft Scientia Eveoh c.s. gesommeerd om iedere inbreuk op de auteursrechten van Scientia te staken, bestaande uit, voor zover in hoger beroep nog van belang, het verveelvoudigen van de structuur van de RDB. Bij brief van haar advocaat van 28 april 2020 heeft Eveoh c.s. laten weten aan die sommatie geen gehoor te zullen geven.

2.17.

In opdracht van Scientia heeft [naam 1] (hierna: [naam 1] ) een verklaring opgesteld, gedateerd 20 mei 2020. Daarin staat onder meer het volgende:

“(…)

3. CHOICES MADE IN THE CREATION OF THE RDB

(…)

The contents of each table, each group of attributes and the relationships between them have been created by Scientia. There is no particular reason to make V_GROUP, V_ZONES, V_NAMEDAVAILABILITY, or V_POOLRESOURCE in separate tables because their attributes could be incorporated within other tables. (…) This demonstrates that there are different ways in which a database such as the RDB can be set up. In doing so, Scientia has made choices pertaining to the content of different views/tables and the correlation(s) between the two.

VIEWS independent on attributes

The data scheme diagrams of the different versions of the RDB included in annex 1 are simplified representations of the tables and views in the RDB. Various choices have been made in compiling the RDB, as is also clear based on these schematic diagrams.

(…)”

Daarna volgen enige voorbeelden van door Scientia gemaakte keuzes, en een tabel met een overzicht van gemaakte keuzes.

2.18.

In opdracht van Eveoh c.s. hebben drs. ing. [naam 2] (hierna: [naam 2] ) en [naam 3] BICT (hierna: [naam 3] ) een rapport opgesteld, gedateerd 10 juni 2020. Daarin staat onder meer het volgende:

“(…)

2 Samenvatting

(…)

Wij hebben geconstateerd dat Eveoh exemplaren van de RDB (in database termen: instances) van haar klanten host als onderdeel van de koppeling van Syllabus Plus.

(…)

Van de RDB instances hebben wij de structuur onderzocht en de claims op creativiteit van dit werk door Scientia tegen de aangetroffen details van de RDB instances aangehouden.

Onze conclusie is dat de vermeende creativiteitsaspecten zoals Scientia deze aanvoert niet terug te vinden zijn op hetgeen wij op de Eveoh omgevingen aantroffen.

Onze bevindingen omtrent de creativiteit van de verschillende onderdelen van de RDB zijn echter in tegenspraak met hetgeen [naam 1] (' [naam 1] ') daarover in zijn verklaring heeft verklaard (…). Dit verschil wordt veroorzaakt doordat [naam 1] feitelijk de creativiteit die is aangewend voor de ontwikkeling van de Syllabus Plus roosterapplicatie ten onrechte ‘plakt’ op de RDB instances.

(…)

7 Conclusies

(…)

Onderzoeksvraag 2: Wat zijn views en worden er bij het maken/schrijven van deze views, individueel en in onderlinge samenhang, creatieve keuzes of zijn die keuzes technisch bepaald (door de gewenste uitkomst)?

In de RDB database model (v3.10) zoals deze bij Eveoh in gebruik is voor haar klanten zijn 78 views aangetroffen. 73 daarvan zijn, zoals Scientia in haar eigen handleiding omschrijft ‘merely an identical copy of an underlying table’ en getuigen dus niet van enige creativiteit. De 5 views die hier vanaf wijken zijn dermate specifiek over wat ze dienen op te leveren aan gegevens dat hier geen realistische grote keuzen te maken zijn voor de ontwikkelaar van de views. Hetzelfde geldt voor de RDB model (v3.11), met dien verstande dat daarin 98 views zijn aangetroffen waarvan er 90 een identieke kopie betreffen en de 8 overgebleven views technisch bepaald zijn.

Ook als we de views als geheel beschouwen kunnen we niet tot een andere conclusie komen. Dit is niet een creatief product. De randvoorwaarden laten geen ruimte voor de bouwers van de views om hierbinnen duidelijke creatieve keuzes te maken.

Onze bevindingen wijken af van wat in de verklaring van [naam 1] staat beschreven. Wij hebben zijn statements onderzocht en zijn tot de conclusie gekomen dat de door hem beschreven creatieve keuzen allen betrekking hebben op de Syllabus Plus roosterapplicatie en dat zodra deze gegevens in de tabellen van de RDB verschijnen en via views omgezet worden tot het gedocumenteerde datamodel van de RDB hier alle creatieve opties niet meer aanwezig zijn.”

2.19.

In een in opdracht van Scientia opgesteld rapport van 17 juni 2020 heeft [naam 4] (hierna: [naam 4] ) in reactie hierop onder meer het volgende geschreven:

“(…)

1. Executive Summary

(…)

1.4 (…)

Whilst Eveoh’s position is that the only possibility for creative work occurs within the views, in my opinion the creative work occurs in both tables and views of the RDB.

1.5 (…)

A complex interwoven table structure is evident from both schema diagrams of the RDB shown in Appendix D. It is also notable that v3.11 (March 2015) has been significantly and creatively enhanced from the earlier v3.2 version (June 2012). This provides evidence that Scientia were providing creative development solutions to the table structure itself and in order to meet the requirements of modern educational establishments. Therefore, it is not possible to consider the creativity of views without taking into account the

overall database structure and its relationships and hierarchies.

1.6

The RDB makes table data available through a standardised process of views, many of which correspond to underlying tables in the RDB that have been populated with data transformed and migrated from the SDB. Whilst many of the views in their current form offer a simple replication of the data in a single underlying table, others make further transformation and customisation through client-controlled text fields, additional business logic and methodology to maintain compatibility with multiple software versions. I consider that the combination of the creative development of the tables and their interwoven structure, plus the decision to further customise and standardise their presentation via views forms creative work.

1.7

The various views of the RDB are joined together in a number of hierarchies and conventions of shared or pooled use of data. I also understand that the decision was taken to standardise the RDB through the use of views throughout, rather than some data being available in tables. Even if the views only have a single (and logical) method for achieving the desired result, the overall process behind the decisions to normalise the use of such simple views would improve compatibility with multiple software versions. This was a creative decision, which contributes to our opinion that the collective set of views qualify as original creative work.

1.8

Creative choices can be made in the design and development of a relational database such as the RDB, whether that is to produce complex queries, adopt a wider hierarchical structure or to use concepts like views or temporary tables as intermediary steps to required outputs. Whilst the majority of tables and views in the RDB would only have a single (and logical) method for achieving the desired result, the overall process behind the decision to normalise the use of views, improves compatibility with multiple software versions.

(…)”

2.20.

In een aanvullend rapport van 24 juni 2020 hebben [naam 2] en [naam 3] onder meer als volgt op het rapport van [naam 4] gereageerd:

“(…)

2. Nieuwe onderzoeksvragen

(…)

Zij achten niet meer alleen de views van de RDB relevant voor de beoordeling van de vraag of de RDB auteursrechtelijk is beschermd, maar nu ook de tabellen. Daarom heeft Kennedy van der Laan ons gevraagd om een aanvullende rapportage op te stellen waarin wij ingaan op de volgende vragen:

• Zijn bij de creatie van de tabellen in de RDB, afzonderlijk of in onderlinge samenhang beschouwd, creatieve keuzes gemaakt?

• Indien het antwoord op de vorige vraag ontkennend luidt: kan gezegd worden dat de tabellen en views, hoewel afzonderlijk beschouwd niet creatief, in onderlinge samenhang beschouwd leiden tot de conclusie dat de RDB getuigt van creatieve keuzes?

(…)

3. Creativiteit van de RDB beoordeeld met inbegrip van de tabellen

(…)

Met betrekking tot de eerste twee onderzoeksvragen komen wij tot de conclusie dat de tabellen afzonderlijk, noch in onderlinge samenhang beschouwd als een creatief werk kunnen worden aangemerkt. Zij zijn banaal en functioneel bepaald. Van de tabellen in combinatie met de views concludeerden wij in ons voorgaande rapport al, dat die afzonderlijk en in onderlinge samenhang geen creatief werk opleverden. Onze conclusie blijft dat de RDB niet creatief is.

(…)”

3
De procedure in eerste aanleg

3.1.

In eerste aanleg heeft Scientia - na wijziging van eis - onder meer gevorderd dat de voorzieningenrechter bij vonnis uitvoerbaar bij voorraad, beknopt weergegeven, Eveoh c.s. beveelt:

- om iedere inbreuk op de auteursrechten van Scientia te staken en gestaakt te houden, in het bijzonder maar niet beperkt tot het verveelvoudigen van de structuur en onderdelen van de RDB op de servers van Eveoh;

- om opgave te doen van degenen aan wie zij de SaaS-versie van MyTimetable voor Syllabus Plus heeft aangeboden;

- om opgave te doen van de afnemers van de SaaS-versie van MyTimetable voor Syllabus Plus;

alles op straffe van een dwangsom en met veroordeling van Eveoh c.s. in de volledige proceskosten op de voet van artikel 1019h Rv, vermeerderd met de wettelijke rente.

Daarnaast heeft Scientia een aantal vorderingen ingesteld betreffende (gestelde) inbreuk op de auteursrechten van Scientia op Exam Scheduler en/of de ESDB.

3.2.

Scientia heeft ter onderbouwing van haar vorderingen - voor zover in hoger beroep nog van belang en beknopt weergegeven - gesteld dat de structuur van de RDB een auteursrechtelijk beschermd werk is en dat Eveoh c.s. inbreuk maakt op de auteursrechten van Scientia door ten behoeve van de SaaS-versie van MyTimetable de structuur en onderdelen van de RDB te kopiëren naar de servers van Eveoh. Scientia heeft voorts gesteld dat zij belang heeft bij toewijzing van de vorderingen tegen [vennoot 1] en [vennoot 2] , aangezien Scientia zich zonder titel tegen de beherend vennoten slechts op het afgescheiden vermogen van Eveoh kan verhalen en niet op het vermogen van de vennoten.

3.3.

Eveoh c.s. heeft verweer gevoerd.

3.4.

De voorzieningenrechter heeft de vorderingen van Scientia afgewezen en Scientia veroordeeld in de kosten van de procedure, begroot met in achtneming van de Indicatietarieven in IE-zaken (versie april 2017, hierna: de Indicatietarieven) voor normale IE-kort gedingen. Ten aanzien van de vorderingen (inclusief nevenvorderingen) betreffende de gestelde auteursrechtinbreuk door het kopiëren van de structuur van de RDB naar de eigen server van Eveoh, heeft de voorzieningenrechter geoordeeld dat het spoedeisend belang bij die vordering ontbrak. In dit kader heeft de voorzieningenrechter - samengevat - overwogen:

- Scientia heeft in het kader van de gesprekken over een mogelijke samenwerking met Eveoh in 2013/2014 inzicht gekregen in het functioneren van MyTimetable in technische zin, zodat Scientia in meerdere opzichten goed bekend moet worden verondersteld met de MyTimetable software;

- Eveoh heeft in 2013 aan Scientia duidelijk gemaakt dat zij graag zou zien dat een RDB wordt “gecreëerd” op de MyTimetable server, waar de data van de ‘source’ RDB naar konden worden overgebracht,

- Scientia weet sinds 2015 dat Eveoh daarin is geslaagd, aangezien Eveoh sinds 2015 de SaaS-versie van MyTimetable levert aan de EUR, waarvoor met toestemming van Scientia een kopie van de RDB op de servers van Eveoh wordt opgeslagen;

- Scientia mag in elk geval sinds het e-mail bericht van de Universiteit Utrecht van 19 oktober 2017 bekend worden verondersteld met de wijze waarop Eveoh voor de SaaS-versie van MyTimetable gebruikt maakt van de RDB,

- de wetenschap van (senior) technical consultants van Scientia kan gelijk worden gesteld aan de wetenschap van Scientia.

Ten aanzien van de vorderingen (inclusief nevenvorderingen) betreffende de gestelde inbreuk op de auteursrechten van Scientia op Exam Scheduler en/of de ESDB heeft de voorzieningenrechter, samengevat, overwogen dat Scientia niet aan haar stelplicht heeft voldaan, dan wel haar vorderingen tegenover het verweer van Eveoh c.s. onvoldoende heeft onderbouwd.

4
Het geschil in hoger beroep

4.1.

In hoger beroep vordert Scientia na aanvulling van eis, samengevat, dat het hof het vonnis bij uitvoerbaar bij voorraad te verklaren arrest vernietigt en, opnieuw rechtdoende, Eveoh c.s. op straffe van een dwangsom beveelt:

- om iedere inbreuk op de auteursrechten van Scientia te staken en gestaakt te houden, in het bijzonder maar niet beperkt tot het verveelvoudigen van de structuur en onderdelen van de RDB op de servers van Eveoh;

- om opgave te doen van degenen aan wie zij de SaaS-versie van MyTimetable voor Syllabus Plus heeft aangeboden;

- om opgave te doen van de afnemers van de SaaS-versie van MyTimetable voor Syllabus Plus;

en dat het hof daarnaast:

- [vennoot 1] en [vennoot 2] ieder afzonderlijk en gezamenlijk gebiedt te bewerkstelligen dat Eveoh B.V. iedere inbreuk op de auteursrechten van Scientia per direct zal staken en gestaakt zal houden,

met hoofdelijke veroordeling van Eveoh c.s. in de volledige proceskosten ex art. 1019h Rv, vermeerderd met de wettelijke rente.

4.2.

Scientia heeft geen afzonderlijke grieven tegen het vonnis geformuleerd. Het hof begrijpt uit de appeldagvaarding dat Scientia vier grieven aanvoert tegen het vonnis:

- grief 1: de voorzieningenrechter heeft ten aanzien van de kwestie rond het kopiëren van de structuur van de RDB ten onrechte beslist dat het spoedeisend belang bij toewijzing van de vorderingen ontbreekt;

- grief 2: Scientia is ten onrechte veroordeeld tot vergoeding van de proceskosten van Eveoh c.s., aangezien de vorderingen van Scientia toegewezen hadden moeten worden;

- grief 3: Scientia is ten onrechte veroordeeld tot vergoeding van de proceskosten van Eveoh c.s., aangezien Eveoh voor die kosten verzekerd is en dus geen schade heeft geleden;

- grief 4: Scientia is ten onrechte veroordeeld tot vergoeding van de kosten die Eveoh c.s. heeft opgevoerd voor de rapporten van [naam 2] en [naam 3] .

Scientia heeft expliciet gesteld dat haar hoger beroep zich niet richt tegen het oordeel van de voorzieningenrechter in de kwestie betreffende Exam Scheduler/de ESDB.

4.3.

Eveoh c.s. voert in principaal hoger beroep verweer. In incidenteel hoger beroep vordert zij vernietiging van de kostenveroordeling van Scientia en veroordeling van Scientia in de werkelijk door Eveoh c.s. gemaakte proceskosten op de voet van artikel 1019h Rv, althans in het maximale bedrag in de categorie complexe bodemzaken, althans in een andere categorie van de Indicatietarieven dan een normaal IE-kort geding, tevens met veroordeling van Scientia in de kosten van Eveoh c.s. in hoger beroep op de voet van artikel 1019h, inclusief de advocaatkosten, deskundigenkosten en nakosten, uitvoerbaar bij voorraad. Daartoe voert zij aan dat de voorzieningenrechter ten onrechte aansluiting heeft gezocht bij het Indicatietarief voor een normaal kort geding.

4.4.

Scientia voert in incidenteel hoger beroep verweer. Zij meent dat de rechtbank terecht de Indicatietarieven heeft toegepast en refereert zich wat de categorie-indeling betreft aan het oordeel van het hof.

5
De beoordeling

In principaal hoger beroep

Ontvankelijkheid

5.1.

In haar akte houdende aanvulling conclusie van eis stelt Scientia dat Eveoh c.s. bij

brief van haar advocaat van 22 oktober 2020 heeft laten weten dat haar onderneming in 2019 is “ingebracht” in Eveoh B.V. Eveoh c.s. heeft hier in haar memorie van antwoord, tevens memorie van grieven in principaal appel, niet op gereageerd. Wat hier ook van zij, Scientia is ontvankelijk in haar hoger beroep tegen Eveoh c.s., omdat het vonnis is gewezen tussen Scientia en Eveoh c.s., terwijl is gesteld noch gebleken dat Eveoh is ontbonden en vereffend.

Spoedeisend belang

5.2.

De vraag of een eisende partij in kort geding voldoende spoedeisend belang heeft bij de gevraagde voorziening dient te worden beantwoord aan de hand van een afweging van de belangen van partijen, beoordeeld naar de toestand ten tijde van de uitspraak. Daarbij heeft als uitgangspunt te gelden dat het spoedeisend belang in beginsel is gegeven zolang de gestelde inbreuk of het gestelde onrechtmatig handelen voortduurt. Indien echter onvoldoende voortvarend tegen het gestelde onrechtmatig handelen is opgetreden, kan dit een aanwijzing zijn dat het belang van de eisende partij kennelijk geen voorlopige maatregel vergt. Een en ander hangt af van de omstandigheden van het geval.

5.3.

Eveoh c.s. voert aan dat Scientia geen spoedeisend belang heeft bij haar vordering, omdat Scientia in elk geval sinds de e-mail van de Universiteit Utrecht van 19 oktober 2017 aan Eveoh (zie r.o. 2.15) wist dat Eveoh niet alleen voor de Erasmus Universiteit gebruik maakte van een kopie/replica van de RDB op de server van Eveoh. Scientia bestrijdt dat zij dit wist. Zij wijst er in dit kader op dat in de e-mail van de Universiteit Utrecht staat:

“the MyTimetable RDB’s (…) are located in the MyTimetable datacenter”.

Volgens Scientia blijkt daaruit niet dat een integrale kopie van de RDB was gemaakt. Scientia heeft dit (in eerste aanleg) aldus toegelicht dat niet duidelijk is (i) dat het gaat om een replicatie van meer dan alleen de data in de RDB, namelijk ook van de hele database structuur, en (ii) dat het gaat om een off premise replicatie van die database structuur. Het hof volgt Scientia hierin niet. Ten aanzien van de omvang van de kopie is de tekst duidelijk; deze verwijst uitdrukkelijk naar de RDB’s zelf en niet slechts naar de data/query’s in de RDB’s.

Ook ten aanzien van de locatie van de gekopieerde RDB’s is de tekst duidelijk: de volledige zin waarin de door Scientia geciteerde opmerking is opgenomen luidt (onderstreping hof):

“On the new test environment Scheduled Extract will have to be configured such that not only the local RDB’s are filled by Scheduled Extract, but also the MyTimetable RDb’s which are located in the MyTimetable datacenter.”

De tekst maakt aldus een duidelijk onderscheid tussen lokale RDB’s en de RDB’s die zich bevinden in het “MyTimetable datacenter”. Daaruit blijkt dat met de term “MyTimetable datacenter” niet wordt gewezen op de lokale server. Voor zover Scientia heeft bedoeld te betogen dat niet duidelijk is dat een kopie wordt gemaakt van de RDB, faalt ook dat betoog. Scientia heeft niet uitgelegd hoe de integrale RDB op de server van Eveoh zou kunnen worden geplaatst, zonder een kopie te maken.

Scientia heeft voorts geen feiten en omstandigheden aangevoerd die de conclusie rechtvaardigen dat zij de tekst, ondanks de duidelijke bewoordingen, anders mocht opvatten, namelijk als een verwijzing naar een kopie/replica van alleen data en/of een verwijzing naar een on premise locatie.

Dit alles leidt tot de conclusie dat de opmerking in de e-mail van 19 oktober 2017 niet anders kan worden begrepen dan dat Eveoh ten behoeve van de Universiteit Utrecht gebruik maakte van een kopie van de gehele RDB (structuur en data) op haar server.

Overigens was Scientia er al in 2013 van op de hoogte dat Eveoh gebruik wenste te maken van kopieën van de RDB’s op haar server (zie r.o. 2.10-2.12) en wist Scientia - gelet op het gebruik van een kopie van de RDB voor de Erasmus Universiteit - in elk geval sinds 2015 dat Eveoh daar ook toe in staat was. Ook in dit licht had Scientia moeten begrijpen dat met de hiervoor geciteerde opmerking werd bedoeld dat de RDB’s integraal waren gekopieerd naar de server van Eveoh.

5.4.

Scientia voert nog aan dat de e-mail van 19 oktober 2017 is gericht aan [ consultant Scientia] en dat zijn wetenschap niet aan Scientia kan worden toegerekend. Het hof volgt Scientia ook daarin niet. Scientia heeft niet bestreden dat het in haar contact met Eveoh gebruikelijk is dat (senior) technical consultants namens Scientia aanspreekpunt zijn. Eveoh mocht er daarom op vertrouwen dat [ consultant Scientia] geïnformeerd was en dat hij Scientia ook informeerde. Dat [ consultant Scientia] geen jurist is maar een programmeur, doet daar, anders dan Scientia betoogt, niet aan af. Van een programmeur mag worden verwacht dat hij er mee bekend is dat het niet is toegestaan om kopieën te maken van auteursrechtelijk beschermd werk van anderen. Die kennis is immers onmisbaar bij een zorgvuldige uitoefening van zijn kerntaak - programmeren. Dat de opmerking over de kopie voor de Universiteit Utrecht maar in één mail staat, betekent evenmin dat de kennis van [ consultant Scientia] niet aan Scientia kan worden toegerekend. Het betreft een duidelijke opmerking, die staat in een e-mail die betrekking heeft op de koppeling tussen Syllabus Plus en MyTimetable (en dus niet, zoals Scientia stelt, in een e-mail over een ander onderwerp). Ten slotte is de e-mail in cc ook naar een andere medewerker van Scientia gestuurd, zodat deze niet alleen bekend was bij [ consultant Scientia] .

5.5.

De stelling van Scientia dat [ consultant Scientia] niet bevoegd was om toestemming te verlenen voor het kopiëren van auteursrechtelijk beschermd werk, kan Scientia ook niet baten. Het gaat er in dezen niet om of [ consultant Scientia] zijn goedkeuring heeft gegeven aan het maken van de kopie en of hij daartoe bevoegd was. Waar het om gaat is of hij wist dat een kopie van de RDB op de server van Eveoh was geplaatst en of die wetenschap aan Scientia kan worden toegerekend. Dat is blijkens het in r.o. 5.2. tot en met 5.4. overwogene het geval.

5.6.

Pas 2,5 jaar na de ontvangst van de e-mail van de Universiteit Utrecht, heeft Scientia Eveoh c.s. gesommeerd het kopiëren van de RDB naar haar eigen server te staken en heeft zij Eveoh c.s. gedagvaard. Aldus heeft Scientia onvoldoende voortvarend gehandeld en kan niet meer worden aangenomen dat Scientia nog spoedeisend belang heeft bij de onderhavige vorderingen.

5.7.

Ook een belangenafweging leidt niet tot de conclusie dat Scientia de uitkomst van een bodemprocedure niet meer zou kunnen afwachten. Het is evident dat Scientia er belang bij heeft dat Eveoh geen product op de markt brengt dat concurreert met haar product Scientia Publish, terwijl Eveoh daarbij - naar de stelling van Scientia - gebruik maakt van een inbreukmakende kopie van de RDB. Daar tegenover staat het eveneens evidente belang van Eveoh c.s. om haar - in haar optiek niet inbreuk makende product - te kunnen blijven exploiteren. Eveoh c.s. heeft onbetwist gesteld dat het voor haar voortbestaan van levensbelang is dat zij die exploitatie op de huidige wijze kan voortzetten. Bij een afweging van deze belangen van partijen, neemt het hof de volgende omstandigheden in aanmerking:

- Eveoh maakt in elk geval sinds 2017 met wetenschap van Scientia gebruik van een kopie van de RDB op haar server, zonder dat Scientia daartegen heeft opgetreden (zie het voorgaande).

- Eveoh c.s. heeft onbestreden gesteld dat de RDB mede is bedoeld voor gebruik met programmatuur van derden.

- Een verbod op het kopiëren van de RDB op de server van Eveoh betekent dat op korte termijn geen dienstverlening met MyTimetable mogelijk is in de SaaS-versie, zodat de onderwijsinstellingen die gebruik maken van de SaaS-versie van MyTimetable de roosters (in elk geval tijdelijk) niet op een werkbare wijze kenbaar kunnen maken aan hun medewerkers en studenten. Scientia heeft als oplossing genoemd dat de roosters via HTML bestanden kunnen worden verschaft. Het hof acht gelet op de aard van HTML bestanden aannemelijk dat dit geen werkbaar alternatief biedt voor de onderwijsinstellingen. De onderwijsinstellingen die de SaaS-versie van MyTimetable gebruiken hebben er dus een groot belang bij dat gebruik - in afwachting van de uitkomst van een bodemprocedure - voort te zetten op de huidige voet.

- Eveoh gebruikt een kopie van een RDB alleen ten behoeve van de onderwijsinstelling ten behoeve waarvan die RDB is gemaakt.

- Scientia heeft niet duidelijk gemaakt wat de schade is die zij in afwachting van de uitkomst van een bodemprocedure lijdt, in aanmerking genomen dat zij wel accepteert dat Eveoh met MyTimetable gebruik maakt van een RDB die “on premise” op de server van de universiteit staat, dat (naar als onbetwist vast staat) de RDB door onderwijsinstellingen wordt gekopieerd naar de ‘cloud’, derhalve naar een server van een derde (waar deze ook kan worden gebruikt voor MyTimetable), en dat Eveoh voor de Erasmus Universiteit gebruik maakt van een kopie van de RDB op de server van Eveoh. Gelet op deze omstandigheden, in onderlinge samenhang bezien, weegt het belang van Eveoh c.s. bij handhaving van de status quo in afwachting van de uitkomst van een bodemprocedure zwaarder dan het belang van Scientia bij de door haar gevorderde  voorlopige voorziening.

5.8.

Het voorgaande leidt tot de conclusie dat Scientia geen spoedeisend belang heeft bij haar vorderingen. De grieven van Scientia falen in zoverre.

5.9.

Ten overvloede overweegt het hof dat ook een inhoudelijke toetsing van het geschil in dit kort geding niet tot toewijzing van de vorderingen zou hebben geleid. Daartoe is het volgende redengevend.

5.9.1.

In de eerste plaats is voorshands onvoldoende aannemelijk dat de structuur van de RDB een auteursrechtelijk beschermd werk is in de zin van artikel 2, onder a, van de Auteursrechtrichtlijn en artikel 10 Auteurswet. Om voor auteursrechtelijke bescherming in aanmerking te komen, is vereist dat een werk een eigen, oorspronkelijk karakter heeft en het persoonlijk stempel van de maker draagt. Het werk moet een eigen intellectuele schepping van de maker zijn die de persoonlijkheid van de maker weerspiegelt, en tot uiting komt door de vrije creatieve keuzes van de maker bij de totstandkoming van het werk. Elementen van het werk die louter een technisch effect dienen of te zeer het resultaat zijn van een door technische uitgangspunten beperkte keuze, zijn van bescherming uitgesloten.

Scientia betoogt dat reeds uit het feit dat de in de RDB opgenomen tabellen en views van versie tot versie verschillen en uit het feit dat Scientia in “bepaalde jurisdicties” werkt met andere RDB structuren, blijkt dat zij bij het maken van de RDB’s creatieve keuzes heeft gemaakt. Dit betoog faalt. Het enkele feit dat er verschillen zijn betekent niet dat auteursrechtelijk relevante creatieve keuzes zijn gemaakt. Ook van versie tot versie en van jurisdictie tot jurisdictie kunnen keuzes zijn gemaakt die louter een technisch effect dienen of het resultaat zijn van een door technische uitgangspunten beperkte keuze.

Ook uit de door Scientia overgelegde rapporten van [naam 1] en [naam 4] (zie r.o. 2.17 en 2.19) blijkt onvoldoende dat de door Scientia gemaakte keuzes creatief zijn. Het is voor het hof voorshands onvoldoende duidelijk of de in die rapporten beschreven keuzes vrije keuzes zijn geweest of keuzes die zijn ingegeven door het beoogde technisch effect. In dit verband is van belang dat Eveoh c.s. de rapporten van [naam 1] en [naam 4] gemotiveerd heeft bestreden door overlegging van de rapporten van [naam 2] en [naam 3] (zie r.o. 2.18 en 2.20). Scientia voert tegen de rapporten van [naam 2] en [naam 3] een aantal bezwaren aan, maar het hof volgt deze bezwaren niet:

- Scientia voert aan dat [naam 2] en [naam 3] ten onrechte alleen hebben gekeken of de ‘views’ creatief zijn. Zij gaat er echter aan voorbij dat [naam 2] en [naam 3] in hun tweede rapport ook zijn ingegaan op de vraag of bij het maken van de structuur van de RDB auteursrechtelijk relevante creatieve keuzes zijn gemaakt. [naam 2] en [naam 3] concluderen dat dat niet het geval is.

- Volgens Scientia zijn [naam 2] en [naam 3] er ten onrechte van uitgegaan dat een oplossing pas creatief is als er sprake is van een (in hun ogen) goede technische oplossing. Dat is echter onjuist. [naam 2] en [naam 3] bespreken in hoeverre Scientia keuzemogelijkheden had en of de keuzes technisch bepaald zijn. Dat zij sommige keuzes een “hack”, “lelijk”, “kort-door-de-bocht” of “quick and dirty” noemen, doet daar niet aan af. Scientia stelt verder ten onrechte dat de creativiteit reeds blijkt uit de vaststelling van [naam 2] en [naam 3] dat de oplossing van Scientia “ongebruikelijk” is. Die vaststelling laat immers onverlet dat de door Scientia gemaakte keuzes volgens [naam 2] en [naam 3] banaal en functioneel bepaald zijn.

- Scientia stelt dat [naam 2] en [naam 3] zijn uitgegaan van het onjuiste uitgangspunt dat de RDB een één-op-één kopie is van de SDB. De constatering van [naam 2] en [naam 3] dat sprake is van een “één-op-één dubbelen”, is echter beperkt tot bepaalde views. [naam 2] en [naam 3] verwijzen op dit punt bovendien naar de handleiding van Scientia zelf, waarin Scientia ten aanzien van de betreffende views zelf stelt dat sprake is van: “merely an identical copy of an underlying table”. Dit duidt er niet op dat [naam 2] en [naam 3] een onjuist uitgangspunt hebben gehanteerd.

- Ook de stelling van Scientia dat [naam 2] en [naam 3] onvoldoende deskundig en onafhankelijk zijn faalt. Het rapport van [naam 2] en [naam 3] van 10 juni 2020 bevat op bladzijde 7 een beschrijving van hun kwalificaties. Deze beschrijving geeft geen aanleiding om aan de deskundigheid van [naam 2] en [naam 3] te twijfelen. Het feit dat de LinkedIn profielen van [naam 2] en [naam 3] niet volledig overeenstemmen met de in het rapport weergegeven werkervaring, maakt dat niet anders. De beantwoording van de vragen en de door [naam 2] en [naam 3] gebruikte bewoordingen geven, anders dan Scientia stelt, ook geen aanleiding voor het oordeel dat [naam 2] en [naam 3] onvoldoende onafhankelijkheid zouden hebben betracht.

Er is op grond van het voorgaande geen reden om de rapporten van [naam 2] en [naam 3] terzijde te stellen. Gelet op de verschillende rapporten van partijen acht het hof het voorshands onvoldoende aannemelijk dat de (structuur van de) RDB een auteursrechtelijk beschermd werk is. Voor nadere bewijslevering door Scientia leent dit kort geding zich niet.

5.9.2.

In de tweede plaats staat vast dat de RDB onder meer is bedoeld voor gebruik met programmatuur van derden. Verder staat vast dat Scientia al vanaf 2013 wist dat Eveoh de mogelijkheid onderzocht om een kopie van de RDB op haar server te plaatsen en dat Scientia daarover aan Eveoh heeft medegedeeld geen reden te zien waarom dit niet succesvol zou kunnen zijn (zie r.o. 2.10). Daarnaast is gesteld noch gebleken dat Scientia, toen haar duidelijk werd dat ten behoeve van de Erasmus Universiteit daadwerkelijk een kopie werd gemaakt op de server van Eveoh, aan Eveoh heeft medegedeeld dat dit slechts bij wijze van uitzondering werd toegestaan. Ook heeft Scientia, nadat Scientia ermee bekend werd dat ten behoeve van de Universiteit Utrecht een kopie van de RDB op de server van Scientia werd geplaatst, daar gedurende 2,5 jaar geen bezwaar tegen gemaakt. Ten slotte staat als onbetwist vast dat Scientia accepteert dat de RDB door of ten behoeve van onderwijsinstellingen wordt gekopieerd naar de ‘cloud’, derhalve eveneens naar een server van een derde. Gelet op dit alles is voorshands aannemelijk dat de bodemrechter tot het oordeel zal komen dat Scientia (impliciet) toestemming heeft gegeven aan Eveoh om een kopie van de RDB op haar server te (doen) plaatsen. Dat de licentieovereenkomsten die Scientia met onderwijsinstellingen sluit sub-licentiering en gebruik van de software anders dan op aangewezen computersystemen verbieden, leidt niet tot een ander oordeel. Het gaat hier immers niet om door de onderwijsinstellingen gegeven goedkeuring, maar om door Scientia zelf (impliciet) gegeven toestemming.

In principaal en incidenteel hoger beroep

Proceskosten

5.10.

Scientia is terecht veroordeeld tot vergoeding van de in eerste aanleg gemaakte proceskosten. De door Eveoh c.s. gemaakte proceskosten zijn als schade aan te merken. Scientia kan zich niet aan aansprakelijkheid voor deze schade onttrekken door er op te wijzen dat Eveoh c.s. ook bij haar verzekeraar terecht kan. Dat Eveoh c.s. voor deze schade verzekerd is, ontslaat Scientia dus niet van haar vergoedingsplicht.

5.11.

Ten aanzien van de begroting van de in eerste aanleg gemaakte proceskosten geldt het volgende. Een gedaagde in een kort geding procedure brengt zijn of haar standpunt doorgaans alleen tijdens de mondelinge behandeling naar voren. In het onderhavige geval heeft Eveoh c.s. haar standpunt in twee schriftelijke stukken naar voren gebracht, waarna er een digitale mondelinge behandeling heeft plaatsgevonden. Doordat Scientia de grondslag van haar vordering in haar conclusie van repliek gedeeltelijk wijzigde, kon Eveoh c.s. in haar conclusie van dupliek bovendien niet volstaan met een nadere toelichting op haar eerder ingenomen standpunt. Zij moest ingaan op het gewijzigde standpunt en heeft, niet ten onrechte, de door haar ingeschakelde deskundigen om een nadere reactie gevraagd. Daarbij komt dat Eveoh c.s. uitgebreid feitenonderzoek heeft gedaan. Ook dit deed zij - alleen al blijkens het feit dat dit ertoe leidde dat Scientia haar standpunt ten aanzien van de Erasmus Universiteit wijzigde - niet ten onrechte. Ten slotte was in eerste aanleg niet alleen de kwestie met betrekking tot het kopiëren van de RDB aan de orde, maar ook de kwestie met betrekking tot Exam Scheduler/de ESDB. Dat droeg bij aan de complexiteit van de zaak. Al met al is het hof van oordeel dat voor de begroting van de advocaatkosten in eerste aanleg aansluiting dient te worden gezocht bij de Indicatietarieven voor een complex kort geding. Het daarin opgenomen tarief van € 25.000,00 wordt geacht redelijk en evenredig te zijn, zodat het hof geen aanleiding ziet om Scientia in de werkelijk gemaakte proceskosten van Eveoh c.s. te veroordelen. Het hof ziet ook geen aanleiding om, zoals Eveoh c.s. heeft verzocht, aansluiting te zoeken bij het Indicatietarief voor een complexe bodemzaak. Daarvoor verschilt het karakter van het kort geding te zeer van dat van een bodemzaak. Zo is er in een kort geding procedure geen ruimte voor nadere bewijslevering.

5.12.

De voorzieningenrechter heeft Scientia op de voet van artikel 1019h Rv eveneens veroordeeld tot vergoeding van de door Eveoh c.s. gemaakte kosten voor de deskundigen [naam 2] / [naam 3] en [naam 5] (die een opinie heeft gegeven over Engels recht). Scientia grieft tegen de veroordeling in de kosten die Eveoh c.s. heeft gemaakt voor [naam 2] en [naam 3] . Zij voert hiertoe twee gronden aan. Allereerst zouden [naam 2] en [naam 3] onvoldoende deskundig zijn. Deze stelling faalt, gelet op het in r.o. 5.9.1. overwogene. Daarnaast zouden [naam 2] en [naam 3] zich, kort gezegd, uitgebreid hebben uitgelaten over irrelevante zaken. Ook deze stelling faalt. De inhoud van de rapporten rechtvaardigt die conclusie niet. De voor de deskundigen gemaakte kosten van € 13.534,99 dienen daarom eveneens bij de kostenveroordeling te worden betrokken.

5.13.

Het voorgaande betekent dat de tegen de proceskostenveroordeling gerichte grieven in het principaal hoger beroep falen en dat het incidenteel hoger beroep slaagt. Het hof zal het vonnis in zoverre vernietigen en, opnieuw rechtdoende, Scientia veroordelen in de kosten van de procedure in eerste aanleg, te begroten aan de hand van het indicatietarief voor een complexe zaak in kort geding, en in de kosten van de deskundigen.

5.14.

Eveoh c.s. heeft in incidenteel hoger beroep ook vergoeding van de nakosten gevorderd. Het hof begrijpt daaruit dat zij grieft tegen de afwijzing door de voorzieningenrechter van de verzochte vergoeding van nakosten. De voorzieningenrechter heeft de nakosten niet in de kostenveroordeling betrokken, overwegende dat de kostenveroordeling op zich een executoriale titel oplevert, dat Eveoh c.s. de nakosten niet had begroot, en dat de voorzieningenrechter over onvoldoende gegevens beschikte om over de hoogte van die kosten te beslissen. Eveoh c.s. heeft nagelaten te motiveren waarom dit oordeel geen stand kan houden. Het hof verwerpt de tegen de afwijzing van de nakosten gerichte grief daarom.

De proceskosten in principaal en incidenteel hoger beroep

5.15.

Scientia zal, als de in het principaal en incidenteel hoger beroep in het ongelijk gestelde partij, worden veroordeeld in de proceskosten van Eveoh c.s. Ook ten aanzien van de procedure in hoger beroep heeft Eveoh c.s. vergoeding van de werkelijk door haar gemaakte proceskosten gevorderd, ex artikel 1019h Rv. Met inachtneming van het feit dat Scientia het geschil in hoger beroep heeft beperkt tot de kwestie rond het kopiëren van de RDB, zoekt het hof voor de begroting van de kosten in principaal hoger beroep aansluiting bij de Indicatietarieven voor een normaal kort geding. De gevorderde nakosten zullen als onbestreden worden toegewezen. De kosten van Eveoh c.s. in het incidenteel hoger beroep begroot het hof op nihil.

6
Beslissing

Het hof:

- vernietigt het door de voorzieningenrechter in de rechtbank Den Haag tussen partijen gewezen vonnis van 16 september 2020, voor zover Scientia in dat vonnis is veroordeeld in de proceskosten van Eveoh, begroot op € 29.190,99,

en in zoverre opnieuw rechtdoende:

- veroordeelt Scientia in de proceskosten, aan de zijde van Eveoh c.s. begroot op € 656,00 aan verschotten, € 25.000,00 aan salaris van de advocaat en € 13.534,99 aan kosten voor de deskundigen;

- bekrachtigt het vonnis voor het overige;

en:

- veroordeelt Scientia in de kosten van het geding in principaal en incidenteel hoger beroep, tot op heden aan de zijde van Eveoh ten aanzien van het principaal hoger beroep begroot op € 760,00 aan verschotten, € 25.000,00 aan salaris voor de advocaat en op € 163,00 aan nasalaris voor de advocaat, nog te verhogen met € 85,00 indien niet binnen veertien dagen na aanschrijving in der minne aan dit arrest is voldaan en vervolgens betekening van dit arrest heeft plaatsgevonden, en ten aanzien van het incidenteel hoger beroep begroot op nihil.

- verklaart deze proceskostenveroordeling uitvoerbaar bij voorraad,

- wijst af het meer of anders gevorderde.

Dit arrest is gewezen door mrs. J.I. de Vreese-Rood, R. Kalden en R.S. Le Poole en ondertekend en in het openbaar uitgesproken door mr. J.E.H.M. Pinckaers, rolraadsheer, op 15 juni 2021 in aanwezigheid van de griffier.

Richtlijn 2001/29/EG van het Europees Parlement en de Raad van 22 mei 2001 betreffende de harmonisatie van bepaalde aspecten van het auteursrecht en de naburige rechten in de informatiemaatschappij.

Vgl. HvJ EU 16 juli 2009, ECLI:EU:2009: nr. C-5/08, LJN BJ3749 (Infopaq I) en HvJ EU 1 december 2011, ECLI:EU:C:2011:798 (Painer).

Vgl. HvJ EU 22 december 2010, ECLU:EU:2010: BP0405 (BSA) en HR 16 juni 2006, ECLI:NL:HR:2006:AU8940 (Kecofa/Lancôme).
