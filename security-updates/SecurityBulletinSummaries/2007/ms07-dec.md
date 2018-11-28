---
title: Microsoftin turvatiedotteiden yhteenveto, joulukuu 2007
TOCTitle: MS07-DEC
ms:assetid: ms07-dec
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms07-dec(v=Security.10)
ms:contentKeyID: 61225583
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, joulukuu 2007

Julkaistu: 11. joulukuuta 2007 | Päivitetty: 16. heinäkuuta 2008

**Versio:** 2.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo joulukuussa 2007 julkaistuista tietoturvatiedotteista.

Joulukuun 2007 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 6. joulukuuta 2007. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 12. joulukuuta 2007, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt joulukuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344696&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (3)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-064</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104988"><strong>DirectX:n haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (941568)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa kaksi suoraan Microsoftille ilmoitettua Microsoft DirectX:n haavoittuvuutta. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen, jos käyttäjä avaa tietyllä tavalla muotoillun tiedoston DirectX-sovelluksessa. Jos käyttäjä on kirjautuneena järjestelmään järjestelmänvalvojan oikeuksin, tätä haavoittuvuutta hyödyntämään onnistuva hyökkääjä saattaa saada haavoittuvuuden sisältävän järjestelmän täysin hallintaansa. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen, paitsi tietyissä tilanteissa.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows, DirectX, DirectShow.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-068</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=99075"><strong>Window</strong> <strong>s-mediatiedostomuodon haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (941569 ja 944275)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa suoraan Microsoftille ilmoitetun Windows Media Formatin haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee erityisesti muodostettua tiedostoa Windows Media Format Runtimessa. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen, paitsi tietyissä tilanteissa.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita ha</strong> <strong>avoittuvuus koskee</strong></td>
<td><strong>Windows, Windows Media Format Runtime. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-069</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=101160"><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (942615)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa neljä suoraan Microsoftille ilmoitettua haavoittuvuutta. Vakavin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun web-sivun Internet Explorerissa. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows, Internet Explorer. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (4)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-063</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104920"><strong>SMBv2:n haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (942624)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa suoraan Microsoftille ilmoitetun ilmoittaman Server Message Block Version 2:n (SMBv2) haavoittuvuuden. Tämä haavoittuvuus voi antaa hyökkääjälle mahdollisuuden käsitellä SMBv2:n kautta siirrettäviä tietoja, mikä puolestaan saattaa sallia koodin suorittamisen verkon välityksellä.</td>
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
<td><strong>Ohjelmistot, joita haavoittuvuus</strong> <strong>koskee</strong></td>
<td><strong>Windows. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-065</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94666"><strong>Message Queuing -haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (937894)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa suoraan Microsoftille ilmoitetun Message Queuing Servicen (MSMQ) haavoittuvuuden, joka saattaa sallia koodin suorittamisen verkon välityksellä Microsoft Windows 2000 Server -järjestelmissä tai käyttöoikeuksien korottamisen Microsoft Windows 2000 Professional ja Windows XP -järjestelmissä. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet, ennen kuin hän pystyy hyödyntämään käyttöoikeuksien korottamisen mahdollistavaa haavoittuvuutta Microsoft Windows 2000 Professional tai Windows XP -käyttöjärjestelmässä. Tällöin hyökkääjä voi asentaa ohjelmia, tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä.</td>
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
<td><strong>Windows. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-066</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104898"><strong>Wi</strong> <strong>ndows-ytimen haavoittuvuus saattaa aiheuttaa käyttöoikeuksien laajentumisen (943078)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa suoraan Microsoftille ilmoitetun ilmoittaman Windows-ytimen haavoittuvuuden. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda tilejä kaikilla valtuuksilla.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Käyttöoikeuksien korottaminen</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-067</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104987"><strong>Macrovision-ohjaimen haavoittuvuus saattaa sallia paikallisen käyttöoikeuksien laajentumisen (944653)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa yhden julkistetun haavoittuvuuden. Tavassa, jolla Macrovision-ohjain käsittelee virheellisesti määritysparametreja, on paikallisen käyttöoikeuksien korottumisen mahdollistama haavoittuvuus. Hyödyntämällä tätä haavoittuvuutta onnistuneesti paikallinen hyökkääjä voi saada järjestelmän kokonaan hallintaansa. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Paikallinen käyttöoikeuksien laajentuminen</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
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
    <th>Tiedot        </th>
  </tr>
            <tr><td>
                <strong>Tiedotteen numero</strong>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=104920">
                  <strong>MS07-063</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=104988">
                  <strong>MS07-064</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=94666">
                  <strong>MS07-065</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=104898">
                  <strong>MS07-066</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=104987">
                  <strong>MS07-067</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=99075">
                  <strong>MS07-068</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=101160">
                  <strong>MS07-069</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td>
                <strong>Luokitus</strong>
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
                  <strong>Kriittinen</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Kriittinen</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="8">Windows-käyttöjärjestelmä</th></tr>
          
            <tr><td>Microsoft Windows 2000 Server Service Pack 4 ja Microsoft Windows 2000 Professional Service Pack 4</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bda9d0b4-f7cb-4d9d-b030-043d7437734b">Tärkeä</a>
              </td><td /><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09d4e6ae-5d19-4f11-bb7e-60cee8263bc8">Keskitaso</a>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7d368d0-f7bf-4946-a4a6-3e88315e5317">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Windows XP Professional x64 Edition</td><td /><td>
                <strong>[1]</strong>
              </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f4fa8e9-fcf2-4daf-93c0-8bb267da69aa">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                <strong>[1]</strong>
              </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f4fa8e9-fcf2-4daf-93c0-8bb267da69aa">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Windows Server 2003 Service Pack 1</td><td /><td>
                <strong>[1]</strong>
              </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f84f5e2-1dd8-4882-b796-444ab70b6b02">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td /><td>
                <strong>[1]</strong>
              </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f84f5e2-1dd8-4882-b796-444ab70b6b02">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Server 2003 x64 Edition</td><td /><td>
                <strong>[1]</strong>
              </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f416b71-783f-4cbc-9b85-9a9be7daa0d7">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td /><td>
                <strong>[1]</strong>
              </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f416b71-783f-4cbc-9b85-9a9be7daa0d7">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Windows Server 2003 with SP1 for Itanium-based Systems</td><td /><td>
                <strong>[1]</strong>
              </td><td /><td /><td /><td /><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td>
                <strong>[1]</strong>
              </td><td /><td /><td /><td /><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Windows Vista</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d22a9ee-cc08-4b2d-af4e-55d326f82761">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9787619f-1297-411e-8b9c-3ad3e6a99797">Tärkeä</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05a9501c-4da3-4fa1-901e-99cb262e5e36">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f382050-8df6-43aa-82e9-8fad5ff8ecec">Tärkeä</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
          
            <tr><th colspan="8">Windows-käyttöjärjestelmien osat</th></tr>
          
            <tr><td>Microsoft Windows 2000 Service Pack 4 ja DirectX 7.0</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06196774-5a11-4525-b53c-8cb000738949">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Microsoft Windows 2000 Service Pack 4 ja DirectX 8.1</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ccb872bd-fc06-4a3f-ac70-3c9a42d57b37">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td>Microsoft Windows 2000 Service Pack 4 ja DirectX 9.0</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03b14ce0-5189-4803-8151-6ac5cb6a9179">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2 ja DirectX 9.0</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04a8f8d3-69f9-4445-baab-f45616a6b9b7">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td>Windows XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2 ja DirectX 9.0</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f096c500-e765-4e75-8443-7ffec4ddf149">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2 ja DirectX 9.0</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d80a295a-baf9-4981-8a28-1b4207ecc5f7">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2 ja DirectX 9.0</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=378086ea-60b8-409f-970a-fcfd62025150">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systemsin ja Windows Server 2003 with SP2 for Itanium-based Systemsin DirectX 9.0</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e6ea4bb-9f4f-46fb-9d51-e20b15e61a89">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td>Windows Vistan DirectX 10.0</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfa571bc-e43f-45e3-bc98-4086985c99aa">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Editionin DirectX 10.0</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d8803da-108b-4b9d-a039-84932dce8e42">Kriittinen</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td>Internet Explorer 5.01 Service Pack 4 ja Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3bd16ea-5d69-4ae3-84b3-ab773052ceeb">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Microsoft Windows 2000 Service Pack 4 ja Internet Explorer 6 Service Pack 1</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc8edf05-262a-4d1d-b196-4fc1a844970c">Kriittinen</a>
              </td></tr>
            <tr><td>Windows XP Service Pack 2 ja Internet Explorer 6</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e4ebafc-34c3-4dc7-b712-152c611d3f0a">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Editionin Internet Explorer 6 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5a5af23-30fb-4e47-94bd-3b05b55c92f2">Kriittinen</a>
              </td></tr>
            <tr><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2 ja Internet Explorer 6</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf466060-a585-4c2e-a48d-70e080c3bbe7">Keskitaso</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2 ja Internet Explorer 6</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=074697f2-18c8-4521-bbf7-1d0e7395d27d">Keskitaso</a>
              </td></tr>
            <tr><td>Internet Explorer 6, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3f390a6-0361-4553-b627-5e7ad6bf5055">Keskitaso</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2 ja Internet Explorer 7</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b15a6506-02dd-43c2-aef4-e10c1c76ee97">Kriittinen</a>
              </td></tr>
            <tr><td>Windows XP Professional x64 Editionin Internet Explorer 7 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c092a6bb-8e62-4d90-bdb1-5f3a15968f75">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2 ja Internet Explorer 7</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34759c10-16a5-42a2-974d-9d532fb5a0a7">Keskitaso</a>
              </td></tr>
            <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2 ja Internet Explorer 7</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7dccce5a-7562-448b-a345-cf1cc758e35c">Keskitaso</a>
              </td></tr>
            <tr class="alternateRow"><td>Internet Explorer 7, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8414f3fb-216a-4d46-b590-4c1f304dff91">Keskitaso</a>
              </td></tr>
            <tr><td>Windows Vistan Internet Explorer 7</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26d303da-bb2e-4555-96f1-becb0e277341">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Editionin Internet Explorer 7</td><td /><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c5e88e0b-a4c2-4690-91d9-326800030a16">Kriittinen</a>
              </td></tr>
            <tr><td>Microsoft Windows 2000 Service Pack 4 ja Windows Media Format Runtime 7.1 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eecdf2ce-9aa7-4f0c-b62b-2fa7a32f369e">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Microsoft Windows 2000 Service Pack 4 ja Windows Media Format Runtime 9.0 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eecdf2ce-9aa7-4f0c-b62b-2fa7a32f369e">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Windows XP Service Pack 2 ja Windows Media Format Runtime 9.0 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2 ja Windows Media Format Runtime 9.5 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Windows XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2 ja Windows Media Format Runtime 9.5 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81f20b45-dfc7-4ddf-a4b4-6c0e9476ed51">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2 ja Windows Media Format Runtime 9.5 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8fea7da8-a7f3-4786-97c2-fb5ea7018159">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2 ja Windows Media Format Runtime 9.5 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffc69c76-02f1-4b15-8ec1-dab8c7e33bd4">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2 ja Windows Media Format Runtime 9.5 x64 Edition (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffc69c76-02f1-4b15-8ec1-dab8c7e33bd4">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Windows XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2 ja Windows Media Format Runtime 9.5 x64 Edition (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72d2ca0e-da81-45ee-9321-4970b80f4a5a">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2 ja Windows Media Format Runtime 11 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Windows XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2 ja Windows Media Format Runtime 11 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1037b224-ac89-4efd-b189-6f3da77a88e6">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vistan Windows Media Format Runtime 11 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a98ef96-bc2e-42b7-9a24-c82c8fb379db">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Windows Vista x64 Editionin Windows Media Format Runtime 11 (KB941569)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ce02c95-d695-4f14-9fb3-30c83a9cfb9c">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2 ja Windows Media Services 9.1 (KB944275)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=096711d4-ce01-45d0-9c2d-ebfa5c671b9f">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2 ja Windows Media Services 9.1 x64 Edition (KB944275)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23c23800-5aaa-455b-96bf-4ead4dfdd95d">Kriittinen</a>
              </td><td /></tr>
          </table>


**Huomautuksia**

**\[1\]** Tähän käyttöjärjestelmään on saatavana tietoturvapäivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa. 

**\* Sisältää** DirectX 9.0a:n, DirectX 9.0b:n ja DirectX 9.0c:n

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin ja laajennettu Inventory-työkalu (ESUIT). Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Micro** **soft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Huomautus** MBSA 1.2.1:n käyttämää MSSecure.XML-tiedostoa ei päivitetä 9.10.2007 jälkeen. Tämän päivämäärän jälkeen uusia tietoturvapäivityksiä ei lisätä MBSA 1.2.1:n käyttämän MSSecure.XML-tiedostoon eikä Enterprise Scan Tool -tarkistustyökalusta julkaista enää uusia versioita. Tämä ei koske SMS 2.0.n ja SMS 2003:n tietoturvapäivityksen Inventory-työkalua (SUIT) tai laajennettua tietoturvapäivityksen Inventory-työkalua (ESUIT). Lisätietoja on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939)-sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU -sivustoissa ja WSUS-palvelussa:

Tässä kuussa:

  - Microsoft on julkaissut MU (Microsoft Update) -sivustolla ja WSUS (Windows Server Update Services) -palvelussa kolme tärkeää päivitystä, jotka **eivät kuitenkaan ole tietoturvapäivityksiä**, ja 2007 Microsoft Office Service Pack 1:n.
  - Microsoft on julkaissut WU (Windows Update) ja WSUS-palvelussa kolme tärkeää Windows-päivitystä, jotka **eivät kuitenkaan ole tietoturvapäivityksiä**, ja Windows SharePoint Services 3.0 Service Pack 1:n.

Huomaa, että nämä tiedot koskevat **vain** sellaisia tärkeitä päivityksiä, **jotka eivät ole tietoturvapäivityksiä** ja jotka julkaistaan saman päivänä kuin tietoturvatiedotteiden yhteenveto Microsoft Update-, Windows Update -sivustoissa ja Windows Server Update Services -palvelussa. Tietoja **ei** julkaista muina päivinä julkaistavista päivityksistä, **jotka eivät ole tietoturvapäivityksiä**.

#### Tietoturvastrategiat ja yhteisö

**Korjaustiedostojen hallintamenetelmät**

[Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivitysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - Jun Mao ([VeriSign iDefense Labs](http://labs.idefense.com/)) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS07-064.
  - Peter Winter Smith ([NGSSoftware](http://www.ngssoftware.com/)) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS07-064
  - Jung-hyung Lee ([AhnLab](http://global.ahnlab.com/)) teki yhteistyötä kanssamme kehittääkseen tietoturvaa koskevia muutoksia DirectX-sovellukseen. Tämä haavoittuvuus on kuvattu tietoturvatiedotteessa MS07-064
  - [Zero Day Initiative](http://www.zerodayinitiative.com/) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS07-065
  - Venustech ([ADLABS](http://www.venustech.com.cn/)) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS07-065
  - Thomas Garnier ([SkyRecon](http://www.skyrecon.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-066
  - Ryan Smith ([ISS X-Force](http://xforce.iss.net/)) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS07-068
  - Alex Wheeler ([ISS X-Force](http://xforce.iss.net/)) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS07-068
  - Peter Vreugdenhil (yhteistyössä [iDefense VCP:n](http://idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-069
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-069.
  - Sam Thomas (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-069.
  - Peter Vreugdenhil (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-069.

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - 1.0 (11. joulukuuta 2007): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (12. joulukuuta 2007): Tiedote on päivitetty vastaamaan tietoturvatiedotteiden MS07-065 ja MS-07-067 yhteenvetoon tehtyjä muutoksia.
  - V1.2 (23.1.2008): Tietoturvatiedote on päivitetty vastaamaan muutoksia tietoturvatiedotteen MS07-064 ohjelmistoihin, joita haavoittuvuus koskee.
  - 2.0 (16. heinäkuuta 2008): Tietoturvatiedote on päivitetty vastaamaan muutoksia tietoturvatiedotteen MS07-064 ohjelmistoihin, joita haavoittuvuus koskee.

*Built at 2014-04-18T01:50:00Z-07:00*

