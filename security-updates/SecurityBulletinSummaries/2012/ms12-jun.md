---
title: Microsoftin tietoturvatiedotteiden yhteenveto, kesäkuu 2012
TOCTitle: MS12-JUN
ms:assetid: ms12-jun
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms12-jun(v=Security.10)
ms:contentKeyID: 61225744
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin tietoturvatiedotteiden yhteenveto, kesäkuu 2012

Julkaistu: 12. kesäkuuta 2012

**Versio:** 1.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo kesäkuussa 2012 julkaistuista tietoturvatiedotteista.

Tämä tietoturvatiedotteiden yhteenveto korvaa kesäkuun 2012 tietoturvatiedotteiden julkaisun yhteydessä tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 7. kesäkuuta 2012. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 13. kesäkuuta 2012, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt kesäkuun tietoturvatiedotteen web-lähetykseen.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499671) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://go.microsoft.com/fwlink/?linkid=217214) kertovassa englanninkielisessä sivustossa.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=246927"><strong>MS12-036</strong></a></td>
<td><strong>Etätyöpöytäasiakkaan haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2685939)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan RDP-etäkäyttöprotokollan haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä lähettää sarjan tietyllä tavalla muodostettuja RDP-paketteja haavoittuvuuden sisältävään järjestelmään. RDP-etäkäyttöprotokollaa ei ole oletusarvoisesti otettu käyttöön missään käyttöjärjestelmässä. Haavoittuvuus ei koske järjestelmiä, joissa ei käytetä RDP-protokollaa.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (2699988)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yhden yleisessä tiedossa olevan haavoittuvuuden ja kaksitoista yksityishenkilön ilmoittamaa Internet Explorerin haavoittuvuutta. Vakavimmat haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun sivun Internet Explorerissa. Jotakin näistä haavoittuvuuksista onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin nykyinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251095"><strong>MS12-038</strong></a></td>
<td><strong>.NET Frameworkin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2706726)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows .NET Frameworkin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä asiakasjärjestelmässä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua selaimella, jossa voidaan suorittaa XAML-selainsovelluksia (XBAP) Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Myös Windows .NET -sovellukset voivat käyttää tätä haavoittuvuutta koodin käyttöoikeusrajoitusten ohittamiseen. Verkkohyökkäyksessä hyökkääjä saattaa isännöidä sivustoa, jossa on tämän haavoittuvuuden hyödyntämistä varten suunniteltu sivusto. Lisäksi sivustot, jotka ovat vaarantuneet ja jotka hyväksyvät tai isännöivät käyttäjien toimittamaa materiaalia, voivat sisältää tätä haavoittuvuutta hyödyntävää, tietyllä tavalla muodostettua sisältöä. Joka tapauksessa hyökkääjä ei voisi millään tavoin pakottaa käyttäjiä siirtymään näille verkkosivuille. Hyökkääjä voi kuitenkin onnistua saamaan käyttäjän avaaman sivuston. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä olevaa linkkiä tai pikaviestinviestiä, joka avaa hyökkääjän sivuston.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td><strong>Lyncin</strong> <strong>haavoittuvuudet</strong> <strong>saattavat sallia koodin suorittamisen verkon välityksellä (2707956)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yhden yleisessä tiedossa olevan haavoittuvuuden ja kolme yksityishenkilön ilmoittamaa Microsoft Lyncin haavoittuvuutta. Vakavimmat haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä on tarkastellut jaettua sisältöä, joka on hahmonnettu tietyllä tavalla muodostetulla TrueType-fontilla.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Lync</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251612"><strong>MS12-040</strong></a></td>
<td><strong>Microsoft Dynamics AX Enterprise Portalin haavoittuvuus voi sallia käyttöoikeuksien laajentamisen (2709100)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Dynamics AX Enterprise Portalin haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen, jos käyttäjä napsauttaa erityisesti muodostettua URL-osoitetta tai siirtyy tietyllä tavalla muodostettuun sivustoon. Sähköpostihyökkäysskenaariossa hyökkääjä voi hyödyntää tätä haavoittuvuutta lähettämällä kohdistetun Microsoft Dynamics AX Enterprise Portalin käyttäjälle sähköpostiviestin, jossa on tietyllä tavalla muodostettu URL-osoite, ja vakuuttamalla käyttäjän napsauttamaan tietyllä tavalla luotua URL-osoitetta. Haavoittuvuus on lievempi Internet Explorer 8:n ja Internet Explorer 9:n käyttäjille, jotka siirtyvät selaimella Microsoft Dynamics AX Enterprise Portal -sivustoon Internet-vyöhykkeellä. Internet Explorer 8:n ja Internet Explorer 9:n XSS-suodatin auttaa estämään hyökkäyksiä Internet-vyöhykkeellä. Internet Explorer 8:n ja Internet Explorer 9:n XSS-suodatinta ei ole oletusarvoisesti otettu käyttöön Intranet-vyöhykkeellä.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Dynamics AX</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td><strong>Windows-ytimen ohjaimien haavoittuvuus voi sallia käyttöoikeuksien korottamisen (2709162)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa viisi yksityishenkilön ilmoittamaa Microsoft Windowsin haavoittuvuutta. Haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen, jos hyökkääjä kirjautuu järjestelmään ja suorittaa tietyllä tavalla muodostetun sovelluksen. Hyökkääjällä on oltava voimassaolevat kirjautumistiedot ja hyökkääjän on pystyttävä kirjautumaan paikallisesti, jotta haavoittuvuuksia voi hyödyntää.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252515"><strong>MS12-042</strong></a></td>
<td><strong>Windows-ytimen haavoittuvuus voi sallia käyttöoikeuksien korottamisen (2711167)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yhden yksityishenkilön ilmoittaman ja yhden yleisesti tiedossa olevan Microsoft Windowsin haavoittuvuuden. Haavoittuvuudet saattavat sallia käyttöoikeuksien korottamisen, jos hyökkääjä kirjautuu järjestelmään, jota haavoittuvuus koskee, ja suorittaa tietyllä tavalla muodostetun sovelluksen, joka hyödyntää haavoittuvuutta. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja pystyttävä kirjautumaan paikallisesti, jotta hän pystyy hyödyntämään tätä haavoittuvuutta. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
</tbody>
</table>


## Hyödyntämisindeksi

Seuraavassa taulukossa on kunkin tässä kuussa käsitellyn haavoittuvuuden hyödyntämisluokitus. Haavoittuvuudet on järjestetty ensin tiedotteen tunnuksen ja sitten CVE-tunnuksen mukaan. Taulukossa on vain haavoittuvuudet, jotka on luokiteltu tiedotteissa kriittisiksi tai tärkeiksi.

**Miten taulukkoa käytetään?**

Tämän taulukon avulla saat selville, kuinka todennäköistä on sellaisen hyväksikäyttökoodin tai palveluneston julkaiseminen 30 päivän kuluessa tietoturvatiedotteen julkaisemisesta, joka koskee tietoturvapäivitystä, joka sinun on ehkä asennettava. Tutustu järjestelmän määritysten perusteella kuhunkin arviointiin. Tällä tavoin voit ottaa päivitykset käyttöön tärkeysjärjestyksessä. Lisätietoja näistä luokituksista ja niiden määrittämisestä on [Microsoftin hyödyntämisindeksissä](http://technet.microsoft.com/security/cc998259.aspx).

Alla olevissa sarakkeissa "Uusin ohjelmistoversio" viittaa uusimpaan ohjelmistoversioon ja "Aiemmat ohjelmistoversiot" viittaa vanhempiin tuettuihin ohjelmistoversioihin tietoturvatiedotteen taulukoissa "Ohjelmistot, joita haavoittuvuus koskee" ja "Ohjelmistot, joita haavoittuvuus ei koske".

<table>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=246927"><strong>MS12-036</strong></a></td>
<td>RDP-etäkäyttöprotokollan haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0173">CVE-2012-0173</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Center-elementin koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1523">CVE-2012-1523</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>HTML-siivoamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858">CVE-2012-1858</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä on tietojen paljastumisen muille käyttäjille aiheuttava haavoittuvuus. Myös tietoturvatiedotteessa <a href="http://go.microsoft.com/fwlink/?linkid=252488">MS12-039</a> käsitellään tätä haavoittuvuutta.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Null Byte -tietojen julkistamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1873">CVE-2012-1873</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä on tietojen paljastumisen muille käyttäjille aiheuttava haavoittuvuus.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Kehitystyökalurivin koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1874">CVE-2012-1874</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Saman ID-ominaisuuden koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1875">CVE-2012-1875</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>Microsoft on saanut ilmoituksia rajoitetuista hyökkäyksistä, jotka yrittävät hyödyntää tätä haavoittuvuutta.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Col-elementin koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1876">CVE-2012-1876</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Title-elementin koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1877">CVE-2012-1877</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>OnBeforeDeactivate-käsittelijän koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1878">CVE-2012-1878</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>insertAdjacentText-käsittelijän koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1879">CVE-2012-1879</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>insertRow-käsittelijän koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1880">CVE-2012-1880</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>OnRowsInserted-käsittelijän koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1881">CVE-2012-1881</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251095"><strong>MS12-038</strong></a></td>
<td>.NET Frameworkin muistin käytön salliva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1855">CVE-2012-1855</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Haavoittuvuus TrueType-fontin jäsennyksessä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402">CVE-2011-3402</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei koske</td>
<td>Pysyvä</td>
<td>Tämä haavoittuvuus on ollut yleisessä tiedossa.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Haavoittuvuus TrueType-fontin jäsennyksessä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0159">CVE-2012-0159</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei koske</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Suojaamattomaan Lync-kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1849">CVE-2012-1849</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei koske</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>HTML-siivoamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858">CVE-2012-1858</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä on tietojen paljastumisen muille käyttäjille aiheuttava haavoittuvuus. Myös tietoturvatiedotteessa <a href="http://go.microsoft.com/fwlink/?linkid=249045">MS12-037</a> käsitellään tätä haavoittuvuutta.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251612"><strong>MS12-040</strong></a></td>
<td>Dynamics AX Enterprise Portalin XSS-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1857">CVE-2012-1857</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei koske</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Atom-merkkijonon luokkanimen käsittelyn haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1864">CVE-2012-1864</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Atom-merkkijonon luokkanimen käsittelyn haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1865">CVE-2012-1865</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Leikepöytämuodon Atom-nimen käsittelyn haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1866">CVE-2012-1866</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Fonttiresurssin Refcount-kokonaisluvun jäsennyksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1867">CVE-2012-1867</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Win32k.sys-kilpailutilanteen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1868">CVE-2012-1868</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252515"><strong>MS12-042</strong></a></td>
<td>UMS-muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0217">CVE-2012-0217</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei koske</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252515"><strong>MS12-042</strong></a></td>
<td>BIOS ROM -muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1515">CVE-2012-1515</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>Tämä haavoittuvuus on ollut yleisessä tiedossa.</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

Seuraavissa taulukoissa tiedotteet on järjestetty pääohjelmistoluokkien ja vakavuuden mukaan.

**Taulukoiden käyttö**

Näiden taulukoiden avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja koskeeko jokin tietoturvapäivitys niiden asennusta. Jos ohjelma tai osa on luettelossa, saatavana olevaan ohjelmistopäivitykseen on linkki. Myös ohjelmistopäivityksen luokitus mainitaan.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää useiden tietoturvapäivitysten asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

#### Windows-käyttöjärjestelmä ja osat

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="6">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
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
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd2216eb-283b-4a23-b259-018a7fa5fe47">Windows XP Service Pack 3</a>
                    <br />(KB2685939) <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f222e05-2a8d-4099-851f-2044811f7425">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=07c75ac6-f92a-4204-aa58-bdf8c033df9e">Internet Explorer 7</a><br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5bc1656f-cf1d-4f77-a078-a8602401b8e1">Internet Explorer 8</a><br />(KB2699988)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a399bd47-ffe1-4476-932c-9c119496222a">Windows XP Service Pack 3</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0efff733-4c8d-4fce-8de3-28465c6b762b">Windows XP Service Pack 3</a>
                    <br />(KB2707511) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e354955-32ae-447c-b16f-960acc01773b">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2685939) <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57e8bf9d-97c3-4166-a5d4-6b0c99afc6a1">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b35e90b-145d-44c2-a8bc-4f9108d46fa1">Internet Explorer 7</a><br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a386b16-74f7-4d36-93d0-75e7da9bf9b5">Internet Explorer 8</a><br />(KB2699988)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bdb356db-bd36-4159-8e64-ecdb3dfc61bf">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="6">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                      <strong>Keskitaso</strong>
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
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e856fec-9f05-49b7-91b6-11c2636a2f1d">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1dcc826-7e96-464b-830e-39946e7802aa">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=de828031-1ace-43df-80f2-db7d503fb0a2">Internet Explorer 7</a><br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e6e5589-b767-4e8a-b8b3-df7b97e002e5">Internet Explorer 8</a><br />(KB2699988)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0b39b00-d7db-4008-8310-1258e84a72a2">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=855611a1-91ad-4d22-8c1c-fdcd6af4cef0">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2707511) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b63fa4d-b42e-43ca-9f2c-cf60c37731a5">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b060e03b-e63e-446b-9cfd-ea4e1e9383a6">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a36f7ffe-d537-4f9e-b676-22a24f50c089">Internet Explorer 7</a><br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1acb2f0-63ba-4524-94cf-42b3534e21e7">Internet Explorer 8</a><br />(KB2699988)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kriittinen) <br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed7359ce-13e8-42b2-956d-e8be534583aa">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7dfdc5dc-54b0-49e3-bf5a-bbc40b0f159f">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=893667c4-ef9f-48d3-ab18-a0df51bd3dcc">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30a9d518-8067-44f4-90fd-09fec8a0c883">Internet Explorer 7</a><br />(KB2699988)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2317c8d9-cae8-497b-952e-78eb4a6d585c">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="6">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
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
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f55b62bf-0571-4888-9061-3f7cc75d7f17">Windows Vista Service Pack 2</a>
                    <br />(KB2685939) <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16f4404e-e6d6-4bde-af15-3bb692412213">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=610e753a-21db-43e6-bc42-3e1227fa4bb1">Internet Explorer 8</a><br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=828fdb71-747b-481d-9683-895325331478">Internet Explorer 9</a><br />(KB2699988)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9188f1eb-b568-4a99-9b39-745c760a693d">Windows Vista Service Pack 2</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab06290c-4f57-4349-8abd-a382b9044631">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2685939) <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=993c5bc4-8903-4c8c-bbc9-da2e47d959f9">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87100a7e-7feb-4a18-b7aa-04fdd2d6ef52">Internet Explorer 8</a><br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b551d67-e0f1-498a-ac4f-06376a0fcf18">Internet Explorer 9</a><br />(KB2699988)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b94ae42-2882-444c-ad5e-74e34b805006">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="6">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812">Windows Server 2008 for 32-bit Systems Service Pack 2</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7f9ad40-d515-4224-90ff-4bd4bff9180f">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4eaeff8-7b7a-4418-a479-09b2146df2bf">Internet Explorer 8</a><br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a20c839c-ce3b-46a5-becb-588de404878d">Internet Explorer 9</a><br />(KB2699988)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745">Windows Server 2008 for 32-bit Systems Service Pack 2</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5">Windows Server 2008 for x64-based Systems Service Pack 2</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7420c9f3-8f7e-4823-aaba-b14b957408d8">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd5308b7-7430-4713-922c-f06c46886fad">Internet Explorer 8</a><br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a737d87-0689-470b-8fc0-8c874af18794">Internet Explorer 9</a><br />(KB2699988)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2">Windows Server 2008 for x64-based Systems Service Pack 2</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4b8af1c-b483-4aed-9be5-b0f1698b2c28">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=472842c4-5fe7-4d4c-a927-05be030b5b4e">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=098607b3-9424-4440-8832-fc1de010977e">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="6">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                  </td></tr>
                <tr><td>Windows 7 for 32-bit Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef">Windows 7 for 32-bit Systems</a>
                    <br />(KB2685939) <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620">Internet Explorer 9</a><br />(KB2699988)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7">Windows 7 for 32-bit Systems</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows 7 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef">Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620">Internet Explorer 9</a><br />(KB2699988)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7">Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows 7 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07">Windows 7 for x64-based Systems</a>
                    <br />(KB2685939) <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503">Internet Explorer 9</a><br />(KB2699988)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c">Windows 7 for x64-based Systems</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb">Windows 7 for x64-based Systems</a>
                    <br />(KB2709715) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07">Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503">Internet Explorer 9</a><br />(KB2699988)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c">Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb">Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2709715) <br />(Tärkeä) </td></tr>
              
                <tr><th colspan="6">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                      <strong>Keskitaso</strong>
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
                <tr><td>Windows Server 2008 R2 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9464b044-e40b-4300-97b8-dc3a13c85929">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf">Internet Explorer 9</a><br />(KB2699988)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2709715) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9464b044-e40b-4300-97b8-dc3a13c85929">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf">Internet Explorer 9</a><br />(KB2699988)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2709715) <br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2008 R2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc">Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c">Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="6">Server Core -asennusvalinta</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812">Windows Server 2008 for 32-bit Systems Service Pack 2</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745">Windows Server 2008 for 32-bit Systems Service Pack 2</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5">Windows Server 2008 for x64-based Systems Service Pack 2</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2">Windows Server 2008 for x64-based Systems Service Pack 2</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2709715) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2685939) <br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2709162) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2709715) <br />(Tärkeä)</td></tr>
              </table>


**Huomautus** **:** **MS12-0** **3** **8**

\[1\] **Koskee .NET Framework 4:ää ja .NET Framework 4 Client Profilea.** .NET Framework version 4 jakelutiedostopaketeista on kaksi versiota: .NET Framework 4 and .NET Framework 4 Client Profile. .NET Framework 4 Client Profile on .NET Framework 4:n osajoukko. Haavoittuvuus, jonka tämä tietoturvapäivitys korjaa, koskee sekä .NET Framework 4:ää että .NET Framework 4 Client Profilea. Lisätietoja on MSDN-artikkelissa, jossa käsitellään [.NET Frameworkin asentamista](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Communications -alustat ja -ohjelmistot

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Communicator</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252488">
                      <strong>MS12-039</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Communicator 2007 R2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75eea324-689a-4892-bdd9-03ef399c4cba">Microsoft Communicator 2007 R2</a>
                    <br />(KB2708980)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="2">Microsoft Lync</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252488">
                      <strong>MS12-039</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Lync 2010 (32-bittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=425406ea-28b9-46f7-8c49-0c7ea46f16e3">Microsoft Lync 2010 (32-bittinen)</a>
                    <br />(KB2693282)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Lync 2010 (64-bittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06e5285f-1947-4409-b608-e0a145fadba4">Microsoft Lync 2010 (64-bittinen)</a>
                    <br />(KB2693282)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Lync 2010 Attendee</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c40f0d38-af90-4966-a0f0-346fa48683d0">Microsoft Lync 2010 Attendee</a>
                    <br />(järjestelmänvalvojatason asennus)<br />(KB2696031)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad864c0e-5850-44a3-b74f-5980a998a384">Microsoft Lync 2010 Attendee</a>[1]<br />(käyttäjätason asennus)<br />(KB2693283)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Lync 2010 Attendant (32-bittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe7ad0f9-ee84-4cda-b252-a8d31ead5053">Microsoft Lync 2010 Attendant (32-bittinen)</a>
                    <br />(KB2702444)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Lync 2010 Attendant (64-bittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe7ad0f9-ee84-4cda-b252-a8d31ead5053">Microsoft Lync 2010 Attendant (64-bittinen)</a>
                    <br />(KB2702444)<br />(Tärkeä)</td></tr>
              </table>


**Huomautus: MS12-0** **39**

\[1\] Päivitys on saatavana vain Microsoft Download Centeristä.

#### Microsoft Enterprise Resource Planning (ERP) -ratkaisut

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Dynamics ERP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251612">
                      <strong>MS12-040</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Dynamics AX 2012 </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45df362d-8fed-4d99-91c1-81c61878300a">Microsoft Dynamics AX 2012 Enterprise Portal</a>
                    [1]
                    <br />(KB2706738) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=780ddcef-19da-44c4-beca-d10b652cd22a">Microsoft Dynamics AX 2012 Enterprise Portal</a>[1]<br />(KB2710639) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41dc5958-c224-40f9-89c2-179607a8ee2a">Microsoft Dynamics AX 2012 Enterprise Portal</a>[1]<br />(KB2711239) <br />(Tärkeä)</td></tr>
              </table>


**Huomautus: MS12-040**

\[1\]Päivitys on saatavana vain Microsoft Download Centeristä sekä Microsoft Dynamics CustomerSource- ja Microsoft Dynamics Partner Source -verkkosivustoista.

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

**System** **Center Configuration Manager**

System Center Configuration Managerin ohjelmistopäivitysten hallinta yksinkertaistaa päivitysten toimittamista yrityksen eri IT-järjestelmiin sekä niiden hallintaa. System Center Configuration Manager auttaa järjestelmänvalvojia toimittamaan Microsoft-tuotteiden päivitykset työasemiin, kannettaviin, palvelimiin ja mobiililaitteisiin.

System Center Configuration Managerin automatisoitu haavoittuvuuksien arviointi havaitsee päivitystarpeet ja tekee raportin suositeltavista toimista. System Center Configuration Managerin ohjelmistopäivitysten hallinta perustuu Microsoftin WSUS (Windows Software Update Services) -palveluihin, ja eri puolilla maailmaa toimivat järjestelmänvalvojat tuntevat tämän aikatestatun päivitysinfrastruktuurin. Lisätietoja tavoista, joilla järjestelmänvalvojat voivat ottaa päivityksiä käyttöön System Center Configuration Managerin avulla, on [ohjelmistopäivitysten hallintaa](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) käsittelevässä sivustossa. Lisätietoja System Center Configuration Managerissa on sivustossa [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän.

**Huomautus** System Management Server 2003:n yleinen tuki päättyi 12.1.2010. Lisätietoja tuotteiden elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) -sivustossa. System Management Serverin seuraava versio, eli System Center Configuration Manager, on nyt saatavana. Katso myös edellä oleva kohta **System Center Configuration Manager**.

Lisätietoja tavoista, joilla järjestelmänvalvojat voivat ottaa päivityksiä käyttöön SMS 2003:n avulla, on artikkelissa [Microsoft Systems Management Server 2003:n skenaarioita ja menetelmiä: ohjelmistojen jakaminen ja korjauspäivitysten hallinta](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (englanninkielinen). Lisätietoja SMS:stä on [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx) -sivustossa.

**Huomautus** SMS hyödyntää Microsoft Baseline Security Analyzer -työkalua tietoturvapäivityksien kattavaan tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat asentaa nämä päivitykset käyttämällä Elevated Rights Deployment Tool -työkalua (sisältyy [Application Compatibility ToolkitiinSMS 2003 Administration Feature Packiin](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

**Update Compatibility Evaluator ja sovellusten yhteensopivuustyökalu**

Päivitykset usein kirjoittavat samoihin tiedostoihin ja rekisteriasetuksiin, joita tarvitaan sovelluksia käytettäessä. Tämä voi aiheuttaa yhteensopivuusongelmia ja pidentää aikaa, joka kuluu tietoturvapäivitysten käyttöönottamiseen. Voit tehostaa Windows-päivitysten testaamista ja tarkistamista asennetuissa sovelluksissa käyttämällä [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) -osia, jotka sisältyvät [Application Compatibility Toolkitiin.](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)

Sovellusten yhteensopivuustyökalu sisältää työkalut ja ohjeistuksen, joilla voi arvioida ja lieventää sovellusten yhteensopivuusongelmia ennen Windows Vistan, Windowsin päivityksen, Microsoftin tietoturvapäivitysten tai Windows Internet Explorerin uuden versioon käyttöönottoa ympäristössäsi.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa: Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tietoja Windows Update- ja Microsoft Update -sivustoissa julkaistavista päivityksistä, jotka eivät ole tietoturvapäivityksiä:

  - [Microsoft Knowledge Base -artikkeli 894199](http://support.microsoft.com/kb/894199): Kuvaus Software Update Services- ja Windows Server Update Services -sisällön muutoksista. Sisältää kaiken Windows-sisällön.
  - [Windows Server Update Services -palvelun aiemmin toimittamat päivitykset](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (englanninkielinen). Näyttää kaikki uudet, muokatut ja uudelleenjulkaistut Microsoft-tuotteiden päivitykset Microsoft Windowsia lukuun ottamatta.

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

  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Adi Cohen ([IBM Security Systems - Application Security](http://blog.watchfire.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Masato Kinugawa ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Roman Shafigullin (LinkedIn) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Code Audit Labs ([VulnHunt](http://www.vulnhunt.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Dark Son ([VulnHunt](http://www.vulnhunt.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - [Qihoo 360 Security Center](http://www.360.cn/) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Yichong Lin (McAfee Labs) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS12-037
  - [Google Inc.](http://www.google.com/) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS12-037
  - [VUPEN Security](http://www.vupen.com) (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-037
  - Vitali Toropov (yhteistyössä [Tipping Pointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-038
  - hamburgers maccoy (Secunia SVCRP:n kautta) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-039
  - Adi Cohen ([IBM Security Systems - Application Security](http://blog.watchfire.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-039
  - Alin Rad Pop (yhteistyössä [Tipping Pointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-039
  - Finian Mackin ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-040
  - Tarjei Mandt ([Azimuth Security](http://www.azimuthsecurity.com/)) ilmoitti kolmesta haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-041
  - [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org) ([Google Inc.](http://www.google.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-041
  - Rafal Wojtczuk ([Bromium](http://www.bromium.com/)) ja Jan Beulich ([SUSE](http://www.suse.com/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-042

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - IT-ammattilaisten tietoturvaratkaisut: [TechNetin ongelmanratkaisu- ja tukisivusto](http://technet.microsoft.com/security/bb980617,aspx)
  - Suojaa Windows-käyttöjärjestelmäsi viruksilta ja haittaohjelmilta: [Virusten ja tietoturvan ratkaisukeskus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
  - Maakohtaiset tukipalvelut: [Kansainvälinen tukipalvelu](http://support.microsoft.com/common/international.aspx)

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (12.6.2012): Tietoturvatiedotteen yhteenveto julkaistu.

*Built at 2014-04-18T01:50:00Z-07:00*

