---
title: Microsoftin turvatiedotteiden yhteenveto, lokakuu 2008
TOCTitle: MS08-OCT
ms:assetid: ms08-oct
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms08-oct(v=Security.10)
ms:contentKeyID: 61225616
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, lokakuu 2008

Julkaistu: 14. lokakuuta 2008 | Päivitetty: 23. lokakuuta 2008

**Versio:** 3.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo lokakuussa 2008 julkaistuista tietoturvatiedotteista.

Lokakuun 2008 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 9. lokakuuta 2008. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 15. lokakuuta 2008, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt lokakuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374639) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (5)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-067</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=130719"><strong>Palvelinpalvelun haavoittuvuus saattaa sallia koodin suorittamisen etäyhteyden välityksellä (958644)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman palvelinpalvelun haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jossa käyttäjä vastaanotti tietyllä tavalla muodostetun RPC-pyynnön haavoittuvuuden sisältävässä järjestelmässä. Microsoft Windows 2000-, Windows XP- ja Windows Server 2003 -järjestelmissä hyökkääjä voi hyödyntää tätä haavoittuvuutta ja suorittaa koodia ilman todennusta. Tämä haavoittuvuutta voi olla mahdollista käyttää siten, että muodostetaan sitä hyödyntävä mato. Palomuurikäytännöistä ja palomuurin vakiomäärityksistä annetut toimintaohjeet suojaavat verkkoresursseja hyökkäyksiltä, joiden lähde on yritysverkon ulkopuolella.</td>
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
<th>Microsoftin tietoturvatiedote MS08-060</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128125"><strong>Active Directoryn haavoittuvuus saattaa sallia koodin suorittamisen ver</strong> <strong>kon välityksellä (957280)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden Microsoft Windows 2000 Serverin Active Directory -toteutuksissa. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä pääsee käsiksi verkkoon, jota haavoittuvuus koskee. Tämä haavoittuvuus koskee vain sellaisia Microsoft Windows 2000 Servereitä, jotka on määritetty toimialueen ohjauskoneiksi. Jos Microsoft Windows 2000 Serveriä ei ole korotettu toimialueen ohjauskoneeksi, se ei kuuntele LDAP- tai LDAPS-kyselyjä eikä altistu tälle haavoittuvuudelle.</td>
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
<th>Microsoftin tietoturvatiedote MS08-058</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060"><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (956390)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa viisi yksityishenkilön ilmoittamia haavoittuvuuksia ja yhden yleisessä tiedossa olleen haavoittuvuuden. Haavoittuvuudet saattavat sallia tietojen paljastumisen muille käyttäjille tai koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua Internet Explorerilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<th>Microsoftin tietoturvatiedote MS08-059</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=125712"><strong>H</strong> <strong>ost Integration Serverin RPC-palvelun haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (956695)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Host Integration Serverin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä lähettää tietyllä tavalla muodostetun RPC-pyynnön haavoittuvuuden sisältävään järjestelmään. Vaikutukset sellaisiin asiakkaisiin, jotka noudattavat hyviä käytäntöjä ja ovat määrittäneet SNA RPC -palvelutilin siten, että järjestelmään on vähän käyttöoikeuksia, ovat vähäisemmät kuin vaikutukset asiakkaisiin, jotka ovat määrittäneet SNA RPC -palvelutilille järjestelmänvalvojan oikeudet.</td>
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
<td><strong>Microsoft Host Integration Server.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-057</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653"><strong>Microsoft Excelin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (956416)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa kolme yksityishenkilön ilmoittamaa Microsoft Office Excelin haavoittuvuutta, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Excel-tiedoston. Hyödyntämällä näitä haavoittuvuuksia onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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


## Tärkeä (6)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-066</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=125709"><strong>Microsoftin lisäfunktio-ohjaimen haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (956803)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoftin lisäfunktio-ohjaimen haavoittuvuuden. Hyödyntämällä tätä haavoittuvuutta onnistuneesti paikallinen hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
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
<th>Microsoftin tietoturvatiedote MS08-061</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738"><strong>Windows-ytimen haavoittuvuus voi sallia käyttöoikeuksien korottamisen (954211)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yhden yleisessä tiedossa olevan Windows-ytimen haavoittuvuuden ja kaksi yksityishenkilön ilmoittamaa Windows-ytimen haavoittuvuutta. Hyödyntämällä näitä haavoittuvuuksia onnistuneesti paikallinen hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään näitä haavoittuvuuksia.</td>
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
<td><strong>Ohjelmistot, joita haavoittuvuus</strong> <strong>koskee</strong></td>
<td><strong>Microsoft Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-062</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120829"><strong>Windowsin internet-tulostuspalvelun haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (953155)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windowsin internet-tulostuspalvelun haavoittuvuuden, joka saattaa sallia koodin suorittamisen verkon välityksellä. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia, tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä.</td>
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
<th>Microsoftin tietoturvatiedote MS08-063</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=127994"><strong>SMB:n haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (957095)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoftin SMB-protokollan haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä palvelimessa, jossa jaetaan tiedostoja tai kansioita. Näitä haavoittuvuuksia onnistuneesti hyödyntänyt hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
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
<th>Microsoftin tietoturvatiedote MS08-064</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128103"><strong>Näennäisosoitteen kuvaajan käsittelyn haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (956841)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman näennäisosoitteen kuvaajan haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen, jos käyttäjä suorittaa tietyllä tavalla muodostetun sovelluksen. Hyödyntämällä tätä haavoittuvuutta todennetun hyökkääjän käyttöoikeuksia voidaan korottaa haavoittuvuuden sisältämässä järjestelmässä. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda tilejä kaikilla valtuuksilla.</td>
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
<th>Microsoftin tietoturvatiedote MS08-065</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128102"><strong>Message Queuing -haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (951071)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys ratkaisee yksityishenkilön ilmoittaman haavoittuvuuden, joka koskee Microsoft Windows 2000 -järjestelmien MSMQ (Message Queuing) -palvelua. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä Microsoft Windows 2000 -järjestelmissä, joissa on otettu käyttöön MSMQ-palvelu.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoitt</strong> <strong>uvuuden vaikutus</strong></td>
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


## Keskitaso (1)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-056</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128145"><strong>Microsoft Officen haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille (957699)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Officen haavoittuvuuden. Haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille, jos käyttäjä napsauttaa tietyllä tavalla muodostettua CDO-URL-osoitetta. Tätä haavoittuvuutta hyödyntävä hyökkääjä voi lisätä käyttäjän selaimeen sellaisen asiakkaan komentosarjan, joka voi väärentää sisältöä, paljastaa tietoja tai tehdä muita toimia, joita käyttäjä voi tehdä haavoittuvuuden sisältävässä sivustossa.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Microsoft Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Hyödyntämisindeksi

**Kuinka taulukkoa käytetään?**

Tämän taulukon avulla saat selville, kuinka todennäköistä on sellaisen hyväksikäyttökoodin julkaiseminen, joka koskee tietoturvapäivitystä, joka sinun on ehkä asennettava. Tutustu järjestelmän määritysten perusteella kuhunkin arviointiin. Tällä tavoin voit ottaa päivitykset käyttöön tärkeysjärjestyksessä. Lisätietoja näistä luokituksista ja niiden määrittämisestä on [Microsoftin hyödyntämisindeksissä](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table>
<thead>
<tr class="header">
<th>Tiedotteen tunnus</th>
<th>Tiedotteen otsikko</th>
<th>CVE-tunnus</th>
<th>Hyödyntämisindeksin arvio</th>
<th>Tärkeät huomautukset</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128145">MS08-056</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128145">Microsoft Officen haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille (957699)</a></td>
<td>CVE-2008-4020</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td>Toimiva hyväksikäyttökoodi voidaan luoda. Ongelman vakavuutta rajoittaa se, että haavoittuvuus sallii valintaikkunan väärentämisen vain tietyissä verkkosovellustilanteissa. Tämän vuoksi hyökkääjät eivät ehkä ole siitä kovin kiinnostuneita.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">MS08-057</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">Microsoft Excelin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (956416)</a></td>
<td>CVE-2008-4019</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 - Yhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">MS08-057</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">Microsoft Excelin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (956416)</a></td>
<td>CVE-2008-3471</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">MS08-057</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">Microsoft Excelin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (956416)</a></td>
<td>CVE-2008-3477</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Internet Explorerin kumulatiivinen tietoturvapäivitys (956390)</a></td>
<td>CVE-2008-2947</td>
<td>(Yleisessä tiedossa, kun tiedote julkaistaan)</td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Internet Explorerin kumulatiivinen tietoturvapäivitys (956390)</a></td>
<td>CVE-2008-3472</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 - Yhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Internet Explorerin kumulatiivinen tietoturvapäivitys (956390)</a></td>
<td>CVE-2008-3473</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 - Yhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Internet Explorerin kumulatiivinen tietoturvapäivitys (956390)</a></td>
<td>CVE-2008-3475</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Internet Explorerin kumulatiivinen tietoturvapäivitys (956390)</a></td>
<td>CVE-2008-3474</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3 - Toimiva hyväksikäyttökoodi epätodennäköinen</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Internet Explorerin kumulatiivinen tietoturvapäivitys (956390)</a></td>
<td>CVE-2008-3476</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3 - Toimiva hyväksikäyttökoodi epätodennäköinen</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125712">MS08-059</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=125712">Host Integration Serverin RPC-palvelun haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (956695)</a></td>
<td>CVE-2008-3466</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 - Yhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td>Vaikka todennäköisesti vain tietynlaiset yritysasiakkaat asentavat Host Integration Serverin, on todennäköistä, että toimiva hyväksikäyttökoodi luodaan.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128125">MS08-060</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128125">Active Directoryn haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (957280)</a></td>
<td>CVE-2008-4023</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td>On todennäköistä, että haavoittuvuuden käynnistäminen aiheuttaa palveluneston. Koodin suorittamista verkon välityksellä hyödyntävän hyväksikäyttökoodin luominen on kuitenkin vaikeaa, koska tarvittavaa kirjoitusosoitetta ei voi hallita.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">MS08-061</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">Windows-ytimen haavoittuvuus voi sallia käyttöoikeuksien korottamisen (954211)</a></td>
<td>CVE-2008-2250</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 - Yhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">MS08-061</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">Windows-ytimen haavoittuvuus voi sallia käyttöoikeuksien korottamisen (954211)</a></td>
<td>CVE-2008-2252</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 - Yhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td>Toimiva heikkoutta hyödyntävä ohjelma luodaan todennäköisimmin moniytimisiin järjestelmiin.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">MS08-061</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">Windows-ytimen haavoittuvuus voi sallia käyttöoikeuksien korottamisen (954211)</a></td>
<td>CVE-2008-2251</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3 - Toimiva hyväksikäyttökoodi epätodennäköinen</a></td>
<td>Haavoittuvuuden käynnistäminen voi olla mahdollista, mutta onnistuneesti toimivan hyväksikäyttökoodin luominen on erittäin vaikeaa.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=120829">MS08-062</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120829">Windowsin internet-tulostuspalvelun haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (953155)</a></td>
<td>CVE-2008-1446</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 - Yhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td>Rajoitetuista, kohdistetuista hyökkäyksistä on löydetty yhtenäinen hyväksikäyttökoodi. Vaikka IPP (Internet Printing Protocol) -palvelu on otettu oletusarvoisesti käyttöön, tämän palvelun käyttäminen IIS-palvelulla edellyttää oletusarvoisesti myös, että kaikki alustat todentavat käyttäjän.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=127994">MS08-063</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=127994">SMB:n haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (957095)</a></td>
<td>CVE-2008-4038</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128103">MS08-064</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128103">Näennäisosoitteen kuvaajan käsittelyn haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (956841)</a></td>
<td>CVE-2008-4036</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128102">MS08-065</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128102">Message Queuing -haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (951071)</a></td>
<td>CVE-2008-3479</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3 - Toimiva hyväksikäyttökoodi epätodennäköinen</a></td>
<td>Vaikka tietojen paljastuminen muille voi olla mahdollista, hyödyllisen sisällön saaminen muistista ei ole aina mahdollista. Muistin vahingoittuminen voi käynnistyä, mutta koodin suorittaminen verkon välityksellä on vaikeaa.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125709">MS08-066</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=125709">Microsoftin lisäfunktio-ohjaimen haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (956803)</a></td>
<td>CVE-2008-3464</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 - Yhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130719">MS08-067</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=130719">Palvelinpalvelun haavoittuvuus saattaa sallia koodin suorittamisen etäyhteyden välityksellä (958644)</a></td>
<td>CVE-2008-4250</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 - Yhtenäinen hyväksikäyttökoodi todennäköinen</a></td>
<td>Windows XP:tä koskevista rajoitetuista, kohdistetuista hyökkäyksistä on löydetty yhtenäinen hyväksikäyttökoodi. Vaikka tämä palvelu on otettu oletusarvoisesti käyttöön kaikissa järjestelmissä, joita haavoittuvuus koskee, sitä hyödynnetään todennäköisimmin Microsoft Windows 2000-, Windows XP- ja Windows Server 2003 -järjestelmissä. Windows Vista-, Windows Server 2008- ja Windows 7 Beta -järjestelmät edellyttävät todennusta, joten haavoittuvuuden hyödyntäminen on hankalampaa ASLR- ja DEP-parannusten vuoksi.</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

**Kuinka taulukkoa käytetään?**

Tämän taulukon avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja edellyttääkö se tietoturvapäivityksen asentamista. Jos ohjelma tai osa on luettelossa, saatavana olevaan ohjelmistopäivitykseen on linkki. Myös ohjelmistopäivityksen luokitus mainitaan.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää usean tietoturvapäivityksen asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

#### Windows-käyttöjärjestelmä ja osat

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
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="10">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-</strong>
                      <strong>064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen luokitus</strong>
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
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e22eb3ae-1295-4fe2-9775-6f43c5c2aed3">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ed7bb9a-4b26-49d7-8c14-60226d2bc20d">Microsoft Windows 2000 Server Service Pack 4:n Active Directory</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=257c0478-56dd-42eb-a90e-607d01613db7">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=02390258-08e9-4b75-960d-be081b749558">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kriittinen)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a6165a6-d7e7-4526-9291-290caf0639b4">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8163d1f6-feb5-4f39-8134-3ed42326b822">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ed29c3a-0682-4586-bbc2-a73deaa18e4c">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=899e2728-2433-4ccb-a195-05b5d65e5469">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="10">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-</strong>
                      <strong>063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Tiedotteen luokitus</strong>
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
                <tr class="alternateRow"><td>Windows XP Service Pack 2 ja Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d5f9b6e-9265-44b9-a376-2067b73d6a03">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Kriittinen)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7f0f47b-b1ee-4516-9fbf-bf8e579963d0">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e73de2b-05e6-4901-9bac-46d8f469e635">Windows Internet Explorer 7</a><br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b16d9dac-c430-4dd8-a1e5-9a614801f1d9">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Tärkeä)<br /></td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7718bf14-c26c-43f3-be67-4c79ab5b2607">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Tärkeä)<br /></td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7ef571f-c9e8-4e14-95a3-3eeaec55b784">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Tärkeä)<br /></td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7e5981-6eef-4f08-86c0-c6a7607ea5d0">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Tärkeä)<br /></td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25997b73-a640-49c1-b19e-768a18bbe22c">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Tärkeä)<br /></td><td>Ei koske</td></tr>
                <tr><td>Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c16a372-7bf8-4571-b982-dac6b2992b25">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=234c05fb-988b-4e02-aab6-bb23e447df3d">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ccf7a3e3-ec30-4b95-9a86-00032301513c">Windows Internet Explorer 7</a><br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b607efc-c6fb-4079-8478-e4f3262386d3">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b06d3a02-b6e4-4d40-913a-3759a31f20f3">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ae4b913-bff0-4974-b198-828ca10d2a87">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e1675eb-6b06-48e9-9765-23a2c7737bdc">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50fae854-0bde-46f8-9444-b9e0d9bfecad">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="10">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Tiedotteen luokitus</strong>
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
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f26d395d-2459-4e40-8c92-3de1c52c390d">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae8d22d5-20aa-471d-a423-f54c9d75febe">Microsoft Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feaf2adf-7892-4dbf-a147-db4d5dbe52f3">Windows Internet Explorer 7</a><br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee88ff2d-1b12-4f4c-a081-9f27a6fba074">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e696762-d652-4a8f-ab8f-622f9746c320">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=437a9b68-6a0c-48c8-9348-0d6fda48aa21">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbbebb3f-f1c7-402c-bd16-6f88da0d042c">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8ef3d5f-dd8e-4945-92cd-9d3e30b16667">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c04d2afb-f9d0-4e42-9e1f-4b944a2de400">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=07fc88c4-2571-4a4d-b573-ae576798ab4c">Microsoft Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=319dba34-07ca-47f9-a1e9-20df2df7966b">Windows Internet Explorer 7</a><br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab4d94d3-458c-4946-ab7f-03a279629d25">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57ca28ea-e5e1-4191-a3d6-84aa90a3d668">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3df6508-a568-449d-ac97-fbf3f97b98ef">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=989ac6f1-515c-467d-a200-2aabe66d9319">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2e754f9-086a-494c-bc19-5feed7df8b65">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab590756-f11f-43c9-9dcc-a85a43077acf">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Kriittinen)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b68937af-f04a-4d1e-9d7f-ec92af5194de">Microsoft Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47381d91-4a14-4a09-96b3-3345155df52d">Windows Internet Explorer 7</a><br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63234f85-6e5d-4ef6-b7cf-d1d2c78a5517">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e6c3f81-85bb-48e6-a5af-635a7e540c93">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=748f54f1-40b9-407c-9819-909061b53743">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91589cfb-15ba-4dd2-9e3b-107899fbcba6">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a3832ec-3f8f-42c1-a603-b1330d527547">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="10">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-</strong>
                      <strong>063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen luokitus</strong>
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
                <tr><td>Windows Vista ja Windows Vista Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18fdff67-c723-42bd-ac5c-cac7d8713b21">Windows Vista ja Windows Vista Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4756e04b-6e1c-4d78-a3c0-17f6b4b97975">Windows Internet Explorer 7</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3483b400-cedc-441f-ba8e-594e3df89190">Windows Vista ja Windows Vista Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b5995df-a3b8-4e81-b118-9bb057e19884">Windows Vista ja Windows Vista Service Pack 1</a>
                    <br />(Ei luokitusta)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72dd6015-25d1-45f4-a769-88ac43074b44">Windows Vista ja Windows Vista Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b4212db5-093e-497d-b999-2e3780f9f7c2">Windows Vista ja Windows Vista Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a976999d-264f-4e6a-9bd6-3ad9d214a4bd">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd19c72b-4f83-47ab-93be-d2c286e732c4">Windows Internet Explorer 7</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=905ab030-14a5-4a3d-aa11-e8f957f6a1ea">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4a0fcf4b-eb8e-456a-b934-400ae18248ee">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Ei luokitusta)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f793af16-5464-4db1-a42b-1c5f17c538ed">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c20808cb-c30a-4b53-91e5-810eb6b4b2e3">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="10">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Tiedotte</strong>
                    <strong>en luokitus</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittine</strong>
                      <strong>n</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittin</strong>
                      <strong>en</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittin</strong>
                      <strong>en</strong>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärke</strong>
                      <strong>ä</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-bit Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25c17b07-1efe-43d7-9b01-3dfdf1ce0bd7">Windows Server 2008 for 32-bit Systems</a>*<br />(Tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec73f416-2204-42d6-8932-c96578ac819f">Windows Internet Explorer 7</a>**<br />(Ei tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b97114a-71aa-47a2-b9e7-f4e158c18c80">Windows Server 2008 for 32-bit Systems</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d6290d8-1745-4bc0-9ca9-eeb1ad0be4a5">Windows Server 2008 for 32-bit Systems</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf6744e6-b54c-40f6-a78d-7ba9453133c0">Windows Server 2008 for 32-bit Systems</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec9eeb82-0497-4c55-94bb-9a47cb3521b4">Windows Server 2008 for 32-bit Systems</a>*<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b12018e-0cc1-4136-a68c-be4e1633c8df">Windows Server 2008 for x64-based Systems</a>*<br />(Tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=baacd1c2-9764-4fea-bd4d-c49791974fef">Windows Internet Explorer 7</a>**<br />(Ei tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e641db2-90c8-458f-9795-3e46b70a5203">Windows Server 2008 for x64-based Systems</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a33c833c-d5c5-4e37-8f89-7b9079f92e59">Windows Server 2008 for x64-based Systems</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=223236e8-7b19-4b47-8a90-bfc35eb9318a">Windows Server 2008 for x64-based Systems</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0bc178b8-f8ae-4f41-8f88-fb6a75be1bca">Windows Server 2008 for x64-based Systems</a>*<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bcf89ef-6446-406c-9c53-222e0f0baf7a">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=250a45dd-7eae-4440-bd10-02a703940976">Windows Internet Explorer 7</a>
                    <br />(Ei tärkeä)</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6546e1c-bf7b-4354-8574-6c16fa707de0">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31783e88-76e2-4bc6-b4ae-308443c6d223">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Ei luokitusta)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=077b697c-04a0-45bd-b08c-331d5c30cb47">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0af72663-4945-4916-8c55-090ba4d82793">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="10">Windows 7 Beta</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Tiedotteen luokitus</strong>
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
                <tr class="alternateRow"><td>Windows 7 Beta for 32-bit Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e877d9c1-3e7c-4551-a899-c3fcc5175bb6">Windows 7 Beta for 32-bit Systems</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td></tr>
                <tr><td>Windows 7 Beta for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0fa96b25-90e3-46ab-bcd5-051f4b2b881b">Windows 7 Beta x64 Edition</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Windows 7 Beta for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66646156-f3e6-48d7-be22-de1772dd1884">Windows 7 Beta for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td></tr>
              </table>


**\*Windows Server 2008 Server Core -asennus, jota haavoittuvuus koskee.** Tämä päivitys koskee tuettuja Windows Server 2008 -versioita samalla luokituksella siitä riippumatta. onko Windows Server 2008:n asennuksessa käytetty Server Core -asennusta vai ei. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Windows Server 2008 Server Core -asennus, joita haavoittuvuus koskee.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksella. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office -ohjelmistopaketit ja -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Microsoft Office -ohjelmistopaketit, -järjestelmät ja -osat</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=124653">
                      <strong>MS08-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128145">
                      <strong>MS08-056</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen luokitus</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2000 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2740e0-ecdd-48ca-84e0-eb187c31eb16">Excel 2000 Service Pack 3</a>
                    <br />(KB955461)<br />(Kriittinen)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27cedef1-c47c-472c-a343-cd9b4ebc2bba">Excel 2002 Service Pack 3</a>
                    <br />(KB955464)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1aee2d5-bfa0-40e3-91b6-98bf65524e8c">Microsoft Office XP Service Pack 3</a>
                    <br />(KB956464)<br />(Keskitaso)</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 2 ja Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368">Excel 2003 Service Pack 2</a>
                    <br />(KB955466)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368">Excel 2003 Service Pack 3</a><br />(KB955466)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>2007 Microsoft Office System ja 2007 Microsoft Office System Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f">Excel 2007</a>
                    <br />(KB955470)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f">Excel 2007 Service Pack 1</a><br />(KB955470)<br />(Tärkeä)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="3">Microsoft Office for Mac</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=124653">
                      <strong>MS08-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128145">
                      <strong>MS08-056</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen luokitus</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2004 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba4fa21a-7e01-4ef8-9b9f-9d51d00ef094">Microsoft Office 2004 for Mac</a>
                    <br />(KB958312)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e70c5ae0-2858-46de-81f8-dcd1786656b7">Microsoft Office 2008 for Mac</a>
                    <br />(KB958267)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Open XML File Format Converter for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a8d9a3b-b8a4-43b6-82a6-a2e7d16ae11d">Open XML File Format Converter for Mac</a>
                    <br />(KB958304)<br />(Tärkeä)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="3">Muu Office-ohjelmisto</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=124653">
                      <strong>MS08-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128145">
                      <strong>MS08-056</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Tiedotteen luokitus</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b">Microsoft Office Excel Viewer 2003</a>
                    <br />(KB955468)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b">Microsoft Office Excel Viewer 2003 Service Pack 3</a><br />(KB955468)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=83c88444-75b8-44d1-b280-3671394ade45">Microsoft Office Excel Viewer</a><br />(KB955935)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti</a>
                    <br />(KB955936)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1</a><br />(KB955936)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535">Microsoft Office SharePoint Server 2007</a>*<br />(KB955937)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535">Microsoft Office SharePoint Server 2007 Service Pack 1</a>*<br />(KB955937)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f">Microsoft Office SharePoint Server 2007 x64 Edition</a>*<br />(KB955937)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f">Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1</a>*<br />(KB955937)<br />(Tärkeä)</td><td>Ei koske</td></tr>
              </table>


\*Tämä päivitys koskee palvelimia, joihin on asennettu Excel-palvelut, kuten Microsoft Office SharePoint Server 2007 Enterprise- ja Microsoft Office SharePoint Server 2007 For Internet Sites -palvelinten oletuskokoonpanot. Microsoft Office SharePoint Server 2007 Standard ei sisällä Excel-palveluja.

#### Microsoft Server -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Host Integration Server</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125712">
                      <strong>MS08-059</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen luokitus</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Host Integration Server 2000</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11cca58b-59a4-4e93-9eb1-19b07c290a10">Microsoft Host Integration Server 2000 Service Pack 2 (palvelin)</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41b49291-1231-4e23-aef7-818207453d56">Microsoft Host Integration Server 2000 Administrator (asiakas)</a><br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft Host Integration Server 2004</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ca255ed-9334-4848-af94-49ef3078cdc0">Microsoft Host Integration Server 2004 (palvelin)</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eca756a1-ca56-4481-b23c-53c159a4e08c">Microsoft Host Integration Server 2004 Service Pack 1 (palvelin)</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92cb54e7-f4ff-40a4-99cb-6257c4d8d4cd">Microsoft Host Integration Server 2004 (asiakas)</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d776515c-09aa-4a04-876d-606bfc26a006">Microsoft Host Integration Server 2004 Service Pack 1 (asiakas)</a><br />(Kriittinen)</td></tr>
                <tr><td>Microsoft Host Integration Server 2006</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ae79da3-ec17-4d4b-8011-d777a237ac93">Microsoft Host Integration Server 2006 for 32-bit Systems</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05da4540-4976-458a-a612-7385d78695a2">Microsoft Host Integration Server 2006 for x64-based Systems</a><br />(Kriittinen)</td></tr>
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

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**System** **s Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso myös [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) -sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää Microsoft Baseline Security Analyzer -työkalua ja Microsoft Office Inventory Tool -työkalua laajan tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseksi. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

**Update Compatibility Evaluator ja Application Compatibility Toolkit**

Päivitykset usein kirjoittavat samoihin tiedostoihin ja rekisteriasetuksiin, joita tarvitaan sovelluksia käytettäessä. Tämä voi aiheuttaa yhteensopivuusongelmia ja pidentää aikaa, joka kuluu tietoturvapäivitysten käyttöönottamiseen. Voit tehostaa Windows-päivitysten testaamista ja tarkistamista asennetuissa sovelluksissa käyttämällä [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) -osia, jotka sisältyvät [Application Compatibility Toolkit 5.0:aan](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Sovellusten yhteensopivuustyökalu sisältää työkalut ja ohjeistuksen, joilla voi arvioida ja lieventää sovellusten yhteensopivuusongelmia ennen Microsoft Windows Vistan, Windowsin päivityksen, Microsoftin tietoturvapäivitysten tai Windows Internet Explorerin uuden versioon käyttöönottoa ympäristössäsi.

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

  - [NetAgent Co., Ltd.](http://www.netagent.co.jp/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-056
  - Joshua J. Drake ([iDefense](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-057
  - Wushi (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-057
  - Lionel d'Hauenens ([Labo Skopia](http://www.laboskopia.com/) yhteistyössä [iDefense VCP:n](http://labs.idefense.com/) kanssa) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-057
  - David Bloom ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-058
  - Gregory Rubin ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-058
  - [Ivan Fratric](http://ifsec.blogspot.com/) (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-058
  - Thierry Zoller ([n.runs](http://www.nruns.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-058
  - Lee Dagon ([Composica](http://www.composica.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-058
  - Stephen Fewer ([Harmony Security](http://www.harmonysecurity.com/) yhteistyössä [iDefense VCP:n](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-059
  - Paul Miseiko ([nCircle](http://www.ncircle.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-060
  - Paul Miseiko ([iShadow](http://www.ishadow.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-061
  - Thomas Garnier ([SkyRecon](http://www.skyrecon.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-061
  - [CERT/CC](http://www.cert.org/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-062
  - Joshua Morin ([Codenomicon](http://www.codenomicon.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-063
  - Alex Ionescu ([http://www.alex-ionescu.com/](http://www.alex-ionescu.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-064
  - Cody Pierce ja Aaron Portnoy ([TippingPoint DVLabs](http://dvlabs.tippingpoint.com)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-065
  - Fabien Le Mentec ([SkyRecon](http://www.skyrecon.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-066

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (14. lokakuuta 2008): Tietoturvatiedotteen yhteenveto julkaistu.
  - V2.0 (15. lokakuuta 2008): Windows Server 2008 for Itanium-based Systemsin luokitus poistettiin (MS08-062).
  - V2.1 (16. lokakuuta 2008): Microsoftin tietoturvatiedotteen MS08-062 yhteenvedon päivitys.
  - V3.0 (23. lokakuuta 2008): Lisätty Microsoftin tietoturvatiedotteeseen MS08-067, palvelinpalvelun haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (958644).

*Built at 2014-04-18T01:50:00Z-07:00*

