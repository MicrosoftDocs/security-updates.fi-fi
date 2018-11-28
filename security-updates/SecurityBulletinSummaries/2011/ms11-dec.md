---
title: Microsoftin tietoturvatiedotteiden yhteenveto, joulukuu 2011
TOCTitle: MS11-DEC
ms:assetid: ms11-dec
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms11-dec(v=Security.10)
ms:contentKeyID: 61225723
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin tietoturvatiedotteiden yhteenveto, joulukuu 2011

Julkaistu: 13. joulukuuta 2011 | Päivitetty: 22. helmikuuta 2012

**Versio:** 2.1

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo joulukuussa 2011 julkaistuista tietoturvatiedotteista.

Tämä tietoturvatiedotteiden yhteenveto korvaa joulukuun 2011 tietoturvatiedotteiden julkaisun yhteydessä tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 28. joulukuuta 2011. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 14. joulukuuta 2011, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt joulukuun tietoturvatiedotteen webcast-lähetykseen](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487961). Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://go.microsoft.com/fwlink/?linkid=217214) kertovassa englanninkielisessä sivustossa.

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 29. joulukuuta 2010, klo 23 Suomen aikaa (kello 13:00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt 29. joulukuuta 2010 klo 23 Suomen aikaa järjestettävään tietoturvatiedotteen webcast-lähetykseen](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032502798&culture=en-us). Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://go.microsoft.com/fwlink/?linkid=217214) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja muut päivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

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
<th>Edellyttää uudelleenkäynnistystä</th>
<th>Ohjelmistot, joita haavoittuvuus koskee</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=233008">MS11-087</a></td>
<td><strong>Windowsin ydintilan ohjaimien haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2639417)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Microsoft Windowsin haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun tai siirtyy haitalliseen sivustoon, joka käyttää upotettuja TrueType-fonttitiedostoja.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232507">MS11-090</a></td>
<td><strong>ActiveX Kill Bit -arvojen kumulatiivinen tietoturvapäivitys (2618451)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft-ohjelmistojen haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua, joka käyttää tietynlaisia binaaritiedostoja Internet Explorerissa. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Tämä päivitys sisältää myös neljä kolmannen osapuolen ActiveX-komponentin Kill Bit -arvoa.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232517">MS11-092</a></td>
<td><strong>Windows Median haavoittuvuus saattaa</strong> <strong>sallia koodin suorittamisen verkon välityksellä (2648048)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Media Playerin ja Windows Media Centerin haavoittuvuuden. Haavoittuvuuden hyödyntäminen saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Microsoft Digital Video Recording (.dvr-ms) -tiedoston. Käyttäjää ei voi missään tapauksessa pakottaa avaamaan tiedostoa, vaan hyökkäys onnistuu vain, jos käyttäjä saadaan suostutelluksi avaamaan tiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227070">MS11-088</a></td>
<td><strong>Microsoft Office IME:n (kiinankielinen) saattaa sallia käyttöoikeuksien laajentamisen (</strong> <strong>2652016)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Office IME:n haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen, jos kirjautunut käyttäjä suorittaa tiettyjä toimia järjestelmässä, johon on asennettu Microsoft Pinyin (MSPY) Input Method Editorin (IME) yksinkertaistetun kiinan kieliversio. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi suorittaa haluamansa koodin ydintilassa. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda tilejä kaikilla valtuuksilla. Tämä haavoittuvuus koskee vain Microsoft Pinyin IME 2010 -toteutuksia. Se ei koske muita yksinkertaistetun kiinan IME-versioita tai muita IME-toteutuksia.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=225739">MS11-089</a></td>
<td><strong>Microsoft Officen haavoittuvuus saattaa</strong> <strong>sallia koodin suorittamisen verkon välityksellä (2590602)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Officen haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Word-tiedoston. Tätä haavoittuvuutta onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin sisäänkirjautunut käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td><strong>Microsoft Publisherin haavoittuvuus saattaa</strong> <strong>sallia koodin suorittamisen verkon välityksellä (2607702)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yhden yleisessä tiedossa olevan haavoittuvuuden ja kolme yksityishenkilön ilmoittamaa Microsoft Officen haavoittuvuutta. Vakavin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Publisher-tiedoston. Hyödyntämällä jotakin näistä haavoittuvuuksista onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232516">MS11-093</a></td>
<td><strong>OLE-haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2624667)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden kaikissa tuetuissa Windows XP- ja Windows Server 2003 -versioissa. Tämä tietoturvatiedote on luokiteltu tärkeäksi kaikissa tuetuissa Windows XP- ja Windows Server 2003 -versioissa. Haavoittuvuus ei koske Windows Vista-, Windows Server 2008-, Windows 7- ja Windows Server 2008 R2 -versioita.<br />
<br />
Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tiedoston, jossa on tietyllä tavalla muodostettu OLE-objekti. Tätä haavoittuvuutta onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin paikallinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td><strong>Microsoft PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (2639142)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksiyksityishenkilön ilmoittamaa Microsoft Officen haavoittuvuutta. Haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun PowerPoint-tiedoston. Hyödyntämällä jompaakumpaa haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232666">MS11-095</a></td>
<td><strong>Active Directoryn haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2640045)</strong><br />
<br />
Tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Active Directoryn, ADAM:n (Active Directory Application Mode) ja AD LDS:n (Active Directory Lightweight Directory Service) haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä kirjautuu Active Directory -toimialueeseen ja suorittaa tietyllä tavalla muodostetun sovelluksen. Haavoittuvuuden hyödyntäminen edellyttää, että hyökkääjällä on kirjautumista varten Active Directory -toimialueen tunnistetiedot.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232696">MS11-096</a></td>
<td><strong>Microsoft Excelin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2640241)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Officen haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Excel-tiedoston. Tätä haavoittuvuutta onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin sisäänkirjautunut käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Jos epäilyttävien tiedostojen avaaminen estetään Office-tiedostojen tarkistustoiminnolla, hyökkääjä ei voi hyödyntää haavoittuvuuksia, jotka on kuvattu tunnuksella CVE-2011-3403.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232663">MS11-097</a></td>
<td><strong>Windows-asiakkaan ja CRSSS</strong> <strong>-järjestelmän haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (2620712)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen, jos hyökkääjä on kirjautunut haavoittuvuuden sisältävään järjestelmään ja suorittaa tietyllä tavalla muodostetun sovelluksen, joka on luotu lähettämään laitteelle tapahtumasanoma korkeampaan eheysprosessiin. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja pystyttävä kirjautumaan paikallisesti, jotta hän pystyy hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232424">MS11-098</a></td>
<td><strong>Windows-ytimen haavoittuvuus saattaa aiheuttaa käyttöoikeuksien laajentumisen (2633171)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen, jos hyökkääjä kirjautuu järjestelmään, jota haavoittuvuus koskee, ja suorittaa tietyllä tavalla muodostetun sovelluksen. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja pystyttävä kirjautumaan paikallisesti, jotta hän pystyy hyödyntämään tätä haavoittuvuutta. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td><strong>Internet Explorerin</strong> <strong>kumulatiivinen tietoturvapäivitys (2618444)</strong><br />
<br />
Tämä tietoturvatiedote korjaa kolme yksityishenkilön ilmoittamaa Internet Explorerin haavoittuvuutta. Vakavin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa oikean HyperText Markup Language (HTML) -tiedoston verkkokansiossa, jossa on myös tietyllä tavalla muodostettu kirjastotiedosto (DLL).</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td><strong>.NET Frameworkin <strong></strong>haavoittuvuudetsaattavat <strong>salli</strong> a käyttöoikeuksien laajentamisen</strong> <strong>(</strong> <strong>2638420</strong> <strong>)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yhden yleisessä tiedossa olevan haavoittuvuuden ja kolme yksityishenkilön ilmoittamaa Microsoft .NET Frameworkin haavoittuvuutta. Haavoittuvuuksista pahin saattaa sallia käyttöoikeuksien korottamisen, jos todentamaton hyökkääjä lähettää tietyllä tavalla muotoillun verkkopyynnön kohdesivustoon. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi suorittaa minkä tahansa toiminnon ASP.NET-sivustolla jo olemassa olevan tilin puitteissa, kuten satunnaisten komentojen suorittamisen. Haavoittuvuuden hyödyntäminen edellyttää hyökkääjän rekisteröivän tilin ASP.NET-sivustolle, jota varten hänen täytyy tietää jo olemassa oleva käyttäjänimi.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>


## Hyödyntämisindeksi

Seuraavassa taulukossa on kunkin tässä kuussa käsitellyn haavoittuvuuden hyödyntämisluokitus. Haavoittuvuudet on järjestetty ensin tiedotteen tunnuksen ja sitten CVE-tunnuksen mukaan. Taulukossa on vain haavoittuvuudet, jotka on luokiteltu tiedotteissa kriittisiksi tai tärkeiksi.

**Miten taulukkoa käytetään?**

Tämän taulukon avulla saat selville, kuinka todennäköistä on sellaisen hyväksikäyttökoodin tai palveluneston julkaiseminen 30 päivän kuluessa tietoturvatiedotteen julkaisemisesta, joka koskee tietoturvapäivitystä, joka sinun on ehkä asennettava. Tutustu järjestelmän määritysten perusteella kuhunkin arviointiin. Tällä tavoin voit ottaa päivitykset käyttöön tärkeysjärjestyksessä. Lisätietoja näistä luokituksista ja niiden määrittämisestä on [Microsoftin hyödyntämisindeksissä](http://technet.microsoft.com/security/cc998259.aspx).

Alla olevissa sarakkeissa "Uusin ohjelmistoversio" viittaa uusimpaan ohjelmistoversioon ja "Aiemmat ohjelmistoversiot" viittaa vanhempiin tuettuihin ohjelmistoversioihin tietoturvatiedotteen taulukoissa "Ohjelmistot, joita haavoittuvuus koskee" ja "Ohjelmistot, joita haavoittuvuus ei koske".

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th>Tiedotteen tunnus</th>
<th>Haavoittuvuuden otsikko</th>
<th>CVE-tunnus</th>
<th>Uusimman ohjelmistoversion koodin suorittamisen hyödyntämisaste</th>
<th>Aiempien ohjelmistoversioiden koodin suorittamisen hyödyntämisaste</th>
<th>Hyödyntämisasteen palvelunesto</th>
<th>Tärkeät huomautukset</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=233008">MS11-087</a></td>
<td>Haavoittuvuus TrueType-fontin jäsennyksessä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402">CVE-2011-3402</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>Tämä haavoittuvuus on ollut yleisessä tiedossa.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227070">MS11-088</a></td>
<td>Pinyin IME:n käyttöoikeuksien korottamista koskeva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2010">CVE-2011-2010</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei koske</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=225739">MS11-089</a></td>
<td>Wordin vapautuksen jälkeistä käyttöä koskeva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1983">CVE-2011-1983</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232507">MS11-090</a></td>
<td>Microsoft Timen koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3397">CVE-2011-3397</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td>Publisherin muistialueen ulkopuolelle osoittavan osoittimen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3410">CVE-2011-3410</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td>Publisherin osoittimen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3411">CVE-2011-3411</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td>Publisherin muistin vioittumishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3412">CVE-2011-3412</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Hyväksikäyttökoodia on vaikea laatia</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232517">MS11-092</a></td>
<td>Windows Media Playerin DVR-MS-muistin vioittumishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3401">CVE-2011-3401</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232516">MS11-093</a></td>
<td>OLE-ominaisuuden haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3400">CVE-2011-3400</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td>Suojaamattomaan PowerPoint-kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3396">CVE-2011-3396</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Haavoittuvuus koskee Microsoft PowerPoint 2010:a vain, jos uusinta Service Pack -päivitystä ei ole asennettu.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td>OfficeArt Shape -tietueen koodin suorittamisen salliva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3413">CVE-2011-3413</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Hyväksikäyttökoodia on vaikea laatia</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232666">MS11-095</a></td>
<td>Active Directoryn puskurin ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3406">CVE-2011-3406</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>Haavoittuvuus koskee vain järjestelmiä, joissa on käytössä Active Directory, AD LDS tai ADAM.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232696">MS11-096</a></td>
<td>Haavoittuvuus tietuemuistin käytössä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3403">CVE-2011-3403</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232663">MS11-097</a></td>
<td>CSRSS:n paikallisten käyttöoikeuksien korottamista koskeva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3408">CVE-2011-3408</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232424">MS11-098</a></td>
<td>Windows-ytimen poikkeuskäsittelyn haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2018">CVE-2011-2018</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td>XSS-suodattimen tietojen paljastumisen salliva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1992">CVE-2011-1992</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä on tietojen paljastumisen muille käyttäjille aiheuttava haavoittuvuus.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td>Suojaamattomaan Internet Explorerin kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2019">CVE-2011-2019</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei koske</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td>HashTable-virheet voivat aiheuttaa DoS-haavoittuvuuden</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3414">CVE-2011-3414</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Väliaikainen</td>
<td>Tämä haavoittuvuus aiheuttaa ainoastaan palveluneston, ja on yleisessä tiedossa.
<div>

</div>
<div>
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">Palvelunestohaavoittuvuudet ovat arvioluokitukseltaan &quot;3&quot;.</a>
</div></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td>ASP.Net-lomakkeiden todentamisen ohitushaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3416">CVE-2011-3416</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Käyttöoikeuksien korottaminen - tilin valtaus</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td>ASP.NET-lomakkeiden todentamispyyntöjen välimuistihaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3417">CVE-2011-3417</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Hyväksikäyttökoodia on vaikea laatia</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Hyväksikäyttökoodia on vaikea laatia</td>
<td>Ei käytössä</td>
<td>Käyttöoikeuksien korottaminen - tilin valtaus</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

Seuraavissa taulukoissa tiedotteet on järjestetty pääohjelmistoluokkien ja vakavuuden mukaan.

**Taulukoiden käyttö**

Näiden taulukoiden avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja koskeeko jokin tietoturvapäivitys niiden asennusta. Jos ohjelma tai osa on luettelossa, saatavana olevaan ohjelmistopäivitykseen on linkki. Myös ohjelmistopäivityksen luokitus mainitaan.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää useiden tietoturvapäivitysten asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

#### Windows-käyttöjärjestelmä ja osat

**Taulukko 1**

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=233008">
                      <strong>MS11-087</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232507">
                      <strong>MS11-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232517">
                      <strong>MS11-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232516">
                      <strong>MS11-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232666">
                      <strong>MS11-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232663">
                      <strong>MS11-097</strong>
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
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b01bb041-005c-48c4-a606-66aa264ba0fa">Windows XP Service Pack 3</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=21b4b999-2dbf-4921-80bd-cc7ab2cd1190">Windows XP Service Pack 3</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d85091b5-69bb-4d0f-839a-a65cd94e2887">Windows XP Service Pack 3</a>
                    <br />(KB2619339)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03bc6446-7cf3-47c4-8ed1-a53a4d53a429">Windows XP Media Center Edition 2005 Service Pack 3</a><br />(KB2619340)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73531165-f299-4b62-b738-52fca410eaae">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b816964-d3c3-4f05-94c3-f54a6f54ca73">Active Directory Application Mode (ADAM)</a>
                    <br />(KB2626416) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=edb594a4-14d2-4ffe-8d1c-2c283689fe8c">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a872cd2-5f4d-400c-a1c4-a2d194746fb6">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=126e8092-980d-471a-867d-d5939671b7df">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d1d1e9a-603c-4895-a69f-b61186a75ad5">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2619339)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a98bb7cf-9939-4927-8d21-ccb3845e7cb7">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=986f0087-c674-4060-8710-af3496adbfdd">Active Directory Application Mode (ADAM)</a>
                    <br />(KB2626416) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e1273e2-7775-40b4-b939-ab530677cd4a">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=233008">
                      <strong>MS11-087</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232507">
                      <strong>MS11-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232517">
                      <strong>MS11-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232516">
                      <strong>MS11-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232666">
                      <strong>MS11-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232663">
                      <strong>MS11-097</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokitus </strong>
                    <strong>kooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
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
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e84e6964-1580-41ef-9d3e-4d0c3ad4cb69">Windows Server 2003 Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dfb948c5-8aee-4bcd-babf-3564b78712dd">Windows Server 2003 Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b555040-1117-4b06-a48c-02f0e1b686d8">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01caf06f-777d-4ea8-95ca-e11d60a973ad">Active Directory</a>
                    <br />(KB2621146) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f7c7ccd-22a3-4fbc-bf21-bd0e42ab1da5">Active Directory Application Mode (ADAM)</a><br />(KB2626416) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a14057e5-e2c2-4dde-8d26-542a9f162e98">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d9f3667-3fd6-4948-83db-282783599f41">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2d37a8cb-2316-4db4-980c-11b6dcbdc696">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eb17782c-f754-42ab-905b-6f141df008c3">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1ba50cf-fc6b-4668-b71c-e9f75a8ac638">Active Directory</a>
                    <br />(KB2621146) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b610eb3-456c-4125-94b7-1ead4face8e3">Active Directory Application Mode (ADAM)</a><br />(KB2626416) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f595fd6-bdfd-4075-97e5-70efb7d49dff">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ecf72cd-6732-4cf3-aa22-8caf15ea633e">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7726ddbe-0578-44fb-a40f-49b804a45989">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4cdde8a9-6d44-41fa-82c0-a25404cdfbb5">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=74099261-60ad-4c68-906c-60e131818955">Active Directory</a>
                    <br />(KB2621146) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=147ec6d3-3401-4aa3-a409-55346bcc7bd7">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=233008">
                      <strong>MS11-087</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232507">
                      <strong>MS11-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232517">
                      <strong>MS11-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232516">
                      <strong>MS11-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232666">
                      <strong>MS11-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232663">
                      <strong>MS11-097</strong>
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
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f69ec9d-43ad-4106-90ef-c191e7ec43af">Windows Vista Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1dd069a2-fb1a-4f31-88cc-bc031c3e2c80">Windows Vista Service Pack 2</a>
                    <br />(Ei luokitusta[1])</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9130fad-de8c-4be0-aea1-62cbaa310b76">Windows Vista Service Pack 2</a>
                    <br />(KB2619339)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=470da512-2c8b-4ba9-b7bb-b9e6c45cd33f">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2621146) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa6e6d91-4aca-49a6-a6e8-c33ec413097e">Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae1f1f86-6f13-4e1e-9f93-4f70b6c9927e">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60fd5bf6-e820-44f6-8081-b98c0103acc1">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Ei luokitusta[1])</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7c4bf05-eb2d-48ac-a6df-8afd88e811d8">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2619339)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8daf9a49-60cb-4813-ac7a-e9a4bf296889">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2621146) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9794756-803d-48ba-86db-350fb577f01b">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=233008">
                      <strong>MS11-087</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232507">
                      <strong>MS11-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232517">
                      <strong>MS11-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232516">
                      <strong>MS11-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232666">
                      <strong>MS11-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232663">
                      <strong>MS11-097</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4ba344d-dd0d-4cfb-81d9-d364d7f37e25">Windows Server 2008 for 32-bit Systems Service Pack 2</a>****<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f485d4c3-a4af-4ae6-9404-e79afcbb4f6e">Windows Server 2008 for 32-bit Systems Service Pack 2</a>**<br />(Ei luokitusta[1])</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f9ddcdb-a471-4e00-a697-92a24e4ea8d4">Active Directory ja Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB2621146) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f934885-b134-400c-a452-50fd4eeedd5e">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=058963f6-9654-41d0-86d2-f25a0c2ad416">Windows Server 2008 for x64-based Systems Service Pack 2</a>****<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28598ef6-13fb-44fd-8c76-599af7b0a01d">Windows Server 2008 for x64-based Systems Service Pack 2</a>**<br />(Ei luokitusta[1])</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5253477b-422f-404a-941e-8b69da5a2670">Active Directory ja Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB2621146) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ade3832-bc20-4fce-8eac-8a3d072d2f1c">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=42cd1c33-11a7-4a29-ae85-f7272a626f91">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5915e19c-b576-453b-b621-5737774f5955">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Ei luokitusta[1])</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4bd7a02b-c6d8-4eb5-a46d-e494a1233dc8">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=233008">
                      <strong>MS11-087</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232507">
                      <strong>MS11-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232517">
                      <strong>MS11-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232516">
                      <strong>MS11-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232666">
                      <strong>MS11-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232663">
                      <strong>MS11-097</strong>
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
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0526727a-f2fb-4846-9b04-f1899f52f1f6">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d112623c-86ce-434a-8fe1-ec3e3e632763">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Ei luokitusta[1])</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6e44069-dec5-48f6-8fc4-8ab375a10b4e">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(KB2619339)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d2e87199-6469-4bc0-a721-f43e817e4344">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2621146) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0666bdf5-9eed-44c9-84ee-b45f9b3e14b3">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cfd42c42-1595-419a-bf04-b23b64663629">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81114ecd-0c73-4ca6-8a66-09c6c636a5db">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Ei luokitusta[1])</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7997ab8-27e0-4714-845a-d237f4326587">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2619339)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba8d7aa9-8299-49a3-b0c0-b8b5eab48434">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2621146) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=620f94f9-1f61-45a0-a22e-e7510b56b9b8">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=233008">
                      <strong>MS11-087</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232507">
                      <strong>MS11-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232517">
                      <strong>MS11-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232516">
                      <strong>MS11-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232666">
                      <strong>MS11-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232663">
                      <strong>MS11-097</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d64a31ca-cccd-488a-98fd-c059b9e9e1ea">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>****<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc018647-08cb-431a-8e7c-5dc04980eaa9">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>**<br />(Ei luokitusta[1])</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a3e0d27c-8b29-4981-bdef-bcd037fd3408">Active Directory ja Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB2621146) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04878e9a-539a-4549-a5af-11d45add91da">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b46f6da7-6d24-4262-8e55-3b657db39813">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9323b9b9-e9b0-4941-afe0-196d22df9ab4">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Ei luokitusta[1])</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b2ebec4-cebb-47b6-864a-12d59a9a3e18">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td></tr>
              </table>


**Huomautukset Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 - tai Windows Server 2008 R2 -versioita, jos se asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*** **\*\*\*** **Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita, joilla on alempi luokitus, jos on käytetty Server Core -asennusta. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Huomautus: MS11-0** **90**

\[1\]Tässä tiedotteessa kuvattu haavoittuvuus ei koske tätä nimenomaista käyttöjärjestelmää. Saatavana oleva päivitys määrittää kolmannen osapuolen ohjausobjektien Kill Bit -arvot.

**Taulukko 2**

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="4">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232424">
                      <strong>MS11-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232505">
                      <strong>MS11-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232432">
                      <strong>MS11-100</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
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
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a6fcf8d-8c7b-4882-90d3-02db79a75238">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=caa9360b-2fd8-4f46-99e6-2decf1b60ca7">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc6dcd8c-c39f-4c4b-b5b2-b4c18c36973b">Internet Explorer 7</a><br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3906245-b6f6-464a-84b6-e1b6b195df95">Internet Explorer 8</a><br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656352)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2657424)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fa77733-70f5-46ff-9cfe-2262d292b870">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0c55d9b-8529-4d3d-910d-1a822a825be2">Internet Explorer 7</a><br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e60e996-8850-4d25-b994-39646e2cc25e">Internet Explorer 8</a><br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656352)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2657424)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)</td></tr>
              
                <tr><th colspan="4">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232424">
                      <strong>MS11-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232505">
                      <strong>MS11-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232432">
                      <strong>MS11-100</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokitus </strong>
                    <strong>kooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Ei tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=281e5bd4-4582-4aa9-af88-518ad3152132">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=759041cf-fd8b-4e04-b289-d74112bf978b">Internet Explorer 6</a>
                    <br />(Ei luokitusta[1])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1b4af92-3ff1-4727-9ba3-52764a7b81bb">Internet Explorer 7</a><br />(Ei luokitusta[1])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1cbe9469-05f4-4305-bbfd-76b4a04cd598">Internet Explorer 8</a><br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7538762a-50e9-4f13-a60e-ff99aa8fbbf8">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656358)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656352)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2657424)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5587eca8-86e9-4a63-81cb-81f68178a6c0">Internet Explorer 6</a>
                    <br />(Ei luokitusta[1])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a87f890-f106-41ab-bc53-4ca44dc99cb1">Internet Explorer 7</a><br />(Ei luokitusta[1])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a42fa727-482c-4578-9a30-61fdf14ed4da">Internet Explorer 8</a><br />(Ei tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656352)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2657424)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=02d5c057-d551-411b-917b-43d7795111bc">Internet Explorer 6</a>
                    <br />(Ei luokitusta[1])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fccb214-6c79-4ef6-9d6e-df4f16ef792e">Internet Explorer 7</a><br />(Ei luokitusta[1])</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656352)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2657424)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)</td></tr>
              
                <tr><th colspan="4">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232424">
                      <strong>MS11-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232505">
                      <strong>MS11-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232432">
                      <strong>MS11-100</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
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
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a6c7c960-768d-40d4-8fe5-7d59f48ead1d">Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0adc422f-73f2-46ee-973f-9b7603a76d1e">Internet Explorer 7</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4327147b-0481-4172-a835-8786abc50596">Internet Explorer 8</a><br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0b19b35-1d48-4419-ba3d-66063cc472a7">Internet Explorer 9</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656362)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2657424)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8a3f2351-380b-4566-b186-906dca426d39">Internet Explorer 7</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=987f0966-01de-4edf-a0d6-4032d1d72966">Internet Explorer 8</a><br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c951044b-4596-462f-bc8f-bdd9d6734297">Internet Explorer 9</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656362)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2657424)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)</td></tr>
              
                <tr><th colspan="4">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232424">
                      <strong>MS11-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232505">
                      <strong>MS11-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232432">
                      <strong>MS11-100</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Ei tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a4443f8-fec8-42be-ad67-8475920f1460">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eaf587f0-9951-4480-a08b-377e61aaf72b">Internet Explorer 7</a>**<br />(Ei luokitusta[1])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f5af52f-dece-4f0c-9fc0-d4973e4f7b1a">Internet Explorer 8</a>**<br />(Ei tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c03e65d6-4f92-4bc1-94b5-2f0183d0133e">Internet Explorer 9</a>**<br />(Ei luokitusta[1])</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB2656353)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2656362)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2657424)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>**[1]<br />(KB2656351)</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f18fc98-984a-4c02-951f-b8438a9e4f6b">Internet Explorer 7</a>**<br />(Ei luokitusta[1])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=808d26f7-c8fa-446d-9d2f-e8c0babb0c4a">Internet Explorer 8</a>**<br />(Ei tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7a582f3-0a18-4fbf-9b99-21c664bfd979">Internet Explorer 9</a>**<br />(Ei luokitusta[1])</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB2656353)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2656362)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2657424)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>**[1]<br />(KB2656351)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc62df39-7185-448b-b356-25a5a07886ec">Internet Explorer 7</a>
                    <br />(Ei luokitusta[1])</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656362)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2657424)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)</td></tr>
              
                <tr><th colspan="4">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232424">
                      <strong>MS11-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232505">
                      <strong>MS11-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232432">
                      <strong>MS11-100</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokitus </strong>
                    <strong>kooste</strong>
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
                <tr><td>Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eb2bd108-5ef1-45be-9157-e7cbfc8afd2a">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=018610bb-e80a-432a-8f32-f50451f71ad9">Internet Explorer 8</a>
                    <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec2046a6-f069-4f02-9600-7640e57be0a3">Internet Explorer 9</a><br />(Tärkeä)</td><td>Vain Windows 7 for 32-bit Systems: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c">Microsoft .NET Framework 3.5.1</a><br />(KB2656355)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)<br /><br />Vain Windows 7 for 32-bit Systems Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9">Microsoft .NET Framework 3.5.1</a><br />(KB2656356)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)<div></div></td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbe85b05-e252-4029-8e25-f2452db1c017">Internet Explorer 8</a>
                    <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c773b3d-0ca3-4b9b-af9a-9d6edcd261f7">Internet Explorer 9</a><br />(Tärkeä)</td><td>Vain Windows 7 for x64-based Systems: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c">Microsoft .NET Framework 3.5.1</a><br />(KB2656355)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)<br /><br />Vain Windows 7 for x64-based Systems Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9">Microsoft .NET Framework 3.5.1</a><br />(KB2656356)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)</td></tr>
              
                <tr><th colspan="4">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232424">
                      <strong>MS11-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232505">
                      <strong>MS11-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232432">
                      <strong>MS11-100</strong>
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
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2108b4ef-942f-4727-a1fc-ee7d0abb427c">Internet Explorer 8</a>**<br />(Ei tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72c1654e-526f-4ece-b7ad-767a0710e076">Internet Explorer 9</a>**<br />(Tärkeä)</td><td>Vain Windows Server 2008 R2 for x64-based Systems:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c">Microsoft .NET Framework 3.5.1</a>*<br />(KB2656355)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)<br /><br />Vain Windows Server 2008 R2 for x64-based Systems Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9">Microsoft .NET Framework 3.5.1</a>*<br />(KB2656356)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>*[1]<br />(KB2656351)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=74614510-e13c-43e8-90e7-d81e63895cf2">Internet Explorer 8</a>
                    <br />(Ei tärkeä)</td><td>Vain Windows Server 2008 R2 for Itanium-based Systems: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c">Microsoft .NET Framework 3.5.1</a><br />(KB2656355)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)<br /><br />Vain Windows Server 2008 R2 for Itanium-based Systems Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9">Microsoft .NET Framework 3.5.1</a><br />(KB2656356)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72">Microsoft .NET Framework 4</a>[1]<br />(KB2656351)</td></tr>
              </table>


**Huomautukset Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 - tai Windows Server 2008 R2 -versioita, jos se asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Huomautus: MS11-0** **99**

\[1\]Tällä päivityksellä ei ole luokitusta, koska tiedotteessa käsiteltyä haavoittuvuutta ei voi hyödyntää oletuskokoonpanossa. Microsoft kuitenkin suosittelee, että ohjelmiston käyttäjät asentavat tämän tietoturvapäivityksen.

**Huomautus: MS11-** **100**

\[1\] **Koskee .NET Framework 4:ää ja .NET Framework 4 Client Profilea.** .NET Framework version 4 jakelutiedostopaketeista on kaksi versiota: .NET Framework 4 and .NET Framework 4 Client Profile. .NET Framework 4 Client Profile on .NET Framework 4:n osajoukko. Haavoittuvuus, jonka tämä tietoturvapäivitys korjaa, koskee sekä .NET Framework 4:ää että .NET Framework 4 Client Profilea. Lisätietoja on MSDN-artikkelissa, jossa käsitellään [.NET Frameworkin asentamista](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Office -ohjelmistopaketit ja -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="6">Microsoft Office -ohjelmistopaketit ja -osat</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227070">
                      <strong>MS11-088</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225739">
                      <strong>MS11-089</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235287">
                      <strong>MS11-091</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232493">
                      <strong>MS11-094</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232696">
                      <strong>MS11-096</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
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
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13f3e884-37bf-4ed2-b3ed-a0e7fb48e44f">Microsoft Publisher 2003 Service Pack 3</a>
                    <br />(KB2553084)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5859014f-afc5-4958-82ea-6ba45a5ad4b3">Microsoft Excel 2003 Service Pack 3</a>
                    <br />(KB2596954)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2007 Service Pack 2 ja Microsoft Office 2007 Service Pack 3</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e924cd85-5764-4056-bd32-b0e57dc25146">Microsoft Office 2007 Service Pack 2 ja Microsoft Office 2007 Service Pack 3</a>
                    <br />(KB2596785)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2856821e-f1fd-424b-b03c-e443685eea6d">Microsoft Publisher 2007 Service Pack 2 ja Microsoft Publisher 2007 Service Pack 3</a>
                    <br />(KB2596705)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0c3156c-c87c-4d3e-aca2-3fab9ff78711">Microsoft PowerPoint 2007 Service Pack 2</a>
                    <br />(KB2596764)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office 2010 ja Microsoft Office 2010 Service Pack 1 (32-bittiset versiot)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d812621e-c35a-4cb0-ba26-928363f3422d">Microsoft Pinyin IME 2010 (32-bittinen versio)</a>
                    <br />(KB2596511)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e47c0694-a9a5-4dd7-bfba-e470d9855c28">Microsoft Office 2010 ja Microsoft Office 2010 Service Pack 1 (32-bittiset versiot)</a>
                    <br />(KB2589320)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd32d083-46e7-4835-ba83-c33332b920bd">Microsoft PowerPoint 2010 (32-bittiset versiot)</a>
                    <br />(KB2553185)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2010 ja Microsoft Office 2010 Service Pack 1 (64-bittiset versiot)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8d3ac17-5aca-4da3-961f-b753be4a3634">Microsoft Pinyin IME 2010 (64-bittinen versio)</a>
                    <br />(KB2596511)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c2d5273-eef9-4ff6-be6f-8d86f417f004">Microsoft Office 2010 ja Microsoft Office 2010 Service Pack 1 (64-bittiset versiot)</a>
                    <br />(KB2589320)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f28b8cf6-8946-448a-ae4e-d11f8a76a679">Microsoft PowerPoint 2010 (64-bittiset versiot)</a>
                    <br />(KB2553185)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="6">Microsoft Office for Mac</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227070">
                      <strong>MS11-088</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225739">
                      <strong>MS11-089</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235287">
                      <strong>MS11-091</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232493">
                      <strong>MS11-094</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232696">
                      <strong>MS11-096</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokitus </strong>
                    <strong>kooste</strong>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2004 for Mac</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef3b559c-0bd2-45dd-8049-6946f6431a2a">Microsoft Office 2004 for Mac</a>
                    <br />(KB2644358) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 for Mac</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c4d0381-f7ab-49ed-a0c0-b381387d1e68">Microsoft Office 2008 for Mac</a>
                    <br />(KB2644354)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office for Mac 2011</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c8017d6-232c-42a6-a133-96efe3ad3385">Microsoft Office for Mac 2011</a>
                    <br />(KB2644347)<br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="6">Muu Microsoft Office -ohjelmisto</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227070">
                      <strong>MS11-088</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225739">
                      <strong>MS11-089</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235287">
                      <strong>MS11-091</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232493">
                      <strong>MS11-094</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232696">
                      <strong>MS11-096</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Microsoft PowerPoint Viewer 2007 Service Pack 2</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4417592a-8db0-4e35-9895-d589bc341077">Microsoft PowerPoint Viewer 2007 Service Pack 2</a>
                    <br />(KB2596912)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e799f654-7e2d-40c7-a3b8-32e44d1aa6ee">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2</a>
                    <br />(KB2596843)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Pinyin SimpleFast Style 2010 ja Microsoft Office Pinyin New Experience Style 2010 (32-bittinen versio)</td><td>Microsoft Office Pinyin SimpleFast Style 2010 ja Microsoft Office Pinyin New Experience Style 2010 (32-bittinen versio)[1]<br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office Pinyin SimpleFast Style 2010 ja Microsoft Office Pinyin New Experience Style 2010 (64-bittinen versio)</td><td>Microsoft Office Pinyin SimpleFast Style 2010 ja Microsoft Office Pinyin New Experience Style 2010 (64-bittinen versio)[1]<br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              </table>


**Huomautus: MS11-088**

\[1\]Tätä Microsoft Office Pinyin -versiota ei enää tueta.

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)- ja [Windows Update -sivustoista.](http://go.microsoft.com/fwlink/?linkid=21130) Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Microsoft Office for Mac -käyttäjät: Microsoft AutoUpdate for Mac helpottaa Microsoft-ohjelmiston pitämistä ajan tasalla. Lisätietoja Microsoft AutoUpdate for Macin käyttämisestä on [ohjelmistopäivitysten automaattista tarkistamista](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) käsittelevällä sivulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut ohjeita tietoturvapäivitysten tunnistamiseen ja käyttöönottamiseen. Ohjeisiin sisältyy suosituksia ja tietoja, joiden avulla IT-ammattilaiset oppivat tunnistamaan ja ottamaan käyttöön tietoturvapäivityksiä erilaisilla työkaluilla. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Microsoft Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Microsoft Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx) -sivustossa.

**SystemCenter Configuration Manager 2007**

Configuration Manager 2007:n ohjelmistopäivitysten hallinta yksinkertaistaa päivitysten toimittamista yrityksen eri IT-järjestelmiin sekä niiden hallintaa. Configuration Manager 2007 auttaa järjestelmänvalvojia toimittamaan Microsoft-tuotteiden päivitykset niin työasemiin, kannettaviin, palvelimiin kuin mobiililaitteisiinkin.

Configuration Manager 2007:n automatisoitu haavoittuvuuksien arviointi havaitsee päivitystarpeet ja tekee raportin suositeltavista toimista. Configuration Manager 2007:n ohjelmistopäivitysten hallinta perustuu Microsoftin WSUS (Windows Software Update Services) -palveluihin, ja eri puolilla maailmaa toimivat järjestelmänvalvojat tuntevat tämän aikatestatun päivitysinfrastruktuurin. Lisätietoja tavoista, joilla järjestelmänvalvojat voivat ottaa päivityksiä käyttöön Configuration Manager 2007:n avulla, on [ohjelmistopäivitysten hallintaa](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) käsittelevässä sivustossa. Lisätietoja Configuration Managerissa on sivustossa [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän.

**Huomautus** System Management Server 2003:n yleinen tuki päättyi 12.1.2010. Lisätietoja tuotteiden elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) -sivustossa. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso myös edellä oleva kohta **System Center Configuration Manager 2007**.

Lisätietoja tavoista, joilla järjestelmänvalvojat voivat ottaa päivityksiä käyttöön SMS 2003:n avulla, on artikkelissa [Microsoft Systems Management Server 2003:n skenaarioita ja menetelmiä: ohjelmistojen jakaminen ja korjauspäivitysten hallinta](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (englanninkielinen). Lisätietoja SMS:stä on [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx) -sivustossa.

**Huomautus** SMS hyödyntää Microsoft Baseline Security Analyzer -työkalua tietoturvapäivityksien kattavaan tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat asentaa nämä päivitykset käyttämällä Elevated Rights Deployment Tool -työkalua (sisältyy [Application Compatibility ToolkitiinSMS 2003 Administration Feature Packiin](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

**Update Compatibility Evaluator ja sovellusten yhteensopivuustyökalu**

Päivitykset usein kirjoittavat samoihin tiedostoihin ja rekisteriasetuksiin, joita tarvitaan sovelluksia käytettäessä. Tämä voi aiheuttaa yhteensopivuusongelmia ja pidentää aikaa, joka kuluu tietoturvapäivitysten käyttöönottamiseen. Voit tehostaa Windows-päivitysten testaamista ja tarkistamista asennetuissa sovelluksissa käyttämällä [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) -osia, jotka sisältyvät [Application Compatibility Toolkitiin.](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)

Sovellusten yhteensopivuustyökalu sisältää työkalut ja ohjeistuksen, joilla voi arvioida ja lieventää sovellusten yhteensopivuusongelmia ennen Microsoft Windows Vistan, Windowsin päivityksen, Microsoftin tietoturvapäivitysten tai Windows Internet Explorerin uuden versioon käyttöönottoa ympäristössäsi.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa: Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tietoja Windows Update- ja Microsoft Update -sivustoissa julkaistavista päivityksistä, jotka eivät ole tietoturvapäivityksiä:

  - [Microsoft Knowledge Base -artikkeli 894199](http://support.microsoft.com/kb/894199): Kuvaus Software Update Services- ja Windows Server Update Services -sisällön muutoksista. Sisältää kaiken Windows-sisällön.
  - [Windows Server Update Services -palvelun aiemmin toimittamat päivitykset](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (englanninkielinen). Näyttää kaikki uudet, muokatut ja uudelleenulkaistut Microsoft-tuotteiden päivitykset Microsoft Windowsia lukuun ottamatta.

#### Microsoft Active Protections Program (MAPP)

Microsoft haluaa parantaa asiakkaittensa tietoturvasuojauksia tarjoamalla haavoittuvuustietoja suurille tietoturvaohjelmistojen valmistajille ennen joka kuukausi julkaistavan tietoturvapäivityksen julkaisemista. Tietoturvaohjelmistojen valmistajat voivat sitten päivittää näiden haavoittuvuustietojen perusteella asiakkailleen tarjoamiaan tietoturvaohjelmistoja tai laitteita. Tällaisia ovat esimerkiksi viruksentorjunta, verkkopohjaiset tunkeutumisen havaintojärjestelmät ja isäntäpohjaiset tunkeutumisenestojärjestelmät. Voit selvittää, mitä aktiivisia suojauksia tietoturvaohjelmistojen toimittajilla on tarjolla tutustumalla ohjelman kumppanien ylläpitämiin aktiivisen suojauksen sivustoihin. Nämä kumppanit ovat [MAPP (Microsoft Active Protections Program) -kumppaneita](http://go.microsoft.com/fwlink/?linkid=215201).

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

  - Symantec ja Laboratory of Cryptography and System Security (CrySyS) tekivät yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS11-087
  - Yang Yanbei ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-088
  - Nikita Tarakanov (CISS Research Team) ja Alexey Sintsov (Digital Security Research Group) yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-089
  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-090
  - Will Dormann ([CERT/CC](http://www.cert.org/)) ilmoitti kolmesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS11-091
  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-092
  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-093
  - Greg MacManus ([iSIGHT Partners Labs](http://www.isightpartners.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-094
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-094
  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-096
  - Alex Ionescu (Winsider Seminars & Solutions Inc.) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-097
  - Matthew Jurczyk (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-098
  - Thomas Stehle ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-099
  - Andy Cooper ([Citrix Security Team](http://www.citrix.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-099
  - [Robert Swiecki](http://www.swiecki.net/) ([Google Inc.](http://www.google.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-099
  - [Yosuke Hasegawa](http://utf-8.jp/) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS11-099
  - [Jan Schejbal](http://janschejbal.wordpress.com/) teki yhteistyötä kanssamme kehittääkseen tietoturvaa koskevia muutoksia liittyen haavoittuvuuteen, joka on kuvattu tietoturvatiedotteessa MS11-099
  - Irene Abezgauz ([Seeker](http://www.seekersec.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-100
  - Kestutis Gudinavicius ([SEC Consult](https://www.sec-consult.com/)) ilmoitti haavoittuvudesta, joka on kuvattu tietoturvatiedotteessa MS11-100
  - Oliver Dewdney ([LBi](http://www.lbi.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-100

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [tietoturvapalvelu](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY (1-866-727-2338). Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia. Lisätietoja saatavissa olevista tukivaihtoehdoista on [Microsoftin Ohjeessa ja tuessa](http://support.microsoft.com/).
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - Versio 1.0 (13.12.2011): Tietoturvatiedotteen yhteenveto julkaistu.
  - Versio 1.1 (13.12.2011): Tiedotteessa MS11-099 korjattiin luokitustiedot ohjelmistoille, joita haavoittuvuus koskee. Tiedotteessa MS11-088 korjattiin hyödyntämisindeksin huomautukset. Muutokset on tarkoitettu vain tiedonannoiksi. Tietoturvapäivityksen tiedostoja tai tunnistustietoja ei muutettu.
  - Versio 2.0 (29.12.2011): Lisätty Microsoftin tietoturvatiedote MS11-100: .NET Frameworkin heikkoudet voi sallia käyttöoikeuksien laajentamisen (2638420) Lisäksi on lisätty tämän erillisen tietoturvatiedotteen webcast-linkki.
  - Versio 2.1 (22.2.2012): Tiedotteessa MS11-088 tarkennettiin Microsoft Office Pinyin SimpleFast Style 2010- ja Microsoft Office Pinyin New Experience Style 2010 -versioiden tuotetukitietoja. Näitä Microsoft Office Pinyin -versioita ei enää tueta. Lisätietoja on tietoturvatiedotteessa.

*Built at 2014-04-18T01:50:00Z-07:00*

