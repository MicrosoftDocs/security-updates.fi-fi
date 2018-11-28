---
title: Microsoftin turvatiedotteiden yhteenveto, kesäkuu 2011
TOCTitle: MS11-JUN
ms:assetid: ms11-jun
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms11-jun(v=Security.10)
ms:contentKeyID: 61225727
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, kesäkuu 2011

Julkaistu: 14. kesäkuuta 2011 | Päivitetty: 14. kesäkuuta 2011

**Versio:** 1.1

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo kesäkuussa 2011 julkaistuista tietoturvatiedotteista.

Tämä tietoturvatiedotteiden yhteenveto korvaa kesäkuun 2011 tietoturvatiedotteiden julkaisun yhteydessä tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 9. tammikuuta 2011. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 15. kesäkuuta 2011, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt kesäkuun tietoturvatiedotteen web-lähetykseen.](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032455073&eventcategory=4) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://go.microsoft.com/fwlink/?linkid=217214) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja muut päivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

## Yhteenveto

Seuraavassa taulukossa on luettelo tämän kuun tietoturvatiedotteista luokittelujärjestyksessä.

Lisätietoja ohjelmistoista, joita haavoittuvuus koskee, on kohdassa **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot**.

<table>
<thead>
<tr class="header">
<th>Tiedotteen tunnus</th>
<th>Tiedotteen otsikko ja yhteenveto</th>
<th>Luokitus ja haavoittuvuuden vaikutus</th>
<th>Edellyttää uudelleenkäynnistystä</th>
<th>Ohjelmistot, joita haavoittuvuus koskee</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212284">MS11-038</a></td>
<td><strong>OLE-automaation haavoittuvuus saattaa</strong> <strong>sallia koodin suorittamisen verkon välityksellä (2476490)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin OLE (Object Linking and Embedding) -automaation haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua Windows Metafile (WMF) -kuvaa. Hyökkääjä ei kuitenkaan pysty missään tapauksessa pakottamaan käyttäjää avaamaan tällaista sivustoa. Sen sijaan hyökkääjän on saatava käyttäjä avaamaan sivusto. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä olevaa linkkiä tai pikaviestimellä lähetettyä pyyntöä.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212287">MS11-039</a></td>
<td><strong>.NET Frameworkin ja Microsoft Silverlightin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2514842)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft .NET Frameworkin ja Microsoft Silverlightin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä asiakasjärjestelmässä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua selaimella, jossa voidaan suorittaa XAML-selainsovelluksia (XBAP:t) tai Silverlight-sovelluksia. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä myös palvelinjärjestelmissä, joissa on käynnissä IIS, jos palvelin sallii ASP.NET-sivujen käsittelemisen ja jos hyökkääjä pystyy lataamaan tietyllä tavalla muodostetun ASP.NET-sivun kyseiseen palvelimeen ja suorittamaan sen. Tämä voi olla mahdollista esimerkiksi Web-palvelujen yhteydessä. Myös Windows .NET -sovellukset voivat käyttää tätä haavoittuvuutta koodin käyttöoikeusrajoitusten ohittamiseen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217470">MS11-040</a></td>
<td><strong>Threat Management Gateway -palomuuriasiakkaan</strong> <strong>haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2520426)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Forefront Threat Management Gateway (TMG) 2010 -asiakkaan haavoittuvuuden. Aiemmin tämä sovellus tunnettiin nimellä Microsoft Threat Management Gateway -palomuuriasiakas. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä tekee asiakkaan kautta tiettyjä pyyntöjä järjestelmään, jossa TMG-palomuuriasiakasta käytetään.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Forefront Threat Management Gateway</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217499">MS11-041</a></td>
<td><strong>Windowsin ydintilan ohjaimien haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2525694)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa jaetun verkkoresurssin (tai avaa sivuston, joka osoittaa jaettuun verkkoresurssiin), joka sisältää tietyllä tavalla muodostetun OTF (OpenType Font) -fontin. Hyökkääjä ei kuitenkaan pysty missään tapauksessa pakottamaan käyttäjää avaamaan tällaista sivustoa tai jaettua verkkoresurssia. Hyökkääjä voi kuitenkin onnistua saamaan käyttäjän avaaman sivuston. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä olevaa linkkiä tai pikaviestinviestiä.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=215838">MS11-042</a></td>
<td><strong>DFS-tiedostojärjestelmän haavoittuvuudet saattavat salli koodin suorittamisen verkon välityksellä. (2535512)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaan Microsoftin hajautetun tiedostojärjestelmän eli DFS (Distributed File System) -järjestelmän haavoittuvuutta. Näistä kahdesta vakavampi haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä lähettää tietyllä tavalla muodostetun DFS-vastauksen asiakkaan lähettämään DFS-pyyntöön. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi suorittaa haluamaansa koodia ja saada kokonaan hallintaansa järjestelmän, jota haavoittuvuus koskee. Palomuurikäytännöistä ja palomuurin vakiomäärityksistä annetut toimintaohjeet suojaavat verkkoa hyökkäyksiltä, joiden lähde on yritysverkon ulkopuolella. Hyvän käytännön mukaisesti internetiin yhteydessä olevissa järjestelmissä pitäisi olla mahdollisimman vähän portteja alttiina uhille.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=215841">MS11-043</a></td>
<td><strong>SMB-asiakkaan haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2536276)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä lähettää tietyllä tavalla muodostetun SMB-vastauksen asiakkaan lähettämään SMB-pyyntöön. Jotta hyökkääjä pystyisi hyödyntämään tätä haavoittuvuutta, hänen on saatava käyttäjä muodostamaan SMB-yhteys tietyllä tavalla muodostettuun SMB-palvelimeen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=216436">MS11-044</a></td>
<td>.<strong>NET Frameworkin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2538814)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Microsoft .NET Frameworkin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä asiakasjärjestelmässä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua selaimella, jossa voidaan suorittaa XAML-selainsovelluksia (XBAP:t) Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä myös palvelinjärjestelmissä, joissa on käynnissä IIS, jos palvelin sallii ASP.NET-sivujen käsittelemisen ja jos hyökkääjä pystyy lataamaan tietyllä tavalla muodostetun ASP.NET-sivun kyseiseen palvelimeen ja suorittamaan sen. Tämä voi olla mahdollista esimerkiksi Web-palvelujen yhteydessä. Myös Windows .NET -sovellukset voivat käyttää tätä haavoittuvuutta koodin käyttöoikeusrajoitusten ohittamiseen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (2530548)</strong><br />
<br />
Tämä tietoturvatiedote korjaa 11 yksityishenkilön ilmoittamaa Internet Explorerin haavoittuvuutta. Vakavimmat haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun sivun Internet Explorerissa. Jotakin näistä haavoittuvuuksista onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin paikallinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=218115">MS11-052</a></td>
<td><strong>VML (Vector Markup Language) -kielen haavoittuvuus saattaa sallia koodin suorittamisen verkon avulla (2544521)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden, joka esiintyy Microsoftin käyttäessä VML (Vector Markup Language) -kieltä. Tämä tietoturvatiedote on luokiteltu kriittiseksi Windows-asiakkaissa käytettävissä Internet Explorer 6-, Internet Explorer 7- ja Internet Explorer 8 -versioissa sekä keskitasoiseksi Windows-palvelimissa käytettävissä Internet Explorer 6-, Internet Explorer 7 ja Internet Explorer 8 -versioissa. Haavoittuvuus ei koske Internet Explorer 9:ää.<br />
<br />
Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon avulla, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet Explorerilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217912">MS11-037</a></td>
<td><strong>MHTML:n haavoittuvuus saattaa sallia tietojen paljastumisen (2544893)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa Microsoft Windowsin MHTML:n protokollan käsittelytoiminnon yleisessä tiedossa olleen haavoittuvuuden. Haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille, jos käyttäjä avaa tietyllä tavalla muodostetun, hyökkääjän sivustosta lähetetyn URL-osoitteen. Hyökkääjän on saatava käyttäjä avaamaan sivusto. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä olevaa linkkiä tai pikaviestinviestiä</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Tietojen paljastuminen muille käyttäjille</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td><strong>Microsoft Excelin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (2537146)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kahdeksan yksityishenkilön ilmoittamaa Microsoft Officen haavoittuvuutta. Haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Excel-tiedoston. Jotakin näistä haavoittuvuuksista onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin järjestelmään kirjautunut käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Jos epäilyttävien tiedostojen avaaminen estetään Office-tiedostojen tarkistustoiminnolla, hyökkääjä ei voi hyödyntää haavoittuvuuksia, jotka on kuvattu tunnuksilla CVE-2011-1272, CVE-2011-1273 ja CVE-2011-1279. Microsoft Excel 2010:tä koskee vain tunnuksella CVE-2011-1273 tässä tiedotteessa kuvattu haavoittuvuus. Automaattinen Microsoft Fix it -ratkaisu, jossa Excel 2010:n suojattu näkymä on poistettu käytöstä (Disable Edit in Protected View for Excel 2010), on saatavana Microsoftin Knowledge Base -artikkelissa 2501584. Tämä ratkaisu estää hyökkääjää hyödyntämästä haavoittuvuutta CVE-2011-1273.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217464">MS11-046</a></td>
<td><strong>Lisäfunktio-ohjaimen haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (2503665)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa Microsoft Windowsin lisäfunktio-ohjaimen yleisessä tiedossa olleen haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen, jos hyökkääjä kirjautuu käyttäjän järjestelmään ja suorittaa tietyllä tavalla muodostetun sovelluksen. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja hänen on pystyttävä kirjautumaan paikallisesti, jotta hän pystyy hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217468">MS11-047</a></td>
<td><strong>Hyper-V:n haavoittuvuus saattaa sallia palveluneston (2525835)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Server 2008 Hyper-V:n ja Windows Server 2008 R2 Hyper-V:n haavoittuvuuden. Haavoittuvuus saattaa sallia palveluneston, jos todennettu käyttäjä lähettää tietyllä tavalla muodostetun paketin VMBus-väylään, joka on yhdessä Hyper-V-palvelimessa olevassa vieras-virtuaalikoneessa. Jotta hyökkääjä pystyisi hyödyntämään tätä haavoittuvuutta, hänellä on oltava kelvolliset kirjautumisoikeudet ja hänen on pystyttävä lähettämään tietyllä tavalla muodostettu paketti vieras-virtuaalikoneesta. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Palvelunesto</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=215840">MS11-048</a></td>
<td><strong>SMB-palvelimen haavoittuvuus saattaa sallia palveluneston (2536275)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia palveluneston, jos hyökkääjä on luonut tietyllä tavalla muodostetun SMB-paketin ja lähettänyt sen haavoittuvuuden sisältävään järjestelmään. Palomuurikäytännöistä ja palomuurin vakiomäärityksistä annetut toimintaohjeet suojaavat verkkoja hyökkäyksiltä, joiden lähde on yrityksen verkon ulkopuolella ja jotka yrittävät hyödyntää tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Palvelunesto</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217077">MS11-049</a></td>
<td><strong>Microsoftin XML-editorin haavoittuvuus</strong> <strong>saattaa sallia tietojen paljastumisen (2543893)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoftin XML-editorin haavoittuvuuden. Haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille, jos käyttäjä avaa tietyllä tavalla muodostetun verkkopalvelun etsintätiedoston (.disco) jossakin sovelluksessa, joka on mainittu tämän tiedotteen Ohjelmistot, joita haavoittuvuus koskee -taulukossa. Huomaa, että tämä haavoittuvuus ei anna hyökkääjien suorittaa koodia tai suoraan nostaa käyttöoikeuksiensa tasoa. Sen avulla voidaan kuitenkin hankkia tietoja, jotka voivat vaarantaa entisestään haavoittuvuuden sisältävää järjestelmää.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Tietojen paljastuminen muille käyttäjille</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office,<br />
Microsoft SQL Server,<br />
Microsoft Visual Studio</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217101">MS11-051</a></td>
<td><strong>Active Directory -varmennepalvelun verkkorekisteröinnin haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (2518295)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Active Directory -varmennepalvelun verkkorekisteröinnin haavoittuvuuden. Haavoittuvuus on tyypiltään XSS (sivustojen välinen komentosarja) -haavoittuvuus, joka saattaa sallia käyttöoikeuksien korottamisen, jolloin hyökkääjä voi suorittaa sivustossa satunnaisia komentoja kohdekäyttäjän käyttöympäristössä. Jotta hyökkääjä voisi hyödyntää tätä haavoittuvuutta, hänen pitäisi lähettää tietyllä tavalla muodostettu linkki, joka käyttäjän olisi avattava. Hyökkääjä ei voi missään tapauksessa pakottaa käyttäjää avaamaan sivustoa. Hyökkääjä voi kuitenkin onnistua saamaan käyttäjän avaaman sivuston. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä olevaa linkkiä tai pikaviestinviestiä, joka avaa hyökkääjän sivuston.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
</tbody>
</table>


## Hyödyntämisindeksi

Seuraavassa taulukossa on kunkin tässä kuussa käsitellyn haavoittuvuuden hyödyntämisluokitus. Haavoittuvuudet on järjestetty ensin tiedotteen tunnuksen ja sitten CVE-tunnuksen mukaan. Taulukossa on vain haavoittuvuudet, jotka on luokiteltu tiedotteissa kriittisiksi tai tärkeiksi.

**Kuinka taulukkoa käytetään?**

Tämän taulukon avulla saat selville, kuinka todennäköistä on sellaisen hyväksikäyttökoodin tai palveluneston julkaiseminen 30 päivän kuluessa tietoturvatiedotteen julkaisemisesta, joka koskee tietoturvapäivitystä, joka sinun on ehkä asennettava. Tutustu järjestelmän määritysten perusteella kuhunkin arviointiin. Tällä tavoin voit ottaa päivitykset käyttöön tärkeysjärjestyksessä. Lisätietoja näistä luokituksista ja niiden määrittämisestä on [Microsoftin hyödyntämisindeksissä](http://technet.microsoft.com/en-us/security/cc998259.aspx).

Alla olevissa sarakkeissa "Uusin ohjelmistoversio" viittaa uusimpaan ohjelmistoversioon ja "Aiemmat ohjelmistoversiot" viittaa vanhempiin tuettuihin ohjelmistoversioihin tietoturvatiedotteen taulukoissa "Ohjelmistot, joita haavoittuvuus koskee" ja "Ohjelmistot, joita haavoittuvuus ei koske".

<table>
<thead>
<tr class="header">
<th>Tiedotteen tunnus</th>
<th>Haavoittuvuuden otsikko</th>
<th>CVE-tunnus</th>
<th>Uusimman ohjelmistoversion koodin suorittamisen hyödyntämisaste</th>
<th>Aiempien ohjelmistoversioiden koodin suorittamisen hyödyntämisaste</th>
<th>Hyödyntämisasteen palvelunesto</th>
<th>Tärkeät huomautukset</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217912">MS11-037</a></td>
<td>Mime-muotoillun MHTML-pyynnön haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1894">CVE-2011-1894</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä haavoittuvuus on ollut yleisessä tiedossa.<br />
<br />
Tämä on tietojen paljastumisen muille käyttäjille aiheuttava haavoittuvuus</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212284">MS11-038</a></td>
<td>OLE-automaation alivuodon haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0658">CVE-2011-0658</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212287">MS11-039</a></td>
<td>.NET Framework -matriisin offset-määritteen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0664">CVE-2011-0664</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217470">MS11-040</a></td>
<td>TMG-palomuuriasiakkaan muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1889">CVE-2011-1889</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217499">MS11-041</a></td>
<td>Win32k OTF -tarkistuksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1873">CVE-2011-1873</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=215838">MS11-042</a></td>
<td>DFS-muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1868">CVE-2011-1868</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=215838">MS11-042</a></td>
<td>DFS-viittauksen vastauksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1869">CVE-2011-1869</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Pysyvä</td>
<td>Tämä on palveluneston aiheuttava haavoittuvuus</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=215841">MS11-043</a></td>
<td>SMB-vastauksen jäsennyksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1268">CVE-2011-1268</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=216436">MS11-044</a></td>
<td>.NET Frameworkin JIT-optimoinnin haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1271">CVE-2011-1271</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>Tämä haavoittuvuus on ollut yleisessä tiedossa.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td>Excel-tietueen riittämättömän tarkistuksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1272">CVE-2011-1272</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td>Excel-tietueen virheellisen jäsennyksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1273">CVE-2011-1273</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td>Excelin raja-alueen ulkopuolisen käytön haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1274">CVE-2011-1274</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td>Excelin kekomuistin korvaushaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1275">CVE-2011-1275</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td>Excelin puskurin ylivuodon haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1276">CVE-2011-1276</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td>Haavoittuvuus Excel-muistin käytössä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1277">CVE-2011-1277</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td>Excelin WriteAV-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1278">CVE-2011-1278</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td>Excelin rajojen ulkopuolelle osoittava WriteAV-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1279">CVE-2011-1279</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217464">MS11-046</a></td>
<td>Lisäfunktio-ohjaimen käyttöoikeuksien korottamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1249">CVE-2011-1249</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>Tämä haavoittuvuus on ollut yleisessä tiedossa.<br />
<br />
Tämä on käyttöoikeuksien korottamista koskeva haavoittuvuus</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217468">MS11-047</a></td>
<td>VMBusin pysyvä palveluneston haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1872">CVE-2011-1872</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Väliaikainen</td>
<td>Tämä on palveluneston aiheuttava haavoittuvuus</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=215840">MS11-048</a></td>
<td>SMB-pyynnön jäsennyksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1267">CVE-2011-1267</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Pysyvä</td>
<td>Tämä on palveluneston aiheuttava haavoittuvuus</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217077">MS11-049</a></td>
<td>Ulkoisen XML-yksikön ratkaisun haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1280">CVE-2011-1280</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä on tietojen paljastumisen muille käyttäjille aiheuttava haavoittuvuus</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td>Linkin ominaisuuksien käsittelymuistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1250">CVE-2011-1250</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td>DOM-käsittelymuistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1251">CVE-2011-1251</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td>Haavoittuvuus toStaticHTML-tiedon käytössä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252">CVE-2011-1252</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä on tietojen paljastumisen muille käyttäjille aiheuttava haavoittuvuus</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td>Vedä ja pudota -muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1254">CVE-2011-1254</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td>Aikaelementin muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1255">CVE-2011-1255</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td>DOM-muokkausmuistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1256">CVE-2011-1256</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td>Taittomuistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1260">CVE-2011-1260</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td>Valintaobjektin muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1261">CVE-2011-1261</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td>HTTP-uudelleenohjauksen muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1262">CVE-2011-1262</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217101">MS11-051</a></td>
<td>Active Directory -varmennepalvelun haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1264">CVE-2011-1264</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä on käyttöoikeuksien korottamista koskeva haavoittuvuus</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=218115">MS11-052</a></td>
<td>VML:n muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1266">CVE-2011-1266</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

Seuraavissa taulukoissa tiedotteet on järjestetty pääohjelmistoluokkien ja vakavuuden mukaan.

**Taulukoiden käyttö**

Näiden taulukoiden avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja koskeeko jokin tietoturvapäivitys niiden asennusta. Jos ohjelma tai osa on luettelossa, saatavana olevaan ohjelmistopäivitykseen on linkki. Myös ohjelmistopäivityksen luokitus mainitaan.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää usean tietoturvapäivityksen asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

#### Windows-käyttöjärjestelmä ja osat

**Taulukko 1**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="8">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2371079f-fb20-4fd5-999e-e73f3701818c">Windows XP Service Pack 3</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f">Microsoft .NET Framework 3,5</a>
                    <br />(KB2478656)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478658)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67a25abd-f43c-4b01-b507-a109b739238f">Windows XP Service Pack 3</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=492310d3-bbb4-4fff-b5fe-3470c17e7681">Windows XP Service Pack 3</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 2,0 Service Pack 2</a>
                    <br />(KB2518864)<br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d">Microsoft .NET Framework 3.5</a><br />(KB2530095)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518864)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26ec66af-9727-4423-90da-012ed5b30856">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4203a59a-a809-45db-a234-fef0ff5063f9">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4a49ec89-2a8f-41d9-8f0b-ee57fdf21f50">Internet Explorer 8</a><br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b53d6631-4ded-48f5-a503-925b89b322b2">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f">Microsoft .NET Framework 3,5</a>
                    <br />(KB2478656)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478658)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=035d5115-54b6-41d3-b9f0-890041ead178">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=af6b7627-c462-45fe-8948-70da37e60659">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e10a4c3c-2ef8-4cfc-ac9b-4d97bfa79ac1">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 2,0 Service Pack 2</a>
                    <br />(KB2518864)<br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d">Microsoft .NET Framework 3.5</a><br />(KB2530095)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518864)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6e05fef-ee8c-44ff-a106-d7b8659c8d91">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9fc734db-a177-43d2-a74a-b1fe6ea6f779">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e4e18a4-97dc-4c5e-a078-8466913aa29e">Internet Explorer 8</a><br />(Kriittinen)</td></tr>
              
                <tr><th colspan="8">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-03</strong>
                      <strong>8</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e6ff410-4552-4687-81ab-83d9c91f8af5">Windows Server 2003 Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f">Microsoft .NET Framework 3,5</a>
                    <br />(KB2478656)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478658)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3aa8f1bc-07de-451a-8244-1733247e6f2e">Windows Server 2003 Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2719e0fb-3cfd-47b2-906d-3e07b0e3c978">Windows Server 2003 Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 2,0 Service Pack 2</a>
                    <br />(KB2518864)<br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d">Microsoft .NET Framework 3.5</a><br />(KB2530095)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518864)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=638f6dd6-bea0-4356-b23a-45e865a6b28b">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a3bd0012-4a45-4f96-8a51-3ff1f85d1e37">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19557984-5088-44cc-b5ba-9bab33df8e7e">Internet Explorer 8</a><br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9c1a539f-1472-4394-8354-bd549d8332e0">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f">Microsoft .NET Framework 3,5</a>
                    <br />(KB2478656)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478658)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aa8c003-0353-4a5b-8aea-c01a103af393">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9018258-5a72-47a1-8584-3d1aa52317c3">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c962531e-f580-4195-989b-cf348cc96fa7">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 2,0 Service Pack 2</a>
                    <br />(KB2518864)<br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d">Microsoft .NET Framework 3.5</a><br />(KB2530095)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518864)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce616970-343d-49f1-994d-4269b9a11448">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ece3b4-e5bb-469c-bfef-c8310681f5a7">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c92d94c5-5e8f-45aa-a24a-f4d0efd93732">Internet Explorer 8</a><br />(Kriittinen)</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c194dd35-b9db-44a5-a252-38f9f803802f">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f">Microsoft .NET Framework 3,5</a>
                    <br />(KB2478656)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478658)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e07b5fa-c9fa-495b-9352-c07ce46a7e8b">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96309c49-4822-4c47-b364-2ba65327cac5">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ea18a916-03cf-4eac-bacc-ceb006491f24">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 2,0 Service Pack 2</a>
                    <br />(KB2518864)<br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d">Microsoft .NET Framework 3.5</a><br />(KB2530095)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518864)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f58ebc9e-00e1-413c-8076-d7a44003d0c7">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80231a27-b37c-4101-a34f-19a26a040836">Internet Explorer 7</a><br />(Kriittinen)</td></tr>
              
                <tr><th colspan="8">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotte</strong>
                    <strong>en numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f33c9e54-c2e5-498d-a798-5bbfe9e4249c">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Vain Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9">Microsoft .NET Framework 2.0 Service Pack 1 ja Microsoft .NET Framework 3.5</a><br />(KB2478657)<br />(Kriittinen)<br /><br />Vain Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478659)<br />(Kriittinen)<br /><br />Vain Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478660)<br />(Kriittinen)<br /><br />Windows Vista Service Pack 1 ja Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aded8f20-479d-40c1-9560-c0581c6f77a2">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a62edfd8-9016-4bb5-bf48-885498fa0042">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Vain Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 2.0 Service Pack 1</a><br />(KB2518863)<br />(Ei luokitusta[2])<br /><br />Vain Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518865)<br />(Ei luokitusta[2])<br /><br />Vain Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 3.5</a><br />(KB2518863)<br />(Kriittinen)<br /><br />Vain Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518865)<br />(Kriittinen)<br /><br />Vain Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518866)<br />(Ei luokitusta[2])<br /><br />Vain Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518866)<br />(Kriittinen)<br /><br />Windows Vista Service Pack 1 ja Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fea735a8-032b-4fa6-8337-1fa411df0b88">Internet Explorer 7</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4cddfc68-eff6-4587-8607-63307d039489">Internet Explorer 8</a><br />(Kriittinen)<br /><br />Vain Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=392316fc-f531-469c-aa60-4ecf061a5354">Internet Explorer 9</a><br />(Kriittinen)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4566528f-62ee-4d78-b3af-131a7cc15e1f">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Vain Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9">Microsoft .NET Framework 2.0 Service Pack 1 ja Microsoft .NET Framework 3.5</a><br />(KB2478657)<br />(Kriittinen)<br /><br />Vain Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478659)<br />(Kriittinen)<br /><br />Vain Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478660)<br />(Kriittinen)<br /><br />Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a519a5d7-bfe3-4e53-99e9-d85f7e34237f">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=962cb40c-680c-4c37-98d4-ca9789ca7270">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb561ba6-af4d-40cc-947c-923f9cca9a7e">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Vain Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 2.0 Service Pack 1</a><br />(KB2518863)<br />(Ei luokitusta[2])<br /><br />Vain Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518865)<br />(Ei luokitusta[2])<br /><br />Vain Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 3.5</a><br />(KB2518863)<br />(Kriittinen)<br /><br />Vain Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518865)<br />(Kriittinen)<br /><br />Vain Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518866)<br />(Ei luokitusta[2])<br /><br />Vain Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518866)<br />(Kriittinen)<br /><br />Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49dcb47b-3c79-4f69-ba07-f471304c16e2">Internet Explorer 7</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0a8fbac-2c31-4cf8-9967-6171edabd560">Internet Explorer 8</a><br />(Kriittinen)<br /><br />Vain Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44b2aa73-c318-47ac-ad87-0d24afd9cdd7">Internet Explorer 9</a><br />(Kriittinen)</td></tr>
              
                <tr><th colspan="8">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c9614d9-6f61-463d-b1fa-bd5eb2c1a5c5">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>**<br />(Kriittinen)</td><td>Vain Windows Server 2008 for 32-bit Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9">Microsoft .NET Framework 2.0 Service Pack 1 ja Microsoft .NET Framework 3.5</a>**<br />(KB2478657)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for 32-bit Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2478659)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for 32-bit Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2478660)<br />(Kriittinen)<br /><br />Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2478663)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ebfa067-0236-4454-8605-df1b99742f90">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ab9679e-6a69-4ca3-9210-7ca4fb1980c2">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Kriittinen)</td><td>Vain Windows Server 2008 for 32-bit Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 2.0 Service Pack 1</a>**<br />(KB2518863)<br />(Ei luokitusta[2])<br /><br />Vain Windows Server 2008 for 32-bit Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2518865)<br />(Ei luokitusta[2])<br /><br />Vain Windows Server 2008 for 32-bit Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 3.5</a>**<br />(KB2518863)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for 32-bit Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2518865)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for 32-bit Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2518866)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for 32-bit Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2518866)<br />(Kriittinen)<br /><br />Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6547ff0-b059-495d-8816-bb094ac11be7">Internet Explorer 7</a>**<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9650c47-ac52-433d-b409-ce1cfe8d3e87">Internet Explorer 8</a>**<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for 32-bit Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f9b1ba2-8247-494b-990c-f62003188c5a">Internet Explorer 9</a>**<br />(Kriittinen)</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=36698775-0e4e-4980-ae4c-43542de424ca">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>**<br />(Kriittinen)</td><td>Vain Windows Server 2008 for x64-based Systems <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9">Microsoft .NET Framework 2.0 Service Pack 1 ja Microsoft .NET Framework 3.5</a>**<br />(KB2478657)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for x64-based Systems <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2478659)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for x64-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2478660)<br />(Kriittinen)<br /><br />Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2478663)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd8f3713-b408-4db6-aecd-7eed2176a715">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1d76b82-9996-4d08-894b-9c16a4b3bb1e">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22c63fc3-2c5a-4e50-9026-2e04a6e74210">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Kriittinen)</td><td>Vain Windows Server 2008 for x64-based Systems <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 2.0 Service Pack 1</a>**<br />(KB2518863)<br />(Ei luokitusta[2])<br /><br />Vain Windows Server 2008 for x64-based Systems <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2518865)<br />(Ei luokitusta[2])<br /><br />Vain Windows Server 2008 for x64-based Systems <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 3.5</a>**<br />(KB2518863)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for x64-based Systems <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2518865)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for x64-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2518866)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for x64-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2518866)<br />(Kriittinen)<br /><br />Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feff3364-4bfd-45f5-99da-9192b47ef5d4">Internet Explorer 7</a>**<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7dff9f08-19cb-41dd-a315-84c1dac81510">Internet Explorer 8</a>**<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for x64-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fdf88a52-c099-44eb-95a0-650129c0e678">Internet Explorer 9</a>**<br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3edb613f-5bf0-4e28-9835-4afbb6ef0e01">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Vain Windows Server 2008 for Itanium-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9">Microsoft .NET Framework 2.0 Service Pack 1 ja Microsoft .NET Framework 3.5</a><br />(KB2478657)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for Itanium-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478659)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for Itanium-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b">Microsoft .NET Framework 2.0 Service Pack 2 ja Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478660)<br />(Kriittinen)<br /><br />Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a61f888-c81e-4b8a-8932-2fe67df4b2ad">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f80c89c6-27ab-4f6a-afad-9c8e92cbbce4">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5bb889de-8ff6-4587-8ef9-ffb13e8d60fd">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Vain Windows Server 2008 for Itanium-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 2.0 Service Pack 1</a><br />(KB2518863)<br />(Ei luokitusta[2])<br /><br />Vain Windows Server 2008 for Itanium-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518865)<br />(Ei luokitusta[2])<br /><br />Vain Windows Server 2008 for Itanium-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 3.5</a><br />(KB2518863)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for Itanium-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518865)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for Itanium-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518866)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 for Itanium-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518866)<br />(Kriittinen)<br /><br />Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d81a9219-da95-4fbf-af7f-898f553b0572">Internet Explorer 7</a>
                    <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="8">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50ae36ff-2406-48a4-97cc-12782b6d30ac">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>Vain Windows 7 for 32-bit Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6">Microsoft .NET Framework 3.5.1</a><br />(KB2478661)<br />(Kriittinen)<br /><br />Vain Windows 7 for 32-bit Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4">Microsoft .NET Framework 3.5.1</a><br />(KB2478662)<br />(Kriittinen)<br /><br />Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9de1bf5d-6f25-496d-bc44-a32c5e8920fe">Windows 7 for 32-bit Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19a15098-1754-4536-a9ca-ff07d16464b7">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>Vain Windows 7 for 32-bit Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98">Microsoft .NET Framework 3.5.1</a><br />(KB2518867)<br />(Kriittinen)<br /><br />Vain Windows 7 for 32-bit Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980">Microsoft .NET Framework 3.5.1</a><br />(KB2518869)<br />(Kriittinen)<br /><br />Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91b98f02-a09e-48f1-9f78-a949f7268542">Internet Explorer 8</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79f846da-3b17-43c9-9016-a055c2c56975">Internet Explorer 9</a><br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1241f0f8-a5c7-420a-a5b7-b6c3caa9e5e2">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>Vain Windows 7 for x64-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6">Microsoft .NET Framework 3.5.1</a><br />(KB2478661)<br />(Kriittinen)<br /><br />Vain Windows 7 for x64-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4">Microsoft .NET Framework 3.5.1</a><br />(KB2478662)<br />(Kriittinen)<br /><br />Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7f52b13-5b3d-438c-ae14-86da50c8b67a">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50d1c677-57aa-4e3f-bdfc-6f01b5d3bfe2">Windows 7 for x64-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b449f23e-b3df-46e5-bfe3-98268d20ad54">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>Vain Windows 7 for x64-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98">Microsoft .NET Framework 3.5.1</a><br />(KB2518867)<br />(Kriittinen)<br /><br />Vain Windows 7 for x64-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980">Microsoft .NET Framework 3.5.1</a><br />(KB2518869)<br />(Kriittinen)<br /><br />Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=264107cc-68b4-401c-82f7-de64b535c18d">Internet Explorer 8</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e87a09f2-b755-48ef-9b85-fc78d0bfce43">Internet Explorer 9</a><br />(Kriittinen)</td></tr>
              
                <tr><th colspan="8">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-</strong>
                      <strong>050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8181c359-cd79-438a-87be-093b363d0b04">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>**<br />(Kriittinen)</td><td>Vain Windows Server 2008 R2 for x64-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6">Microsoft .NET Framework 3.5.1</a>*<br />(KB2478661)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 R2 for x64-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4">Microsoft .NET Framework 3.5.1</a>*<br />(KB2478662)<br />(Kriittinen)<br /><br />Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>*[1]<br />(KB2478663)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b77e5be6-d3eb-4e3a-9be2-831578f0447c">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d66b1e7-dbf9-4475-a973-49fb85557eca">Windows Server 2008 R2 for x64-based Systems</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06008192-3cac-477b-a913-83eed39d8718">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Kriittinen)</td><td>Vain Windows Server 2008 R2 for x64-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98">Microsoft .NET Framework 3.5.1</a>*<br />(KB2518867)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 R2 for x64-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980">Microsoft .NET Framework 3.5.1</a>*<br />(KB2518869)<br />(Kriittinen)<br /><br />Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>*[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b18e6f9-96b8-4dec-bcd0-d71f1bac3eb0">Internet Explorer 8</a>**<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81814b15-ebdf-4817-932b-5ea7a37fa6ed">Internet Explorer 9</a>**<br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b63a1eb-445a-4cd3-b357-9a1dd82d7a35">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>Vain Windows Server 2008 R2 for Itanium-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6">Microsoft .NET Framework 3.5.1</a><br />(KB2478661)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 R2 for Itanium-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4">Microsoft .NET Framework 3.5.1</a><br />(KB2478662)<br />(Kriittinen)<br /><br />Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c00a33bc-c874-4693-b0f7-5034c5df9424">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c8455f1-b8a0-4ba2-84a2-043d25ef75c5">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93a32bd9-7e67-4ace-8c45-116f91b032f9">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>Vain Windows Server 2008 R2 for Itanium-based Systems: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98">Microsoft .NET Framework 3.5.1</a><br />(KB2518867)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 R2 for Itanium-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980">Microsoft .NET Framework 3.5.1</a><br />(KB2518869)<br />(Kriittinen)<br /><br />Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab2406a8-06f7-4f88-9af4-dc136d64bc35">Internet Explorer 8</a>
                    <br />(Kriittinen)</td></tr>
              </table>


**Huomautukset: Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Huomautukset: MS11-039**

\[1\] **Koskee .NET Framework 4.0:ää ja .NET Framework 4.0 Client Profilea.** .NET Framework version 4 jakelutiedostopaketeista on kaksi versiota: .NET Framework 4.0 ja .NET Framework 4.0 Client Profile .NET Framework 4.0 Client Profile on .NET Framework 4.0:n osajoukko. Haavoittuvuus, jonka tämä tietoturvapäivitys korjaa, koskee sekä .NET Framework 4.0:ää että .NET Framework 4.0 Client Profilea. Lisätietoja on MSDN-artikkelissa, jossa käsitellään [.NET Frameworkin asentamista](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

**Huomautukset: MS11-044**

\[1\] **Koskee .NET Framework 4.0:ää ja .NET Framework 4.0 Client Profilea.** .NET Framework version 4 jakelutiedostopaketeista on kaksi versiota: .NET Framework 4.0 ja .NET Framework 4.0 Client Profile .NET Framework 4.0 Client Profile on .NET Framework 4.0:n osajoukko. Haavoittuvuus, jonka tämä tietoturvapäivitys korjaa, koskee sekä .NET Framework 4.0:ää että .NET Framework 4.0 Client Profilea. Lisätietoja on MSDN-artikkelissa, jossa käsitellään [.NET Frameworkin asentamista](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

\[2\]Tällä päivityksellä ei ole luokitusta, koska tiedotteessa käsitelty haavoittuvuus ei koske tätä ohjelmistoa. Microsoft kuitenkin suosittelee, että käyttäjät asentavat tämän tietoturvapäivityksen, jotta järjestelmä on suojattu myös mahdollisilta myöhemmin havaittavilta uusilta hyökkäystavoilta.

**Taulukko 2**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>Ei mitään</td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c760c7f-94f1-437f-a645-fd33b50d03f4">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b88f9e9-3439-44e5-92c8-66a3c97cb03d">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03b45ad8-cc6b-473b-8112-bd513ed97f5d">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce5bc2d7-9438-4bf0-be5e-be9dd00c3286">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1db7736-f3e4-45df-af1d-52746978a0a8">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c94c0d17-fdbe-41b3-a23d-98f43f907b89">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ff955dc3-58ca-40ea-b7f1-9ff40c37f997">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed502ece-737e-44cb-84fd-8a0d1bc321c8">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b211b02-a005-46a3-ad1d-d4baaeec8289">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71497891-41a2-476d-b524-4eb5cecb9639">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Ei tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5dafb455-969e-4be9-8735-d4ee0682d22f">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba3beb80-a921-489e-a6ff-a7b2d665ada6">Internet Explorer 7</a><br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8038325-0d14-445b-a5d9-ce7ac1fa44b5">Internet Explorer 8</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6427ea5d-05d0-4367-805c-9cb305802b3c">Windows Server 2003 Service Pack 2</a>
                    <br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c614cb8b-223e-4f84-b94c-f15747760aa5">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef90d6c1-ea7f-4c32-9c90-0303e04c7436">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e78829d0-8215-4e56-8959-ebd3bc8e9a91">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3bec943e-5758-4439-a947-a8fafd30edec">Internet Explorer 7</a><br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7bcbad-f647-4fbb-88d4-b19c54db6f00">Internet Explorer 8</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7f65891-32c0-4817-b3b2-d8be73145df9">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a951087-25c5-4f5c-8407-a1585491ae0b">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62944095-33d6-4131-be32-a79d9ec4d4a9">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e822515-9f0a-4ef0-bb70-d4889d200f47">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47a0fdc6-7576-4c32-b8fd-cbb05d57599d">Internet Explorer 7</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ca8b1d09-9f80-417b-99b1-8f86e86e1f11">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd48b93b-24fa-45a3-91fb-9f9f9418c49f">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e541f1bb-c9bf-4dc8-96ec-58a3de5ba7fd">Internet Explorer 7</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd059690-52b0-4b37-9fbb-d9906ae46fed">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebea38a7-1fbe-4141-a529-52d7a7326d6a">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b69e3bda-940b-4524-a724-0af4ae0ec719">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f0007c3-8d11-4940-8766-1112e3777aae">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c7d7162-ef19-49f4-a8fc-5db7415445a4">Internet Explorer 7</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=256bb26f-df9e-4259-881b-e8313a9fafa8">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54833350-a385-4a31-995a-9ddc38798c21">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e3a26bc5-1757-4b38-9cae-419c919f4877">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fadf6f12-1f09-4d49-93b1-8fce01400b4f">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Ei tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4446121a-0aab-4fbc-ba74-68d7650e8bca">Internet Explorer 7</a>**<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed089de4-c9ec-4ac7-a711-5f7cb29c05bc">Internet Explorer 8</a>**<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a3bbd67-94db-40b2-8786-cb39a493ec92">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>**<br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e34e4cf9-cdae-4240-8574-950c0be00822">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8960dd62-7cf7-41cb-97b2-b082bd1750aa">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46ade106-e0cb-4c71-8230-793a15062823">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>**<br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01399fc7-dc2b-461e-a1a5-751a3b61bde0">Internet Explorer 7</a>**<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd32b7c6-daa1-47aa-807f-25a678790cf2">Internet Explorer 8</a>**<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4cb870f3-9878-4075-b8fd-2ee90c8e3bc8">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>**<br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a3604f05-26b2-451b-9153-0e718158371e">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=24789423-72b7-48d1-bdc1-f0e5174d99bb">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0abc6908-ac6a-4da3-843a-af6841ccc1db">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6141a1c5-ecaf-4553-9d27-dd6e5c4a13fd">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>**<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16a8b78a-3979-4cc7-bbe5-6d962aa64336">Internet Explorer 7</a>
                    <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1243011-00e6-49f2-a676-c04cb805d36a">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8a82b44-e1d8-45f8-b8b8-b1f74e1efce0">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=057f1356-9c70-4457-a1df-69334fdab467">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr><td>Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27e767d8-84e3-434f-bb8d-3b2303774ad0">Internet Explorer 8</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3647646-658a-423b-b0cb-bba7613b67e7">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63d8b801-5178-474b-a21e-72a0ce501d3e">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf9e5ecd-68f7-4982-b4ed-be80859b757c">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=747ba56a-0d47-4946-99a4-bae1f11ea748">Internet Explorer 8</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7996511d-4b8e-49c3-a0fa-4da907a6c947">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd7d3cb9-cb60-4b62-b0df-a38fe21802e9">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2707650a-604c-4044-acc4-07a30b5640d8">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Ei tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cff7f53d-0fd6-48f8-a9d6-bf19e0a32905">Internet Explorer 8</a>**<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40354f73-4f4d-4a4a-abac-f8a3d4c3ae5f">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>**<br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e67c73ca-d0f9-40c1-8b6e-25b1b13caa3a">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9c6c36d-a455-42f7-b7d4-9fb9824c07cb">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f9824310-772d-4e1e-980e-11e2db3ac53e">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1da04414-6210-43ea-8e0a-cf21cf144076">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>**<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4dd2c0f4-b29c-4648-a123-83d3ae6a878f">Internet Explorer 8</a>
                    <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22853823-8f63-4258-8991-1ad50e58a0d9">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72d1d6b6-e8bd-492b-b65a-82060beef441">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0533d293-e186-4d39-a925-ab3d9ed46290">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              </table>


**Huomautus: Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office -ohjelmistopaketit ja -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Microsoft Office -ohjelmistopaketit ja -osat</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217502">
                      <strong>MS11-045</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr><td>Microsoft Office XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=853c0663-94f7-4634-98ad-47ca4b1f7b1e">Microsoft Excel 2002 Service Pack 3</a>
                    <br />(KB2541003)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f38f183a-9c64-406b-9bf6-807cb2d55e56">Microsoft Excel 2003 Service Pack 3</a>
                    <br />(KB2541025)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office 2007 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b271f87-a279-419f-9437-ded224fa19f1">Microsoft Excel 2007 Service Pack 2</a>
                    [1]
                    <br />(KB2541007)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2010 (32-bit edition)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=baba7ec1-4a5e-4e13-9d0e-9085a39a0554">Microsoft Excel 2010 (32-bit editions)</a>
                    <br />(KB2523021)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office 2010 (64-bit edition)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6e9f422-43b0-4da5-8356-c38482e8eebb">Microsoft Excel 2010 (64-bittiset versiot)</a>
                    <br />(KB2523021)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="3">Microsoft Office for Mac</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217502">
                      <strong>MS11-045</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2004 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d12d0868-4f28-4c0a-ab61-338878064b70">Microsoft Office 2004 for Mac</a>
                    <br />(KB2555786)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office 2008 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e2d348b-c753-4eab-838c-370cd5af5e14">Microsoft Office 2008 for Mac</a>
                    <br />(KB2555785)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office for Mac 2011</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c58555c-1eba-42fe-a10f-b30af9031e44">Microsoft Office for Mac 2011</a>
                    <br />(KB2555784)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Open XML File Format Converter for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6118d5f5-b6fd-4584-be25-209534772379">Open XML File Format Converter for Mac</a>
                    <br />(KB2555787)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="3">Microsoft InfoPath</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217502">
                      <strong>MS11-045</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft InfoPath 2007 Service Pack 2</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88eedb0b-a2cf-4a1b-b1b9-0b2926c25872">Microsoft InfoPath 2007 Service Pack 2</a>
                    <br />(KB2510061)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft InfoPath 2010 (32-bit editions)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90ffe910-bd9c-48aa-8007-2b43e1a99999">Microsoft InfoPath 2010 (32-bit editions)</a>
                    <br />(KB2510065)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft InfoPath 2010 (64-bit editions)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3244003-fb63-44d8-bedc-6399c39aacba">Microsoft InfoPath 2010 (64-bit editions)</a>
                    <br />(KB2510065)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="3">Muu Office-ohjelmisto</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217502">
                      <strong>MS11-045</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr><td>Microsoft Excel Viewer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77c1e7e2-207f-46fd-81f2-43a25eddc010">Microsoft Excel Viewer Service Pack 2</a>
                    <br />(KB2541015)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3512a033-871d-49ec-a8d2-1b9c7dec4936">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2</a>
                    <br />(KB2541012)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              </table>


**Huomautus: MS11-045**

\[1\]Jos käyttäjällä on Microsoft Office Excel 2007 Service Pack 2, hänen on asennettava tietoturvapäivityksen KB2541007 lisäksi Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2:n tietoturvapäivitys (KB2541012). Vain tällä tavoin järjestelmä voidaan suojata tässä tiedotteessa kuvatuilta haavoittuvuuksilta.

**Huomautus: MS11-049**

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

#### Microsoft Server -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft SQL Server</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>SQL Server 2005 Service Pack 3</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e">SQL Server 2005 Service Pack 3</a><br />(KB2494113)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867">SQL Server 2005 Service Pack 3</a><br />(KB2494112)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2005 x64 Edition Service Pack 3</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e">SQL Server 2005 x64 Edition Service Pack 3</a><br />(KB2494113)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867">SQL Server 2005 x64 Edition Service Pack 3</a><br />(KB2494112)<br />(Tärkeä)</td></tr>
                <tr><td>SQL Server 2005 for Itanium-based Systems Service Pack 3</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e">SQL Server 2005 for Itanium-based Systems Service Pack 3</a><br />(KB2494113)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867">SQL Server 2005 for Itanium-based Systems Service Pack 3</a><br />(KB2494112)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2005 Service Pack 4</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad">SQL Server 2005 Service Pack 4</a><br />(KB2494120)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57">SQL Server 2005 Service Pack 4</a><br />(KB2494123)</td></tr>
                <tr><td>SQL Server 2005 x64 Edition Service Pack 4</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad">SQL Server 2005 x64 Edition Service Pack 4</a><br />(KB2494120)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57">SQL Server 2005 x64 Edition Service Pack 4</a><br />(KB2494123)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2005 for Itanium-based Systems Service Pack 4</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad">SQL Server 2005 for Itanium-based Systems Service Pack 4</a><br />(KB2494120)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57">SQL Server 2005 for Itanium-based Systems Service Pack 4</a><br />(KB2494123)<br />(Tärkeä)</td></tr>
                <tr><td>SQL Server 2005 Express Edition Service Pack 3</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e">SQL Server 2005 Express Edition Service Pack 3</a><br />(KB2494113)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867">SQL Server 2005 Express Edition Service Pack 3</a><br />(KB2494112)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2005 Express Edition Service Pack 4</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad">SQL Server 2005 Express Edition Service Pack 4</a><br />(KB2494120)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57">SQL Server 2005 Express Edition Service Pack 4</a><br />(KB2494123)<br />(Tärkeä)</td></tr>
                <tr><td>SQL Server 2005 Express Edition ja Advanced Services Service Pack 3</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e">SQL Server 2005 Express Edition ja Advanced Services Service Pack 3</a><br />(KB2494113)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867">SQL Server 2005 Express Edition ja Advanced Services Service Pack 3</a><br />(KB2494112)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2005 Express Edition ja Advanced Services Service Pack 4</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad">SQL Server 2005 Express Edition ja Advanced Services Service Pack 4</a><br />(KB2494120)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57">SQL Server 2005 Express Edition ja Advanced Services Service Pack 4</a><br />(KB2494123)<br />(Tärkeä)</td></tr>
                <tr><td>SQL Server Management Studio Express (SSMSE) 2005</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34c3ba21-b158-4e6d-82ba-831053d41161">SQL Server Management Studio Express (SSMSE) 2005</a><br />(KB2546869)<br />(Tärkeä)<br /><br />QFE-päivitys:<br />Ei käytössä</td></tr>
                <tr class="alternateRow"><td>SQL Server Management Studio Express (SSMSE) 2005 x64 Edition</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34c3ba21-b158-4e6d-82ba-831053d41161">SQL Server Management Studio Express (SSMSE) 2005 x64 Edition</a><br />(KB2546869)<br />(Tärkeä)<br /><br />QFE-päivitys:<br />Ei käytössä</td></tr>
                <tr><td>SQL Server 2008 for 32-bit Systems Service Pack 1</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c">SQL Server 2008 for 32-bit Systems Service Pack 1</a><br />(KB2494096)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c">SQL Server 2008 for 32-bit Systems Service Pack 1</a><br />(KB2494100)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2008 for x64-based Systems Service Pack 1</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c">SQL Server 2008 for x64-based Systems Service Pack 1</a><br />(KB2494096)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c">SQL Server 2008 for x64-based Systems Service Pack 1</a><br />(KB2494100)<br />(Tärkeä)</td></tr>
                <tr><td>SQL Server 2008 for Itanium-based Systems Service Pack 1</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c">SQL Server 2008 for Itanium-based Systems Service Pack 1</a><br />(KB2494096)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c">SQL Server 2008 for Itanium-based Systems Service Pack 1</a><br />(KB2494100)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2008 for 32-bit Systems Service Pack 2</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276">SQL Server 2008 for 32-bit Systems Service Pack 2</a><br />(KB2494089)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91">SQL Server 2008 for 32-bit Systems Service Pack 2</a><br />(KB2494094)<br />(Tärkeä)</td></tr>
                <tr><td>SQL Server 2008 for x64-based Systems Service Pack 2</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276">SQL Server 2008 for x64-based Systems Service Pack 2</a><br />(KB2494089)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91">SQL Server 2008 for x64-based Systems Service Pack 2</a><br />(KB2494094)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2008 for Itanium-based Systems Service Pack 2</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276">SQL Server 2008 for Itanium-based Systems Service Pack 2</a><br />(KB2494089)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91">SQL Server 2008 for Itanium-based Systems Service Pack 2</a><br />(KB2494094)<br />(Tärkeä)</td></tr>
                <tr><td>SQL Server 2008 R2 for 32-bit Systems</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41">SQL Server 2008 R2 for 32-bit Systems</a><br />(KB2494088)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4">SQL Server 2008 R2 for 32-bit Systems</a><br />(KB2494086)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2008 R2 for x64-based Systems</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41">SQL Server 2008 R2 for x64-based Systems </a><br />(KB2494088)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4">SQL Server 2008 R2 for x64-based Systems </a><br />(KB2494086)<br />(Tärkeä)</td></tr>
                <tr><td>SQL Server 2008 R2 for Itanium-based Systems</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41">SQL Server 2008 R2 for Itanium-based Systems </a><br />(KB2494088)<br />(Tärkeä)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4">SQL Server 2008 R2 for Itanium-based Systems </a><br />(KB2494086)<br />(Tärkeä)</td></tr>
              </table>


**Huomautus: MS11-049**

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

#### Microsoft-kehitystyökalut ja ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Microsoft Silverlight</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr><td>Microsoft Silverlight 4 </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8">Microsoft Silverlight 4</a> asennettuna Macintosh-järjestelmään<br />(KB2512827)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8">Microsoft Silverlight 4</a> asennettuna Microsoft Windows -asiakkaaseen<br />(KB2512827)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8">Microsoft Silverlight 4</a> asennettuna Microsoft Windows -palvelimeen**<br />(KB2512827)<br />(Kriittinen)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="3">Microsoft Visual Studio</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio 2005 Service Pack 1</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5ce8a9a-e89b-4095-9f21-7e6f307fbf2b">Microsoft Visual Studio 2005 Service Pack 1</a>
                    <br />(KB2251481)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Visual Studio 2008 Service Pack 1</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cc01bce9-3f38-4590-9c6e-a4048c886d33">Microsoft Visual Studio 2008 Service Pack 1</a>
                    <br />(KB2251487)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio 2010 </td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=213b820f-dcba-4895-b339-b50eeb92524d">Microsoft Visual Studio 2010</a>
                    <br />(KB2251489)<br />(Tärkeä)</td></tr>
              </table>


**Huomautukset: MS11-039**

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

**Huomautus: MS11-049**

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

#### Microsoft-tietoturvaohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Forefront</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217470">
                      <strong>MS11-040</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Forefront Threat Management Gateway 2010 -asiakas</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1c85acd-a6df-4634-9cd4-c562ad92097e">Microsoft Forefront Threat Management Gateway 2010 -asiakas</a>
                    <br />(Kriittinen)</td></tr>
              </table>


## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)- ja [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) -sivustoista. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Microsoft Office for Mac -käyttäjät: Microsoft AutoUpdate for Mac helpottaa Microsoft-ohjelmiston pitämistä ajan tasalla. Lisätietoja Microsoft AutoUpdate for Macin käyttämisestä on [ohjelmistopäivitysten automaattista tarkistamista](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) käsittelevällä sivulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut ohjeita tietoturvapäivitysten tunnistamiseen ja käyttöönottamiseen. Ohjeisiin sisältyy suosituksia ja tietoja, joiden avulla IT-ammattilaiset oppivat tunnistamaan ja ottamaan käyttöön tietoturvapäivityksiä erilaisilla työkaluilla. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Microsoft Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Microsoft Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx) -sivustossa.

**System Center Configuration Mana** **ger 2007**

Configuration Manager 2007:n ohjelmistopäivitysten hallinta yksinkertaistaa päivitysten toimittamista yrityksen eri IT-järjestelmiin sekä niiden hallintaa. Configuration Manager 2007 auttaa järjestelmänvalvojia toimittamaan Microsoft-tuotteiden päivitykset niin työasemiin, kannettaviin, palvelimiin kuin mobiililaitteisiinkin.

Configuration Manager 2007:n automatisoitu haavoittuvuuksien arviointi havaitsee päivitystarpeet ja tekee raportin suositeltavista toimista. Configuration Manager 2007:n ohjelmistopäivitysten hallinta perustuu Microsoftin WSUS (Windows Software Update Services) -palveluihin, ja eri puolilla maailmaa toimivat järjestelmänvalvojat tuntevat tämän aikatestatun päivitysinfrastruktuurin. Lisätietoja tavoista, joilla järjestelmänvalvojat voivat ottaa päivityksiä käyttöön Configuration Manager 2007:n avulla, on [ohjelmistopäivitysten hallintaa](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) käsittelevässä sivustossa. Lisätietoja Configuration Managerissa on sivustossa [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän.

**Huomautus** System Management Server 2003:n yleinen tuki päättyi 12.1.2010. Lisätietoja tuotteiden elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) -sivustossa. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso myös edellä oleva kohta **System Center Configuration Manager 2007**.

Lisätietoja tavoista, joilla järjestelmänvalvojat voivat ottaa päivityksiä käyttöön SMS 2003:n avulla, on artikkelissa [Microsoft Systems Management Server 2003:n skenaarioita ja menetelmiä: ohjelmistojen jakaminen ja korjauspäivitysten hallinta](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (englanninkielinen). Lisätietoja SMS:stä on [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx) -sivustossa.

**Huomautus** SMS tukee tietoturvapäivitysten kattavaa tunnistamista ja käyttöönottoa Microsoft Baseline Security Analyzer -työkalulla. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat asentaa nämä päivitykset käyttämällä Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

**Update Compatibility Evalua** **tor ja Application Compatibility Toolkit**

Päivitykset usein kirjoittavat samoihin tiedostoihin ja rekisteriasetuksiin, joita tarvitaan sovelluksia käytettäessä. Tämä voi aiheuttaa yhteensopivuusongelmia ja pidentää aikaa, joka kuluu tietoturvapäivitysten käyttöönottamiseen. Voit tehostaa Windows-päivitysten testaamista ja tarkistamista asennetuissa sovelluksissa käyttämällä [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) -osia, jotka sisältyvät [Application Compatibility Toolkitiin](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Sovellusten yhteensopivuustyökalu sisältää työkalut ja ohjeistuksen, joilla voi arvioida ja lieventää sovellusten yhteensopivuusongelmia ennen Microsoft Windows Vistan, Windowsin päivityksen, Microsoftin tietoturvapäivitysten tai Windows Internet Explorerin uuden versioon käyttöönottoa ympäristössäsi.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa: Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tietoja Windows Update- ja Microsoft Update -sivustoissa julkaistavista päivityksistä, jotka eivät ole tietoturvapäivityksiä:

  - [Microsoft Knowledge Base -artikkeli 894199](http://support.microsoft.com/kb/894199): Kuvaus Software Update Services- ja Windows Server Update Services -sisällön muutoksista. Sisältää kaiken Windows-sisällön.
  - [Windows Server Update Services -palvelun aiemmin toimittamat päivitykset](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (englanninkielinen). Näyttää kaikki uudet, muokatut ja uudelleenulkaistut Microsoft-tuotteiden päivitykset Microsoft Windowsia lukuun ottamatta.

#### Microsoft Active Protections Program (MAPP)

Microsoft haluaa parantaa asiakkaittensa tietoturvasuojauksia tarjoamalla haavoittuvuustietoja suurille tietoturvaohjelmistojen valmistajille ennen joka kuukausi julkaistavan tietoturvapäivityksen julkaisemista. Tietoturvaohjelmistojen valmistajat voivat sitten päivittää näiden haavoittuvuustietojen perusteella asiakkailleen tarjoamiaan tietoturvaohjelmistoja tai laitteita. Tällaisia ovat esimerkiksi viruksentorjunta, verkkopohjaiset tunkeutumisen havaintojärjestelmät ja isäntäpohjaiset tunkeutumisenestojärjestelmät. Voit selvittää, mitä aktiivisia suojauksia tietoturvaohjelmistojen toimittajilla on tarjolla, tutustumalla ohjelman kumppanien ylläpitämiin aktiivisen suojauksen sivustoihin. Nämä kumppanit ovat [MAPP (Microsoft Active Protections Program) -kumppaneita](http://go.microsoft.com/fwlink/?linkid=215201).

#### Tietoturvastrategiat ja yhteisö

**Korjaustiedostojen hallintamenetelmät**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivitysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - Yamata Li ([Palo Alto Networks](http://www.paloaltonetworks.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-038
  - Michael J. Liu ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-039
  - Koro ( [www.korosoft.net](http://www.korosoft.net/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-041
  - Laurent Gaffié ([NGS Software](http://www.ngssoftware.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-042
  - Dan Kaminsky teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS11-044
  - Bing Liu ([Fortinetin FortiGuard Labs](http://www.fortiguard.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-045
  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-045
  - Omair (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-045
  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-045
  - Nicolas Gregoire ([Agarri](http://www.agarri.fr/)) (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-045
  - Omair ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-045
  - Will Dormann ([CERT/CC](http://www.cert.org/)) ilmoitti kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS11-045
  - Steven Adair ([Shadowserver Foundation](http://www.shadowserver.org)) ja Chris S. ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa ms11-046
  - Nicolas Economou ([Core Security Technologies](http://www.coresecurity.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-047
  - Jesse Ou ([Cigital](http://www.cigital.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-049
  - Robert Swiecki ([Google Inc.](http://www.google.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-050
  - [NSFOCUS Security Team](http://www.nsfocus.com/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-050
  - Tuntematon tutkija (yhteistyössä [Beyond Securityn SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) -ohjelman kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-050
  - Adi Cohen ([IBM Rational Application Security](http://blog.watchfire.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-050
  - [Trend Micro](http://www.trendmicro.com/) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS11-050
  - Nirmal Singh Bhary ([Norman](http://www.norman.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-050
  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-050
  - Damian Put (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-050
  - Yoel Gluck, Yogesh Badwe ja Varun Badhwar ([salesforce.comin](http://www.salesforce.com/) tuoteturvallisuustiimi) ilmoittivat haavoittuvuudesta, joka on kuvatta tietoturvatiedotteessa MS11-050
  - Jose Antonio Vazquez Gonzalez (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-050
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-050
  - Peter Winter-Smith (yhteistyössä [Tipping Pointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-050
  - Stephen Fewer ([Harmony Security](http://www.harmonysecurity.com/) yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) teki yhteistyötä kanssamme kehittääkseen tietoturvaa koskevia muutoksia. Tämä haavoittuvuus on kuvattu tietoturvatiedotteessa MS11-050
  - Ruggero Strabla ([Emaze](http://www.emaze.net/) Networks, [Saipem Security Team](http://www.saipem.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-051
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-052

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [tietoturvapalvelu](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia. Lisätietoja saatavissa olevista tukivaihtoehdoista on [Microsoftin Ohjeessa ja tuessa](http://support.microsoft.com/).
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (14. kesäkuuta 2011): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (14. kesäkuuta 2011): Tietoturvatiedotteen MS11-042 **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -osiosta poistettiin Windows 7 for 32-bit Systems Service Pack 1, Windows 7 for x64-based Systems Service Pack 1, Windows Server 2008 R2 for x64-based Systems Service Pack 1 ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1. Tämä on vain tiedonanto. Tietoturvapäivityksen tiedostoja tai tunnistustietoja ei muutettu.

*Built at 2014-04-18T01:50:00Z-07:00*

