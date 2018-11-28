---
title: Microsoftin turvatiedotteiden yhteenveto, kesäkuu 2008
TOCTitle: MS08-JUN
ms:assetid: ms08-jun
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms08-jun(v=Security.10)
ms:contentKeyID: 61225612
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, kesäkuu 2008

Julkaistu: 10. kesäkuuta 2008 | Päivitetty: 1. huhtikuuta 2009

**Versio:** 2.1

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo kesäkuussa 2008 julkaistuista tietoturvatiedotteista.

Kesäkuun 2008 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 5. toukokuuta 2008. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 11. kesäkuuta 2008, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt kesäkuun tietoturvatiedotteen web-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357225&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (3)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-030</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=119619"><strong>Bluetooth-pinon saattaa sallia koodin suorittamisen verkon välityksellä (951376)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windowsin Bluetooth-pinon haavoittuvuuden, joka saattaa sallia koodin suorittamisen verkon välityksellä. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
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
<td><strong>Microsoft Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-031</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116367"><strong>Internet Explorerin kumulatiivinen tietoturvapä</strong> <strong>ivitys (950759)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yhden yksityishenkilön ilmoittaman haavoittuvuuden ja yhden yleisessä tiedossa olleen haavoittuvuuden. Tämä yksityishenkilön ilmoittama haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet Explorerilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Tämä yleisessä tiedossa oleva haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet Explorerilla.</td>
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


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-033</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=118655"><strong>DirectX:n haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (951698)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamia Microsoft DirectX:n haavoittuvuutta, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun mediatiedoston. Hyödyntämällä jompaakumpaa haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Microsoft Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (3)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-034</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsik</strong> <strong>ko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111957"><strong>WINS:n haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen (948745)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman WINS:n (Windows Internet Name Service) haavoittuvuuden, joka saattaa sallia käyttöoikeuksien laajentamisen. Hyödyntämällä tätä haavoittuvuutta onnistuneesti paikallinen hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia, tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä.</td>
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
<th>Microsoftin tietoturvatiedote MS08-035</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111953"><strong>Active Directoryn haavoittuvuus voi aiheuttaa palveluneston (953235)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden, joka esiintyy seuraavissa Active Directory -toteutuksissa: Microsoft Windows 2000 Server, Windows Server 2003 ja Windows Server 2008, Windows XP Professional- ja Windows Server 2003 -käyttöjärjestelmiin asennettu ADAM (Active Directory Application Mode) sekä Windows Server 2008:aan asennettu AD LDS (Active Directory Lightweight Directory Service). Haavoittuvuutta hyödyntämällä hyökkääjä voi aiheuttaa palveluneston. Windows XP Professional-, Windows Server 2003- ja Windows Server 2008 -käyttöjärjestelmässä haavoittuvuuden hyödyntäminen edellyttää, että hyökkääjällä on voimassa olevat kirjautumistiedot. Tätä haavoittuvuutta hyödyntävä hyökkääjä voi saada järjestelmän lopettamaan pyyntöihin vastaamisen tai käynnistymään automaattisesti uudelleen.</td>
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
<th>Microsoftin tietoturvatiedote MS08-036</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=117297"><strong>P</strong> <strong>GM (Pragmatic General Multicast) -protokolla voi aiheuttaa palveluneston (950762)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa PGM (Pragmatic General Multicast) -protokollan haavoittuvuutta, jotka voivat aiheuttaa palveluneston, jos järjestelmä, jota haavoittuvuus koskee, vastaanottaa virheellisesti muodostettuja PGM-paketteja. Tätä haavoittuvuutta onnistuneesti hyödyntävä hyökkääjä saattaa aiheuttaa sen, että käyttäjän järjestelmä ei vastaa ja että normaalin toiminnan jatkaminen voi edellyttää uudelleenkäynnistämistä. Huomaa, että palvelunestohaavoittuvuus ei anna hyökkääjän suorittaa koodia tai nostaa käyttöoikeuksiensa tasoa, mutta se saattaa saada haavoittuvuuden sisältävän järjestelmän lopettamaan pyyntöjen vastaanottamisen.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Päivitys vaatii uudelleenkäynnistyksen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Microsoft Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Keskitaso (1)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-032</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116368"><strong>ActiveX Kill Bit -arvojen kumulatiivinen tietoturvapäivitys (950760)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa julkisesti raportoidun Microsoft Speech API:n haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua Internet Explorerilla ja jos Windowsin Puheentunnistus-toiminto on otettu käyttöön. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Tähän päivitykseen sisältyy myös BackWebin valmistama ohjelmiston Kill Bit -arvo.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Keskitaso</a></td>
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
<td><strong>Microsoft Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

**Miten taulukkoa käytetään?**

Tämän taulukon avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja edellyttääkö se tietoturvapäivityksen asentamista. Jos ohjelma tai osa on luettelossa, saatavana olevaan ohjelmistopäivitykseen on linkki. Myös ohjelmistopäivityksen luokitus mainitaan.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää useiden tietoturvapäivitysten asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

#### Windows-käyttöjärjestelmä ja palvelimet

<table>
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=119619"><strong>MS08-030</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116367"><strong>MS08-031</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=118655"><strong>MS08-033</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111957"><strong>MS08-034</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111953"><strong>MS08-035</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=117297"><strong>MS08-036</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116368"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td><strong>Tiedotteen luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Keskitaso</strong></a></td>
</tr>
<tr class="odd">
<td>Microsoft Windows 2000 Service Pack 4</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=88990b23-d37f-4d02-a5a3-2ee389ade53c">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(Tärkeä)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c47cf8a-8100-4d43-855a-f225a3492b19">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=65640123-a9e4-455c-a51a-9df28bd2d412">DirectX 7.0</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c6a28d45-13cf-48c4-8f89-3417d552e90b">DirectX 8.1</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4dc47e04-5e95-4636-a814-3f912d961461">DirectX 9.0, DirectX 9.0a, DirectX 9.0b tai DirectX 9.0c</a><br />
(Kriittinen)</td>
<td>Ei koske</td>
<td>Ei koske</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=cedfd988-232c-4cba-ac65-beb54b8946e0">Microsoft Windows 2000 Service Pack 4</a><br />
(Keskitaso)</td>
</tr>
<tr class="even">
<td>Microsoft Windows 2000 Server Service Pack 4</td>
<td>Ei koske</td>
<td>Ei koske</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=aa8aa79f-c2cc-440c-9e5c-089143e6f814">Microsoft Windows 2000 Server Service Pack 4</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=53438880-9ea9-4975-9b85-2a1d3d232793">Active Directory</a><br />
(KB949014)<br />
(Tärkeä)</td>
<td>Ei koske</td>
<td>Ei koske</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows XP</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=119619"><strong>MS08-030</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116367"><strong>MS08-031</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=118655"><strong>MS08-033</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111957"><strong>MS08-034</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111953"><strong>MS08-035</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=117297"><strong>MS08-036</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116368"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td><strong>Tiedotteen luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Keskitaso</strong></a></td>
</tr>
<tr class="odd">
<td>Windows XP Service Pack 2 ja Windows XP Service Pack 3</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=980bb421-950f-4825-8039-44cc961a47b8">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=cc325017-3a48-4475-90e4-0c79a002fce3">Microsoft Internet Explorer 6</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=fbc31bde-0bf5-490c-96a8-071310d9464a">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7aaa6427-1e22-4566-960c-836a3b9e5f36">DirectX 9.0, DirectX 9.0a, DirectX 9.0b tai DirectX 9.0c</a><br />
(Kriittinen)</td>
<td>Ei koske</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=36b14a81-5979-4e38-9ba3-ed83dfc17adf">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2d8957c2-e473-4dca-8d68-19fdaea36e26">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a><br />
(Keskitaso)</td>
</tr>
<tr class="even">
<td>Windows XP Professional Service Pack 2 ja Windows XP Professional Service Pack 3</td>
<td>(Katso Windows XP Service Pack 2:n ja Windows XP Service Pack 3:n rivi)</td>
<td>(Katso Windows XP Service Pack 2:n ja Windows XP Service Pack 3:n rivi)</td>
<td>(Katso Windows XP Service Pack 2:n ja Windows XP Service Pack 3:n rivi)</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7d6aec31-cfb4-470c-983e-78c6a3ebabfe">ADAM</a><br />
(KB949269)<br />
(Keskitaso)</td>
<td>(Katso Windows XP Service Pack 2:n ja Windows XP Service Pack 3:n rivi)</td>
<td>(Katso Windows XP Service Pack 2:n ja Windows XP Service Pack 3:n rivi)</td>
</tr>
<tr class="odd">
<td>Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=81ab56ca-933f-4974-a393-290a54c30a78">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c8783cfe-9da5-4842-ab3a-1e2be4fafc47">Microsoft Internet Explorer 6</a><br />
(Kriittinen)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=19c0ccdc-95c9-4151-96b6-4f49b594ebe0">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5e8e7e9d-828d-442c-acac-8d91e80dfb36">DirectX 9.0, DirectX 9.0a, DirectX 9.0b tai DirectX 9.0c</a><br />
(Kriittinen)</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ef2e0b48-1bde-4ccc-8f40-2918c2568b2b">ADAM</a><br />
(KB949269)<br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9e9d24ee-8183-428c-8067-168a8d85eaa1">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=62874096-7d17-4116-9795-4756e2fb6dae">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a><br />
(Keskitaso)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=119619"><strong>MS08-030</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116367"><strong>MS08-031</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=118655"><strong>MS08-033</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111957"><strong>MS08-034</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111953"><strong>MS08-035</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=117297"><strong>MS08-036</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116368"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td><strong>Tiedotteen luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Keskitaso</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=286aada6-a358-41f1-b81a-8de39b9f908a">Microsoft Internet Explorer 6</a><br />
(Keskitaso)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a1ae9ad2-8329-4c96-b950-7534b3287eaa">Windows Internet Explorer 7</a><br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2274ecb2-2802-47e2-84fd-6621fcb17758">DirectX 9.0, DirectX 9.0a, DirectX 9.0b tai DirectX 9.0c</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=08fc90d5-23aa-4327-8aef-16bc5170769d">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a4aed117-3c76-4d80-b50e-8e07e2ef2f7d">Active Directory</a><br />
(KB949014)<br />
(Keskitaso)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=0a983ffb-4f5a-4b78-9bf5-813dcc5df8d3">ADAM</a><br />
(KB949269)<br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=1e8e2faf-009f-403b-a5fe-a47cf014db3a">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=dadead99-09cb-4f2b-850d-e98a627cb9f8">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a><br />
(Ei tärkeä)</td>
</tr>
<tr class="even">
<td>Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6604569a-3db0-47e7-bd30-7dfba8145386">Microsoft Internet Explorer 6</a><br />
(Keskitaso)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=fb0c70b4-ce9f-43d6-875a-3cfd0d3a2681">Windows Internet Explorer 7</a><br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5ba63bb7-ed6d-4c59-88b3-456eda07e190">DirectX 9.0, DirectX 9.0a, DirectX 9.0b tai DirectX 9.0c</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=71675ae8-d60a-4834-b358-2d8e761e62fc">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8298a6e4-d3e2-48ea-ac29-aa4dc5a8ec77">Active Directory</a><br />
(KB949014)<br />
(Keskitaso)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=334252db-4a7a-4161-bb71-2a20c0b5bd93">ADAM</a><br />
(KB949269)<br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=78bf92d8-63c4-4596-8425-8fcfea7f5582">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=84f9b533-b0cb-46d1-b4a8-5c9469abbd22">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Ei tärkeä)</td>
</tr>
<tr class="odd">
<td>Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0262beb8-1eb5-4c2d-a50a-0c6c6e0c1f61">Microsoft Internet Explorer 6</a><br />
(Keskitaso)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=28d2913c-1c6b-4671-9892-de08698cd5a6">Windows Internet Explorer 7</a><br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=be71c002-2f64-49e9-9f4b-ba99c4f3caf6">DirectX 9.0, DirectX 9.0a, DirectX 9.0b tai DirectX 9.0c</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=87affdc9-d9fe-413c-af30-f3d3b671ec72">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=f6bf4b85-b91d-4378-a356-cd11f12cbbfd">Active Directory</a><br />
(KB949014)<br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5b7e94fa-22ed-4f7c-b452-647b2e620113">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(Tärkeä)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ac35ce19-d761-4529-9f55-1e1b5b2447ad">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a><br />
(Ei tärkeä)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Vista</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=119619"><strong>MS08-030</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116367"><strong>MS08-031</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=118655"><strong>MS08-033</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111957"><strong>MS08-034</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111953"><strong>MS08-035</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=117297"><strong>MS08-036</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116368"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td><strong>Tiedotteen luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Keskitaso</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Vista ja Windows Vista Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6524debe-be50-44d1-8543-af0bfaf086ad">Windows Vista ja Windows Vista Service Pack 1</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6d68b39d-157f-4c3d-ac76-bc5a9386db59">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4d4b305b-57f8-448d-92fa-3dcdd1f42ed7">DirectX 10.0</a><br />
(Kriittinen)</td>
<td>Ei koske</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ef2d2a4b-4831-41be-b5d0-8df5b01fd205">Windows Vista ja Windows Vista Service Pack 1</a><br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4af6575e-b061-45a6-b3d8-ecb32d76b2d3">Windows Vista ja Windows Vista Service Pack 1</a><br />
(Keskitaso)</td>
</tr>
<tr class="even">
<td>Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=6adee8b9-3455-4f3b-8bdd-2585c8ff83b8">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4cf92235-861e-4b74-bee3-8e977c8688d9">Windows Internet Explorer 7</a><br />
(Kriittinen)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b040cfad-2290-44f4-8f5a-5d1ed98a7265">DirectX 10.0</a><br />
(Kriittinen)</td>
<td>Ei koske</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0839fcf4-85ca-445e-896b-f634b10b6700">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a><br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=67576acb-9cb6-4c76-9a72-dc5e5556b658">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a><br />
(Keskitaso)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Server 2008</caption>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen numero</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=119619"><strong>MS08-030</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116367"><strong>MS08-031</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=118655"><strong>MS08-033</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111957"><strong>MS08-034</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111953"><strong>MS08-035</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=117297"><strong>MS08-036</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=116368"><strong>MS08-032</strong></a></td>
</tr>
<tr class="even">
<td><strong>Tiedotteen luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kriittinen</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Tärkeä</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Keskitaso</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Server 2008 for 32-bit Systems</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a8922e7e-9264-4e09-b8ad-c5420fed8690">Windows Internet Explorer 7</a><br />
(Keskitaso)<strong>**</strong></td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c0c495f8-2a35-4638-a635-1e55dd15e062">DirectX 10.0</a><br />
(Kriittinen)<strong>**</strong></td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2981156e-2e2f-469e-91be-da127d50f3fc">Active Directory</a><br />
(KB949014)<br />
(Keskitaso)<strong>*</strong><br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=2981156e-2e2f-469e-91be-da127d50f3fc">AD LDS</a><br />
(KB949014)<br />
(Keskitaso)<strong>*</strong></td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0466a6e7-fdca-4647-af62-449e5f20d1e4">Windows Server 2008 for 32-bit Systems</a><br />
(Keskitaso)<strong>**</strong></td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8a507fba-8c93-4952-91e4-98e9e7affbd2">Windows Server 2008 for 32-bit Systems</a><br />
(Ei tärkeä)<strong>***</strong></td>
</tr>
<tr class="even">
<td>Windows Server 2008 for x64-based Systems</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=05b0e838-24d7-4387-b069-2604bbcc43b9">Windows Internet Explorer 7</a><br />
(Keskitaso)<strong>**</strong></td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0b70fc2e-4e80-4ae8-8682-41ea04c24e4e">DirectX 10.0</a><br />
(Kriittinen)<strong>**</strong></td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b5cfe6f4-c5ba-4be9-a6b8-9381c40c85aa">Active Directory</a><br />
(KB949014)<br />
(Keskitaso)<strong>*</strong><br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=b5cfe6f4-c5ba-4be9-a6b8-9381c40c85aa">AD LDS</a><br />
(KB949014)<br />
(Keskitaso)<strong>*</strong></td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=304898e6-21a7-476f-b9ed-7ac0d88a91e2">Windows Server 2008 for x64-based Systems</a><br />
(Keskitaso)<strong>**</strong></td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=1a11499d-a008-407f-9084-a5189fa27015">Windows Server 2008 for x64-based Systems</a><br />
(Ei tärkeä)<strong>***</strong></td>
</tr>
<tr class="odd">
<td>Windows Server 2008 for Itanium-based Systems</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=640e1865-ebcc-4d69-a770-fd360020da1e">Windows Internet Explorer 7</a><br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=80ec83e0-cfb8-4a5e-9254-6679a7225b83">DirectX 10.0</a><br />
(Kriittinen)</td>
<td>Ei koske</td>
<td>Ei koske</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8907783b-e3fe-40b2-9fc8-4937e7d58b7e">Windows Server 2008 for Itanium-based Systems</a><br />
(Keskitaso)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=59b1689c-e723-4d87-973e-4beac107a6f7">Windows Server 2008 for Itanium-based Systems</a><br />
(Ei tärkeä)</td>
</tr>
</tbody>
</table>


**\*W** **indows Server 2008 Server Core -asennus, jota haavoittuvuus koskee.** Tämä päivitys koskee tuettuja Windows Server 2008 -versioita samalla luokituksella siitä riippumatta. onko Windows Server 2008:n asennuksessa käytetty Server Core -asennusta vai ei. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Windows Server 2008 Server Core -asennus, joita haavoittuvuus koskee.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksella. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Haavoittuvuus ei koske Windows Server 2008:n Server Core -asennusta, mutta tämä päivitys on tarjolla.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksena, vaikka järjestelmässä olisi tiedostoja, joita nämä haavoittuvuudet koskevat. Käyttäjille, joilla on haavoittuvia tiedostoja, kuitenkin tarjotaan tämä päivitys, koska päivitystiedostot ovat uudempia (niiden versionumero on suurempi) kuin järjestelmässä olevat tiedostot. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**System** **s Management Server**

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

**IT Pro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - Sebastian Apelt, Peter Vreugdenhil ja tuntematon tutkija (yhteistyössä [Tipping Pointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-031.
  - Mark Dowd ([IBM Internet Security Systems X-Forcen](http://xforce.iss.net/) tutkija) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-033.
  - Tuntematon tutkija (yhteistyössä [Tipping Pointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-033.
  - Alex Matthews ja John Guzik ([Securify](http://www.securify.com/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-035.

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (10. kesäkuuta 2008): Tietoturvatiedotteen yhteenveto julkaistu.
  - Versio 1.1 (11.6.2008): Ohjelmistot, joita haavoittuvuus koskee -taulukkoa on tarkennettu tietoturvatiedotteiden MS08-030, MS08-031, MS08-032, MS08-033 ja MS08-036 kohdalla käsittämään Windows XP:n osalta järjestelmät Windows XP Service Pack 2 ja Windows XP Service Pack 3.
  - 2.0 (16. heinäkuuta 2008): DirectX 9.0a on lisätty ohjelmistona, jota tietoturvatiedote MS08-033 koskee.
  - V2.1 (1. huhtikuuta 2009): Tietoturvatiedotteeseen MS08-032 on lisätty selvennys, että käsitelty haavoittuvuus ei koske Windows Server 2008:n Server Core -asennusta mutta päivitys on kuitenkin tarjolla. Tämä on vain tiedonanto. Kyseisten asennusten käyttäjien ei tarvitse asentaa tätä päivitystä.

*Built at 2014-04-18T01:50:00Z-07:00*

