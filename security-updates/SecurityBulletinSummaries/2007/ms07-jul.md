---
title: Microsoftin turvatiedotteiden yhteenveto, heinäkuu 2007
TOCTitle: MS07-JUL
ms:assetid: ms07-jul
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms07-jul(v=Security.10)
ms:contentKeyID: 61225586
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, heinäkuu 2007

Julkaistu: 10. heinäkuuta 2007

**Versio:** 1.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo heinäkuussa 2007 julkaistuista tietoturvatiedotteista.

Heinäkuun 2007 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 7. heinäkuuta 2007. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Lisätietoja automaattisen ilmoituksen saamisesta aina, kun Microsoftin tietoturvatiedote julkaistaan, on [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) -sivustossa.

Microsoft isännöi web-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Web-lähetyksen ajankohta on heinäkuun 11. 2007, kello 11.00 Tyynenmeren aikaa (USA ja Kanada). [Rekisteröidy nyt heinäkuun tietoturvatiedotteen web-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032343783&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen web-lähetyksen voi pyytää katsottavaksi. Lisätietoja on [Microsoftin tietoturvatiedotteista ja web-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät, muut kuin tietoturvapäivitykset, jotka julkaistaan samana päivänä kuin kuukausittain julkaistavat tietoturvapäivitykset. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (3)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-036</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=93447"><strong>Microsoft Excelin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (936542)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen päivitys korjaa julkistetun haavoittuvuuden ja kaksi yksityishenkilöiden ilmoittamaa haavoittuvuutta sekä muita tutkimuksen aikana havaittuja tietoturvaongelmia. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Excel-tiedoston. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Office, Excel</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-039</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=93365"><strong>Windows Active Directoryn haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (926122)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen päivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden Active Directory -toteutuksissa Windows 2000 Server- ja Windows Server 2003 -käyttöjärjestelmissä. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä tai aiheuttaa palveluneston. Tätä haavoittuvuutta hyödyntävät hyökkäykset johtavat todennäköisesti palvelunestoon. Koodin suorittaminen verkon välityksellä saattaa kuitenkin olla mahdollista. Windows Server 2003 -käyttöjärjestelmässä haavoittuvuuden hyödyntäminen edellyttää, että hyökkääjällä on voimassa olevat kirjautumistiedot. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia, tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-040</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=91233"><strong>.NET Frameworkin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (931212)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä päivitys korjaa kolme yksityishenkilöiden ilmoittamaa haavoittuvuutta. Kaksi näistä haavoittuvuuksista saattaa sallia koodin suorittamisen verkon välityksellä asiakasjärjestelmissä, joissa on asennettuna .NET Framework. Yksi haavoittuvuuksista saattaa sallia tietojen paljastumisen muille käyttäjille web-palvelimilla, joissa on käynnissä ASP.NET. Koodin suorittaminen verkon välityksellä vaikuttaa kaikissa tapauksissa vähemmän sellaisiin käyttäjiin, joilla on rajoitetut oikeudet, kuin käyttäjiin, joilla on järjestelmänvalvojan oikeudet.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>.NET Framework</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (2)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-037</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=93448"><strong>Microsoft Office Publisherin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (936548)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa yhden julkistetun haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua Microsoft Office Publisher -tiedostoa. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Tämän haavoittuvuuden hyödyntäminen edellyttää käyttäjän toimia.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Office, Publisher</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-041</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=93706"><strong>Microsoft Internet Information Services -osan haavoittuvuus</strong> <strong>saattaa sallia koodin suorittamisen verkon välityksellä (939373)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä lähettää tietyllä tavalla muodostettuja URL-pyyntöjä Internet Information Services (IIS) 5.1 -järjestelmää käyttävälle web-sivulle Windows XP Professional Service Pack 2 -käyttöjärjestelmässä. IIS 5.1 ei sisälly Windows XP Professional Service Pack 2 -ohjelmaan. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows XP Professional</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Keskitaso (1)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-038</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotte</strong> <strong>en otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=91033"><strong>Windows Vistan palomuurin haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille (935807)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä keskitasoinen tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Tämä haavoittuvuus saattaa sallia sen, että tuleva aiheeton verkkoliikenne käyttää verkkoliittymää. Hyökkääjä voi mahdollisesti kerätä tietoja hyökkäyksen kohteena olevasta isännästä.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Keskitaso</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Tietojen paljastuminen muille käyttäjille</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows Vista</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

**Miten taulukkoa käytetään?**

Tämän taulukon avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja edellyttääkö se tietoturvapäivityksen asentamista. Kunkin mainitun ohjelman tai osan yhteydessä näkyy haavoittuvuuden vaikutus ja linkki saatavana oleviin ohjelmistopäivityksiin.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää useiden tietoturvapäivitysten asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

**Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
  </tr>
            <tr><td>
                <strong>Tiedotteen numero</strong>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=93447">
                  <strong>MS07-036</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=93448">
                  <strong>MS07-037</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=91033">
                  <strong>MS07-038</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=93365">
                  <strong>MS07-039</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=91233">
                  <strong>MS07-040</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=93706">
                  <strong>MS07-041</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td>
                <strong>Korkein luokitustaso</strong>
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
                  <strong>Keskitaso</strong>
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
              </td></tr>
          
            <tr><th colspan="7">Windows-käyttöjärjestelmät, joita haavoittuvuus koskee</th></tr>
          
            <tr><td>Windows 2000 Service Pack 4</td><td /><td /><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows 2000 Server Service Pack 4</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=812e62c5-6e19-4b3b-8a10-861b871e1b41">Kriittinen</a>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Windows XP Service Pack 2</td><td /><td /><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Professional Service Pack 2</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fccbfe90-f838-47df-8310-352e2fb47132">Tärkeä</a>
              </td></tr>
            <tr><td>Windows XP Professional x64 Edition</td><td /><td /><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Windows Server 2003 Service Pack 1</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28e84603-8159-4429-aaff-a1020531e84f">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28e84603-8159-4429-aaff-a1020531e84f">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Server 2003 x64 Edition</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=107902f9-be94-457f-a936-519efbd64779">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=107902f9-be94-457f-a936-519efbd64779">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Windows Server 2003 with SP1 for Itanium-based Systems</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Itanium-järjestelmien Windows Server 2003 ja SP2</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Windows Vista</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9b64746-6afa-4a30-833d-e058e000c821">Keskitaso</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vista x64</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0df5d190-3ad7-42d5-8629-43c47ec450cb">Keskitaso</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
          
            <tr><th colspan="7">Windows-käyttöjärjestelmien osat, joita haavoittuvuus koskee</th></tr>
          
            <tr><td>Microsoft .NET Framework 1.0<br />(KB928367)</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91d7afe4-069b-4ce8-976e-9a01345a8603">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Microsoft .NET Framework 1.0<br />(KB930494)</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=829a2c5b-11ec-4ed7-91ab-6961034147bc">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Microsoft .NET Framework 1.1<br />(KB928366)</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=281fb2cd-c715-4f05-a01f-0455d2d9ebfb">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Microsoft .NET Framework 1.1<br />(KB933854)</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2495e656-1e0a-4b83-90da-821e68067a71">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Microsoft .NET Framework 1.1<br />(KB929729)</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7eea368d-7b82-4583-8537-30351718a4e9">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Microsoft .NET Framework 2.0<br />(KB928365)</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba3ceb78-8e1b-4c38-adfd-e8bc95ae548d">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Microsoft .NET Framework 2.0<br />(KB929916)</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cbc9f3cf-c3c3-45c4-82e3-e11398bc2cd2">Kriittinen</a>
              </td><td /></tr>
          
            <tr><th colspan="7">Office-ohjelmistot, joita haavoittuvuus koskee</th></tr>
          
            <tr class="alternateRow"><td>Excel 2000 Service Pack 3</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=83d94d8e-dda6-4d74-b40d-476c2f0a3af4">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td>Excel 2003 Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d93c0ce-5124-4234-ba84-3c27005e010f">Tärkeä</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Excel 2003 Viewer</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11f42977-8828-494a-a183-d1aba827b708">Tärkeä</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td>Excel 2007</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ab28283-0320-4527-b033-5e80ef32cd34">Tärkeä</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Office-yhteensopivuuspaketti</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e592ae5b-09ac-4f5b-b457-a54c9850ad4a">Tärkeä</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td>Publisher 2007</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25d272e7-f2dd-4342-92be-7ebc2e770b44">Tärkeä</a>
              </td><td /><td /><td /><td /></tr>
          </table>


**Huomautuksia**

**\[1\]** Tähän käyttöjärjestelmään on saatavana tietoturvapäivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa. 

****

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security\_patch" avulla. Tietoturvapäivitykset voidaan ladata lisäksi Windows Update Catalog -palvelusta. Lisätietoja Windows Update Catalogista on [Microsoft Knowledge Base -artikkelissa 323166](http://support.microsoft.com/kb/323166).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla myös IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin, laajennettu Inventory-työkalu ja Enterprise Update Scan (EST) -työkalu. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline** **Security Analyzer ja Enterprise Update Scan Tool**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

Kun MBSA 1.2.1 ei tue tietyn tietoturvapäivityksen tunnistamista, Microsoft julkaisee kyseistä tietoturvapäivitystä varten EST (Enterprise Update Scan Tool) -version. Lisätietoja EST-tarkistustyökalusta on sivustossa [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193).

**Huomautus** MBSA 1.2.1:n käyttämää MSSecure.XML-tiedostoa ei päivitetä 9.10.2007 jälkeen. Tämän päivämäärän jälkeen uusia tietoturvapäivityksiä ei lisätä MBSA 1.2.1:n käyttämän MSSecure.XML-tiedostoon eikä Enterprise Scan Tool -tarkistustyökalusta julkaista enää uusia versioita. Lisätietoja on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Software Update Services**

Microsoft Software Update Services (SUS) -palvelun avulla järjestelmänvalvojat voivat ottaa käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset nopeasti ja luotettavasti Windows 2000- ja Windows Server 2003 -pohjaisissa palvelimissa sekä työasemissa, joissa on Windows 2000 Professional- tai Windows XP Professional -käyttöjärjestelmä.

Lisätietoja tämän tietoturvapäivityksen ottamisesta käyttöön Software Update Services -palvelun avulla on [Software Update Services](http://go.microsoft.com/fwlink/?linkid=21133) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939)-sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

Huomaa, että tätä työkalua **ei** jaeta Software Update Services (SUS) -palvelun kautta.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU-, WSUS- ja SUS-sivustoissa

Tässä kuussa:

  - Microsoft on julkaissut neljä tärkeää päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**, MU (Microsoft Update)- ja WSUS (Windows Server Update Services) -sivustoissa.
  - Microsoft on julkaissut yhden Windows-päivityksen, **joka ei kuitenkaan ole tietoturvapäivitys**, WU (Windows Update)- ja SUS (Software Update Services) -sivustoissa.

Huomaa, että nämä tiedot koskevat **vain** sellaisia tärkeitä päivityksiä, **jotka eivät ole tietoturvapäivityksiä** ja jotka julkaistaan saman päivänä kuin tietoturvatiedotteiden yhteenveto Microsoft Update-, Windows Update-, Windows Server Update Services- ja Software Update Services -sivustoissa. Tietoja **ei** julkaista muina päivinä julkaistavista päivityksistä, **jotka eivät ole tietoturvapäivityksiä**.

#### Tietoturvastrategiat ja yhteisö

**Korjaustiedostojen hallintamenetelmät**

[Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivitysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan security\_patch avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - Dinis Cruz ([OWASP](http://www.owasp.org/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - Paul Craig ([Security Assessment](http://www.smsiinc.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - Jeroen Frijters ([Sumatra](http://www.sumatra.nl/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - [ProCheckUp](http://www.procheckup.com/) yhteistyössä [UK CPNIn](http://www.cpni.gov.uk/) kanssa ilmoitti ensimmäisenä haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - Ferruh T. Mavituna ([Portcullis Computer Security Ltd.](http://www.portcullis-security.com/)) teki yhteistyötä Microsoftin kanssa ja antoi lisätietoja haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - Johannes Gumbel ([TrueSec](http://www.truesec.com/)) teki yhteistyötä Microsoftin kanssa ja antoi lisätietoja haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - Peter Winter-Smith ([NGSSoftware](http://www.nextgenss.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS06-039](http://go.microsoft.com/fwlink/?linkid=93365).
  - Neel Mehta ([IBM Internet Security Systems x-Force](http://xforce.iss.net/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-039](http://go.microsoft.com/fwlink/?linkid=93365).
  - [eEye](http://www.eeye.com/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-037](http://go.microsoft.com/fwlink/?linkid=93488).
  - Jim Hoagland ja Ollie Whitehouse ([Symantec](http://www.symantec.com/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-038](http://go.microsoft.com/fwlink/?linkid=91033).
  - Jonathan Afek ja Adi Sharabani ([Watchfire](http://www.watchfire.com/)) tekivät yhteistyötä Microsoftin kanssa ja antoivat lisätietoja haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-041](http://go.microsoft.com/fwlink/?linkid=93706).
  - Peter Winter-Smith ([NGSSoftware](http://www.nextgenss.com/)) teki yhteistyötä Microsoftin kanssa ja antoi lisätietoja haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-041](http://go.microsoft.com/fwlink/?linkid=93706).

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (10. heinäkuuta 2007): Tietoturvatiedotteen yhteenveto julkaistu.

*Built at 2014-04-18T01:50:00Z-07:00*

