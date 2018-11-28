---
title: Microsoftin turvatiedotteiden yhteenveto, joulukuu 2008
TOCTitle: MS08-DEC
ms:assetid: ms08-dec
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms08-dec(v=Security.10)
ms:contentKeyID: 61225608
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, joulukuu 2008

Julkaistu: 9. joulukuuta 2008 | Päivitetty: 29. huhtikuuta 2009

**Versio:** 6,0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo joulukuussa 2008 julkaistuista tietoturvatiedotteista.

Joulukuun 2008 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 4. joulukuuta 2008. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 10. joulukuuta 2008, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt joulukuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374647) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft järjestää kaksi webcast-lähetystä, jotka koskevat tämän tietoturvatiedotteiden yhteenvedon versioon 3.0 lisättyä erillistä tietoturvatiedotetta MS08-078 ja joissa Microsoft vastaa asiakkaiden kysymyksiin. Webcast-lähetykset järjestetään 17. joulukuuta 2008, kello 23 Suomen aikaa (kello 13 Tyynenmeren aikaa, USA ja Kanada) ja 18 joulukuuta 2008, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). Rekisteröidy nyt [17. joulukuuta](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399448&culture=en-us) ja [18. joulukuuta järjestettävään webcast-lähetykseen](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399449&culture=en-us). Myöhemmin webcast-lähetyksistä voi katsoa tallenteen. lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

## Yhteenveto

Seuraavassa taulukossa on luettelo tämän kuun tietoturvatiedotteista luokittelujärjestyksessä.

Lisätietoja ohjelmistoista, joita haavoittuvuus koskee, on kohdassa **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot**.

<table>
<thead>
<tr class="header">
<th>Tiedotteen tunnus</th>
<th>Tiedotteen otsikko ja yhteenveto</th>
<th>Luokitus ja haavoittuvuuden vaikutus</th>
<th>Uudelleenkäynnistysvaatimus</th>
<th>Ohjelmistot, joita haavoittuvuus koskee</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td><strong>GDI:n haavoittuvuudet saattavat sallia koodin suorittamisen verkon välitykse</strong> <strong>llä (956802)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa GDI:n haavoittuvuutta. Jommankumman haavoittuvuuden hyödyntäminen saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun WMF-kuvatiedoston. Hyödyntämällä näitä haavoittuvuuksia onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td><strong>Windowsin haun haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (959349)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa Windowsin haun haavoittuvuutta. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa ja tallentaa erityisesti muodostetun tallennettu haku -tiedoston Windowsin Resurssienhallinnassa tai napsauttaa erityisesti muodostettua haku-URL-osoitetta. Hyödyntämällä näitä haavoittuvuuksia onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (958215)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa neljä yksityishenkilön ilmoittamaa haavoittuvuutta. Haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua Internet Explorerilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=137335">MS08-078</a></td>
<td><strong>Internet Explorerin tietoturvapäivitys (960714)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa julkistetun haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua Internet Explorerilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td><strong>Visual Basic 6.0:n suorituksenaikaisten lisätiedostojen (ActiveX-komponenttien) haavoi</strong> <strong>ttuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (932349)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa viisi yksityishenkilön ilmoittamaa haavoittuvuutta ja yhden julkistetun Microsoft Visual Basic 6.0:n suorituksenaikaisten lisätiedostojen ActiveX-komponenttien haavoittuvuuden. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä selaa sivustoa, jossa on tietyllä tavalla muodostettua sisältöä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft-kehitystyökalut ja ohjelmisto, Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td><strong>Microsoft Office Wordin suodattimien haavoittuvuu</strong> <strong>det saattavat sallia koodin suorittamisen verkon välityksellä (957173)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kahdeksan yksityishenkilön ilmoittamaa Microsoft Office Wordin ja Microsoft Office Outlookin haavoittuvuutta, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Word- tai Rich Text Format (RTF) -tiedoston. Hyödyntämällä näitä haavoittuvuuksia onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td><strong>Microsoft Office Excelin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (959070)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kolme yksityishenkilön ilmoittamaa Microsoft Office Excelin haavoittuvuutta, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Excel-tiedoston. Hyödyntämällä näitä haavoittuvuuksia onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126307">MS08-077</a></td>
<td><strong>Microsoft Office SharePoint Serverin haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen (957175)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen, jos hyökkääjä ohittaa todennuksen siirtymällä selaimella SharePoint-sivuston hallinto-URL-osoitteeseen. Jos käyttöoikeuksien laajennushyökkäys onnistuu, se voi johtaa palvelun estoon tai tietojen paljastumiseen muille käyttäjille.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office, Microsoft Server -ohjelmisto</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td><strong>Windows Media Componentsin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (959807)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi seuraavaa yksityishenkilön ilmoittamaa Windows Media Componentsin haavoittuvuutta: Windows Media Player, Windows Media Format Runtime ja Windows Media Services. Vakavin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä. Jos käyttäjä on kirjautuneena järjestelmään järjestelmänvalvojan oikeuksin, tätä haavoittuvuutta hyödyntämään onnistuva hyökkääjä saattaa saada haavoittuvuuden sisältävän järjestelmän täysin hallintaansa. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
</tbody>
</table>


## Hyödyntämisindeksi

**Miten t** **aulukkoa käytetään?**

Tämän taulukon avulla saat selville, kuinka todennäköistä on sellaisen hyväksikäyttökoodin julkaiseminen 30 päivän kuluessa tietoturvatiedotteen julkaisemisesta, joka koskee tietoturvapäivitystä, joka sinun on ehkä asennettava. Tutustu järjestelmän määritysten perusteella kuhunkin arviointiin. Tällä tavoin voit ottaa päivitykset käyttöön tärkeysjärjestyksessä. Lisätietoja näistä luokituksista ja niiden määrittämisestä on [Microsoftin hyödyntämisindeksissä](http://technet.microsoft.com/en-us/security/cc998259.aspx).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Visual Basic 6.0:n suorituksenaikaisten lisätiedostojen (ActiveX-komponenttien) haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3704">CVE-2008-3704</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Yhtenäinen hyväksikäyttökoodi on julkisesti saatavana</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Visual Basic 6.0:n suorituksenaikaisten lisätiedostojen (ActiveX-komponenttien) haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4252">CVE-2008-4252</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Visual Basic 6.0:n suorituksenaikaisten lisätiedostojen (ActiveX-komponenttien) haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4256">CVE-2008-4256</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Visual Basic 6.0:n suorituksenaikaisten lisätiedostojen (ActiveX-komponenttien) haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4253">CVE-2008-4253</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Visual Basic 6.0:n suorituksenaikaisten lisätiedostojen (ActiveX-komponenttien) haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4254">CVE-2008-4254</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Visual Basic 6.0:n suorituksenaikaisten lisätiedostojen (ActiveX-komponenttien) haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4255">CVE-2008-4255</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Windows 2000 -järjestelmät ovat suurimmassa vaarassa. Toimiva hyväksikäyttökoodi ei todennäköisesti koske Windows XP SP2- ja Windows Server 2003 SP1 -käyttöjärjestelmiä sekä näitä uudempia käyttöjärjestelmiä, sillä niiden kekomuisti on suojattu paremmin.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td>GDI:n haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (956802)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3465">CVE-2008-3465</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td>GDI:n haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (956802)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2249">CVE-2008-2249</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Microsoft Office Wordin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4024">CVE-2008-4024</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Microsoft Office Wordin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4025">CVE-2008-4025</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Microsoft Office Wordin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4026">CVE-2008-4026</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Microsoft Office Wordin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4027">CVE-2008-4027</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Microsoft Office Wordin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4028">CVE-2008-4028</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Microsoft Office Wordin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4030">CVE-2008-4030</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Microsoft Office Wordin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4837">CVE-2008-4837</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Microsoft Office Wordin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4031">CVE-2008-4031</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td>Internet Explorerin kumulatiivinen tietoturvapäivitys (958215)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4258">CVE-2008-4258</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td>Internet Explorerin kumulatiivinen tietoturvapäivitys (958215)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4259">CVE-2008-4259</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td>Internet Explorerin kumulatiivinen tietoturvapäivitys (958215)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4261">CVE-2008-4261</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td>Internet Explorerin kumulatiivinen tietoturvapäivitys (958215)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4260">CVE-2008-4260</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td>Microsoft Office Excelin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (959070)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4265">CVE-2008-4265</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td>Microsoft Office Excelin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (959070)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4266">CVE-2008-4266</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td>Microsoft Office Excelin suodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (959070)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4264">CVE-2008-4264</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td>Windowsin haun haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (959349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4269">CVE-2008-4269</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td>Windowsin haun haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (959349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4268">CVE-2008-4268</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td>Windows Media Componentsin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (959807)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3009">CVE-2008-3009</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Tähän ongelmaan liittyvä hyväksikäyttökoodi voidaan luoda. Koska hyökkäystavat ovat hyvin rajallisia, varsinaisia hyökkäyksiä ei todennäköisesti tapahdu.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td>Windows Media Componentsin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (959807)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3010">CVE-2008-3010</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Tähän ongelmaan liittyvä hyväksikäyttökoodi voidaan luoda. Koska hyökkäystavat ovat hyvin rajallisia, varsinaisia hyökkäyksiä ei todennäköisesti tapahdu.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126307">MS08-077</a></td>
<td>Microsoft Office SharePoint Serverin haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen (957175)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4032">CVE-2008-4032</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Tähän ongelmaan liittyvä hyväksikäyttökoodi voidaan luoda. Tätä heikkoutta hyödyntävät hyökkäykset aiheuttavat todennäköisesti vain tietojen paljastumisen muille käyttäjille mutta eivät mahdollista koodin suorittamista verkon välityksellä.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=137335">MS08-078</a></td>
<td>Internet Explorerin tietoturvapäivitys (960714)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4844">CVE-2008-4844</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen<br />
(Yleisessä tiedossa, kun tiedote julkaistaan)</td>
<td>Aktiivisista hyökkäyksistä on löydetty yhtenäinen hyväksikäyttökoodi. Internet Explorer kuitenkin suoritetaan Windows Vistan ja Windows Server 2008:n oletusasennuksissa suojatussa tilassa, mikä vaikeuttaa hyväksikäyttöä.</td>
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
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="6">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125440">
                      <strong>MS08-071</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=132148">
                      <strong>MS08-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=133437">
                      <strong>MS08-073</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=137335">
                      <strong>MS08-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125419">
                      <strong>MS08-076</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
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
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b775fb1-1077-455d-af4a-4ccb5237974f">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kriittinen)<br /></td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c242ba42-556b-4c87-bf33-9d99166ff096">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c0583745-7e57-4265-9429-c3415cb8465f">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3e18732-47f1-40ce-999c-d1fd283bf138">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=124c14b6-9323-4f6f-902b-727aa56444bc">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c33d558e-45f9-4e85-b48c-03bd0e8cb4bc">Windows Media Player 6.4</a>
                    <br />(KB954600)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a459497-0ab8-41cb-87d0-b551631d8d8a">Windows Media Format Runtime 7.1 ja Windows Media Format Runtime 9.0</a><br />(KB952069)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58b7d241-cef6-48fa-aa52-017695f71db1">Windows Media Services 4.1</a><br />(KB952068)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="6">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125440">
                      <strong>MS08-071</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=132148">
                      <strong>MS08-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=133437">
                      <strong>MS08-073</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=137335">
                      <strong>MS08-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125419">
                      <strong>MS08-076</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
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
                <tr class="alternateRow"><td>Windows XP Service Pack 2 ja Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2151fbba-c464-4d1e-82d4-5b096e82bed0">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Kriittinen)<br /></td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=af9a6cb0-725d-490c-9858-16ec40e98560">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b582695-b3cc-4c65-bc4b-d673c9a6d82a">Windows Internet Explorer 7</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d83e0af-46fa-4bfc-ba57-635435a7ef2d">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0190a289-164e-41a7-8c01-fa1aaed3f531">Windows Internet Explorer 7</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99241309-e644-4088-a8f3-38837fab4037">Windows Media Player 6.4</a>
                    <br />(KB954600)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=504f816c-f554-4b93-ac28-b085574d9bac">Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 ja Windows Media Format Runtime 11</a><br />(vain Windows XP Service Pack 2)<br />(KB952069)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad76fcf3-a2f9-4e36-bd1b-c1536749173c">Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 ja Windows Media Format Runtime 11</a><br />(vain Windows XP Service Pack 3)<br />(KB952069)<br />(Tärkeä)<br /></td></tr>
                <tr><td>Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2247f6a5-aa33-4c68-9ea8-a63488d126d3">Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)<br /></td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60bf9851-24fe-4658-8333-d353e82063c7">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=107cf54b-29d4-4c54-b091-2b5b3ffbf49d">Windows Internet Explorer 7</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a585cb73-2c1a-4fa8-862a-ad6aeaeaf2f8">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ba71e23-8cef-4399-b215-983b0dcf5cb5">Windows Internet Explorer 7</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=946d47c9-b208-4fab-8ef6-774413d61bc8">Windows Media Player 6.4</a>
                    <br />(KB954600)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=644ef023-ee40-45b0-9c9d-c76d9fab0005">Windows Media Format Runtime 9.5</a><br />(KB952069)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524">Windows Media Format Runtime 9.5 x64 Edition</a><br />(KB952069)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2dadc017-2be5-4240-ab8f-0291756dca6b">Windows Media Format Runtime 11</a><br />(KB952069)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="6">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125440">
                      <strong>MS08-071</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=132148">
                      <strong>MS08-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=133437">
                      <strong>MS08-073</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=137335">
                      <strong>MS08-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125419">
                      <strong>MS08-076</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
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
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c396796-0929-4cd2-99e8-3c0f7075a89e">Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</a>
                    <br />(Kriittinen)<br /></td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d53adf6f-9501-4862-a1ca-57eb4d40cd75">Microsoft Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9cdd4f9e-c578-405c-af9e-628f2d77fdf4">Windows Internet Explorer 7</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d81e9cf9-ce0c-463a-a359-49a348cb89ae">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=388847ec-817e-45cf-8fa7-32c7e1f57f80">Windows Internet Explorer 7</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2315ce20-2f46-42c2-bb40-045f003409d7">Windows Media Player 6.4</a>
                    <br />(KB954600)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8958248-c889-499e-a6a9-3b394cdb27ea">Windows Media Format Runtime 9.5</a><br />(KB952069)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e71abc2d-d60e-444a-9b7b-062c5805fe9e">Windows Media Services 9 Series</a><br />(KB952068)<br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6d5c7d2f-1a82-4cdf-b3f2-b2c2390c6a64">Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)<br /></td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e37cb34-32be-4bbe-87f3-c4e1974e4d00">Microsoft Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c36f92c-d8a0-4b70-b85f-83588a0299a0">Windows Internet Explorer 7</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=015df302-d79f-43a1-b5c5-32ac04de0510">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ae17caf-6204-470e-8480-380d3d505657">Windows Internet Explorer 7</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c29bed9-1b88-4d2f-80a5-305c2bedd89f">Windows Media Player 6.4</a>
                    <br />(KB954600)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2278022e-a716-46c0-bedf-d626933bd815">Windows Media Format Runtime 9.5</a><br />(KB952069)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524">Windows Media Format Runtime 9.5 x64 Edition</a><br />(KB952069)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0030155-1a9a-46cc-bbc8-6d0d1ed65c1f">Windows Media Services 9 Series</a><br />(KB952068)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1edb62b4-3d0f-4891-b4b3-8f8bc4e7bdfe">Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Kriittinen)<br /></td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0da4e424-4682-4401-a226-7d8f1be19d44">Microsoft Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3811030d-5958-4b91-b5b8-20587dc7c4d6">Windows Internet Explorer 7</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18016305-7f72-47f6-ab4c-94282289bf5f">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=97d6c093-f68d-4ddf-8e3c-f29662a1940f">Windows Internet Explorer 7</a><br />(Kriittinen)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="6">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125440">
                      <strong>MS08-071</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=132148">
                      <strong>MS08-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=133437">
                      <strong>MS08-073</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=137335">
                      <strong>MS08-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125419">
                      <strong>MS08-076</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
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
                  </td></tr>
                <tr><td>Windows Vista ja Windows Vista Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cddf9cf6-bdeb-4429-823a-879387a428d7">Windows Vista ja Windows Vista Service Pack 1</a>
                    <br />(Kriittinen)<br /></td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0dcc5373-0435-42d5-864d-298e5bb122d9">Windows Vista ja Windows Vista Service Pack 1</a>
                    <br />(KB958623)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b1b65f0-6848-47c6-bdd5-be3c0621b323">Windows Vista ja Windows Vista Service Pack 1</a><br />(KB958624)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f62030a-9ce2-4c92-b948-143a6881921e">Windows Internet Explorer 7</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7887111d-4fac-4823-bdd2-a18d9468fdf0">Windows Internet Explorer 7</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1fcdc8dd-26d9-4d1a-8b3f-7b6a21a95999">Windows Media Format Runtime 11</a>
                    <br />(KB952069)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73dc3775-b6f0-40f1-bd36-6b5fb80eb2fa">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Kriittinen)<br /></td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2112c5c8-7c9f-4491-b127-b1093085e105">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a>
                    <br />(KB958623)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eb1d0ffe-1644-457b-9e82-768bd4c7f7ab">Windows Vista x64 Edition ja Windows Vista x64 Edition Service Pack 1</a><br />(KB958624)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8800493-fba4-41f8-bde5-a53eeaf89d54">Windows Internet Explorer 7</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=69979d92-8d45-47fe-ac4c-c2f1f23cf1fb">Windows Internet Explorer 7</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8839f6cd-dfbf-448c-bf1e-1da9bb5f3f25">Windows Media Format Runtime 11</a>
                    <br />(KB952069)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="6">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125440">
                      <strong>MS08-071</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=132148">
                      <strong>MS08-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=133437">
                      <strong>MS08-073</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=137335">
                      <strong>MS08-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=125419">
                      <strong>MS08-076</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
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
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-bit Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbed9e8b-e75e-44ef-ba1d-fd6f852c1f67">Windows Server 2008 for 32-bit Systems</a>*<br />(Kriittinen)<br /></td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90ab7e6f-5ae7-4f55-8838-868fc98d8a16">Windows Server 2008 for 32-bit Systems</a>***<br />(KB958623)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=470d506f-77ae-4a44-8598-df645f484295">Windows Server 2008 for 32-bit Systems</a>***<br />(KB958624)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45a0de3c-c7d1-4314-a456-1f7428b7c90a">Windows Internet Explorer 7</a>**<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5552e564-dd1c-4e2a-9a42-6317522c884d">Windows Internet Explorer 7</a>**<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91ec4195-bc1c-444e-a7b0-ebde46c088fa">Windows Media Format Runtime 11</a>
                    <br />(KB952069)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffb5d945-7f98-4849-b020-ed4873fa42df">Windows Media Services 2008</a>*<br />(KB952068)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffb5d945-7f98-4849-b020-ed4873fa42df">Windows Media Services 2008</a>*<br />(KB952068)<br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48aecf4c-1296-490d-ba37-a28e3ec19bd6">Windows Server 2008 for x64-based Systems</a>*<br />(Kriittinen)<br /></td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1deab57-ada2-4b12-9157-5615e7b0071d">Windows Server 2008 for x64-based Systems</a>***<br />(KB958623)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e41f23e4-6a2f-4ebb-b425-d241a08da316">Windows Server 2008 for x64-based Systems</a>***<br />(KB958624)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=405b28db-47d7-4d6b-90e6-834c0a409323">Windows Internet Explorer 7</a>**<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=889c6eb1-7d1f-4e60-b637-535cb6e4e443">Windows Internet Explorer 7</a>**<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8cab6fe8-161d-4d8c-9772-eb3174a2c3c3">Windows Media Format Runtime 11</a>
                    <br />(KB952069)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0204a366-5641-4036-9cb0-a46d04af9d72">Windows Media Services 2008</a>*<br />(KB952068)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0204a366-5641-4036-9cb0-a46d04af9d72">Windows Media Services 2008</a>*<br />(KB952068)<br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9bfe15cd-02ff-45cf-85c8-5ff1e6c1a871">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Kriittinen)<br /></td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48bed90d-c243-4969-8e54-326d9a7af343">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(KB958623)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=83de2263-de2a-4c13-96ba-ecfebdaf0bb9">Windows Server 2008 for Itanium-based Systems</a><br />(KB958624)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f0d4f321-941e-4da7-958f-582c75542ee8">Windows Internet Explorer 7</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06cb502a-6818-4599-aa24-6eddb83e4b84">Windows Internet Explorer 7</a>
                    <br />(Kriittinen)</td><td>Ei koske</td></tr>
              </table>


**Huomautus: MS08-078**

Tietoturvatiedotteessa MS08-078 käsiteltävästä haavoittuvuudesta ilmoitettiin Windows Internet Explorer 8 Beta 2:n julkistamisen jälkeen. Windows Internet Explorer 8 Beta 2:n käyttäjiä suositellaan lataamaan ja asentamaan päivitys järjestelmäänsä.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)- ja [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) -sivustoista. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

**Huomautukset : Windows Server 2008**

**\*Windows Server 2008 Server Core -asennus, jota haavoittuvuus koskee.** Tämä päivitys koskee tuettuja Windows Server 2008 -versioita samalla luokituksella siitä riippumatta. onko Windows Server 2008:n asennuksessa käytetty Server Core -asennusta vai ei. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Windows Server 2008 Server Core -asennus, joita haavoittuvuus koskee.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksella. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Haavoittuvuus ei koske Windows Server 2008 Server Core -asennuksia.** Haavoittuvuudet, jotka nämä päivitykset korjaavat, eivät koske tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksena, vaikka järjestelmässä olisi tiedostoja, joita nämä haavoittuvuudet koskevat. Käyttäjille, joilla on haavoittuvia tiedostoja, kuitenkin tarjotaan tämä päivitys, koska päivitystiedostot ovat uudempia (niiden versionumero on suurempi) kuin järjestelmässä olevat tiedostot. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office -ohjelmistopaketit ja -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="5">Microsoft Office -ohjelmistopaketit, -järjestelmät ja -osat</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=130478">
                      <strong>MS08-070</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=126306">
                      <strong>MS08-072</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=131481">
                      <strong>MS08-074</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=126307">
                      <strong>MS08-077</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
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
                  </td><td>Ei mitään</td></tr>
                <tr><td>Microsoft Office 2000 Service Pack 3</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43e8c4d8-307b-48f6-ac99-a9617421d40a">Microsoft Office Word 2000 Service Pack 3</a>
                    <br />(KB956328)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f39d2a49-f861-4f2d-bf91-94a8a85af40c">Microsoft Office Excel 2000 Service Pack 3</a>
                    <br />(KB958435)<br />(Kriittinen)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ef41412-50b3-4077-b0e3-9a3704d2f876">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB956329)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72076e21-2aa3-48e8-883a-c3cb756fc72a">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB958372)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45c81c60-4b1b-4246-839b-198ebc4eeae2">Microsoft Office Word 2003 Service Pack 3</a>
                    <br />(KB956357)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c0771e5-fcd4-4365-b903-1a3bd95d9e66">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB958436)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>2007 Microsoft Office System</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37">Microsoft Office Word 2007</a>
                    <br />(KB956358)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37">Microsoft Office Outlook 2007</a><br />(KB956358)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf">Microsoft Office Excel 2007</a>
                    <br />(KB958437)**** <br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>2007 Microsoft Office System Service Pack 1</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37">Microsoft Office Word 2007 Service Pack 1</a>
                    <br />(KB956358)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37">Microsoft Office Outlook 2007 Service Pack 1</a><br />(KB956358)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf">Microsoft Office Excel 2007 Service Pack 1</a>
                    <br />(KB958437)****<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Office FrontPage</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a6130ae-c5b4-43cb-afe3-ab6a55b9d9ea">Microsoft Office FrontPage 2002 Service Pack 3</a>*<br />(KB957797)<br />(Kriittinen)</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Office Project</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89a44042-a629-40f3-800a-0bb45fc36591">Microsoft Office Project 2003 Service Pack 3</a>
                    <br />(KB949045)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6">Microsoft Office Project 2007</a><br />(KB949046)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6">Microsoft Office Project 2007 Service Pack 1</a><br />(KB949046)<br />(Kriittinen)</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td></tr>
              
                <tr><th colspan="5">Microsoft Office for Mac</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=130478">
                      <strong>MS08-070</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=126306">
                      <strong>MS08-072</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=131481">
                      <strong>MS08-074</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=126307">
                      <strong>MS08-077</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2004 for Mac</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820">Microsoft Office 2004 for Mac</a>**<br />(KB960402)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820">Microsoft Office 2004 for Mac</a>**<br />(KB960402)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Office 2008 for Mac</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62">Microsoft Office 2008 for Mac</a>**<br />(KB960401)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62">Microsoft Office 2008 for Mac</a>**<br />(KB960401)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Open XML File Format Converter for Mac</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7">Open XML File Format Converter for Mac</a>**<br />(KB960403)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7">Open XML File Format Converter for Mac</a>**<br />(KB960403)<br />(Tärkeä)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="5">Muu Office-ohjelmisto</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=130478">
                      <strong>MS08-070</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=126306">
                      <strong>MS08-</strong>
                      <strong>072</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=131481">
                      <strong>MS08-074</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=126307">
                      <strong>MS08-077</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>
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
                <tr><td>Microsoft Works</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1537d181-90d9-4bb5-b5ae-8d9990a349af">Microsoft Works 8</a>***<br />(KB959487)<br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer</td><td>Ei koske</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e">Microsoft Office Excel Viewer 2003</a>
                    <br />(KB958434)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e">Microsoft Office Excel Viewer 2003 Service Pack 3</a><br />(KB958434)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9dbb35c1-aa7a-481b-a330-8ba916ddd443">Microsoft Office Excel Viewer</a><br />(KB958442)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Office Word Viewer</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70de7c3c-519f-4f4a-a03f-027f80b5415c">Microsoft Office Word Viewer 2003 Service Pack 3 ja Microsoft Office Word Viewer</a>
                    <br />(KB956366)<br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti</a>
                    <br />(KB956828)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1</a><br />(KB956828)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti</a>
                    <br />(KB958439)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1</a><br />(KB958439)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Office SharePoint Server 2007</td><td>Ei koske</td><td>Ei koske</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e">Microsoft Office SharePoint Server 2007 (32-bittiset versiot)</a>
                    <br />(KB956716)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e">Microsoft Office SharePoint Server 2007 Service Pack 1 (32-bittiset versiot)</a><br />(KB956716)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86">Microsoft Office SharePoint Server 2007 (64-bittiset versiot)</a><br />(KB956716)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86">Microsoft Office SharePoint Server 2007 Service Pack 1 (64-bittiset versiot)</a><br />(KB956716)<br />(Tärkeä)</td></tr>
              </table>


**Huomautus: MS08-070**  
Seuraavana olevassa kohdassa **Microsoft-kehitystyökalut ja ohjelmisto** on lisää päivitystiedostoja. Tämä tiedote kattaa sekä Microsoft Officen että Microsoft-kehitystyökalut ja ohjelmiston.

**Huomautus: MS08-077**  
Kohdassa **Microsoft Server -ohjelmisto** on lisää päivitystiedostoja. Tämä tiedote kattaa sekä Microsoft Office -ohjelmistopaketit ja -ohjelmiston että Microsoft Server -ohjelmiston.

**Huomautus: Microsoft Office FrontPage tiedotteessa MS08-070**  
\*Tämä päivitys koskee vain seuraavia FrontPage 2002 Service Pack 3 -kieliversioita: yksinkertaistettu kiina (Kiina), yleiskiina (Hongkong), perinteinen kiina (Taiwan) ja korea.

**Huomautus: Microsoft Office for Mac tiedotteissa MS08-072 ja MS08-074**  
\*\*Tiedotteiden MS08-072 ja MS08-074 vastaavat päivitykset ovat samanlaiset. Koska haavoittuvuudet ovat samoissa tiedostoissa, kummankin tiedotteen päivitykset ovat samat.

**Huomautus: Works 8 tietoturvatiedotteessa MS08-072**  
\*\*\*Jotta Microsoft Works 8.0:aa käyttäville asiakkaille voitaisiin tarjota tämä tietoturvapäivitys, heidän on ensin päivitettävä ohjelmansa Works 8.5:een artikkelissa [Microsoft Works -päivitys](http://www.microsoft.com/products/works/international/update_1001.mspx) (englanninkielinen) kuvatulla tavalla. Tämä koskee kaikkia asiakkaita, jotka käyttävät ohjelmia Microsoft Works 8.0, Works Suite 2004 ja Works Suite 2005. Jos asiakkaiden käytössä on Works Suite 2006, Works 8.5 sisältyy siihen.

**Huomautus: Microsoft Office Excel 2007 ja Microsoft Office Excel 2007 Service Pack 1 tietoturvatiedotteessa MS08-074**  
\*\*\*\*Microsoft Office Excel 2007 ja Microsoft Office Excel 2007 Service Pack 1: tietoturvapaketin KB958437 lisäksi asiakkaiden on asennettava [Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin](http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f) (KB958439) tietoturvapäivitys, joka suojaa tietoturvatiedotteessa MS08-074 kuvatuilta haavoittuvuuksilta. Jos asiakkaan päivityspakettien KB958437 ja KB958439 asennus onnistui, niitä ei tarvitse asentaa uudelleen.

#### Microsoft-kehitystyökalut ja ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Visual Studio</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=130478">
                      <strong>MS08-070</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visual Basic</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e27eebcb-095d-43ec-a19e-4a46e591715c">Microsoft Visual Basic 6.0:n suorituksenaikaiset lisätiedostot</a>
                    <br />(KB926857)<br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio .NET</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afad980d-7f27-49d9-aa23-b762c7b94cd6">Microsoft Visual Studio .NET 2002 Service Pack 1</a>
                    <br />(KB958392)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ac7cf8f-d046-43a8-b4ef-253153d65aed">Microsoft Visual Studio .NET 2003 Service Pack 1</a><br />(KB958393)<br />(Kriittinen)</td></tr>
                <tr><td>Microsoft Visual FoxPro</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a6977f81-f7f6-486b-96ad-8d296d79f205">Microsoft Visual FoxPro 8.0 Service Pack 1</a>
                    <br />(KB958369)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=386d27a6-b2c7-4acc-bf3e-edcbc7358172">Microsoft Visual FoxPro 9.0 Service Pack 1</a><br />(KB958370)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b1f28a9-da8d-463a-8ae4-dfc8fcc6c41a">Microsoft Visual FoxPro 9.0 Service Pack 2</a><br />(KB958371)<br />(Kriittinen)</td></tr>
              </table>


**Huomautus: M** **S08-070**  
Edellä olleessa kohdassa **Microsoft Office -ohjelmistopaketit ja -ohjelmisto** on lisää päivitystiedostoja. Tämä tiedote kattaa sekä Microsoft Office -ohjelmistopaketit ja -ohjelmiston että Microsoft-kehitystyökalut ja ohjelmiston.

#### Microsoft Server -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Search Server</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=126307">
                      <strong>MS08-077</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Search Server</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e">Microsoft Search Server 2008 (32-bittiset versiot)</a>*<br />(KB956716)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86">Microsoft Search Server 2008 (64-bittiset versiot)</a>*<br />(KB956716)<br />(Tärkeä)</td></tr>
              </table>


**Huomautus: MS08-077**

Microsoft Search Server 2008 Express (32-bittiset versiot)

Microsoft Search Server 2008 Express (64-bittiset versiot)

Kohdassa **Microsoft Office -ohjelmistopaketit ja -ohjelmisto** on lisää päivitystiedostoja. Tämä tiedote kattaa sekä Microsoft Office -ohjelmistopaketit ja -ohjelmiston että Microsoft Server -ohjelmiston.

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakes** **kus**

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

#### Microsoft Active Protections Program (MAPP)

Microsoft haluaa parantaa asiakkaittensa tietoturvasuojauksia tarjoamalla haavoittuvuustietoja suurille tietoturvaohjelmistojen valmistajille ennen joka kuukausi julkaistavan tietoturvapäivityksen julkaisemista. Tietoturvaohjelmistojen valmistajat voivat sitten päivittää näiden haavoittuvuustietojen perusteella asiakkailleen tarjoamiaan tietoturvaohjelmistoja tai laitteita. Tällaisia ovat esimerkiksi viruksentorjunta, verkkopohjaiset tunkeutumisen havaintojärjestelmät ja isäntäpohjaiset tunkeutumisenestojärjestelmät. Voit selvittää, mitä aktiivisia suojauksia tietoturvaohjelmistojen toimittajilla on tarjolla, tutustumalla ohjelman kumppanien ylläpitämiin aktiivisen suojauksen sivustoihin. Nämä kumppanit ovat [MAPP (Microsoft Active Protections Program) -kumppaneita](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

#### Tietoturvastrategiat ja yhteisö

**Ko** **rjaustiedostojen hallintamenetelmät**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivit** **ysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - ADLab ([Venustech](http://www.venustech.com.cn/)) ilmoitti useista haavoittuvuuksista, jotka on kuvattu tietoturvatiedotteessa MS08-070
  - Jason Medeiros ([Affiliated Computer Services](http://www.acs-inc.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-070
  - Carsten Eiram ([Secunia Research](http://secunia.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-070
  - Mark Dowd (yhteistyössä [McAfee Avert Labsin](http://www.avertlabs.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-070
  - Brett Moore ([Insomnia Security](http://www.insomniasec.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-070
  - CHkr\_D591 (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-070
  - Michal Bucko (yhteistyössä [CERT/CC](http://www.cert.org/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-070
  - Symantecin [Security Intelligence Analysis Team](http://www.symantec.com/) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS08-070
  - Jun Mao ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-071
  - Juan Caballero (yhteistyössä [Bitblaze-ryhmä Carnegie Mellon- ja UC Berkeley -yliopistoissa](http://bitblaze.cs.berkeley.edu/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-071
  - Ricardo Narvaja ([Core Security Technologies](http://www.coresecurity.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-072
  - Dyon Balding ([Secunia Research](http://secunia.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-072
  - Yamata Li ([Palo Alto Networks](http://www.paloaltonetworks.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-072
  - Wushi (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-072
  - Aaron Portnoy ([TippingPoint DVLabs](http://dvlabs.tippingpoint.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-072
  - Wushi ([team509](http://www.team509.com/)) yhteistyössä [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-072
  - Wushi ja Ling (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-072
  - Carlo Di Dato (eli shinnai) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-073
  - Brett Moore (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-073
  - Chris Weber ([Casaba Security](http://www.casabasecurity.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-073
  - Jun Mao ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-073
  - Joshua J. Drake ([Verisign iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-074
  - Claes M Nyberg ([signedness.org](http://www.signedness.org/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-074
  - Dyon Balding ([Secunia](http://secunia.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-074
  - Andre Protas ([eEye Digital Security](http://www.eeye.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-075
  - Nate McFeters ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-075
  - Tuntematon löytäjä ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS08-077

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (9. joulukuuta 2008): Tietoturvatiedotteen yhteenveto julkaistu.
  - V2.0 (10. joulukuuta 2008): Ohjelmistoja, joita tietoturvatiedote MS08-076 koskee, on tarkennettu lisäämällä Windows Media Format Runtime 9.5 ja Windows Media Format Runtime 11 erillisinä Windows XP Professional x64 Editionin ja Windows XP Professional x64 Edition Service Pack 2:n erillisinä päivityksinä. Lisäksi tietoturvatiedotteesta MS08-076 poistettiin virheelliset viittaukset ohjelmiin Windows Media Format Runtime 11 x64 Edition Windows XP Professional x64 Editionissa, Windows XP Professional x64 Edition Service Pack 2:ssa, Windows Server 2003 x64 Editionissa ja Windows Server 2003 x64 Edition Service Pack 2:ssa.
  - V3.0 (17. joulukuuta 2008): Yhteenvetoon on lisätty Microsoftin tietoturvatiedote MS08-078, Internet Explorerin tietoturvapäivitys (960714). Lisäksi on lisätty tämän erillisen tietoturvatiedotteen webcast-linkit.
  - V3.1 (18. joulukuuta 2008): Tietoturvatiedotteeseen MS08-078 on lisätty Windows Server 2008 for 32-bit Systemsin ja Windows Server 2008 for x64-based Systemsin Windows Internet Explorer 7:ää koskeva huomautus siitä, että ei koske Server Core -asennusta.
  - V3.2 (7. tammikuuta 2009): Poistettiin Microsoft Office Word Viewer 2003 ohjelmistoista, joita haavoittuvuuden kerrottiin koskevan tiedotteessa MS08-072.
  - V4.0 (13. tammikuuta 2009): Microsoft on julkaissut uudelleen tiedotteen MS08-076. Tiedote sisältää nyt uudet Windows XP Service Pack 2:n (KB952069) ja Windows XP Service Pack 3:n (KB952069) Windows Media Format Runtime 9.5:n päivitykset. Asiakkaiden, jotka käyttävät sellaisia Windows Media -osien versioita, joita haavoittuvuus koskee ja joita tuetaan, ja jotka ovat päivittäneet järjestelmänsä alkuperäisellä MS08-076-tietoturvapäivityksellä, ei tarvitse tehdä mitään. Myös Windows Media Player 6.4 ja Windows Media Services 4.1 mainittiin tiedotteessa MS08-076 ohjelmistoina, joita haavoittuvuus koskee kaikissa Microsoft Windows 2000 Service Pack 4 -asennusversioissa. Asiakkaat, joille päivitystä tarjottiin mutta jotka eivät ole sitä asentaneet (päivitys KB954600 koskee Windows Media Player 6.4:ää ja KB952068 Windows Media Services 4.1:tä), on asennettava päivitys nyt. Tämän lisäksi Microsoft Office Word Viewer mainittiin tiedotteessa MS08-072 ohjelmistona, jota haavoittuvuus koskee. Asiakkaat, jotka ovat asentaneet tietoturvapäivityksen KB956366, ei tarvitse asentaa sitä uudelleen.
  - V5.0 (28. tammikuuta 2009): Tietoturvatiedotteen MS08-074 **Ohjelmistot, joita haavoittuvuus koskee** -taulukkoon lisättiin alaviite. Se koskee tuettujen Microsoft Office Excel 2007 -versioiden tietoturvapäivityspaketteja KB958437 ja KB958439. Tietoturvapäivityksen binaaritiedostoja tai tunnistusta ei muutettu. Jos Microsoft Office Excel 2007:n tai Microsoft Office Excel 2007 Service Pack 1:n käyttäjät ovat asentaneet onnistuneesti päivitykset KB958437 ja KB958439, niitä ei tarvitse asentaa uudelleen.
  - V6.0 (29. huhtikuuta 2009): Windows Server 2008 Service Pack 2:n 32-bittisiin ja x64-pohjaisiin versioihin asennettu Windows Media Services 2008 (KB952068) on lisätty ohjelmistona, jota tietoturvatiedote MS08-076 koskee. Muutos koskee ainoastaan tunnistusta, binaareja ei ole muutettu. Jos asiakkaan päivityspaketin KB952068 asennus onnistui, sitä ei tarvitse asentaa uudelleen.

*Built at 2014-04-18T01:50:00Z-07:00*

