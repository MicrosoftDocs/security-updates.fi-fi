---
title: Microsoftin turvatiedotteiden yhteenveto, elokuu 2007
TOCTitle: MS07-AUG
ms:assetid: ms07-aug
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms07-aug(v=Security.10)
ms:contentKeyID: 61225582
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, elokuu 2007

Julkaistu: 14. elokuuta 2007 | Päivitetty: 24. kesäkuuta 2008

**Versio:** 4,0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo elokuussa 2007 julkaistuista tietoturvatiedotteista.

Tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 9. elokuuta 2007. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi 15.8.2007 klo 21 Suomen aikaa (klo 11.00 Tyynenmeren aikaa) web-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. [Rekisteröidy nyt elokuun tietoturvatiedotteen web-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344688&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (6)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-042</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=88350"><strong>Microsoft XML Core Services -osan haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (936227)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet Explorerilla. Haavoittuvuutta voidaan käyttää hyväksi Microsoft XML Core Services -osaan kohdistuvilla hyökkäyksillä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows, XML Core Services.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-043</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=70249"><strong>OLE-automaation haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (921503)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon avulla, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua. Haavoittuvuutta voidaan käyttää hyväksi OLE (Object Linking and Embedding) -tekniikkaan kohdistuvilla hyökkäyksillä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows, Visual Basic, Office for Mac</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-044</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=96778"><strong>Microsoft Excelin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (940965)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden sekä muita tietoturvaongelmia, jotka havaittiin tutkinnan aikana. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Excel-tiedoston. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden</strong> <strong>vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Office</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-045</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=91712"><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (937143)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa kolme yksityishenkilön ilmoittamaa haavoittuvuutta. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon avulla, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet Explorerilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows, Internet Explorer</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-046</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94466"><strong>GDI:n haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (938829)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Grafiikanmuodostusohjelmassa on haavoittuvuus, joka koskee koodin suorittamista verkon välityksellä. Tämä haavoittuvuus on tavassa, jolla se käsittelee erityisesti muotoiltuja kuvia. Hyökkääjä voi hyödyntää tätä haavoittuvuutta luomalla erityisesti muotoillun kuvan, joka saattaa sallia koodin suorittamisen verkon avulla, mikäli käyttäjä avaa haitallisen sähköpostin liitetiedoston. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän.</td>
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
<th>Microsoftin tietoturvatiedote MS07-050</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94737"><strong>VML (Vector Markup Language) -kielen haavoittuvuus saattaa sall</strong> <strong>ia koodin suorittamisen verkon avulla (938127)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden, joka esiintyy kun VML (Vector Markup Language) -kieltä käytetään Windowsissa. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon avulla, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet Explorerilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows, Internet Explorer</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (3)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-047</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=88628"><strong>Windows Media Playerin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (936782)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa haavoittuvuutta. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun tiedoston Windows Media Playerissä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-048</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94465"><strong>Windowsin pienoisohjelman haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (938123)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa haavoittuvuutta sekä muita haavoittuvuuksia, jotka havaittiin tutkinnan aikana. Nämä haavoittuvuudet saattavat sallia tuntemattoman etähyökkääjän suorittaa koodia kirjautuneen käyttäjän käyttöoikeuksin. Jos käyttäjä on tilannut haitallisen RSS-syötteen otsikkosyötteiden pienoisohjelmassa, lisännyt haitallisen yhteystietotiedoston yhteystietopienoisohjelmaan tai napsauttanut sääpienoisohjelmassa haitallista linkkiä, hyökkääjä voi mahdollisesti suorittaa järjestelmässä koodia. Kaikissa hyökkäystavoissa käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Windows Vista.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-049</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=92734"><strong>Vi</strong> <strong>rtual PC:n ja näennäispalvelimen haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (937986)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Tämä on käyttöoikeuksien korottamista koskeva haavoittuvuus. Virtual PC:n ja näennäispalvelimen haavoittuvuus saattaa sallia vieras-käyttöjärjestelmän käyttäjän suorittaa koodin isäntäjärjestelmässä tai muissa vieras-käyttöjärjestelmissä. Vain ne vieras-käyttöjärjestelmän käyttäjät, joilla on kyseisen järjestelmän järjestelmänvalvojan oikeudet, voivat hyödyntää tätä haavoittuvuutta. Ne vieras-käyttöjärjestelmän käyttäjät, joilla ei ole kyseisen järjestelmän järjestelmänvalvojan oikeuksia, eivät voi hyödyntää tätä haavoittuvuutta.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Virtual PC, näennäispalvelin.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

**Miten taulukkoa käytetään?**

Tämän taulukon avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja edellyttääkö se tietoturvapäivityksen asentamista. Kunkin mainitun ohjelman tai osan yhteydessä näkyy haavoittuvuuden vaikutus ja linkki saatavana oleviin ohjelmistopäivityksiin.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää useiden tietoturvapäivitysten asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

#### Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot MS07-042 - MS07-046

**Ohjelmistot, joita haavoittuvuus koskee, ja lataussivust** **ot**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
  </tr>
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=88350">
                      <strong>MS07-042</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=70249">
                      <strong>MS07-043</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=96778">
                      <strong>MS07-044</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=91712">
                      <strong>MS07-045</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=94466">
                      <strong>MS07-046</strong>
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
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
              
                <tr><th colspan="6">Windows-käyttöjärjestelmät, joita haavoittuvuus koskee</th></tr>
              
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c35b6e8-732a-4451-b5d4-23ed63e6e792">Kriittinen</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8fc8340b-c2b3-4559-835c-caa00cf086b9">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e8de050-8589-4831-ae19-075c93509485">Kriittinen</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc29475d-c0bb-4d35-8dd6-4ca1cac32315">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b85bb583-dc61-4d37-b458-208f5bb07ece">Kriittinen</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c81730a-981a-4649-b2d9-45144230d512">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b85bb583-dc61-4d37-b458-208f5bb07ece">Kriittinen</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=15d4d4fa-9bab-4da5-978e-f89c78c8086a">Keskitaso</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5374583d-de68-4d65-bca8-598d6b98b8b3">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=15d4d4fa-9bab-4da5-978e-f89c78c8086a">Keskitaso</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Server 2003 x64 Edition</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6608d722-3ef8-4085-b771-7b17bb0ba06e">Keskitaso</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3359f27-e03e-4a4f-b896-3bda39f69f7e">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6608d722-3ef8-4085-b771-7b17bb0ba06e">Keskitaso</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systems</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc04451a-0696-4a21-b2b6-f02d4e2c33bf">Keskitaso</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92822479-2060-4357-a340-ed096f180b2b">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc04451a-0696-4a21-b2b6-f02d4e2c33bf">Keskitaso</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Windows Vista</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <strong>[1]</strong>
                  </td><td /></tr>
                <tr><td>Windows Vista Service Pack 1</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <strong>[1]</strong>
                  </td><td /></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 1</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows Server 2008 for x64-based Systems</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td /><td /></tr>
              
                <tr><th colspan="6">Windows-käyttöjärjestelmien osat, joita haavoittuvuus koskee</th></tr>
              
                <tr><td>Internet Explorer 5.01 Service Pack 4 ja Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fcf9440f-bb36-4ed1-9b6b-74a4f055650b">Kriittinen</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Microsoft Windows 2000 Service Pack 4:n Internet Explorer 6 Service Pack 1</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8db75461-4dca-43db-aa30-c7e67ce954ad">Kriittinen</a>
                  </td><td /></tr>
                <tr><td>Windows XP Service Pack 2:n Internet Explorer 6</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d31d916-867f-4dbf-b8a4-c75ea83f4f51">Kriittinen</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Editionin Internet Explorer 6 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b15b2442-d6da-41dd-a424-11c9893be595">Kriittinen</a>
                  </td><td /></tr>
                <tr><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Internet Explorer 6</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f2f9fb69-0399-4df0-9f5b-8f42a130c581">Keskitaso</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Internet Explorer 6</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0bd886d-2c80-4dd7-82b7-1bd1f8d398cc">Keskitaso</a>
                  </td><td /></tr>
                <tr><td>Internet Explorer 6, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf41033a-d6f0-451e-9b69-4cbe2bb3f804">Keskitaso</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2:n Internet Explorer 7</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a2b4395-eaba-45ec-8d0c-932ebcc3d344">Tärkeä</a>
                  </td><td /></tr>
                <tr><td>Windows XP Professional x64 Editionin Internet Explorer 7 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd7ed4d5-7790-41db-8b68-cfd59105ca36">Tärkeä</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Internet Explorer 7</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f8daed8-9925-494d-b2f5-1e29f4040f6a">Ei tärkeä</a>
                  </td><td /></tr>
                <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Internet Explorer 7</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34669ca2-46b0-4fbf-8fbd-ad7a13920103">Ei tärkeä</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Internet Explorer 7, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5bd7bcbd-528a-4a16-a39a-a5ff5f69a2e2">Ei tärkeä</a>
                  </td><td /></tr>
                <tr><td>Windows Vistan Internet Explorer 7</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ae27b2f-aca4-4758-8ce4-a98f1ff6ba70">Tärkeä</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Editionin Internet Explorer 7</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=53497e53-d10c-43af-ad56-9f07739a5284">Tärkeä</a>
                  </td><td /></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4:n Microsoft XML Core Services 3.0 (KB936021)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=245214ea-76f9-4755-8a14-a74232e20c1c">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2:n Microsoft XML Core Services 3.0 (KB936021)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dea6a48f-fb00-43f3-a374-3220f9759c2d">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows  XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2:n Microsoft XML Core Services 3.0 (KB936021)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8862ca9-1203-4056-a257-29271838ac0d">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Microsoft XML Core Services 3.0 (KB936021)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12618ad0-aefd-4c9a-a769-4b14a7603d6e">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Microsoft XML Core Services 3.0 (KB936021)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=61bf00a9-aeea-431a-86d3-526a4a373bb7">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systemsin ja Windows Server 2003 with SP2 for Itanium-based Systemsin Microsoft XML Core Services 3.0 (KB936021)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0285dd7-bf66-4226-9948-26e8aae99046">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows Vistan Microsoft XML Core Services 3.0 (KB936021)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c734d7de-5d87-4904-81c3-714db2cb8b0d">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Editionin Microsoft XML Core Services 3.0 (KB936021)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a465d77-a737-4d26-82a1-570f9c788a8a">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4:ään asennettu Microsoft XML Core Services 4.0 (KB936181)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 ja Windows XP Service Pack 3 asennettu Microsoft XML Core Services 4.0 (KB936181)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows  XP Professional x64 Editioniin ja Windows XP Professional x64 Edition Service Pack 2:een asennettu Microsoft XML Core Services 4.0 (KB936181)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:een ja Windows Server 2003 Service Pack 2:een asennettu Microsoft XML Core Services 4.0 (KB936181)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows Server 2003 x64 Editioniin ja Windows Server 2003 x64 Edition Service Pack 2:een asennettu Microsoft XML Core Services 4.0 (KB936181)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systemsiin ja Windows Server 2003 with SP2 for Itanium-based Systemsiin asennettu Microsoft XML Core Services 3.0 (KB936021)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows Vistaan ja Windows Vista Service Pack 1:een asennettu Microsoft XML Core Services 4.0 (KB936181)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Editioniin ja Windows Vista x64 Edition Service Pack 1:een asennettu Microsoft XML Core Services 4.0 (KB936181)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows Server 2008 for 32-bit Systemsiin asennettu Microsoft XML Core Services 4.0 (KB936181)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64 Systemsiin asennettu Microsoft XML Core Services 4.0 (KB936181)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systemsiin asennettu Microsoft XML Core Services 4.0 (KB936181)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft XML Core Services 6.0<br />(KB933579) Microsoft Windows 2000 Service Pack 4:ään asennettuna</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows XP Service Pack 2:ään asennettu Microsoft XML Core Services 6.0 (KB933579)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows  XP Professional x64 Editioniin ja Windows XP Professional x64 Edition Service Pack 2:een asennettu Microsoft XML Core Services 6.0 (KB933579)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows Server 2003 Service Pack 1:een ja Windows Server 2003 Service Pack 2:een asennettu Microsoft XML Core Services 6.0 (KB933579)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Editioniin ja Windows Server 2003 x64 Edition Service Pack 2:een asennettu Microsoft XML Core Services 6.0 (KB933579)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows Server 2003 with SP1 for Itanium-based Systemsiin ja Windows Server 2003 with SP2 for Itanium-based Systemsiin asennettu Microsoft XML Core Services 6.0 (KB933579)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976">Keskitaso</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Vistan Microsoft XML Core Services 6.0 (KB933579)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14270529-3ae5-43bf-a471-722ab010d81e">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Windows Vista x64 Editionin Microsoft XML Core Services 6.0 (KB933579)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=928da3d2-b0b9-447a-b37a-4350497fe563">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
              
                <tr><th colspan="6">Office-ohjelmistot, joita haavoittuvuus koskee</th></tr>
              
                <tr class="alternateRow"><td>Microsoft Excel 2000 Service Pack 3</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=082b98f7-9556-4f1f-823a-c41ddf5a7c9a">Kriittinen</a>
                  </td><td /><td /></tr>
                <tr><td>Microsoft Excel 2002 Service Pack 3</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91308769-2577-4f9f-8209-06f2c8c8a86f">Tärkeä</a>
                  </td><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Excel 2003 Service Pack 2</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0130e9e-8845-4d79-aaa1-a21cc9388abe">Tärkeä</a>
                  </td><td /><td /></tr>
                <tr><td>Microsoft Office 2003 Service Pack 2 ja Microsoft XML Core Services 6.0 (KB936048)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a339cb7b-e08a-47f8-ac0b-df449191424a">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Excel Viewer 2003</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4a87572-3128-44f7-8069-95535a78500a">Tärkeä</a>
                  </td><td /><td /></tr>
                <tr><td>Microsoft Word Viewer 2003 ja Microsoft XML Core Services 5.0 (KB936048)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a339cb7b-e08a-47f8-ac0b-df449191424a">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Office 2004 for Mac</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/mac/downloads.aspx">Kriittinen</a>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/mac/downloads.aspx">Tärkeä</a>
                  </td><td /><td /></tr>
                <tr><td>2007 Office System ja Microsoft XML Core Services 5.0 (KB936960)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a97478a-832c-4a6b-b074-0e18b1e4ed33">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Office Groove Server 2007 ja Microsoft XML Core Services 5.0 (KB936056)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e875613b-2f32-4f28-a635-664a25c95c18">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
                <tr><td>Microsoft Office SharePoint Server ja Microsoft XML Core Services 5.0 (KB936056)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e875613b-2f32-4f28-a635-664a25c95c18">Kriittinen</a>
                  </td><td /><td /><td /><td /></tr>
              
                <tr><th colspan="6">Muut ohjelmistot, joita haavoittuvuus koskee</th></tr>
              
                <tr class="alternateRow"><td>Microsoft Visual Basic 6.0 Service Pack 6 (KB924053)</td><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1646fb0-29d5-4a6e-a8d2-304c4d7735b7">Kriittinen</a>
                  </td><td /><td /><td /></tr>
              </table>


**Huomautuksia**

**\[1\]** Tähän käyttöjärjestelmään on saatavana tietoturvapäivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa. 

#### Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot MS07-047 - MS07-050

**Ohjelmistot,** **joita haavoittuvuus koskee, ja lataussivustot**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
  </tr>
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=88628">
                      <strong>MS07-047</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=94465">
                      <strong>MS07-048</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=92734">
                      <strong>MS07-049</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=94737">
                      <strong>MS07-050</strong>
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
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
              
                <tr><th colspan="5">Windows-käyttöjärjestelmät, joita haavoittuvuus koskee</th></tr>
              
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr><td>Windows XP Professional x64 Edition</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 1</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr><td>Server 2003 x64 Edition</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <strong>[1]</strong>
                  </td><td /><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr><td>Windows Server 2003 with SP1 for Itanium-based Systems</td><td /><td /><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td /><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr><td>Windows Vista</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49a5bd84-da71-4529-b4d3-ac57dab59e01">Tärkeä</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td>
                    <strong>[1]</strong>
                  </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=24443f59-b908-480b-9b72-7094d4b5e128">Tärkeä</a>
                  </td><td /><td>
                    <strong>[1]</strong>
                  </td></tr>
              
                <tr><th colspan="5">Windows-käyttöjärjestelmien osat, joita haavoittuvuus koskee</th></tr>
              
                <tr><td>Internet Explorer 5.01 Service Pack 4 ja Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31e63d6f-b6b7-41d7-8ae6-dd7fcf89d477">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Windows 2000 Service Pack 4:n Internet Explorer 6 Service Pack 1</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7099d33a-0ef6-423f-824e-757482517612">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 2:n Internet Explorer 6</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4447d74f-09ea-4be0-9dae-c243ce657fb7">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Editionin Internet Explorer 6 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98ccd207-f4d0-4625-aeab-0ebf1643a5fd">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Internet Explorer 6</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=463535aa-e04e-4a30-b3ab-8cd6d8cdd13c">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Internet Explorer 6</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d4375d4-fb9b-4771-bd6f-e5d23eedbc6b">Kriittinen</a>
                  </td></tr>
                <tr><td>Internet Explorer 6, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7be313b-3405-42e1-9e4b-0cb6bf3d2cb1">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2:n Internet Explorer 7</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f5da816-194c-478e-8a96-9421a0c52c9f">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows XP Professional x64 Editionin Internet Explorer 7 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c3168a9-d959-4137-868a-ec70da737c21">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Internet Explorer 7</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59884e97-4912-4a9a-8a31-8182ea2d24db">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Internet Explorer 7</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=42060e27-de14-4d0c-92a0-138cb57fe2b5">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Internet Explorer 7, kun käyttöjärjestelmänä on Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a536206e-9d1b-49a8-81a1-53d46f2de973">Kriittinen</a>
                  </td></tr>
                <tr><td>Windows Vistan Internet Explorer 7</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2dd908a4-6152-4976-aaaa-01f5f37c9143">Kriittinen</a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Editionin Internet Explorer 7</td><td /><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=592435bc-1d43-4544-bd8a-4a2d829dc1a1">Kriittinen</a>
                  </td></tr>
                <tr><td>Microsoft Windows Server 2000 Service Pack 4:n Windows Media Player 7.1 </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f46b1fc-ee7b-437f-9492-67d003711021">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Microsoft Windows Server 2000 Service Pack 4:ään asennettu Windows Media Player 7.1 </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd4a6474-5fde-415e-840e-7d973cb71c95">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows XP Service Pack 2:n Windows Media Player 9 </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd4a6474-5fde-415e-840e-7d973cb71c95">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2:een asennettu Windows Media Player 10 </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48f5a9d3-b859-4cb6-a68e-abde76a14782">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2:n Windows Media Player 10</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=949580be-cbb3-4271-8ca0-0ead7f2d8801">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Windows Media Player 10</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8d9f1fdf-6d4c-44d4-9b5f-bdbe8ac28d7f">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Windows Media Player 10</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c04c7f2-728e-43bd-8574-26e411fcd129">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2:een asennettu Windows Media Player 11 </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a690d042-1137-4aaf-bd0e-565ea04d1f2b">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2:n Windows Media Player 11</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bdc89f34-c1ff-46ab-b52d-c02d51c5c373">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr class="alternateRow"><td>Windows Vistan Windows Media Player 11 </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80e5167c-4f75-4ce3-8b15-2f50958deec8">Tärkeä</a>
                  </td><td /><td /><td /></tr>
                <tr><td>Windows Vista x64 Editionin Windows Media Player 11</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf30b714-d6e7-47ea-b79e-84c18370a661">Tärkeä</a>
                  </td><td /><td /><td /></tr>
              
                <tr><th colspan="5">Muut ohjelmistot, joita haavoittuvuus koskee</th></tr>
              
                <tr class="alternateRow"><td>Microsoft Virtual PC 2004</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cbdeaa50-7115-4673-97c4-10009f9c5c42">Tärkeä</a>
                  </td><td /></tr>
                <tr><td>Microsoft Virtual PC 2004 Service Pack 1</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17ffe5a2-3551-4858-93b6-5e25af87d808">Tärkeä</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Microsoft Virtual Server 2005 Standard Edition</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc02ea6d-2884-4637-9894-3413a71329ee">Tärkeä</a>
                  </td><td /></tr>
                <tr><td>Microsoft Virtual Server 2005 Enterprise Edition</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da474b6f-9f0c-43f6-b432-050f7e76967d">Tärkeä</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Microsoft Virtual Server 2005 R2 Standard Edition</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43fa1327-8e5e-4c92-901f-1ff2a0a087b4">Tärkeä</a>
                  </td><td /></tr>
                <tr><td>Microsoft Virtual Server 2005 R2 Enterprise Edition</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2fc16c4-1fb0-4c09-b04a-684b40df8517">Tärkeä</a>
                  </td><td /></tr>
                <tr class="alternateRow"><td>Microsoft Virtual PC for Mac Version 6.1</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/mac/downloads.aspx">Tärkeä</a>
                  </td><td /></tr>
                <tr><td>Microsoft Virtual PC for Mac Version 7</td><td /><td /><td>
                    <a runat="server" href="http://www.microsoft.com/mac/downloads.aspx">Tärkeä</a>
                  </td><td /></tr>
              </table>


**Huomautuksia**

**\[1\]** Tähän käyttöjärjestelmään on saatavana tietoturvapäivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa. 

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security\_patch" avulla. Tietoturvapäivitykset voidaan ladata lisäksi Windows Update Catalog -palvelusta. Lisätietoja Windows Update Catalogista on [Microsoft Knowledge Base -artikkelissa 323166](http://support.microsoft.com/kb/323166).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla myös IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin, laajennettu Inventory-työkalu ja Enterprise Update Scan (EST) -työkalu. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyz** **er ja Enterprise Update Scan Tool**

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

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:? Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tässä kuussa:

  - Microsoft on julkaissut neljä tärkeää päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**, MU (Microsoft Update)- ja WSUS (Windows Server Update Services) -sivustoissa.
  - Microsoft on kaksi tärkeää Windows-päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**, WU (Windows Update) -sivustossa.

Huomaa, että nämä tiedot koskevat **vain** sellaisia tärkeitä päivityksiä, **jotka eivät ole tietoturvapäivityksiä** ja jotka julkaistaan saman päivänä kuin tietoturvatiedotteiden yhteenveto Microsoft Update-, Windows Update- ja Windows Server Update Services -sivustoissa. Tietoja **ei** julkaista muina päivinä julkaistavista päivityksistä, **jotka eivät ole tietoturvapäivityksiä**.

#### Tietoturvastrategiat ja yhteisö

**Korjaustiedostojen hall** **intamenetelmät**

[Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivitysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security\_patch" avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT P** **ro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense VCP:n](http://idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-042](http://go.microsoft.com/fwlink/?linkid=88350).
  - Tuntematon tutkija (yhteistyössä [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-042](http://go.microsoft.com/fwlink/?linkid=88350).
  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense VCP:n](http://idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-043](http://go.microsoft.com/fwlink/?linkid=70249).
  - Tuntematon tutkija (yhteistyössä [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-043](http://go.microsoft.com/fwlink/?linkid=70249).
  - Dyon Balding ([Secunia](http://secunia.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-044](http://go.microsoft.com/fwlink/?linkid=96778).
  - [NSFocus Security Team](http://www.nsfocus.com/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-045](http://go.microsoft.com/fwlink/?linkid=91712).
  - Brett Moore ([Security-Assessment.com](http://www.security-assessment.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-045](http://go.microsoft.com/fwlink/?linkid=91712).
  - [eEye Digital Security](http://www.eeye.com/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-046](http://go.microsoft.com/fwlink/?linkid=94466).
  - Piotr Bania (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayintiative.com/) kanssa)?ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-047](http://go.microsoft.com/fwlink/?linkid=88628).
  - Aviv Raff ([Finjan](http://www.finjan.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-048](http://go.microsoft.com/fwlink/?linkid=94465).
  - Aviv Raff (yhteistyössä [iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-024](http://go.microsoft.com/fwlink/?linkid=94465).
  - Rafal Wojtczuk ([McAfee Avert Labs](http://www.avertlabs.com/)) teki yhteistyötä Microsoftin kanssa selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa [MS07-049](http://go.microsoft.com/fwlink/?linkid=92734).
  - [eEye Digital Security](http://www.eeye.com/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-050](http://go.microsoft.com/fwlink/?linkid=94737).

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (14. elokuuta 2007): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (29. elokuuta 2007): Ohjelmistot, joita haavoittuvuus koskee -taulukko on päivitetty siten, että tietoturvatiedotteen MS07-044 kohdassa Office-ohjelmistot, joita haavoittuvuus koskee on muutettu kohdat Office 2000, Office XP ja Office 2003 kohdiksi Excel 2000, Excel 2002 ja Excel 2003.
  - V2.0 (13. marraskuuta 2007): Ohjelmistot, joita haavoittuvuus koskee -taulukko on päivitetty siten, että se sisältää tietoturvatiedotteen MS07-049 päivitetyt latauslinkit. Korjatun tietoturvapäivityksen voi nyt asentaa seuraaviin järjestelmiin: Microsoft Virtual PC 2004, Microsoft Virtual PC 2004 Service Pack 1, Microsoft Virtual Server 2005 Standard Edition, Microsoft Virtual Server 2005 Enterprise Edition, Microsoft Virtual Server 2005 R2 Standard Edition ja Microsoft Virtual Server 2005 R2 Enterprise Edition.
  - V3.0 (9. tammikuuta 2008): Ohjelmistot, joita haavoittuvuus koskee -taulukko on päivitetty siten, että tietoturvatiedotteeseen MS07-042 on lisätty Microsoft Word Viewer 2003. Sama Microsoft Office 2003 Service Pack 2 -päivitys koskee Microsoft Word Viewer 2003:a.
  - V4.0 (24.6.2008): Ohjelmistot, joita haavoittuvuus koskee -taulukko on päivitetty siten, että tietoturvatiedotteeseen MS07-042 (Microsoft XML Core Services 4.0:n KB936181-päivitys) on lisätty Windows XP Service Pack 3, Windows Vista Service Pack 1, Windows Vista x64 edition Service Pack 1, Windows Server 2008 for 32-bit Systems, Windows Server 2008 for x64-based Systems ja Windows Server 2008 for Itanium-based Systems. Muutos koskee ainoastaan tunnistusta. Binaareja ei ole muutettu.

*Built at 2014-04-18T01:50:00Z-07:00*

