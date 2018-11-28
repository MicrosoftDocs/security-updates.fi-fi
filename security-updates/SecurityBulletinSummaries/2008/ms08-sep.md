---
title: Microsoftin turvatiedotteiden yhteenveto, syyskuu 2008
TOCTitle: MS08-SEP
ms:assetid: ms08-sep
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms08-sep(v=Security.10)
ms:contentKeyID: 61225617
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, syyskuu 2008

Julkaistu: 9. syyskuuta 2008 | Päivitetty: 9. joulukuuta 2008

**Versio:** 3.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo syyskuussa 2008 julkaistuista tietoturvatiedotteista.

Syyskuun 2008 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 4. syyskuuta 2008. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 10. syyskuuta 2008, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt syyskuun tietoturvatiedotteen web-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374633&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (4)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-054</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=121739"><strong>Windows Media Playerin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (954154)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Media Playerin haavoittuvuuden, joka saattaa sallia koodin suorittamisen verkon välityksellä, kun tietyllä tavalla muodostettu äänitiedosto suoratoistetaan Windows Media -palvelimesta. Jos käyttäjä on kirjautuneena järjestelmään järjestelmänvalvojan oikeuksin, tätä haavoittuvuutta hyödyntämään onnistuva hyökkääjä saattaa saada haavoittuvuuden sisältävän järjestelmän täysin hallintaansa. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Microsoft Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-052</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=125468"><strong>GDI+:n haavoittuvuudet saattavat sallia koodin</strong> <strong>suorittamisen verkon välityksellä (954593)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa useita yksityishenkilön ilmoittamia Microsoft Windows GDI+:n haavoittuvuuksia. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua kuvatiedostoa ohjelmistolla, johon haavoittuvuus vaikuttaa, tai selaavat sivustoa, jossa on tietyllä tavalla muodostettua sisältöä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td><strong>Microsoft Windows, Internet Explorer</strong> <strong>, .NET Framework, Office, SQL Server, Visual Studio.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-053</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=123091"><strong>Windows Media Encoder 9:n haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (954156)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Media Encoder 9:n haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua. Jos käyttäjä on kirjautuneena järjestelmään järjestelmänvalvojan oikeuksin, tätä haavoittuvuutta hyödyntämään onnistuva hyökkääjä saattaa saada haavoittuvuuden sisältävän järjestelmän täysin hallintaansa. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<th>Microsoftin tietoturvatiedote MS08-055</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=125229"><strong>Microsoft Officen haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (955047)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Officen haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä napsauttaa tietyllä tavalla muodostettua OneNote-URL-osoitetta. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Yleensä tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Mic</strong> <strong>rosoft Office.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

**Miten taulukkoa käytetään?**

Tämän taulukon avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja edellyttääkö se tietoturvapäivityksen asentamista. Jos ohjelma tai osa on luettelossa, saatavana olevaan ohjelmistopäivitykseen on linkki. Myös ohjelmistopäivityksen luokitus mainitaan.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää useiden tietoturvapäivitysten asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

#### Windows-käyttöjärjestelmä ja osat

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="4">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121739">
                      <strong>MS08-054</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125468">
                      <strong>MS08-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=123091">
                      <strong>MS08-053</strong>
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
                  </td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a860d2d9-653d-4ddb-bbff-323d3ccdb866">Microsoft Internet Explorer 6 Service Pack 1</a>
                    <br />(KB938464)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7cbcd19-acc1-4a89-adfa-99b2f431510d">Microsoft .NET Framework 1.0 Service Pack 3</a><br />(KB947739)<br />(Ei luokitusta)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6013f866-3ea1-4672-b1bf-e516204c3a7a">Microsoft .NET Framework 1.1 Service Pack 1</a><br />(KB947742)<br />(Ei luokitusta)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f1cd013-2c4b-4582-9114-cb840a96124a">Microsoft .NET Framework 2.0</a><br />(KB947746)<br />(Ei luokitusta)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=215b73a3-46ab-44a8-a0fb-6d37bd1c39b8">Microsoft .NET Framework 2.0 Service Pack 1</a><br />(KB947748)<br />(Ei luokitusta)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0cabfbc0-db5d-4a6a-a4cd-e6df89ac2b25">Windows Media Encoder 9 Series</a>
                    <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="4">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedott</strong>
                    <strong>een numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121739">
                      <strong>MS08-054</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125468">
                      <strong>MS08-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=123091">
                      <strong>MS08-053</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 ja Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5891180-5dd1-49ec-bcc6-3030a544202c">Windows Media Player 11</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0bd6fbe-f46e-4961-9a79-49ec77d39439">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57bcb3c2-49d3-4f18-8d03-36abd03d7403">Windows Media Encoder 9 Series</a>
                    <br />(Kriittinen)</td></tr>
                <tr><td>Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=caf8a45e-a9f8-4e91-98fd-87eddbeae64c">Windows Media Player 11</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c5d26771-1f49-4bbf-902c-bf92e527cadb">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18efea9e-b103-46de-90d9-5e295854cec3">Windows Media Encoder 9 Series</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebc1737c-6e78-4244-a1b2-a56d031f16e9">Windows Media Encoder 9 Series x64 Edition</a><br />(Kriittinen)</td></tr>
              
                <tr><th colspan="4">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121739">
                      <strong>MS08-054</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125468">
                      <strong>MS08-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=123091">
                      <strong>MS08-053</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac03f138-eca4-46e1-9782-e811820e547f">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54ce1080-94cf-4e4f-8e09-a7dbab2757c5">Windows Media Encoder 9 Series</a>
                    <br />(Keskitaso)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93f1451b-5b62-47e5-8f0c-b720b957999a">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c83011cd-90b8-494c-9cad-fa055e101992">Windows Media Encoder 9 Series</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8f1b782-136b-443f-b5f2-63aa4d1fd94a">Windows Media Encoder 9 Series x64 Edition</a><br />(Keskitaso)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14e99f8a-cdd4-40d7-8cfc-73ae6bd6dfad">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Kriittinen)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="4">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121739">
                      <strong>MS08-054</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125468">
                      <strong>MS08-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=123091">
                      <strong>MS08-053</strong>
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
                  </td></tr>
                <tr><td>Windows Vista ja Windows Vista Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f4118fd-1ffb-46da-b922-cd4ca4f9d84e">Windows Media Player 11</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16f3ad21-ed77-4c32-93df-3b650b2b32a5">Windows Vista ja Windows Vista Service Pack 1</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99beebc4-553a-46f8-8245-e3d932306c93">Windows Media Encoder 9 Series</a>
                    <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=334352e7-d41f-494f-866d-f1f1745ffd17">Windows Media Player 11</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa47d016-f5c9-4586-8876-f1f4f255f54d">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99beebc4-553a-46f8-8245-e3d932306c93">Windows Media Encoder 9 Series</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54d1279a-7f26-4727-a39d-5505bcd4fc53">Windows Media Encoder 9 Series x64 Edition</a><br />(Kriittinen)</td></tr>
              
                <tr><th colspan="4">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=121739">
                      <strong>MS08-054</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125468">
                      <strong>MS08-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=123091">
                      <strong>MS08-053</strong>
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
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-bit Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72fc6028-6af4-44ec-8d2a-28c53807d6bc">Windows Media Player 11</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23bd3be5-cc66-46f8-9420-49d65d8afe1d">Windows Server 2008 for 32-bit Systems</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec">Windows Media Encoder 9 Series</a>*<br />(Keskitaso)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3906512b-26db-473e-b522-3883ff34a21c">Windows Media Player 11</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f1e0f05-6c9d-4ad1-9b19-50ee4fa7bd7e">Windows Server 2008 for x64-based Systems</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec">Windows Media Encoder 9 Series</a>*<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e30f9427-26d0-4e86-b9b8-bc637c3b5734">Windows Media Encoder 9 Series x64 Edition</a>*<br />(Keskitaso)</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5159bdba-3825-4816-a2be-ab035332b9e2">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Kriittinen)</td><td>Ei koske</td></tr>
              </table>


**\*Haavoittuvuus ei koske Windows Server 2008 Server Core -asennuksia.** Haavoittuvuudet, jotka nämä päivitykset korjaavat, eivät koske tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksena, vaikka järjestelmässä olisi tiedostoja, joita nämä haavoittuvuudet koskevat. Käyttäjille, joilla on haavoittuvia tiedostoja, kuitenkin tarjotaan tämä päivitys, koska päivitystiedostot ovat uudempia (niiden versionumero on suurempi) kuin järjestelmässä olevat tiedostot. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125468">
                      <strong>MS08-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125229">
                      <strong>MS08-055</strong>
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
                  </td></tr>
                <tr><td>Microsoft Office XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d">Microsoft Office XP Service Pack 3</a>
                    <br />(KB953405)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d">Microsoft Office XP Service Pack 3</a>
                    <br />(KB953405)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 2 ja Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8">Microsoft Office 2003 Service Pack 2</a>
                    <br />(KB954478)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8">Microsoft Office 2003 Service Pack 3</a><br />(KB954478)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3">Microsoft Office 2003 Service Pack 2</a>
                    <br />(KB953404)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3">Microsoft Office 2003 Service Pack 3</a><br />(KB953404)<br />(Tärkeä)</td></tr>
                <tr><td>2007 Microsoft Office System ja 2007 Microsoft Office System Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2">2007 Microsoft Office System</a>
                    <br />(KB954326)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2">2007 Microsoft Office System Service Pack 1</a><br />(KB954326)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e">2007 Microsoft Office System</a>
                    <br />(KB951944)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e">2007 Microsoft Office System Service Pack 1</a><br />(KB951944)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="3">Muu Office-ohjelmisto</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125468">
                      <strong>MS08-052</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125229">
                      <strong>MS08-055</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Project 2002 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d">Microsoft Office Project 2002 Service Pack 1</a>
                    <br />(KB953405)*<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Visio 2002 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a6d9d3ef-f087-4f61-9ec1-522b7d4b9c48">Microsoft Visio 2002 Service Pack 2</a>
                    <br />(KB954479)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Word Viewer, Microsoft Word Viewer 2003, Microsoft Word Viewer 2003 Service Pack 3, Microsoft Office Excel Viewer 2003, Microsoft Office Excel Viewer 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8">Microsoft Office Word Viewer, Microsoft Word Viewer 2003, Microsoft Word Viewer 2003 Service Pack 3, Microsoft Office Excel Viewer 2003, Microsoft Office Excel Viewer 2003 Service Pack 3</a>
                    <br />(KB954478)**<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Office PowerPoint Viewer 2003</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd503f08-1831-45ff-bdf4-dd918ca40505">Microsoft Office PowerPoint Viewer 2003</a>
                    <br />(KB956500)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer, Microsoft Office PowerPoint Viewer 2007, Microsoft Office PowerPoint Viewer 2007 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2">Microsoft Office Excel Viewer, Microsoft Office PowerPoint Viewer 2007, Microsoft Office PowerPoint Viewer 2007 Service Pack 1</a>
                    <br />(KB954326)***<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti ja Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti ja Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1</a>
                    <br />(KB954326)***<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Expression Web ja Microsoft Expression Web 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2">Microsoft Expression Web ja Microsoft Expression Web 2</a>
                    <br />(KB954326)***<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Office Groove 2007 ja Microsoft Office Groove 2007 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2">Microsoft Office Groove 2007 ja Microsoft Office Groove 2007 Service Pack 1</a>
                    <br />(KB954326)***<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Works</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eb0d224e-a517-40d9-9fc6-2345fa12a841">Microsoft Works 8</a>
                    <br />(KB956483)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Digital Image Suite 2006</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04afd760-8173-4069-9e82-d3bf053d9eae">Microsoft Digital Image Suite 2006</a>
                    <br />(KB955992)<br />(Kriittinen)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Office OneNote 2007</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395">Microsoft Office OneNote 2007</a>
                    <br />(KB950130)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395">Microsoft Office OneNote 2007 Service Pack 1</a><br />(KB950130)<br />(Kriittinen)</td></tr>
              </table>


\*Näiden ohjelmistojen, joita haavoittuvuus koskee, päivitys on sama kuin Microsoft Office XP Service Pack 3 -päivitys.

\*\*Näiden ohjelmistojen, joita haavoittuvuus koskee, päivitys on sama kuin Microsoft Office 2003 Service Pack 2- ja Microsoft Office 2003 Service Pack 3 -päivitys.

\*\*\*Näiden ohjelmistojen, joita haavoittuvuus koskee, päivitys on sama kuin 2007 Microsoft Office systemin ja 2007 Microsoft Office system Service Pack 1:n päivitys.

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
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125468">
                      <strong>MS08-052</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen luokitus</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>SQL Server 2000 Reporting Services Service Pack 2</td><td>GDR-päivitys:<br />Ei koske<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f9e7f78-7439-414b-a9dc-a779b89427db">SQL Server 2000 Reporting Services Service Pack 2</a><br />(KB954609)<br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2005 Service Pack 2</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47">SQL Server 2005 Service Pack 2</a><br />(KB954606)<br />(Kriittinen)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213">SQL Server 2005 Service Pack 2</a><br />(KB954607)<br />(Kriittinen)</td></tr>
                <tr><td>SQL Server 2005 x64 Edition Service Pack 2</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47">SQL Server 2005 x64 Edition Service Pack 2</a><br />(KB954606)<br />(Kriittinen)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213">SQL Server 2005 x64 Edition Service Pack 2</a><br />(KB954607)<br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>SQL Server 2005 for Itanium-based Systems Service Pack 2</td><td>GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47">SQL Server 2005 for Itanium-based Systems Service Pack 2</a><br />(KB954606)<br />(Kriittinen)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213">SQL Server 2005 for Itanium-based Systems Service Pack 2</a><br />(KB954607)<br />(Kriittinen)</td></tr>
              </table>


#### Microsoft-kehitystyökalut ja ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Visual Studio</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125468">
                      <strong>MS08-052</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen luokitus</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visual Studio .NET 2002 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7848a652-4025-44bb-9c98-37a078b56d01">Microsoft Visual Studio .NET 2002 Service Pack 1</a>
                    <br />(KB947736)<br />(Ei luokitusta)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio .NET 2003 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9bc1e8f8-6c30-4aa0-90f5-fbb0ad5fd90e">Microsoft Visual Studio .NET 2003 Service Pack 1</a>
                    <br />(KB947737)<br />(Ei luokitusta)</td></tr>
                <tr><td>Microsoft Visual Studio 2005 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7bf790b-3249-4ee8-9440-fa911ebbc08a">Microsoft Visual Studio 2005 Service Pack 1</a>
                    <br />(KB947738)<br />(Ei luokitusta)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio 2008</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8c80b29-6d00-4949-a005-5d706122919a">Microsoft Visual Studio 2008</a>
                    <br />(KB952241)<br />(Ei luokitusta)</td></tr>
                <tr><td>Microsoft Report Viewer 2005 Service Pack 1 -jakelutiedostopaketti</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82833f27-081d-4b72-83ef-2836360a904d">Microsoft Report Viewer 2005 Service Pack 1 -jakelutiedostopaketti</a>
                    <br />(KB954765)<br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft Report Viewer 2008 -jakelutiedostopaketti</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ae0aa19-3e6c-474c-9d57-05b2347456b1">Microsoft Report Viewer 2008 -jakelutiedostopaketti</a>
                    <br />(KB954766)<br />(Kriittinen)</td></tr>
                <tr><td>Microsoft Visual FoxPro 8.0 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f4371b9-b8be-4455-94d2-2304ee340543">Microsoft Visual FoxPro 8.0 Service Pack 1, </a>kun asennettu Microsoft Windows 2000 Service Pack 4 -järjestelmään<br />(KB955368)<br />(Ei luokitusta)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual FoxPro 9.0 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49b21e30-722d-446e-9020-aceb3870db69">Microsoft Visual FoxPro 9.0 Service Pack 1, </a>kun asennettu Microsoft Windows 2000 Service Pack 4 -järjestelmään<br />(KB955369)<br />(Ei luokitusta)</td></tr>
                <tr><td>Microsoft Visual FoxPro 9.0 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=36957f47-9d8b-477d-bd60-5959e5a2eafa">Microsoft Visual FoxPro 9.0 Service Pack 2, </a>kun asennettu Microsoft Windows 2000 Service Pack 4 -järjestelmään<br />(KB955370)<br />(Ei luokitusta)</td></tr>
                <tr class="alternateRow"><td>Microsoft Platform SDK -jakelutiedosto: GDI+</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a">Microsoft Platform SDK -jakelutiedosto: GDI+</a>
                    <br />(Ei luokitusta)</td></tr>
              </table>


#### Microsoft-tietoturvaohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Forefront Security</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125468">
                      <strong>MS08-052</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen luokitus</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Forefront Client Security 1.0</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1eb1a79f-44ca-499e-90bb-ac51894e9d1e">Microsoft Forefront Client Security 1.0</a>, kun asennettu Microsoft Windows 2000 Service Pack 4 -järjestelmään<br />(KB957177)<br />(Tärkeä)</td></tr>
              </table>


## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyt** **töönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin ja laajennettu Inventory-työkalu (ESUIT). Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso myös [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) -sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

**Update Compatibility Evaluator ja sovellusten yhteensopivuustyökalu**

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

**Korj** **austiedostojen hallintamenetelmät**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivitys** **ten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - Greg MacManus ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-052.
  - Bing Liu ([Fortinet's FortiGuard Global Security Research Team](http://www.fortiguardcenter.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-052
  - Peter Winter-Smith ([NGSSoftware](http://www.ngssoftware.com/)) ja Ivan Fratric yhteistyössä [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-052
  - [Vulnerability Research Team (Assurent Secure Technologies)](http://www.assurent.com/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-052
  - Tuntematon tutkija (yhteistyössä [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-052.
  - Nguyen Minh Duc ja Le Manh Tung yhdessä [Bach Khoa Internetwork Security Centerin (BKIS) Hanoi University of Technology (Vietnam)](http://security.bkis.vn/) kanssa ilmoittavat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-053
  - Brett Moore ([Insomnia Security](http://www.insomniasec.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-055

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (9. syyskuuta 2008): Tietoturvatiedotteen yhteenveto julkaistu.
  - V2.0 (9. syyskuuta 2008): Microsoft Office Project 2002 Service Pack 2, kaikki Microsoft Office 2003:n Office Viewer -ohjelmistot sekä kaikki 2007 Microsoft Office systemin Office Viewer -ohjelmistot on lisätty tietoturvatiedotteen yhteenvetoon ohjelmistona, jota tietoturvatiedote MS08-052 koskee.
  - V2.1 (17. syyskuuta 2008): Tietoturvatiedotteen yhteenvetoa on päivitetty siten, että Microsoft Office Project 2002 Service Pack 2 -ohjelmiston nimeksi on muutettu Ohjelmistot, joita haavoittuvuus koskee -taulukossa Microsoft Office Project 2002 Service Pack 1. Tämä on pelkkä nimimuutos. Binaareja tai tunnistusta ei ole muutettu.
  - V2.2 (29. lokakuuta 2008): Tietoturvatiedotteen yhteenvetoa on päivitetty siten, että Microsoft Visio 2003 Viewer, Microsoft Visio 2007 Viewer ja Microsoft Visio 2007 Viewer Service Pack 1 poistettu ohjelmistoista, joita tietoturvatiedote MS08-052 koskee.
  - V3.0 (9. joulukuuta 2008): Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti ja Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1, Microsoft Expression Web ja Microsoft Expression Web 2 sekä Microsoft Office Groove 2007 ja Microsoft Office Groove 2007 Service Pack 1 on lisätty tietoturvatiedotteen yhteenvetoon tuotteena, jota tietoturvatiedote MS08-052 koskee.

*Built at 2014-04-18T01:50:00Z-07:00*

