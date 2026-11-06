# Winterthur (city): law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Winterthur, Zurich, Switzerland, which global-law reads at `switzerland/zurich/winterthur/acts/`.

The municipal law of the city of Winterthur (Stadt Winterthur, canton of Zurich, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Zurich is in [lexifina/switzerland-zurich-law](https://github.com/lexifina/switzerland-zurich-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the city publishes it.

## What this repository holds

151 acts with 318 versions so far: the Gemeindeordnung (the city's charter) first, then the city's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1-go/` | Gemeindeordnung (SRS 1.1-1) | 4 | oldest version available, then each consolidated version: 14 May 2018 to 1 May 2026 |
| `1-1-3/` | Verordnung über die zeitliche Beanspruchung und Entschädigung der Mitglieder der Schulpflege (SRS 1.1-3) | 1 | as enacted, 1 January 2022 |
| `1-1-5/` | Reglement über die Entschädigung an Behördenmitglieder (SRS 1.1-5) | 8 | oldest version available, then each consolidated version: 14 May 2018 to 1 January 2026 |
| `1-1-5-1/` | Besondere Entschädigungen an Mitglieder städtischer Kommissionen und Institutionen (SRS 1.1-5.1) | 1 | as enacted, 29 March 1989 |
| `1-2-1-ov-parl/` | Organisationsverordnung Stadtparlament (SRS 1.2-1) | 6 | oldest version available, then each consolidated version: 14 May 2018 to 16 May 2022 |
| `1-3-1-gescho-sr/` | Geschäftsordnung des Stadtrats (SRS 1.3-1) | 2 | oldest version available, then each consolidated version: 1 April 1991 to 1 March 2022 |
| `1-3-5/` | Beschluss des Grossen Gemeinderates betr. Löhne und Spesenentschädigungen der Mitglieder des Stadtrates (SRS 1.3-5) | 1 | as enacted, 1 July 2002 |
| `1-4-1-1-organisationsverordnung-stadtverwaltung-ovs/` | Verordnung über die Organisation und die Aufgaben der Stadtverwaltung (SRS 1.4.1-1) | 4 | oldest version available, then each consolidated version: 25 October 2016 to 1 June 2026 |
| `1-4-1-2/` | Auskunftserteilung von Beamten an die Mitglieder des Grossen Gemeinderates (SRS 1.4.1-2) | 1 | as enacted, 16 April 1986 |
| `1-4-1-3/` | Verordnung betreffend Sprachdienstleistungen (SRS 1.4.1-3) | 2 | as enacted, then each consolidated version: 1 August 2020 to 1 November 2024 |
| `1-4-1-8/` | Reglement des Migrationsbeirats (SRS 1.4.1-8) | 2 | as enacted, then each consolidated version: 1 July 2014 to 1 December 2018 |
| `1-4-1-9/` | Reglement der Mitwirkungsgruppe von Menschen mit Behinderungen WINklusion (SRS 1.4.1-9) | 1 | as enacted, 1 November 2025 |
| `1-4-5-1-pst/` | Personalstatut (SRS 1.4.5-1) | 7 | oldest version available, then each consolidated version: 1 January 2019 to 1 January 2026 |
| `1-4-5-1-1-vvo-pst/` | Vollzugsverordnung zum Personalstatut (SRS 1.4.5-1.1) | 8 | as enacted, then each consolidated version: 1 January 2019 to 1 January 2026 |
| `1-4-5-3/` | Verordnung über die Nutzung von E-Mail und Internet sowie die elektronische Ablage privater Dokumente (SRS 1.4.5-3) | 1 | as enacted, 1 April 2012 |
| `1-4-5-4/` | Parkplatz-Reglement für das Personal der Stadt Winterthur (SRS 1.4.5-4) | 1 | as enacted, 1 February 2014 |
| `1-4-5-5/` | Kantonale Schlichtungsstelle für Streitigkeiten über Diskriminierungen im Erwerbsleben (SRS 1.4.5-5) | 1 | as enacted, 26 May 1997 |
| `1-4-5-8/` | Besoldungsordnung für die städtischen Lehrpersonen (SRS 1.4.5-8) | 2 | as enacted, then each consolidated version: 1 August 2013 to 29 August 2022 |
| `1-4-5-8-1-vvo-lehrpersonal/` | Vollzugsverordnung für das Lehrpersonal und weitere schulische Funktionen (SRS 1.4.5-8.1) | 11 | oldest version available, then each consolidated version: 1 August 2018 to 1 August 2025 |
| `1-4-5-8-2-spesenreglement/` | Reglement über den Ersatz Dienstlicher Auslagen von Lehrpersonen und Schulleitungen (SRS 1.4.5-8.2) | 2 | as enacted, then each consolidated version: 1 August 2020 to 1 August 2022 |
| `1-4-5-9-pvo-aufsichtsstellen/` | Personalverordnung für die städtischen Aufsichtsstellen (SRS 1.4.5-9) | 1 | as enacted, 1 November 2025 |
| `1-4-8-1/` | Verordnung über die Pensionskasse der Stadt Winterthur (SRS 1.4.8-1) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `1-4-8-1-1/` | Stiftungsurkunde der Pensionskasse der Stadt Winterthur (SRS 1.4.8-1.1) | 1 | as enacted, 1 January 2014 |
| `1-4-8-1-2/` | Statuten der Pensionskasse der Stadt Winterthur (SRS 1.4.8-1.2) | 1 | current PDF text as one file, 25 February 2013 |
| `1-4-8-5/` | Verordnung über die Pensionsversicherung der Mitglieder des Stadtrates (SRS 1.4.8-5) | 1 | as enacted, 1 January 2006 |
| `1-5-1/` | Verordnung über die städtische Ombudsstelle (SRS 1.5-1) | 4 | oldest version available, then each consolidated version: 1 November 2010 to 1 November 2025 |
| `1-6-1-vo-burgerrecht-winterthur/` | Verordnung über das Bürgerrecht der Stadt Winterthur (SRS 1.6-1) | 2 | oldest version available, then each consolidated version: 14 May 2018 to 1 September 2025 |
| `1-6-1-1-vvo-burgerrecht/` | Vollzugsverordnung zur Verordnung über das Bürgerrecht der Stadt Winterthur (SRS 1.6-1.1) | 3 | oldest version available, then each consolidated version: 1 September 2013 to 1 September 2025 |
| `1-7-1/` | Verordnung über die Wahlen und Abstimmungen (SRS 1.7-1) | 3 | as enacted, then each consolidated version: 1 March 1974 to 1 May 2026 |
| `1-7-1-1/` | Vollzugsverordnung über die Wahlen und Abstimmungen (SRS 1.7-1.1) | 2 | as enacted, then each consolidated version: 1 May 2024 to 1 May 2026 |
| `1-8-1/` | Verordnung über das Bestattungs- und Friedhofwesen (SRS 1.8-1) | 2 | as enacted, then each consolidated version: 11 June 1979 to 1 July 2021 |
| `1-8-1-1/` | Stadträtliche Ausführungsvorschriften zur Verordnung über das Bestattungs- und Friedhofwesen (SRS 1.8-1.1) | 1 | one version (the oldest available), 1 January 1989 |
| `1-8-3-grabmalverordnung/` | Ausführungsrichtlinien über das Aufstellen von Grabmalen auf den Friedhöfen von Winterthur (SRS 1.8-3) | 1 | one version (the oldest available), 15 December 1997 |
| `2-1-1/` | Vorschriften über Gebühren, Auslagen und Entschädigungen des Stadtrichteramts als Übertretungsstrafbehörde (SRS 2.1-1) | 1 | as enacted, 1 January 2018 |
| `3-1-1/` | Verordnung über die/den Datenschutzbeauftragte/n der Stadt Winterthur (SRS 3.1-1) | 3 | as enacted, then each consolidated version: 30 August 2010 to 1 November 2025 |
| `3-1-2/` | Verordnung über die Bearbeitung besonderer Personendaten (SRS 3.1-2) | 1 | as enacted, 16 September 2013 |
| `3-2-1-informationsverordnung-infv/` | Verordnung betreffend die Information der Öffentlichkeit über städtische Belange (SRS 3.2-1) | 3 | as enacted, then each consolidated version: 1 July 2021 to 1 April 2025 |
| `3-2-1-1-vvo-infv/` | Vollzugsverordnung zur Informationsverordnung (SRS 3.2-1.1) | 2 | as enacted, then each consolidated version: 1 July 2021 to 1 April 2025 |
| `4-1-1/` | Verordnung über die Volksschule in der Stadt Winterthur (SRS 4.1-1) | 2 | as enacted, then each consolidated version: 1 August 2010 to 29 August 2022 |
| `4-1-1-1-ost/` | Organisationsstatut für die Volksschule in Winterthur (SRS 4.1-1.1) | 6 | oldest version available, then each consolidated version: 1 August 2018 to 18 August 2025 |
| `4-1-1-2/` | Finanzstatut für die Volksschule der Stadt Winterthur (SRS 4.1-1.2) | 5 | oldest version available, then each consolidated version: 1 January 2018 to 19 August 2024 |
| `4-1-1-5/` | Reglement über die Übernahme von Kosten von Kunst- und Sportschulen durch die Stadt Winterthur (SRS 4.1-1.5) | 2 | as enacted, then each consolidated version: 19 August 2019 to 1 February 2025 |
| `4-1-4-2/` | Reglement über die Mitarbeiter/innenbeurteilung der Lehrpersonen in Winterthur (SRS 4.1-4.2) | 1 | one version (the oldest available), 9 December 2014 |
| `4-1-5/` | Reglement über die Schuldienste in der Stadt Winterthur (SRS 4.1-5) | 1 | one version (the oldest available), 1 August 2017 |
| `4-1-7/` | Sonderpädagogikstatut der Stadt Winterthur (SRS 4.1-7) | 5 | oldest version available, then each consolidated version: 1 August 2014 to 18 August 2025 |
| `4-1-8-gescho-wsp/` | Geschäftsordnung der Schulpflege (SRS 4.1-8) | 1 | as enacted, 17 August 2026 |
| `4-2-1-1/` | Reglement über die Mechatronik Schule Winterthur (SRS 4.2.1-1) | 3 | as enacted, then each consolidated version: 1 August 2016 to 22 August 2022 |
| `4-2-1-3/` | Reglement über die Schule für Berufsvorbereitung Winterthur (SRS 4.2.1-3) | 2 | as enacted, then each consolidated version: 1 August 2014 to 22 August 2022 |
| `4-2-1-3-1-beitragsreglement-profil/` | Reglement über die Ausrichtung von Beiträgen an Angebote für fremdsprachige Schülerinnen und Schüler der Schule Profil. Berufsvorbereitung Winterthur (SRS 4.2.1-3.1) | 1 | as enacted, 1 May 2017 |
| `4-2-2-3/` | Verordnung über die Sonderschulen der Stadt Winterthur (SRS 4.2.2-3) | 1 | as enacted, 22 August 2022 |
| `4-2-2-3-1/` | Reglement über die Sonderschulen der Stadt Winterthur (SRS 4.2.2-3.1) | 1 | as enacted, 22 August 2022 |
| `4-3-1/` | Verordnung über die Schulzahnpflege der Stadt Winterthur (SRS 4.3-1) | 2 | as enacted, then each consolidated version: 1 August 2014 to 29 August 2022 |
| `4-3-1-1/` | Beitragsreglement für die Schulzahnpflege (SRS 4.3-1.1) | 1 | as enacted, 1 August 2014 |
| `4-4-1/` | Verordnung über Berufsbildungs- und Weiterbildungsangebote der Stadt Winterthur (SRS 4.4-1) | 2 | oldest version available, then each consolidated version: 1 March 2018 to 22 August 2022 |
| `4-5-1-kita-verordnung/` | Verordnung über die Kinderbetreuung im Vorschulbereich sowie in Tagesfamilien der Stadt Winterthur (SRS 4.5-1) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 January 2020 |
| `4-5-1-1-kita-reglement/` | Reglement über die Kinderbetreuung im Vorschulbereich sowie in Tagesfamilien der Stadt Winterthur (SRS 4.5-1.1) | 4 | oldest version available, then each consolidated version: 1 July 2016 to 1 January 2026 |
| `4-5-2/` | Verordnung über die Kinderbetreuung im schulischen Bereich (SRS 4.5-2) | 1 | one version (the oldest available), 1 January 2015 |
| `4-5-2-1-beirschu/` | Beitrags- und Betriebsreglement über die Kinderbetreuung im schulischen Bereich (SRS 4.5-2.1) | 2 | oldest version available, then each consolidated version: 1 August 2016 to 1 February 2025 |
| `4-6-1-benutzungsverordnung/` | Verordnung über die Benützung von Schul- und Sportanlagen der Stadt Winterthur durch Dritte (SRS 4.6-1) | 2 | as enacted, then each consolidated version: 1 August 2008 to 29 August 2022 |
| `4-6-1-1/` | Betriebsreglement für die Schul- und Sportanlagen der Stadt Winterthur (SRS 4.6-1.1) | 2 | oldest version available, then each consolidated version: 1 February 2015 to 1 February 2026 |
| `4-6-1-2/` | Gebührenreglement für die Schul- und Sportanlagen der Stadt Winterthur (SRS 4.6-1.2) | 2 | oldest version available, then each consolidated version: 1 February 2015 to 1 March 2019 |
| `4-7-1/` | Verordnung über das öffentliche Bibliothekswesen (SRS 4.7-1) | 1 | as enacted, 1 July 1996 |
| `4-7-1-1/` | Reglement für die öffentlichen Bibliotheken der Stadt Winterthur (SRS 4.7-1.1) | 2 | as enacted, then each consolidated version: 1 February 2014 to 12 May 2022 |
| `4-7-2/` | Reglement des Stadtarchivs Winterthur (SRS 4.7-2) | 1 | as enacted, 2 October 1981 |
| `4-7-2-1/` | Gebührenordnung Stadtarchiv (SRS 4.7-2.1) | 1 | as enacted, 1 August 2005 |
| `4-8-1/` | Theaterverordnung (SRS 4.8-1) | 1 | as enacted, 1 August 2019 |
| `4-8-2/` | Verordnung über die Kulturförderung (SRS 4.8-2) | 1 | as enacted, 1 November 2023 |
| `5-1-1/` | Allgemeine Polizeiverordnung der Stadt Winterthur (SRS 5.1-1) | 1 | one version (the oldest available), 1 June 2014 |
| `5-1-1-1/` | Verordnung über das gemeinderechtliche Ordnungsbussenverfahren der Stadt Winterthur mit Anhang «Bussenliste» (SRS 5.1-1.1) | 2 | as enacted, then each consolidated version: 1 October 2010 to 1 January 2025 |
| `5-1-2/` | Gebührenordnung für die Stadtpolizei (SRS 5.1-2) | 1 | as enacted, 1 January 2015 |
| `5-1-5-polizeireglement/` | Organisations- und Dienstreglement der Stadtpolizei Winterthur (SRS 5.1-5) | 1 | as enacted, 1 January 2011 |
| `5-2-1-vosfo/` | Verordnung über die Städtische Krisenführungsorganisation Winterthur (SRS 5.2-1) | 2 | as enacted, then each consolidated version: 1 April 2018 to 1 June 2026 |
| `5-3-1/` | Reglement über die Organisation der Feuerwehr (SRS 5.3-1) | 1 | as enacted, 25 June 1982 |
| `5-3-2-drsiw/` | Dienstreglement Schutz & Intervention Winterthur (SRS 5.3-2) | 1 | as enacted, 1 July 2020 |
| `5-3-3/` | Gebührenordnung Schutz & Intervention Winterthur (SRS 5.3-3) | 1 | as enacted, 1 February 2021 |
| `5-4-1/` | Gebührenordnung für den Brandschutz (SRS 5.4-1) | 2 | oldest version available, then each consolidated version: 1 July 2017 to 1 February 2025 |
| `5-4-2/` | Gebührenordnung für die Feuerungskontrolle (SRS 5.4-2) | 2 | oldest version available, then each consolidated version: 1 October 2007 to 1 February 2025 |
| `6-1-1/` | Verordnung über den Finanzhaushalt der Stadt Winterthur (SRS 6.1-1) | 3 | oldest version available, then each consolidated version: 3 October 2016 to 1 January 2022 |
| `6-1-1-1-vvfh/` | Vollzugsverordnung über den Finanzhaushalt (SRS 6.1-1.1) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 May 2023 |
| `6-2-1/` | Geschäftsordnung des Steueramtes der Stadt Winterthur (SRS 6.2-1) | 2 | as enacted, then each consolidated version: 1 June 1998 to 1 March 2021 |
| `6-2-1-1/` | Gebührenverordnung für das Steueramt Winterthur (SRS 6.2-1.1) | 1 | as enacted, 1 May 2017 |
| `6-3-1/` | Verordnung über die Kanzlei- und Verwaltungsgebühren (SRS 6.3-1) | 4 | as enacted, then each consolidated version: 1 January 2018 to 1 May 2026 |
| `6-4-1-finanzkontrollverordnung/` | Verordnung über die Finanzkontrolle (SRS 6.4-1) | 3 | oldest version available, then each consolidated version: 1 July 2017 to 1 November 2025 |
| `6-5-1/` | Verordnung über die Vergabe von Darlehen zur Förderung des gemeinnützigen Wohn- und Gewerberaums in der Stadt Winterthur (SRS 6.5-1) | 1 | as enacted, 1 June 2018 |
| `6-5-2/` | Beschluss des Grossen Gemeinderates betreffend Förderung des Wohnungsbaus und des Wohneigentums in der Stadt Winterthur (SRS 6.5-2) | 1 | as enacted, 8 April 1991 |
| `6-5-3/` | Verordnung zur Förderung eines vielfältigen Wohn- und Gewerberaumangebots sowie räumlicher Durchmischung (SRS 6.5-3) | 1 | as enacted, 1 July 2025 |
| `7-1-3-1-bzo/` | Bau- und Zonenordnung (SRS 7.1.3-1) | 6 | oldest version available, then each consolidated version: 16 June 2017 to 15 October 2026 |
| `7-1-3-1-1-zusto-bau/` | Zuständigkeitsordnung für das Bauwesen (SRS 7.1.3-1.1) | 3 | as enacted, then each consolidated version: 1 July 2021 to 1 January 2024 |
| `7-1-3-1-2/` | Verordnung über den kommunalen Mehrwertausgleichsfonds (SRS 7.1.3-1.2) | 1 | as enacted, 15 June 2022 |
| `7-1-3-1-3/` | Ausführungsbestimmungen zum kommunalen Mehrwertausgleich (SRS 7.1.3-1.3) | 1 | as enacted, 1 March 2024 |
| `7-1-3-2/` | Verordnung über die Gebühren im Bauwesen (SRS 7.1.3-2) | 3 | oldest version available, then each consolidated version: 1 December 2014 to 1 July 2024 |
| `7-1-3-4-parkplatzverordnung-ppvo/` | Verordnung über Fahrzeugabstellplätze (SRS 7.1.3-4) | 2 | as enacted, then each consolidated version: 1 May 1987 to 1 September 2020 |
| `7-1-3-5/` | Gebührenordnung für den baulichen Zivilschutz (SRS 7.1.3-5) | 1 | as enacted, 1 July 2004 |
| `7-1-3-7/` | Richtlinien Gebäudebeschriftung Sulzerareal (Stadtmitte) (SRS 7.1.3-7) | 1 | as enacted, 15 July 2022 |
| `7-2-4-1/` | Schutzverordnung "Siedlung Neuwiesen" (SRS 7.2.4-1) | 1 | as enacted, 8 October 2022 |
| `7-2-4-3/` | Schutzverordnung betreffend den Fassadenschutz für die Wohnüberbauung St. Gallerstrasse / Mühlebrückestrasse (SRS 7.2.4-3) | 1 | as enacted, 23 April 2003 |
| `7-2-4-4/` | Schutzverordnung betreffend Siedlung "Bachtelstrasse", Bachtelstrasse 101-123 (ungerade Nummern) (SRS 7.2.4-4) | 1 | as enacted, 18 April 2011 |
| `7-3-1/` | Gebührenordnung für die allgemeine Baukontrolle (SRS 7.3-1) | 1 | as enacted, 1 July 2004 |
| `7-3-2/` | Gebührenordnung für die vorübergehende Benützung des öffentlichen Grundes für Bauinstallationen (SRS 7.3-2) | 1 | as enacted, 1 July 2004 |
| `7-3-3/` | Verordnung über die Verrechnung von Leistungen des Geomatik- und Vermessungsamtes (SRS 7.3-3) | 4 | as enacted, then each consolidated version: 1 December 2020 to 1 January 2026 |
| `7-4-3-vvo-ml/` | Vollzugsverordnung zum Massnahmenplan Luftreinhaltung der Stadt Winterthur (SRS 7.4-3) | 1 | as enacted, 1 May 2024 |
| `7-4-4/` | Geschäftsreglement der Naturschutz- und Freiraumkommission (SRS 7.4-4) | 1 | as enacted, 1 December 2016 |
| `7-4-5/` | Verordnung über die Umwandlung von Strassenflächen in Flächen für Bäume und in Grünflächen (SRS 7.4-5) | 1 | as enacted, 1 January 2025 |
| `7-4-6/` | Verordnung über die Umwandlung von Strassenflächen in Flächen für Fussverkehr, Veloverkehr und öffentlichen Verkehr (SRS 7.4-6) | 1 | as enacted, 1 January 2025 |
| `7-5-1/` | Verordnung über die Abfallentsorgung (SRS 7.5-1) | 1 | one version (the oldest available), 1 January 2017 |
| `7-5-2/` | Ausführungsbestimmungen zur Verordnung über die Abfallentsorgung in der Stadt Winterthur (SRS 7.5-2) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2021 |
| `7-6-2-vec/` | Verordnung über das Energie-Contracting (SRS 7.6-2) | 1 | as enacted, 1 October 2017 |
| `7-6-4/` | Reglement Förderprogramm Energie Winterthur (SRS 7.6-4) | 4 | as enacted, then each consolidated version: 1 July 2018 to 1 October 2023 |
| `7-6-4-1/` | Festsetzung Abgaben an das Gemeinwesen für das Förderprogramm Energie im Gebäudebereich und die öffentliche Beleuchtung ab 1. Januar 2017 (§ 32 Abs. 3 VAE) (SRS 7.6-4.1) | 1 | as enacted, 1 January 2017 |
| `7-6-4-2-vvae/` | Vollzugsverordnung zur Verordnung über die Abgabe von Elektrizität (SRS 7.6-4.2) | 3 | as enacted, then each consolidated version: 1 January 2023 to 1 January 2026 |
| `7-6-5-vae/` | Verordnung über die Abgabe von Elektrizität (SRS 7.6-5) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2027 |
| `7-6-5-1-tarifo-e/` | Tarifordnung über die Abgabe von Elektrizität (SRS 7.6-5.1) | 8 | as enacted, then each consolidated version: 1 January 2020 to 1 January 2027 |
| `7-6-6-vag/` | Verordnung über die Abgabe von Gas (SRS 7.6-6) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 December 2021 |
| `7-6-6-1-tarifo-g/` | Tarifordnung betreffend die Abgabe von Gas (SRS 7.6-6.1) | 5 | as enacted, then each consolidated version: 1 January 2019 to 1 January 2023 |
| `7-6-6-2-vvag/` | Vollzugsverordnung zur Verordnung über die Abgabe von Gas (SRS 7.6-6.2) | 1 | as enacted, 1 July 2023 |
| `7-6-7-fernwarmeverordnung/` | Verordnung über die Fernwärmeversorgung (SRS 7.6-7) | 1 | one version (the oldest available), 1 January 2017 |
| `7-6-7-1-tvfw/` | Tarif- und Vollzugsverordnung betreffend die Abgabe von Fernwärme (SRS 7.6-7.1) | 3 | as enacted, then each consolidated version: 1 April 1996 to 1 October 2025 |
| `7-6-8-telekomverordnung-tvo/` | Verordnung über die Erbringung von Telekommunikations-Leistungen (SRS 7.6-8) | 1 | one version (the oldest available), 1 February 2024 |
| `7-7-1-vaw/` | Verordnung über die Abgabe von Wasser (SRS 7.7-1) | 1 | as enacted, 1 January 2011 |
| `7-7-1-1-tarifo-w/` | Tarifordnung über die Abgabe von Wasser (SRS 7.7-1.1) | 4 | oldest version available, then each consolidated version: 1 July 2016 to 1 January 2024 |
| `7-7-3-vse/` | Verordnung über die Siedlungsentwässerung (SRS 7.7-3) | 2 | as enacted, then each consolidated version: 1 October 2001 to 1 January 2019 |
| `7-7-3-1/` | Ausführungsbestimmungen zur Verordnung über die Siedlungsentwässerung (SRS 7.7-3.1) | 2 | as enacted, then each consolidated version: 1 October 2001 to 1 October 2024 |
| `7-7-3-2/` | Tarifblatt Gebühren gemäss Verordnung und Ausführungsbestimmungen über die Siedlungsentwässerung (SRS 7.7-3.2) | 6 | as enacted, then each consolidated version: 1 January 2013 to 1 October 2024 |
| `7-8-1/` | Verordnung über die Strassenbenennung und die Adressierung von Gebäuden (SRS 7.8-1) | 3 | as enacted, then each consolidated version: 1 January 2016 to 1 May 2023 |
| `7-8-2-beitragsverordnung/` | Verordnung über die Grundeigentümerbeiträge, insbesondere an die Erstellungskosten öffentlicher Trottoirs und Kanalisationshauptleitungen (SRS 7.8-2) | 1 | as enacted, 1 October 1973 |
| `7-8-3/` | Richtlinien über die Grundeigentümerbeiträge an die Erstellungs- und Verbesserungskosten öffentlicher Strassen und Plätze (Fahrbahnbeiträge) (SRS 7.8-3) | 1 | as enacted, 1 October 1973 |
| `7-8-4-privatstrassenverordnung/` | Verordnung über die privaten Zugänge (SRS 7.8-4) | 1 | as enacted, 1 March 2009 |
| `7-8-5/` | Zuständigkeitsordnung der Stadt Winterthur betreffend Kantonale Signalisationsverordnung (KSigV) vom 21. November 2001 (SRS 7.8-5) | 4 | as enacted, then each consolidated version: 4 November 1981 to 1 May 2023 |
| `7-8-6/` | Beschluss über die Festlegung der Höchstwerte für die zulässigen Wohneinheiten zur Bestimmung der jeweiligen Zufahrtsart für dicht besiedelte Siedlungsteile, die mit öffentlichen Verkehrsmitteln gut erschlossen sind (SRS 7.8-6) | 1 | as enacted, 18 April 2022 |
| `7-8-7-baukoordinationsverordnung/` | Verordnung über die Koordination von Bauarbeiten im öffentlichen Strassenraum der Stadt Winterthur (SRS 7.8-7) | 1 | as enacted, 1 September 2024 |
| `7-9-1/` | Vorschriften über die Benützung des öffentlichen Grundes zu Sonderzwecken (SRS 7.9-1) | 1 | one version (the oldest available), 18 September 1996 |
| `7-9-2-vgp/` | Verordnung über das gebührenpflichtige Parkieren auf öffentlichem Grund (SRS 7.9-2) | 2 | as enacted, then each consolidated version: 6 June 2005 to 1 May 2023 |
| `7-9-2-1-nachtparkierverordnung-npv/` | Verordnung über das nächtliche Dauerparkieren auf öffentlichem Grund (SRS 7.9-2.1) | 3 | oldest version available, then each consolidated version: 1 May 2015 to 1 May 2023 |
| `7-9-2-1-1-vvo-npv/` | Vollzugsverordnung zur Nachtparkierverordnung (SRS 7.9-2.1.1) | 1 | as enacted, 1 January 2022 |
| `7-9-2-2-pbz/` | Verordnung über das unbeschränkte Parkieren in der Blauen Zone (SRS 7.9-2.2) | 3 | as enacted, then each consolidated version: 13 June 1988 to 1 May 2023 |
| `7-9-2-2-1-vvo-pbz/` | Vollzugsverordnung über das unbeschränkte Parkieren in der Blauen Zone (SRS 7.9-2.2.1) | 1 | as enacted, 1 January 2022 |
| `7-9-2-3-vvo-vgp/` | Vollzugsverordnung über das gebührenpflichtige Parkieren auf öffentlichem Grund (SRS 7.9-2.3) | 2 | as enacted, then each consolidated version: 1 May 2023 to 1 June 2024 |
| `7-9-3/` | Verordnung betreffend die Ausnahmebewilligungen zu signalisierten Strassenverkehrsvorschriften (SRS 7.9-3) | 1 | as enacted, 1 August 1988 |
| `7-9-4/` | Nutzungs- und Gebührenordnung für den Teuchelweiher-, Viehmarkt- und Reitwegplatz (SRS 7.9-4) | 2 | as enacted, then each consolidated version: 1 June 2017 to 1 July 2023 |
| `7-9-5/` | Verordnung Parkieren Winterthur (SRS 7.9-5) | 1 | as enacted, 1 January 2022 |
| `7-9-5-1/` | Tarifordnung Parkieren Winterthur (SRS 7.9-5.1) | 1 | as enacted, 1 March 2024 |
| `8-1-1/` | Verordnung über Alters- und Pflegeeinrichtungen (SRS 8.1-1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 May 2021 |
| `8-1-1-1/` | Leistungs- und Taxordnung der Alterszentren der Stadt Winterthur (SRS 8.1-1.1) | 2 | as enacted, then each consolidated version: 1 May 2021 to 1 December 2023 |
| `8-2-1/` | Verordnung über die Spitex-Dienste (SRS 8.2-1) | 1 | one version (the oldest available), 1 January 2011 |
| `8-3-1/` | Verordnung über den Vollzug der Zusatzleistungen zur AHV/IV und die Gewährung von Gemeindezuschüssen (SRS 8.3-1) | 1 | one version (the oldest available), 1 January 2011 |
| `8-3-3/` | Geschäftsordnung der Sozialhilfebehörde (SRS 8.3-3) | 2 | as enacted, then each consolidated version: 1 June 2014 to 1 June 2022 |
| `8-4-1/` | Geschäftsordnung KESB Winterthur-Andelfingen (SRS 8.4-1) | 3 | oldest version available, then each consolidated version: 1 March 2016 to 1 December 2022 |
| `9-1-1/` | Winterthurer Marktordnung (SRS 9.1-1) | 1 | one version (the oldest available), 1 February 1990 |
| `9-1-1-1/` | Ausführungsbestimmungen zur Marktverordnung (SRS 9.1-1.1) | 1 | as enacted, 1 January 1984 |
| `9-1-3/` | Vollzugsvorschriften zur Gesetzgebung über das Gastgewerbe und den Handel mit alkoholischen Getränken (SRS 9.1-3) | 1 | as enacted, 1 May 1990 |
| `9-2-1/` | Verordnung über Taxistandplätze auf öffentlichem Grund (SRS 9.2-1) | 2 | as enacted, then each consolidated version: 1 August 1989 to 1 January 2025 |

## Source

The SRS (systematic collection) of the city, published by the city at <https://winterthur.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the city's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@winterthur.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the city publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
