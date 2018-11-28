---
title: Microsoftin turvatiedotteiden yhteenveto, helmikuu 2008
TOCTitle: MS08-FEB
ms:assetid: ms08-feb
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms08-feb(v=Security.10)
ms:contentKeyID: 61225609
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, helmikuu 2008

Julkaistu: 12. helmikuuta 2008 | Päivitetty: 13. helmikuuta 2008

**Versio:** 1.1

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo helmikuussa 2008 julkaistuista tietoturvatiedotteista.

Helmikuun 2008 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 7. helmikuuta 2008. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Lisätietoja Microsoftin tietoturvatiedotteita koskevasta automaattisesta ilmoituksessa on osoitteessa [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 13. helmikuuta 2008, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt helmikuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357215&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedotteet

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (6)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-007</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=107349"><strong>WebDAV Mini-Redirector -liittymä saattaa sallia koodin suorittamisen verkon välityksellä (946026)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa suoraan Microsoftille ilmoitetun WebDAV Mini-Redirector -liittymän haavoittuvuuden. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
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
<td><strong>Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-008</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108277"><strong>OLE-automaation haavoittuvuus saattaa sallia koodin suorittami</strong> <strong>sen verkon välityksellä (947890)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys Microsoftille suoraan ilmoitetun haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon avulla, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua. Haavoittuvuutta voidaan käyttää hyväksi OLE (Object Linking and Embedding) -automaatioon kohdistuvilla hyökkäyksillä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows, Office, Visual Basic.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-009</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110056"><strong>Microsoft Wordin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (947077)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa suoraan Microsoftille ilmoitetun Microsoft Wordin haavoittuvuuden, joka saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Word-tiedoston. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-010</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=105692"><strong>I</strong> <strong>nternet Explorerin kumulatiivinen tietoturvapäivitys (944533)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa kolme suoraan Microsoftille ilmoitettua haavoittuvuutta ja yhden yleisessä tiedossa olleen haavoittuvuuden. Vakavin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun web-sivun Internet Explorerissa. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows, Internet Explorer.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-012</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110054"><strong>Microsoft Office Publisherin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (947085)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa kaksi suoraan Microsoftille ilmoitettua Microsoft Office Publisherin haavoittuvuutta, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Publisher-tiedoston. Hyödyntämällä näitä haavoittuvuuksia onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-013</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110060"><strong>Microsoft Officen haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (947108)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa suoraan Microsoftille ilmoitetun Windows Officen haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun, väärin muotoillun objektin sisältävän Microsoft Office -tiedoston. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (5)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-003</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104925"><strong>Active Directoryn haavoittuvuus voi aiheuttaa palveluneston (946538)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa suoraan Microsoftille ilmoitetun Microsoft Windows 2000 Server- tai Windows Server 2003 -käyttöjärjestelmään asennetun Active Directoryn sekä Windows XP Professional- tai Windows Server 2003 -käyttöjärjestelmään asennetun ADAM:n (Active Directory Application Mode) haavoittuvuuden. Haavoittuvuus voi aiheuttaa palveluneston. Windows Server 2003- ja Windows XP Professional -käyttöjärjestelmässä haavoittuvuuden hyödyntäminen edellyttää, että hyökkääjällä on voimassa olevat kirjautumistiedot. Tätä haavoittuvuutta hyödyntävä hyökkääjä voi saada järjestelmän lopettamaan pyyntöihin vastaamisen tai käynnistymään automaattisesti uudelleen.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Palvelunesto</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows, Active Directory, ADAM. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-004</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108164"><strong>Haavoittuvuus Windowsin TCP/IP-yhteydessä voi aiheuttaa palveluneston (946456)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä päivitys korjaa suoraan Microsoftille ilmoitetun haavoittuvuuden TCP/IP (Transmission Control Protocol/Internet Protocol) -käsittelyssä. Tätä haavoittuvuutta hyödyntävä hyökkääjä voi saada haavoittuvuuden sisältävän järjestelmän lopettamaan pyyntöihin vastaamisen ja käynnistymään automaattisesti.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Palvelunesto</td>
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
<th>Microsoftin tietoturvatiedote MS08-005</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=106361"><strong>In</strong> <strong>ternet Information Servicesin haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen (942831)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä päivitys korjaa suoraan Microsoftille ilmoitetun IIS:n (Internet Information Services) haavoittuvuuden. Hyödyntämällä tätä haavoittuvuutta onnistuneesti paikallinen hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia, tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows, IIS. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-006</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=106375"><strong>Internet Information Servicesin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (942830)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä päivitys korjaa suoraan Microsoftille ilmoitetun IIS:n (Internet Information Services) haavoittuvuuden. Koodin suorittamisen verkon välityksellä mahdollistava haavoittuvuus aiheutuu tavasta, jolla IIS käsittelee ASP-verkkosivujen syötteitä. Hyödyntämällä tätä haavoittuvuutta hyökkääjä voi suorittaa IIS-palvelimessa toimia, joita työprosessikäyttäjätiedot (WPI) voivat suorittaa. WPI määritetään oletusarvoisesti verkkopalvelutilin oikeuksissa. IIS-palvelimet, joiden ASP-sivujen sovellussarjojen määrityksessä on käytetty järjestelmänvalvojan oikeudet sisältävää WPI:tä, ovat ehkä haavoittuvampia kuin IIS-palvelimet, joiden sovellussarjan määrityksessä on käytetty WPI:n oletusasetuksia.</td>
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
<td><strong>Windows, IIS. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-011</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110059"><strong>Microsoft Worksin tiedostomuuntimen haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (947081)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa kolme suoraan Microsoftille ilmoitettua Microsoft Worksin tiedostomuuntimen haavoittuvuutta. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Works (.wps) -tiedoston sellaisessa Microsoft Officen, Microsoft Worksin tai Microsoft Works Suiten versiossa, jota haavoittuvuus koskee. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
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
<td><strong>Office, Works, Works Suite. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

**Miten taulukkoa käytetään?**

Tämän taulukon avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja edellyttääkö se tietoturvapäivityksen asentamista. Kunkin mainitun ohjelman tai osan yhteydessä näkyy haavoittuvuuden vaikutus ja linkki saatavana oleviin ohjelmistopäivityksiin.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää useiden tietoturvapäivitysten asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

**Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot**

#### Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot tietoturvatiedotteille MS08-003–MS08-008

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th>Tiedot</th>
    <th>Tiedot</th>
    <th>Tiedot</th>
    <th>Tiedot</th>
    <th>Tiedot</th>
    <th>Tiedot</th>
  </tr>
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=104925">
                      <strong>MS08-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=108164">
                      <strong>MS08-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=106361">
                      <strong>MS08-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=106375">
                      <strong>MS08-006</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=107349">
                      <strong>MS08-007</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=108277">
                      <strong>MS08-008</strong>
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
              
                <tr><th colspan="7">Windows-käyttöjärjestelmä</th></tr>
              
                <tr><td>Microsoft Windows 2000 Server Service Pack 4</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Windows 2000 Service Pack 4</td><td /><td /><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93b3d0a3-2091-405e-8dd4-10f20dc2be7f">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows XP Professional Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <strong>[1]</strong>
                  </td><td /><td /></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td /><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afeef3ec-6160-4c1d-94bd-0bfce641d0a2">Kriittinen</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c331a3a-93e0-42e4-9cd1-4e32ebdda38d">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=15b7d1c4-4ef4-47b2-9e3b-22eafbdb90d8">Kriittinen</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0a15967-7184-4194-8edb-81760e440604">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7e725bf-7248-4119-aca5-b7d502c09cfc">Kriittinen</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cfa0d5c6-a9b0-4c5c-a651-898e9f900799">Keskitaso</a>
                  </td></tr>
                <tr><td>Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8af82f86-731c-46a0-a025-b62447e2af38">Kriittinen</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a08e87dc-993b-493b-8af3-be6e98643aeb">Keskitaso</a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <strong>[1]</strong>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bca224db-fe0e-411d-a948-1c776ce974f3">Kriittinen</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a88522b-ee30-4deb-878b-598e852fd60e">Keskitaso</a>
                  </td></tr>
                <tr><td>Windows Vista</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ce9608b-7049-47cd-adc4-22a803877d33">Tärkeä</a>
                  </td><td>
                    <strong>[1]</strong>
                  </td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba7a2b42-1c89-45e5-b8a6-049fa500c03a">Kriittinen</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c67ec357-0f86-4f7d-9af0-d63d8b765f44">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d7b9c3d1-9c23-4e05-bac6-d0b327feaf53">Tärkeä</a>
                  </td><td>
                    <strong>[1]</strong>
                  </td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45962232-af78-42cb-bfa0-9ce7de199585">Kriittinen</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9137108f-e80b-46f1-b547-82da8fb058bf">Kriittinen</a>
                  </td></tr>
              
                <tr><th colspan="7">Windows-käyttöjärjestelmien osat, joita haavoittuvuus koskee</th></tr>
              
                <tr><td>Microsoft Windows 2000 Service Pack 4:n Microsoft Internet Information Services 5.0</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b24f34fb-40b9-4aa5-b5ac-e3f0a6062753">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows XP Professional Service Pack 2:n Microsoft Internet Information Services 5.1</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73d24fcf-bea9-4b13-9f1c-4e068c53a4ae">Tärkeä</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b498065-d682-4227-b23e-d234d7d6a3fe">Tärkeä</a>
                  </td><td /><td /></tr>
                <tr><td>Windows XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2:n Microsoft Internet Information Services 6.0</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=103a6bc0-034a-443d-b1d4-81117820dcb2">Tärkeä</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=df9875f7-04d6-486e-bdb5-35e9e305fa1d">Tärkeä</a>
                  </td><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Microsoft Internet Information Services 6.0</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=516ef8e8-3cb6-4660-b771-3c7f66917a11">Tärkeä</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6583e798-d16d-419c-aee1-30c3e6c635b3">Tärkeä</a>
                  </td><td /><td /></tr>
                <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Microsoft Internet Information Services 6.0</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e24fb33c-67b9-4ed4-9317-b5fd535d005a">Tärkeä</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8286174-8209-409f-8805-e534715a741c">Tärkeä</a>
                  </td><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systemsin ja Windows Server 2003 with SP2 for Itanium-based Systemsin Microsoft Internet Information Services 6.0</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a4a6083-8c67-4403-8e20-7f2b82178124">Tärkeä</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29faa70d-f1ac-4da4-b72a-faf1973cd845">Tärkeä</a>
                  </td><td /><td /></tr>
                <tr><td>Windows Vistan Microsoft Internet Information Services 7.0</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8c7018ec-ae80-4a30-93fc-0f7386732514">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Editionin Microsoft Internet Information Services 7.0</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4de2fffc-5793-4acf-98ee-1b801e59ae39">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Microsoft Windows 2000 Server Service Pack 4:n Active Directory</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9df0875d-0466-4974-b4c0-1ecc777173b1">Tärkeä</a>
                  </td><td /><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Windows XP Professional Service Pack 2:n ADAM</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bff7dcb9-5d00-442e-b03c-ce923d213faa">Keskitaso</a>
                  </td><td /><td /><td /><td /><td /></tr>
                <tr><td>Windows XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2:n ADAM</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=36e36e1a-ed0d-45a6-b707-766fabc01fbd">Keskitaso</a>
                  </td><td /><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Active Directory</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63d3d784-f057-4686-b85e-ab5fbab5a722">Keskitaso</a>
                  </td><td /><td /><td /><td /><td /></tr>
                <tr><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n ADAM</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60781cf3-7c6d-4795-a9d0-bc18ee356e94">Keskitaso</a>
                  </td><td /><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Active Directory</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=835d647a-dce6-476e-b7c4-928a67b0acfb">Keskitaso</a>
                  </td><td /><td /><td /><td /><td /></tr>
                <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n ADAM</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e97698d-8150-44f9-9d34-87a0db6ba5a7">Keskitaso</a>
                  </td><td /><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systemsin ja Windows Server 2003 with SP2 for Itanium-based Systemsin Active Directory</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eda8af09-1a4c-4163-a8bb-97dacdebeae4">Keskitaso</a>
                  </td><td /><td /><td /><td /><td /></tr>
              
                <tr><th colspan="7">Microsoft Office</th></tr>
              
                <tr><td>Microsoft Office 2004 for Mac</td><td /><td /><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=36b00c58-192d-488c-a069-730c69f0b6b0">Kriittinen</a>
                  </td></tr>
              
                <tr><th colspan="7">Muut ohjelmistot, joita haavoittuvuus koskee</th></tr>
              
                <tr class="alternateRow"><td>Microsoft Visual Basic 6.0 Service Pack 6</td><td /><td /><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c96420a9-7436-4625-9649-75f1514b0fe3">Kriittinen</a>
                  </td></tr>
              </table>


**Huomautuksia**

**\[1\]** Tähän käyttöjärjestelmään on saatavana tietoturvapäivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa. 

#### Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot tietoturvatiedotteille MS08-009–MS08-013

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th>Tiedot</th>
    <th>Tiedot</th>
    <th>Tiedot</th>
    <th>Tiedot</th>
    <th>Tiedot</th>
  </tr>
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=110056">
                      <strong>MS08-009</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=105692">
                      <strong>MS08-010</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=110059">
                      <strong>MS08-011</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=110054">
                      <strong>MS08-012</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=110060">
                      <strong>MS08-013</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokitus</strong>
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
                  </td></tr>
              
                <tr><th colspan="6">Windows-käyttöjärjestelmä</th></tr>
              
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td /><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td /><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</td><td /><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</td><td /><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows Vista</td><td /><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td /><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /></tr>
              
                <tr><th colspan="6">Windows-käyttöjärjestelmien osat, joita haavoittuvuus koskee</th></tr>
              
                <tr><td>Internet Explorer 5.01 Service Pack 4 ja Microsoft Windows 2000 Service Pack 4</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1032a039-468b-4c5f-8c1c-5e54c2832e41">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Windows 2000 Service Pack 4:n Internet Explorer 6 Service Pack 1</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87e66dce-5060-4814-8754-829b4e190359">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows XP Service Pack 2:n Internet Explorer 6</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb2aa3cb-021f-4890-ab20-2a51f8e17554">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Editionin Internet Explorer 6 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8989f576-8b30-4866-90ec-929d24f3b409">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Internet Explorer 6</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=429b7ed1-fe78-459a-b834-d0f3c69cb703">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Internet Explorer 6</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e989e23c-38bb-4fe7-a830-d7bdf7659392">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Internet Explorer 6, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a097f7a-b696-48d0-b13f-337c5fd14e24">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2:n Internet Explorer 7</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4aa293a-6332-4c6c-b128-876f516bd030">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows XP Professional x64 Editionin Internet Explorer 7 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b72af1b6-6e23-4005-aef6-82195b380153">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Internet Explorer 7</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b2aa6562-881e-4fd6-be1b-53426a0ff4a9">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Internet Explorer 7</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4bb99afc-be14-4f2e-9570-b7fe09e39131">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Internet Explorer 7, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6fa80e2c-5e91-4b33-acd9-33f156660ae7">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows Vistan Internet Explorer 7</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0de25b98-f443-4874-a06f-4daae14c16b0">Kriittinen</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Editionin Internet Explorer 7</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c08ebbe7-639b-4ea2-8304-fab531930abf">Kriittinen</a>
                  </td><td /><td /><td /></tr>
              
                <tr><th colspan="6">Microsoft Office</th></tr>
              
                <tr><td>Microsoft Office 2000 Service Pack 3</td><td /><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5fb74e24-d9ee-4951-9c46-e1c84617f097">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td /><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e147b1a-f3be-465f-8587-7f3a33d6a6e5">Tärkeä</a>
                  </td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 2</td><td /><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4ac0f34-4604-4bbe-9669-01db645041ca">Tärkeä</a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2004 for Mac</td><td /><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=36b00c58-192d-488c-a069-730c69f0b6b0">Tärkeä</a>
                  </td></tr>
                <tr><td>Microsoft Word 2000 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a513069b-8244-48e9-b136-01ddd3862802">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Word 2002 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78c338aa-e410-4422-9e36-562f70d742e9">Tärkeä</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Microsoft Word 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85cb1aa5-211f-4652-827b-2e79b8ffc2fc">Tärkeä</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Office Word Viewer 2003</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd4ddecd-abd6-4783-b300-32b9d4bad22a">Tärkeä</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Microsoft Office Publisher 2000</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8b085fb-858f-4c7e-96de-edff8f49d62a">Kriittinen</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Microsoft Office Publisher 2002</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1135c63a-6ce7-4051-81ba-bfbba8d857fb">Tärkeä</a>
                  </td><td /></tr>
                <tr><td>Microsoft Office Publisher 2003 Service Pack 2</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7078b952-09f6-4c47-8c05-40667e1f1c3b">Tärkeä</a>
                  </td><td /></tr>
              
                <tr><th colspan="6">Office-ohjelmistot, joita haavoittuvuus koskee</th></tr>
              
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 2:n Microsoft Works 6 -tiedostomuunnin</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30c9c3fe-fb85-43d9-bbc3-0b30d3a20286">Keskitaso</a>
                  </td><td /><td /></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3:n Microsoft Works 6 -tiedostomuunnin</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30c9c3fe-fb85-43d9-bbc3-0b30d3a20286">Keskitaso</a>
                  </td><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Works 8.0:n Microsoft Works 6 -tiedostomuunnin</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30c9c3fe-fb85-43d9-bbc3-0b30d3a20286">Tärkeä</a>
                  </td><td /><td /></tr>
                <tr><td>Microsoft Works Suite 2005:n Microsoft Works 6 -tiedostomuunnin</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30c9c3fe-fb85-43d9-bbc3-0b30d3a20286">Tärkeä</a>
                  </td><td /><td /></tr>
              </table>


**Huomautuksia**

**\[1\]** Tähän käyttöjärjestelmään on saatavana tietoturvapäivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa. 

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin ja laajennettu Inventory-työkalu (ESUIT). Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

System Center Configuration Manager (SCCM) 2007 tunnistaa päivitykset WSUS 3.0:n avulla. Lisätietoja SCCM 2007 -ohjelmiston päivityksen hallinnasta on sivustossa [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso myös [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) -sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU- ja WU-sivustoissa sekä WSUS-palvelussa:

Tässä kuussa:

  - Microsoft on julkaissut seitsemän tärkeää päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**, MU (Microsoft Update)-sivustossa ja WSUS (Windows Server Update Services)-palvelussa.
  - Microsoft on julkaissut WU (Windows Update)-sivustossa ja WSUS (Windows Server Update Services)-palvelussa kaksi tärkeää Windows-päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**.

Huomaa, että nämä tiedot koskevat **vain** sellaisia tärkeitä päivityksiä, **jotka eivät ole tietoturvapäivityksiä** ja jotka julkaistaan saman päivänä kuin tietoturvatiedotteiden yhteenveto Microsoft Update-, Windows Update- ja Windows Server Update Services -sivustoissa. Tietoja **ei** julkaista muina päivinä julkaistavista päivityksistä, **jotka eivät ole tietoturvapäivityksiä**.

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

  - Thomas Garnier ([SkyRecon](http://www.skyrecon.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-003
  - Tomas Potok, Martin Dominik, Martin Luptak ja Eva Juhasova ([Whitestein](http://www.whitestein.com/) Technologies) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-004
  - Steven ([COSEINC Vulnerability Research Lab](http://www.coseinc.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-007
  - Ryan Smith ja Alex Wheeler ([IBM ISS X-Force](http://www.iss.net/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-008
  - Rubén Santamarta ([Reversemode.com](http://reversemode.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-009
  - Shane Macaulay ja Riley Hassell ([Security Objectives](http://www.security-objectives.com/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-010
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-010.
  - hyy (yhteistyössä [VeriSign iDefense VCP:n](http://idefense.com/) ja Microsoftin kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-010
  - ADLab ([Venustech](http://www.venustech.com.cn/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-010
  - [VeriSign iDefense VCP](http://labs.idefense.com/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-011
  - Damian Put (yhteistyössä [VeriSign iDefense VCP:n](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-011
  - [IBM Internet Security Systems X-Force](http://xforce.iss.net/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-011
  - Piotr Bania ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-012
  - Bing Liu ([Fortinet Security Research](http://www.fortinet.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-012
  - Bing Liu ([Fortinet Security Research](http://www.fortinet.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-012
  - Shaun Colley ([NGSSoftware](http://www.ngssoftware.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-013

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (12. helmikuuta 2008): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (13. maaliskuuta 2008): Tietoturvatiedote on päivitetty. MS08-005: Windows XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2:n latauslinkkiviittaus Internet Information Services 6.0:aan korjattiin. Latauslinkki ohjasi käyttäjät oikein IIS 6.0 -päivitykseen, mutta viitelinkki virheellisesti aiemmin ilmoitettuun IIS 5.1:een.

*Built at 2014-04-18T01:50:00Z-07:00*

