---
title: Microsoftin turvatiedotteiden yhteenveto, huhtikuu 2008
TOCTitle: MS08-APR
ms:assetid: ms08-apr
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms08-apr(v=Security.10)
ms:contentKeyID: 61225606
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, huhtikuu 2008

Julkaistu: 8. huhtikuuta 2008 | Päivitetty: 18. helmikuuta 2009

**Versio:** 1.3

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo huhtikuussa 2008 julkaistuista tietoturvatiedotteista.

Huhtikuun 2008 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 3. huhtikuuta 2008. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 9. huhtikuuta 2008, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt huhtikuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357219&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (5)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-018</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115454"><strong>Microsoft Projectin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (950183)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Projectin haavoittuvuuden, joka saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Project-tiedoston. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Microsoft Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-021</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>GDI:n haavoittuvuudet saattavat salli</strong> <strong>a koodin suorittamisen verkon välityksellä (948590)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa GDI:n haavoittuvuutta. Jommankumman haavoittuvuuden hyödyntäminen saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun EMF- tai WMF-kuvatiedoston. Hyödyntämällä näitä haavoittuvuuksia onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Päivitys vaatii uudelleenkäynnistyksen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Microsoft Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-022</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>VBScript- ja JScript-komentosarjamoduulien haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (944338)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windowsin VBScript- ja JScript-komentosarjamoduulien haavoittuvuuden. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Päivitys vaatii uudelleenkäynnistyksen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Microsoft Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-023</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>ActiveX-estoarvojen tietoturvapäivitys (948881)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön Microsoft-tuotetta koskevan haavoittuvuuden. Tämä päivitys sisältää myös estoarvon Yahoo! Music Jukebox -tuotteeseen. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon avulla, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet Explorerilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Microsoft Windows, Internet Explorer.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-024</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (947864)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon avulla, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet Explorerilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Päivitys vaatii uudelleenkäynnistyksen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Microsoft Windows, Internet Explorer.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (3)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-020</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>DNS-asiakkaan haavoittuvuus saattaa sallia tietojen väärentämisen (945553)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Tämä Windows DNS -asiakkaissa olevan tietojen väärentämisen mahdollistavan haavoittuvuuden takia hyökkääjä saattaa pystyä lähettämään tietyllä tavalla muodostettuja vastauksia DNS-pyyntöihin ja väärentää tai uudelleenohjata näin internet-tietoliikennettä luotettavista sijainneista.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Tietojen väärentäminen</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Päivitys vaatii uudelleenkäynnistyksen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Microsoft Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-025</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>Windows-ytimen haavoittuvuus saattaa aiheuttaa käyttöoikeuksien laajentumisen (941693)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows-ytimen haavoittuvuuden. Hyödyntämällä tätä haavoittuvuutta onnistuneesti paikallinen hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia, tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Päivitys vaatii uudelleenkäynnistyksen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Microsoft Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-019</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115455"><strong>Microsoft Vision haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (949032)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittamat Microsoft Office Projectin haavoittuvuudet, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Visio-tiedoston. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Microsoft Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

**Miten taulukkoa käytetään?**

Tämän taulukon avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja edellyttääkö se tietoturvapäivityksen asentamista. Jos ohjelma tai osa on luettelossa, saatavana olevaan ohjelmistopäivitykseen on linkki. Myös ohjelmistopäivityksen luokitus mainitaan.

**Huomaut** **us** Yksittäinen haavoittuvuus saattaa edellyttää useiden tietoturvapäivitysten asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

#### Windows-käyttöjärjestelmä ja osat

<table>
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
</tr>
<tr class="odd">
<td>Microsoft Windows 2000 Service Pack 4</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=caac000a-22b6-48cb-aa00-1a0bfe886de2">Microsoft Windows 2000 Service Pack 4</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.1 ja JScript 5.1</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.6 ja JScript 5.6</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0395451f-b719-4f71-a7b4-403d0c7e8fcc">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=ba6d3aeb-e35a-47cc-bace-7bd9d58a9d3f">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b051ae04-fe81-440d-9136-d6b239ca954e">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=75d2dc78-e3a4-4ff6-9e2d-bf1935003e8e">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=41326ade-96b6-47ce-9291-d4e3039471c4">Microsoft Windows 2000 Service Pack 4</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8db9f328-da0e-4fb8-96c4-6d368b47c224">Microsoft Windows 2000 Service Pack 4</a><br />
(Tärkeä)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows XP</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
</tr>
<tr class="odd">
<td>Windows XP Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c2763dd8-a03e-4a48-aa86-a7ec00250a7a">Windows XP Service Pack 2</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c0124698-3b94-4474-9473-22a2f39a4a56">VBScript 5.6 ja JScript 5.6</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9dbf002f-fe53-4cc7-a430-35f45c520d10">Windows XP Service Pack 2</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=36c641ad-953f-4b09-ba1c-9c383295e180">Microsoft Internet Explorer 6</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=e771efe8-8881-4f23-b5b0-15651a390ba9">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=893f4cef-0395-4c44-ba28-7a10b6e7dd48">Windows XP Service Pack 2</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0e937f65-abd0-46dd-8883-5bfd70ea1178">Windows XP Service Pack 2</a><br />
(Tärkeä)</td>
</tr>
<tr class="even">
<td>Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=166f2ab5-913c-47a9-86fe-b814797b751e">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=87b80ae3-e299-4d15-a135-3b1bcf943652">VBScript 5.6 ja JScript 5.6</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=01400970-df68-4daf-aa39-2fc4f969974c">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=85beacc0-8ca2-4ded-9c24-23348d05c735">Microsoft Internet Explorer 6</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=9364bf81-6505-4788-958d-a4bd29dc98ad">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8fdd1207-6e93-4c43-bacc-fe3623a6ebe7">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a29bbd13-761f-44fa-8948-e1a8c244bd7a">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a><br />
(Tärkeä)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen</strong> <strong>numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-</strong> <strong>022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-</strong> <strong>024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-</strong> <strong>020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bee91d80-d49a-4d3d-82d6-d5aa63f54979">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=88518aa6-e334-4529-aa63-0bf2ef417ce3">VBScript 5.6 ja JScript 5.6</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ad384fea-53be-4be3-8acb-1cd23a7f5405">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a><br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0444b76e-93fa-43c2-b1bc-a5c054529eb5">Microsoft Internet Explorer 6</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=9acd2a03-5530-49c8-9ea1-0bfaf259700d">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=214bd8f5-6eb2-414c-b013-c516a306d692">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d3b855a6-4648-4771-826d-11a151828eac">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a><br />
(Tärkeä)</td>
</tr>
<tr class="even">
<td>Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e3dde449-e062-4ce0-a9f4-433bff23e224">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=12cefefc-8553-4dca-9850-c653371de61e">VBScript 5.6 ja JScript 5.6</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ffc5c893-cb24-4875-b0a7-6d5c7aa4d642">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5ebb5ef9-615f-4cab-bac5-6f45f1b94952">Microsoft Internet Explorer 6</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a9e406aa-33e2-49b8-ab54-4a7328e46147">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fd123394-a5d6-4b55-be74-2938f52ce922">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=320fd100-35e1-4345-9399-796393235cbc">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Tärkeä)</td>
</tr>
<tr class="odd">
<td>Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7886a802-f2b5-489c-b14b-631f4c4c0742">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fe22a828-cca4-4b51-bbd5-995c65fead21">VBScript 5.6 ja JScript 5.6</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=94cf78d3-b6c3-41bc-993e-3af3be0d70f1">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=63da8040-fda2-42c7-8543-26ad6f9811f2">Microsoft Internet Explorer 6</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=75a05d3a-92a0-4a00-95d4-e2b2f6755180">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e0e63f03-904d-47ee-94fc-51a8dea668eb">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=126426a7-be38-4327-89db-02d99d76589d">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(Tärkeä)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Vista</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Vista ja Windows Vista Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9b51deb8-3873-4146-977f-7e3d0840a4c5">Windows Vista ja Windows Vista Service Pack 1</a><br />
(Kriittinen)</td>
<td>Ei mitään</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d7f14001-7f42-4ca0-9193-cdf061179b59">Windows Vista ja Windows Vista Service Pack 1</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d4e24966-6530-463a-9ee2-f6a9d000f998">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8203d303-c855-4579-9bbf-b06ddf5c1b87">Windows Vista</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9640cd8b-d749-4ddd-8af9-b298cebed969">Windows Vista ja Windows Vista Service Pack 1</a><br />
(Tärkeä)</td>
</tr>
<tr class="even">
<td>Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4ad6dcd1-6ea5-43bf-8bee-a5f507beadc6">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a><br />
(Kriittinen)</td>
<td>Ei mitään</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d33462b6-7391-482d-babe-fb4cd0beaa21">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=295cf8f2-265e-4570-b708-21033337fe05">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=73f3a234-3973-4467-be7e-69efa7ee978c">Windows Vista x64 Edition</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d56bb4fe-304e-45e0-95f2-fde2f47b2a04">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a><br />
(Tärkeä)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Server 2008</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Server 2008 for 32-bit Systems</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=006d5c47-53e6-4ee1-932c-497611804938">Windows Server 2008 for 32-bit Systems</a><br />
(Kriittinen)</td>
<td>Ei mitään</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=95691924-2813-4a86-9e11-99d853f8e606">Windows Server 2008 for 32-bit Systems</a><br />
(Ei tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e57b4d94-19ad-4818-8311-a3f94be01a4b">Windows Internet Explorer 7</a>*<br />
(Kriittinen)</td>
<td>Ei mitään</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4497333c-9418-4b91-83dc-0155735421c0">Windows Server 2008 for 32-bit Systems</a><br />
(Tärkeä)</td>
</tr>
<tr class="even">
<td>Windows Server 2008 for x64-based Systems</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8909f144-655b-4f07-916f-fd967f1efb2b">Windows Server 2008 for x64-based Systems</a><br />
(Kriittinen)</td>
<td>Ei mitään</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=920ae29b-19d0-4089-ac79-f2da824a2256">Windows Server 2008 for x64-based Systems</a><br />
(Ei tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=93e9f52a-c7d0-4033-9c12-740665a219af">Windows Internet Explorer 7</a>*<br />
(Kriittinen)</td>
<td>Ei mitään</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5aefc7a6-79a4-45a2-b534-35d0ec400dda">Windows Server 2008 for x64-based Systems</a><br />
(Tärkeä)</td>
</tr>
<tr class="odd">
<td>Windows Server 2008 for Itanium-based Systems</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b7771a4a-4e4f-48d1-8551-bb8b778ca5a7">Windows Server 2008 for Itanium-based Systems</a><br />
(Kriittinen)</td>
<td>Ei mitään</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=66df79ac-8364-4922-9688-ebc7ec76d89f">Windows Server 2008 for Itanium-based Systems</a><br />
(Ei tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=acf948e8-c4a9-40da-b282-f5e584e77b05">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td>Ei mitään</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3080c26b-7456-41ef-8668-28f15bc7b8ce">Windows Server 2008 for Itanium-based Systems</a><br />
(Tärkeä)</td>
</tr>
</tbody>
</table>


**\*Haavoittuvuus ei koske Windows Server 2008 Server Core -asennuksia.** Haavoittuvuudet, jotka nämä päivitykset korjaavat, eivät koske tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksena, vaikka järjestelmässä olisi tiedostoja, joita nämä haavoittuvuudet koskevat. Käyttäjille, joilla on haavoittuvia tiedostoja, kuitenkin tarjotaan tämä päivitys, koska päivitystiedostot ovat uudempia (niiden versionumero on suurempi) kuin järjestelmässä olevat tiedostot. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office -ohjelmistopaketit ja -ohjelmisto

<table>
<caption>Microsoft Project</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115454"><strong>MS08-018</strong></a></td>
</tr>
<tr class="even">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
</tr>
<tr class="odd">
<td>Microsoft Project 2000 Service Release 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fbe46241-b9da-40c6-803d-42eb6234be77">Project 2000 Service Release 1</a><br />
(KB949043)<br />
(Kriittinen)</td>
</tr>
<tr class="even">
<td>Microsoft Project 2002 Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=07a90718-6597-426d-9dca-a336d60c01b8">Project 2002 Service Pack 1</a><br />
(KB949005)<br />
(Tärkeä)</td>
</tr>
<tr class="odd">
<td>Microsoft Project 2003 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=aaba07d6-e972-4e85-bccd-406aa2c4a4f4">Project 2003 Service Pack 2</a><br />
(KB948962)<br />
(Tärkeä)</td>
</tr>
</tbody>
</table>


<table>
<caption>Microsoft Visio</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115455"><strong>MS08-019</strong></a></td>
</tr>
<tr class="even">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
</tr>
<tr class="odd">
<td>Microsoft Visio 2002 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0056a936-def5-40fa-bcfc-0ab0dd5c3964">Visio 2002 Service Pack 2</a><br />
(KB947896)<br />
(Tärkeä)</td>
</tr>
<tr class="even">
<td>Microsoft Visio 2003 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 Service Pack 2</a><br />
(KB947650)<br />
(Tärkeä)</td>
</tr>
<tr class="odd">
<td>Microsoft Visio 2003 Service Pack 3</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 Service Pack 3</a><br />
(KB947650)<br />
(Tärkeä)</td>
</tr>
<tr class="even">
<td>Microsoft Visio 2007</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007</a><br />
(KB947590)<br />
(Tärkeä)</td>
</tr>
<tr class="odd">
<td>Microsoft Visio 2007 Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007 Service Pack 1</a><br />
(KB947590)<br />
(Tärkeä)</td>
</tr>
</tbody>
</table>


## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin ja laajennettu Inventory-työkalu (ESUIT). Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Ser** **ver Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso myös [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) -sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tietoja Windows Update- ja Microsoft Update -sivustoissa julkaistavista päivityksistä, jotka eivät ole tietoturvapäivityksiä:

  - [Microsoft Knowledge Base -artikkeli 894199](http://support.microsoft.com/kb/894199): Kuvaus Software Update Services- ja Windows Server Update Services -sisällön muutoksista vuonna 2008. Sisältää kaiken Windows-sisällön.
  - [Muiden Microsoft-tuotteiden kuin Microsoft Windowsin uudet, päivitetyt ja julkaistut päivitykset](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

#### Tietoturvastrategiat ja yhteisö

**Korjaustiedostojen hallintamenetelmät**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivitysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT Pro Securit** **y Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - [National Cyber Security Center](http://www.ncsc.go.kr/eng/) (Etelä-Korea) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-018
  - Tuntematon löytäjä ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-019
  - Tuntematon löytäjä ilmoitti toisesta haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-019
  - Amit Klein ([Trusteer](http://www.trusteer.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-020
  - Alla Berzroutchko ([Scanit](http://www.scanit.be/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-020
  - Roy Arends ([Nominet UK](http://www.nominet.org.uk/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-020
  - Jun Mao ([iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-021
  - Sebastian Apelt ([Zero Day Initiative](http://www.zerodayinitiative.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-021
  - Thomas Garnier ([SkyRecon](http://www.skyrecon.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-021
  - Yamata Li ([Palo Alto Networks](http://www.paloaltonetworks.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-021
  - Peter Ferrie ([Symantec](http://www.symantec.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-022
  - Tuntematon tutkija (yhteistyössä [iDefense VCP:n](http://labs.idefense.com/vcp/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-023.
  - Carsten Eiram ([Secunia](http://secunia.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-024.
  - Thomas Garnier ([SkyRecon](http://www.skyrecon.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-025

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (8. huhtikuuta 2008): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (9. huhtikuuta 2008): Microsoftin tietoturvatiedotteen MS08-018 yhteenvedon päivitys.
  - V1.2 (16. huhtikuuta 2008): Haavoittuvuuden löytäjän tiedot päivitetty tietoturvatiedotteessa MS08-021 sekä selkeytetty Microsoft Office -ohjelmistopaketteja ja -ohjelmistoja, joita haavoittuvuus koskee.
  - V1.3 (18. helmikuuta 2009): Tietoturvatiedotteeseen MS08-024 on lisätty Windows Server 2008 for 32-bit Systemsiä ja Windows Server 2008 for x64-based Systemsiä koskeva huomautus siitä, että ongelma ei koske Server Core -asennusta.

*Built at 2014-04-18T01:50:00Z-07:00*

