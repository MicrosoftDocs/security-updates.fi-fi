---
title: Microsoftin turvatiedotteiden yhteenveto, lokakuu 2007
TOCTitle: MS07-OCT
ms:assetid: ms07-oct
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms07-oct(v=Security.10)
ms:contentKeyID: 61225591
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, lokakuu 2007

Julkaistu: 9. lokakuuta 2007

**Versio:** 1.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo lokakuussa 2007 julkaistuista tietoturvatiedotteista.

Lokakuun 2007 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 4. lokakuuta 2007. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 10. lokakuuta 2007, kello 21.00 Suomen aikaa (kello 11.00 Tyynenmeren aikaa). [Rekisteröidy nyt lokakuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344692&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut päivitykset, jotka julkaistaan samana päivänä. Lisätietoja kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (4)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-055</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94668"><strong>Kodak Image Viewerin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (923810)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Koodin suorittamisen verkon välityksellä mahdollistava haavoittuvuus aiheutuu tavasta, jolla Kodak Image Viewer (entiseltä nimeltään Wang Image Viewer) käsittelee tietyllä tavalla muodostettuja kuvatiedostoja. Haavoittuvuus saattaa antaa hyökkääjän suorittaa haavoittuvuuden sisältävässä järjestelmässä koodia verkon välityksellä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-056</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=96629"><strong>Outlook Expressin ja Windows Mailin tietoturvapäivitys (941202)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä virheellisesti käsitellyn väärin muotoillun NNTP-vastauksen takia. Hyökkääjä voi hyödyntää tätä haavoittuvuutta luomalla erityisesti muodostetun web-sivun.</td>
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
<td>Microsoft Baseline Security Analyzer ja Enterprise Update Scan Tool havaitsevat, tarvitseeko tietokone tämän päivityksen. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen, paitsi tietyissä tilanteissa käytettäessä Windows Vistaa.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmisto</strong> <strong>t, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows, Outlook Express, Windows Mail.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-057</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=95045"><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (939653)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa kolme yksityishenkilön ilmoittamaa haavoittuvuutta ja yhden yleisessä tiedossa olleen haavoittuvuuden. Vakavin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun web-sivun Internet Explorerissa. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuude</strong> <strong>n vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows, Internet Explorer.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-060</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=101656"><strong>Microsoft Wordin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (942695)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Wordin haavoittuvuuden, joka saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Word-tiedoston, jossa on väärin muodostettu merkkijono. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (2)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-058</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=91031"><strong>RPC:n suojaushaavoittuvuus voi aiheuttaa palveluneston</strong> <strong>(933729)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä päivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Etäproseduurikutsutoiminnossa (RPC) on palvelunestohaavoittuvuus, joka aiheutuu NTLM-tietoturvatarjoajan viestintävirheestä RPC-pyyntöjen todennuksen aikana.</td>
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
<td><strong>Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-059</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=95631"><strong>Wi</strong> <strong>ndows SharePoint Services 3.0:n ja Office SharePoint Server 2007:n haavoittuvuus saattaa aiheuttaa käyttöoikeuksien laajentumisen SharePoint-sivustossa (942017)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa Microsoft Windows SharePoint Services 3.0:n ja Microsoft Office SharePoint Server 2007:n julkistetun haavoittuvuuden. Haavoittuvuus saattaa antaa hyökkääjälle mahdollisuuden suorittaa koodin, joka saattaa aiheuttaa käyttöoikeuksien laajentumisen SharePoint-sivustossa sen sijaan, että käyttöoikeudet laajentuisivat työasemassa tai palvelinympäristössä. Lisäksi haavoittuvuus saattaa antaa hyökkääjälle mahdollisuuden suorittaa käyttäjän välimuistia muokkaavan koodin, mikä aiheuttaa työaseman tietojen paljastumisen.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen, paitsi tietyissä tilanteissa.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows, Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
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
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=94668">
                  <strong>MS07-055</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=96629">
                  <strong>MS07-056</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=95045">
                  <strong>MS07-057</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=101656">
                  <strong>MS07-060</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=91031">
                  <strong>MS07-058</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=95631">
                  <strong>MS07-059</strong>
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
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Tärkeä</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Tärkeä</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="7">Windows-käyttöjärjestelmä</th></tr>
          
            <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29763117-c2dc-4746-b31e-0b27350118e6">Kriittinen</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c7fb9a8-1d8d-4307-b5c6-bc6c28ee09de">Ei tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=be52f740-e9c9-4228-95c0-00995213bbd0">Kriittinen</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1fee539c-ab86-4298-b6f4-22ce31ee7b8b">Tärkeä</a>
              </td><td /></tr>
            <tr><td>Windows XP Professional x64 Edition</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac7bd100-0a03-426b-adc8-0516c602a280">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac7bd100-0a03-426b-adc8-0516c602a280">Tärkeä</a>
              </td><td /></tr>
            <tr><td>Windows Server 2003 Service Pack 1</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a5c9e5d-4908-48bf-9346-745b4c6f6d4e">Kriittinen</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=011593a0-f37e-4578-bee1-a985639b521b">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a5c9e5d-4908-48bf-9346-745b4c6f6d4e">Kriittinen</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=011593a0-f37e-4578-bee1-a985639b521b">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Server 2003 x64 Edition</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9bb8df5-f39e-4473-9d0c-e84430c7f859">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9bb8df5-f39e-4473-9d0c-e84430c7f859">Tärkeä</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Windows Server 2003 with SP1 for Itanium-based Systems</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=492ae87c-047c-45c1-ad04-ee36352de85b">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=492ae87c-047c-45c1-ad04-ee36352de85b">Tärkeä</a>
              </td><td /></tr>
            <tr><td>Windows Vista</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ceca7f8c-7b56-48fc-8c17-87ffadf25629">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7625f5a4-2921-41ce-986d-4cc0c264135c">Tärkeä</a>
              </td><td /></tr>
          
            <tr><th colspan="7">Windows-käyttöjärjestelmien osat</th></tr>
          
            <tr><td>Microsoft Windows 2000 Service Pack 4:n Outlook Express 5.5 Service Pack 2</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5aa009c9-4edc-4f34-989b-0493549649e8">Kriittinen</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Microsoft Windows 2000 Service Pack 4:n Outlook Express 6 Service Pack 1</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b537115d-611c-4486-960c-08d2df450579">Kriittinen</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Windows XP Service Pack 2:n Outlook Express 6</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ed7f466-78c7-4251-ba24-8ae71ad54e18">Kriittinen</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2:n Outlook Express 6</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6468a552-2194-4866-97d5-ff77ae205eea">Kriittinen</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Outlook Express 6</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=708926e4-f8af-4533-8747-22d6536ebd66">Kriittinen</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Outlook Express 6 </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26720f5a-d7e9-44b9-9330-2e9faa4af0d9">Kriittinen</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Outlook Express 6, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8844fbb-5b2c-41f3-80f1-dce563aa7cb7">Kriittinen</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Vistan Windows Mail</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6ac8d93-adc3-4ec3-bad1-4990bd7d52b4">Tärkeä</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Windows Vista x64 Editionin Windows Mail</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34aaf9dd-4d63-43e2-b631-bbf492d56a26">Tärkeä</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 5.01 Service Pack 4 ja Microsoft Windows 2000 Service Pack 4</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95827f3f-a984-4e34-a949-d16a0614121a">Kriittinen</a>
              </td><td /><td /><td /></tr>
            <tr><td>Microsoft Windows 2000 Service Pack 4:n Internet Explorer 6 Service Pack 1</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=df3ba596-7c5b-4151-9884-6957aa884aab">Kriittinen</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2:n Internet Explorer 6</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=513a8320-6d36-4fc9-a38a-867192b55b53">Kriittinen</a>
              </td><td /><td /><td /></tr>
            <tr><td>Windows XP Professional x64 Editionin Internet Explorer 6 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae8a26d8-1910-4b8c-8a73-6e2fa6b5b29f">Kriittinen</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Internet Explorer 6</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aefaa38-8757-4e6e-8924-57cabd1c2fc3">Keskitaso</a>
              </td><td /><td /><td /></tr>
            <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Internet Explorer 6</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88aba9dd-653b-4cdf-a513-cca32a7d7e41">Keskitaso</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=309a8f10-c7ea-4961-a969-092b0c4d7bbc">Keskitaso</a>
              </td><td /><td /><td /></tr>
            <tr><td>Windows XP Service Pack 2:n Internet Explorer 7</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ca0ac93-bf51-40fe-a1ba-cb3e0a36d8b5">Kriittinen</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Editionin Internet Explorer 7 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbd284d0-2664-42a4-ad16-a0535244c81c">Kriittinen</a>
              </td><td /><td /><td /></tr>
            <tr><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Internet Explorer 7</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a31c451-32f4-4551-ae45-d600f8b3b11b">Keskitaso</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Internet Explorer 7</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1915633-d181-4ca1-a4f0-7ca0f865aa72">Keskitaso</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 7, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=093a2250-3be3-494f-80e0-89ca7217030f">Keskitaso</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Vistan Internet Explorer 7</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=86392e8d-098c-427f-a233-699cdb9375ae">Kriittinen</a>
              </td><td /><td /><td /></tr>
            <tr><td>Windows Vista x64 Editionin Internet Explorer 7</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62490e6d-0a21-4a15-90bd-63ca8f8886b6">Kriittinen</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:n Windows SharePoint Services 3.0 (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76fc2225-2802-46e5-a294-a842e3841877">Tärkeä</a>
              </td></tr>
            <tr><td>Windows Server 2003 Service Pack 2:n Windows SharePoint Services 3.0 (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76fc2225-2802-46e5-a294-a842e3841877">Tärkeä</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Editionin Windows SharePoint Services 3.0 (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=667335dd-df2e-4f14-a130-5758701be055">Tärkeä</a>
              </td></tr>
            <tr><td>Windows Server 2003 x64 Edition Service Pack 2:n Windows SharePoint Services 3.0 (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=667335dd-df2e-4f14-a130-5758701be055">Tärkeä</a>
              </td></tr>
          
            <tr><th colspan="7">Microsoft Office</th></tr>
          
            <tr class="alternateRow"><td>Microsoft Word 2000 Service Pack 3</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b3072fb-5933-47f7-a498-13a93e268e57">Kriittinen</a>
              </td><td /><td /></tr>
            <tr><td>Microsoft Word 2002 Service Pack 3</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6b787bb-03ff-4f67-8b69-6011fb18ba75">Tärkeä</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Microsoft Office 2004 for Mac</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/mac/downloads.aspx">Tärkeä</a>
              </td><td /><td /></tr>
            <tr><td>Microsoft Office SharePoint Server 2007 (KB937832)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aaea9695-f541-4c4c-9107-81ead5cfc8c9">Tärkeä</a>
              </td></tr>
            <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007 x64 Edition (KB937832)</td><td /><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d319164-d133-4493-be27-1aeda62362c4">Tärkeä</a>
              </td></tr>
          </table>


**Huomautuksia**

**\[1\]** Tähän käyttöjärjestelmään on saatavana tietoturvapäivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa. 

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security\_patch" avulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla myös IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin, laajennettu Inventory-työkalu ja Enterprise Update Scan (EST) -työkalu. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer ja Enterprise Update Scan Tool**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

Kun MBSA 1.2.1 ei tue tietyn tietoturvapäivityksen tunnistamista, Microsoft julkaisee kyseistä tietoturvapäivitystä varten EST (Enterprise Update Scan Tool) -version. Lisätietoja EST-tarkistustyökalusta on sivustossa [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193).

**Huomautus** MBSA 1.2.1:n käyttämää MSSecure.XML-tiedostoa ei päivitetä 9.10.2007 jälkeen. Tämän päivämäärän jälkeen uusia tietoturvapäivityksiä ei lisätä MBSA 1.2.1:n käyttämän MSSecure.XML-tiedostoon eikä Enterprise Scan Tool -tarkistustyökalusta julkaista enää uusia versioita. Lisätietoja on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939)-sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tässä kuussa:

  - Microsoft on julkaissut kolme tärkeää päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**, MU (Microsoft Update)- ja WSUS (Windows Server Update Services) -sivustoissa.
  - Microsoft on julkaissut yhden tärkeän Windows-päivityksen, **joka ei kuitenkaan ole tietoturvapäivitys**, WU (Windows Update) -sivustossa.

Huomaa, että nämä tiedot koskevat **vain** sellaisia tärkeitä päivityksiä, **jotka eivät ole tietoturvapäivityksiä** ja jotka julkaistaan saman päivänä kuin tietoturvatiedotteiden yhteenveto Microsoft Update-, Windows Update- ja Windows Server Update Services -sivustoissa. Tietoja **ei** julkaista muina päivinä julkaistavista päivityksistä, **jotka eivät ole tietoturvapäivityksiä**.

#### Tietoturvastrategiat ja yhteisö

**Korjaustiedostojen** **hallintamenetelmät**

[Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivitysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security\_patch" avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - Cu Fang ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-055.
  - Rita Schappler ([Global 360](http://www.global360.com/products/g360_imaging/default.asp)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-055.
  - Greg MacManus ([VeriSign iDefense Labs](http://www.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-056.
  - Pierre Geyer (next.motion OHG) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-057.
  - Carsten H. Eiram ([Secunia Research](http://secunia.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-057.
  - Jakob Balle ([Secunia Research](http://secunia.com/)) ilmoitti ensimmäisenä haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-057.
  - [Zero Day Initiative](http://www.zerodayinitiative.com/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-058.
  - Liu Kun-Hao (Information & Communication Security Technology Center) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-060.

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (9. lokakuuta 2007): Tietoturvatiedotteen yhteenveto julkaistu.

*Built at 2014-04-18T01:50:00Z-07:00*

