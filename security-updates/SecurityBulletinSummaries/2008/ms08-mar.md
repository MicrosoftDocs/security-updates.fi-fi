---
title: Microsoftin turvatiedotteiden yhteenveto, maaliskuu 2008
TOCTitle: MS08-MAR
ms:assetid: ms08-mar
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms08-mar(v=Security.10)
ms:contentKeyID: 61225613
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, maaliskuu 2008

Julkaistu: 11. maaliskuuta 2008 | Päivitetty: 16. huhtikuuta 2008

**Versio:** 2.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo maaliskuussa 2008 julkaistuista tietoturvatiedotteista.

Maaliskuun 2008 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 6. maaliskuuta 2008. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 12. maaliskuuta 2008, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt maaliskuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357217&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (4)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-014</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112111"><strong>Microsoft Excelin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (949029)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa useita yksityishenkilön ilmoittamia ja yleisessä tiedossa olleita Microsoft Office Excelin haavoittuvuuksia, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Excel-tiedoston. Hyödyntämällä näitä haavoittuvuuksia onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikut</strong> <strong>us</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Microsoft Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-015</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112113"><strong>Microsoft Outlookin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (949031)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Office Outlookin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos Outlookille toimitetaan tietyllä tavalla muodostettu sähköposti URI-tunnukseen. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Haavoittuvuutta ei voi hyödyntää, jos sähköpostia vain katsotaan Outlookin esikatseluruudun kautta.</td>
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
<td><strong>Microsoft Office. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-016</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112112"><strong>Microsoft Officen haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (949030)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa Microsoft Office Publisherin haavoittuvuutta, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa väärin muodostetun Office-tiedoston. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Microsoft Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-017</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112114"><strong>M</strong> <strong>icrosoft Office Web Components -komponenttien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (933103)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa Microsoft Office Web Componentsin haavoittuvuutta. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on ehkä käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Microsoft Of</strong> <strong>fice Web Components.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

**Kuinka taulukkoa käytetään?**

Tämän taulukon avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja edellyttääkö se tietoturvapäivityksen asentamista. Kunkin mainitun ohjelman tai osan yhteydessä näkyy haavoittuvuuden vaikutus ja linkki saatavana oleviin ohjelmistopäivityksiin.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää usean tietoturvapäivityksen asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

**Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th>Tiedot</th>
    <th>Tiedot</th>
    <th>Tiedot</th>
    <th>Tiedot</th>
  </tr>
            <tr><td>
                <strong>Tiedotteen numero</strong>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=112111">
                  <strong>MS08-014</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=112113">
                  <strong>MS08-015</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=112112">
                  <strong>MS08-016</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=112114">
                  <strong>MS08-017</strong>
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
                  <strong>Kriittinen</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Kriittinen</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="5">Office-ohjelmistopaketit ja -ohjelmisto </th></tr>
          
            <tr><td>Microsoft Office 2000 Service Pack 3</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72735aa1-e22c-40ed-8c79-38fba89979aa">Kriittinen</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9cf8aafa-71a5-4017-b53c-4e80ef6e1188">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Microsoft Office 2003 Service Pack 2</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Microsoft Office Excel 2000 Service Pack 3</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7f90c30-1bfd-406b-a77f-612443e30185">Kriittinen</a>
              </td><td /><td /><td /></tr>
            <tr><td>Microsoft Office Excel 2002 Service Pack 3</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=907f96d5-d1e9-4471-b41c-3ac811e63038">Tärkeä</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Microsoft Office Excel 2003 Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=296e5f2c-f594-41c8-a20a-3e4c40ae3948">Tärkeä</a>
              </td><td /><td /><td /></tr>
            <tr><td>Microsoft Office Excel Viewer 2003</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=280bb2ac-b21a-46b5-8751-5a50fbebf107">Tärkeä</a>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Microsoft Office Excel Viewer 2003 Service Pack 3</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa">Tärkeä</a>
              </td><td /></tr>
            <tr><td>Microsoft Office Word Viewer 2003</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Microsoft Office Word Viewer 2003 Service Pack 3</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa">Tärkeä</a>
              </td><td /></tr>
            <tr><td>Microsoft Office Excel 2007</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7634cb5-9531-4284-9554-4168fc488e0c">Tärkeä</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9251d71-9098-4125-ae91-7d4c83ea58ad">Tärkeä</a>
              </td><td /><td /><td /></tr>
            <tr><td>Microsoft Office Outlook 2000 Service Pack 3</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=714a49cd-5bca-4719-96a1-e1077f279533">Kriittinen</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Microsoft Office Outlook 2002 Service Pack 3</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59853687-d885-4059-9460-ee403855dbd8">Kriittinen</a>
              </td><td /><td /></tr>
            <tr><td>Microsoft Office Outlook 2003 Service Pack 2</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fccc7c4c-8496-4682-bd46-6590503c1bf2">Kriittinen</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Microsoft Office Outlook 2003 Service Pack 3</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fccc7c4c-8496-4682-bd46-6590503c1bf2">Kriittinen</a>
              </td><td /><td /></tr>
            <tr><td>Microsoft Office Outlook 2007</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e2baf00-88eb-4eb6-961a-54245b363c21">Kriittinen</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Microsoft Office 2004 for Mac</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95dceb37-b35f-46db-b280-db0f3b298aa9">Tärkeä</a>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95dceb37-b35f-46db-b280-db0f3b298aa9">Tärkeä</a>
              </td><td /></tr>
            <tr><td>Microsoft Office 2008 for Mac</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8fe8c32a-6d7a-482b-97c6-42562f089ee4">Tärkeä</a>
              </td><td /><td /><td /></tr>
          
            <tr><th colspan="5">Muu ohjelmisto </th></tr>
          
            <tr class="alternateRow"><td>Microsoft Office Web Components 2000<br />(KB931660)</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=806c654a-35e3-4385-855a-4b803249bfcf">Kriittinen</a>
              </td></tr>
            <tr><td>Microsoft Office Web Components 2000<br />(KB932031)</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f54d2a5e-c0ed-4f70-9746-38dd61c8e9d7">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Microsoft Office Web Components 2000<br />(KB933367)</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d71b23fa-a873-406d-bad7-e38e565dee39">Kriittinen</a>
              </td></tr>
            <tr><td>Microsoft Office Web Components 2000<br />(KB933369)</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fe10ccd-40cb-4090-b83d-eae3d4eca174">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Microsoft Office Web Components 2000<br />(KB939714)</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5fddd54f-7a33-4ea3-b68d-b96a9bae509d">Kriittinen</a> <br /><strong>[2]</strong></td></tr>
            <tr><td>Microsoft Office Web Components 2000<br />(KB939714)</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5fddd54f-7a33-4ea3-b68d-b96a9bae509d">Kriittinen</a> <br /><strong>[3]</strong></td></tr>
            <tr class="alternateRow"><td>Microsoft Office Web Components 2000<br />(KB941305)</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71de76ba-b62c-4a7a-a78a-9317f5255b13">Kriittinen</a>
              </td></tr>
            <tr><td>Microsoft Office Web Components 2000<br />(KB948257)</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=526d87bd-c3da-412e-8765-c15987ae9b01">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Visual Studio .NET 2002 Service Pack 1<br />(KB933367)</td><td /><td /><td /><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Visual Studio .NET 2003 Service Pack 1<br />(KB933369)</td><td /><td /><td /><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Microsoft BizTalk Server 2000<br />(KB939714)</td><td /><td /><td /><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Microsoft BizTalk Server 2002<br />(KB939714)</td><td /><td /><td /><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Microsoft Commerce Server 2000<br />(KB941305)</td><td /><td /><td /><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Internet Security and Acceleration Server 2000 Service Pack 2<br />(KB948257)</td><td /><td /><td /><td>
                <strong>[1]</strong>
              </td></tr>
          </table>


**Huomautuksia**

**\[1\]** Tälle ohjelmistolle on saatavana tietoturvapäivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa. 

**\[2\]** Tämä tietoturvapäivitys liittyy Microsoft BizTalk Server 2000:een. Lisätietoja on kyseistä haavoittuvuutta käsittelevässä tietoturvatiedotteessa.

**\[3\]** Tämä tietoturvapäivitys liittyy Microsoft BizTalk Server 2002:een. Lisätietoja on kyseistä haavoittuvuutta käsittelevässä tietoturvatiedotteessa.

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietotur** **vakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin ja laajennettu Inventory-työkalu (ESUIT). Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso myös [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) -sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää Microsoft Baseline Security Analyzer -työkalua ja Microsoft Office Inventory Tool -työkalua laajan tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseksi. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tässä kuussa:

  - Microsoft on julkaissut on kaksi tärkeää päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**, MU (Microsoft Update)- ja WSUS (Windows Server Update Services) -sivustoissa.
  - Microsoft on julkaissut WU (Windows Update)- ja WSUS (Windows Server Update Services) -sivustoissa kolme tärkeää Windows-päivitystä, **jotka** **eivät kuitenkaan ole tietoturvapäivityksiä**.

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

  - Mike Scott ([SAIC](http://www.saic.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-014
  - Matt Richard ([VeriSign](http://www.verisign.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-014
  - Greg MacManus ([iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-014
  - Yoshiya Sasaki ([JFE Systems](http://www.jfe-systems.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-014
  - Bing Liu ([Fortinet](http://www.fortinet.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-014
  - [iDefense Labs](http://labs.idefense.com/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-014
  - Cody Pierce ([TippingPoint DVLabs](http://dvlabs.tippingpoint.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-014
  - Moti Joseph ja Dan Hubbard ([Websense Security Labs](http://www.websense.com/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-014
  - Greg MacManus ([iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-015
  - Arnaud Dovi ([Zero Day Initiative \[ZDI\]](http://www.zerodayinitiative.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-016
  - Tuntematon löytäjä ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-016
  - Chris Ries ([VigilantMinds Inc](http://www.vigilantminds.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-017
  - Xiaohui ([NCNIPC](http://www.nipc.org.cn/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-017
  - Golan Yosef ([Finjan](http://www.finjan.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-017.
  - Yuval Ben-Itzhak ([Finjan](http://www.finjan.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-017

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (11. maaliskuuta 2008): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (12. maaliskuuta 2008): Tietoturvatiedotteen yhteenveto on päivitetty sisältämään uusi Microsoft Office Web Components 2000 for BizTalk Server 2000:n ja 2002:n latauslinkki.
  - V1.2 (26. maaliskuuta 2008): Tietoturvatiedotteen yhteenveto on päivitetty sisältämään tietoturvatiedotteessa MS08-017 kuvatun haavoittuvuuden löytänyt henkilö.
  - V2.0 (16. huhtikuuta 2008): Microsoft Office Word Viewer 2003 ja Microsoft Office Word Viewer 2003 Service Pack 3 on lisätty tietoturvatiedotteen yhteenvetoon ohjelmistoina, joita koskee tietoturvatiedote MS08-016.

*Built at 2014-04-18T01:50:00Z-07:00*

