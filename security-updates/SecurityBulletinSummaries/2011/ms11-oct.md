---
title: Microsoftin tietoturvatiedotteiden yhteenveto, lokakuu 2011
TOCTitle: MS11-OCT
ms:assetid: ms11-oct
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms11-oct(v=Security.10)
ms:contentKeyID: 61225731
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin tietoturvatiedotteiden yhteenveto, lokakuu 2011

Julkaistu: 11. lokakuuta 2011 | Päivitetty: 26. lokakuuta 2011

**Versio:** 1.1

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo lokakuussa 2011 julkaistuista tietoturvatiedotteista.

Tämä tietoturvatiedotteiden yhteenveto korvaa lokakuun 2011 tietoturvatiedotteiden julkaisun yhteydessä tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 6. lokakuuta 2011. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 12. lokakuuta 2011, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt lokakuun tietoturvatiedotteen webcast-lähetykseen.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487956) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://go.microsoft.com/fwlink/?linkid=217214) kertovassa englanninkielisessä sivustossa.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=227075">MS11-078</a></td>
<td><strong>.NET Frameworkin ja Microsoft Silverlightin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2604930)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft .NET Frameworkin ja Microsoft Silverlightin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä asiakasjärjestelmässä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua selaimella, jossa voidaan suorittaa XAML-selainsovelluksia (XBAP:t) tai Silverlight-sovelluksia. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä myös palvelinjärjestelmissä, joissa on käynnissä IIS, jos palvelin sallii ASP.NET-sivujen käsittelemisen ja jos hyökkääjä pystyy lataamaan tietyllä tavalla muodostetun ASP.NET-sivun kyseiseen palvelimeen ja suorittamaan sen. Tämä voi olla mahdollista esimerkiksi Web-palvelujen yhteydessä. Myös Windows .NET -sovellukset voivat käyttää tätä haavoittuvuutta koodin käyttöoikeusrajoitusten ohittamiseen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft .NET Framework, Microsoft Silverlight</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (2586448)</strong><br />
<br />
Tämä tietoturvatiedote korjaa kahdeksan yksityishenkilön ilmoittamaa Internet Explorerin haavoittuvuutta. Vakavimmat haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun sivun Internet Explorerissa. Jotakin näistä haavoittuvuuksista onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin paikallinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221538">MS11-075</a></td>
<td><strong>Microsoft Active Accessibilityn haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (2623699)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Active Accessibility -komponentin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä onnistuu saamaan käyttäjän avaamaan oikean tiedoston siinä verkkokansiossa, jossa on myös tietyllä tavalla muodostettu kirjastotiedosto (DLL). Avattaessa oikeaa tiedostoa Microsoft Active Accessibility -komponentti saattaa yrittää ladata DLL-tiedoston ja suorittaa siinä olevan koodin. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja avattava tiedosto tästä sijainnista. Lisäksi sovelluksen, jota haavoittuvuus koskee, on ladattava kyseinen tiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227073">MS11-076</a></td>
<td><strong>Windows Media Centerin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2604926)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Windows Media Centerin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä onnistuu saamaan käyttäjän avaamaan oikean tiedoston siinä verkkokansiossa, jossa on myös tietyllä tavalla muodostettu kirjastotiedosto (DLL). Avattaessa oikeaa tiedostoa Windows Media Center saattaa yrittää ladata DLL-tiedoston ja suorittaa siinä olevan koodin. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja avattava tiedosto tästä sijainnista.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=225915">MS11-077</a></td>
<td><strong>Windowsin ydintilan ohjaimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (2567053)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa neljä yksityishenkilön ilmoittamaa Microsoft Windowsin haavoittuvuutta. Vakavimman haavoittuvuuden hyödyntäminen saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun fonttitiedoston (kuten .fon) jaetussa verkkoresurssissa, UNC- tai WebDAV-resurssissa tai sähköpostin liitetiedostona. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja avattava tietyllä tavalla muodostettu fonttitiedosto tai avattava sähköpostin liitteenä ollut tiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td><strong>Microsoft Forefront Unified Access Gatewayn haavoittuvuudet saattavat aiheuttaa koodin suorittamisen verkon välityksellä (2544641)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa viisi yksityishenkilön ilmoittamaa Forefront Unified Access Gateway (UAG) -haavoittuvuutta. Pahin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä siirtyy erityisesti muodostetun URL-osoitteen avulla haavoittuvuuden sisältävään sivustoon. Hyökkääjä ei kuitenkaan pysty pakottamaan käyttäjää avaamaan tällaista Web-sivustoa. Hyökkääjä voi kuitenkin onnistua saamaan käyttäjän avaaman sivuston. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä olevaa linkkiä tai pikaviestinviestiä, joka avaa hyökkääjän sivuston.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Forefront United Access Gateway</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227486">MS11-080</a></td>
<td><strong>Lisäfunktio-ohjaimen haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (2592799)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin lisäfunktio-ohjaimen haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen, jos hyökkääjä kirjautuu käyttäjän järjestelmään ja suorittaa tietyllä tavalla muodostetun sovelluksen. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja hänen on pystyttävä kirjautumaan paikallisesti, jotta hän pystyy hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=228596">MS11-082</a></td>
<td><strong>Host Integration Serverin haavoittuvuudet saattavat sallia palveluneston (2607670)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi yleisessä tiedossa olevaa Host Integration Serverin haavoittuvuutta. Haavoittuvuudet saattavat sallia palveluneston, jos hyökkääjä lähettää tietyllä tavalla muodostetun paketin Host Integration Serveriin UDP-portin 1478 tai TCP porttien 1477 tai 1478 kautta. Palomuurikäytännöistä ja palomuurin vakiomäärityksistä annetut toimintaohjeet suojaavat verkkoa hyökkäyksiltä, joiden lähde on yritysverkon ulkopuolella. Hyvän käytännön mukaisesti internetiin yhteydessä olevissa järjestelmissä pitäisi olla mahdollisimman vähän portteja alttiina uhille. Tässä tapauksessa Host Integration Server -porttien internet-yhteys pitäisi estää.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Palvelunesto</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Host Integration Server</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=221538">MS11-075</a></td>
<td>Active Accessibility -komponenttien suojaamattoman kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1247">CVE-2011-1247</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227073">MS11-076</a></td>
<td>Media Centerin suojaamattoman kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2009">CVE-2011-2009</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä haavoittuvuus on ollut yleisessä tiedossa.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=225915">MS11-077</a></td>
<td>Win32k:n NULL-osoittimen viittauksen poistamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1985">CVE-2011-1985</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=225915">MS11-077</a></td>
<td>Fonttikirjastotiedoston puskurin ylivuodon haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2003">CVE-2011-2003</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=225915">MS11-077</a></td>
<td>Win32k:n vapautuksen jälkeistä käyttöä koskeva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2011">CVE-2011-2011</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227075">MS11-078</a></td>
<td>.NET Frameworkin luokan periytyvyyden haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1253">CVE-2011-1253</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td>Excel-taulukon XSS-vastauksen kahdentava haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1895">CVE-2011-1895</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Tietojen paljastuminen muille käyttäjille käyttöympäristöissä, joihin on viitattu tietoturvatiedotteessa</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td>Excel-taulukon XSS-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1896">CVE-2011-1896</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Tietojen paljastuminen muille käyttäjille käyttöympäristöissä, joihin on viitattu tietoturvatiedotteessa</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td>Oletettu XSS-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1897">CVE-2011-1897</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Tietojen paljastuminen muille käyttäjille käyttöympäristöissä, joihin on viitattu tietoturvatiedotteessa</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td>Koodin suorittamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1969">CVE-2011-1969</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td>Ei-valtuutetun istunnon evästeen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2012">CVE-2011-2012</a></td>
<td>Ei koske</td>
<td>Ei koske</td>
<td>Pysyvä</td>
<td>Tämä on palveluneston aiheuttava haavoittuvuus</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227486">MS11-080</a></td>
<td>Lisäfunktio-ohjaimen käyttöoikeuksien korottamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2005">CVE-2011-2005</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td>Scroll Event -käsittelijän koodin suorittamisen verkon välityksellä salliva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1993">CVE-2011-1993</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td>OLEAuto32.dll-koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1995">CVE-2011-1995</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td>Option-elementin koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1996">CVE-2011-1996</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td>OnLoad Event -käsittelijän koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1997">CVE-2011-1997</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td>Jscript9.dll-koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1998">CVE-2011-1998</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei koske</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td>Select-elementin koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1999">CVE-2011-1999</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td>Body-elementin koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2000">CVE-2011-2000</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td>Virtuaalisen funktiotaulukon vioittumiseen liittyvä haavoittuvuus, joka sallii koodin suorittamisen verkon välityksellä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2001">CVE-2011-2001</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=228596">MS11-082</a></td>
<td>Päättymättömän loop-lauseen salliva snabase.exen DoS-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2007">CVE-2011-2007</a></td>
<td>Ei koske</td>
<td>Ei koske</td>
<td>Pysyvä</td>
<td>Tämä on palveluneston aiheuttava haavoittuvuus.<br />
<br />
Tämä haavoittuvuus on ollut yleisessä tiedossa.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=228596">MS11-082</a></td>
<td>Varaamattoman muistin käytön salliva DoS-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2008">CVE-2011-2008</a></td>
<td>Ei koske</td>
<td>Ei koske</td>
<td>Pysyvä</td>
<td>Tämä on palveluneston aiheuttava haavoittuvuus.<br />
<br />
Tämä haavoittuvuus on ollut yleisessä tiedossa.</td>
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
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227075">
                      <strong>MS11-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=226382">
                      <strong>MS11-081</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221538">
                      <strong>MS11-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227073">
                      <strong>MS11-076</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225915">
                      <strong>MS11-077</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227486">
                      <strong>MS11-080</strong>
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
                  </td><td>
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
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a54a7ad5-0504-4cc6-9eca-ba9f31c35a17">Microsoft .NET Framework 1.0 Service Pack 3</a>
                    <br />(KB2572066)<br />(vain Media Center Edition 2005 ja Tablet PC Edition 2005)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507">Microsoft .NET Framework 1.1 Service Pack 1</a><br />(KB2572067)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2572073)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=822f91f5-bf92-42c4-ad33-b971be37d772">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e942554d-6cb6-4e48-a876-3470671a95a2">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a911b5b0-5e46-4a37-83e7-595e20585c56">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96af60b9-4b8d-4a9b-b125-10775bb48252">Windows XP Service Pack 3</a>
                    <br />(KB2564958)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9157e677-ab3f-44b0-9735-192bc7421ba7">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1b2dceb-5bef-4522-9001-8dff0545d805">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2572067)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2572073)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6260318c-e579-4cdf-93e3-4608892bc79e">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f04ad852-1418-4fc4-bd57-f47895bbf3a8">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67ebf641-1341-4642-96ba-bab5446d7b5d">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8fcf427-17d0-4caa-b406-50703f980862">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2564958)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f2444ac-61bd-47cf-9c1e-da86a2b0cfb5">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a37864e-8543-4c52-aa73-e3c190860d76">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227075">
                      <strong>MS11-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=226382">
                      <strong>MS11-081</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221538">
                      <strong>MS11-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227073">
                      <strong>MS11-076</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225915">
                      <strong>MS11-077</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227486">
                      <strong>MS11-080</strong>
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
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b968b0bd-577b-4ea2-a192-a80fe7c20791">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2572069)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2572073)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=172c55f3-6249-4ba3-a4a4-677a03262ff3">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ffbdb93-7b92-4197-bb6c-5c305e8072a8">Internet Explorer 7</a><br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14ef20d4-3530-49b2-91b7-d278d9098023">Internet Explorer 8</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09e178f8-2bd2-46e1-b975-4938ee1f304d">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2564958)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3bd62bf6-3400-4c03-95fe-148112b341e8">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29228167-b811-43d7-b4a0-91e385b598a5">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2572067)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2572073)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5a0a8db-34d4-4f0a-ab6b-7b2fb420ab91">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7379b3bf-6af0-43cb-bf8b-505e8563fc84">Internet Explorer 7</a><br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b35c95f5-30b0-43a9-aa6a-6db63cab0dcb">Internet Explorer 8</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b8030db-1f47-4666-8cb5-1c56577f2340">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2564958)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b73f4e87-9655-46d5-beb2-ea245dcd280d">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0816d729-6769-4ca6-a14e-71750eca8d29">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2572067)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2572073)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5825cb4a-47d5-423f-b4c5-2d0fc50856c0">Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11c4878e-df58-4369-b9c0-cb0a230c92dd">Internet Explorer 7</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82653b8c-0e58-440d-9702-8847f599caed">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(KB2605295)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a618cc19-5ebc-462e-a518-d9bfe41ed98e">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=42465652-2664-4fd5-9a22-ae847b08e7c8">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227075">
                      <strong>MS11-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=226382">
                      <strong>MS11-081</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221538">
                      <strong>MS11-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227073">
                      <strong>MS11-076</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225915">
                      <strong>MS11-077</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227486">
                      <strong>MS11-080</strong>
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
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2572067)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2572075)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=630335ac-5a30-46b4-acc1-c4d8bd289668">Internet Explorer 7</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76c8124e-81b9-4a6a-bd53-fbdaf45189aa">Internet Explorer 8</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7de276a3-a20d-49de-82b0-51cb22ad73af">Internet Explorer 9</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96b089c0-a2e7-44cb-9fc4-9569b3993afa">Windows Vista Service Pack 2</a>
                    <br />(KB2564958)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44f7f10b-86ff-470f-996a-d4aa51c4d18f">Windows Vista Service Pack 2</a>
                    <br xmlns="http://www.w3.org/1999/xhtml" />(KB2579686)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60e50f72-4001-423c-831c-8ff1f1b8f090">Windows Media Center TV Pack for Windows Vista (32-bittiset versiot</a>)[1]<br />(KB2579692)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ff53d01b-97b7-40d2-af88-4978f1099a7c">Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2572067)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2572075)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9aabd7a2-0b2f-4c42-a9cf-2ec69ae6b82d">Internet Explorer 7</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3454940c-acc2-4e09-8154-075b4be1b697">Internet Explorer 8</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3df0c31b-344a-4163-93d2-79df1653b339">Internet Explorer 9</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b79a389c-8340-4dd2-9ab1-a0943c5a220f">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2564958)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cbb66cd7-2688-410f-8a03-fd28e6ef5b01">Windows Vista x64 Edition Service Pack 2</a>
                    <br xmlns="http://www.w3.org/1999/xhtml" />(KB2579686)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=371c7dab-5aa6-4502-80ee-ae69b736b972">Windows Media Center TV Pack for Windows Vista (64-bittiset versiot</a>)[1]<br />(KB2579692)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47322e11-f1cf-4f70-b939-8cac9bbfc2bc">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227075">
                      <strong>MS11-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=226382">
                      <strong>MS11-081</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221538">
                      <strong>MS11-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227073">
                      <strong>MS11-076</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225915">
                      <strong>MS11-077</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227486">
                      <strong>MS11-080</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB2572067)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2572075)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>**[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5660e23c-13a3-4275-ac69-38f03f17491a">Internet Explorer 7</a>**<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd144435-1afd-4d6e-a100-fbd613eee409">Internet Explorer 8</a>**<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a7f9855-20ce-4fe0-a903-bd1f145075df">Internet Explorer 9</a>**<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7cd1ecec-8a3f-4cb2-833c-a177c9602ff5">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(KB2564958)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c7498ee-eba4-44fd-8846-0b2e96c96705">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB2572067)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2572075)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>**[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=415b1c59-f3dc-4f4f-b2eb-68692d6efc05">Internet Explorer 7</a>**<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0c4949f-bce0-4255-a5f2-cf5ecf7416da">Internet Explorer 8</a>**<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28a09e42-5865-48b2-af26-ebc8162c3286">Internet Explorer 9</a>**<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=456e450c-3928-4130-8127-e4d3f482c1ca">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(KB2564958)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40386742-f397-402e-8810-63d3d6ba12a6">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2572067)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2572075)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31e68c7f-4db5-463f-a315-92f574af080b">Internet Explorer 7</a>
                    <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e9930d3-ba13-446d-bfa0-60720c48203b">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(KB2564958)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3633402b-96cb-4f36-b137-d07d1baf28c7">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227075">
                      <strong>MS11-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=226382">
                      <strong>MS11-081</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221538">
                      <strong>MS11-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227073">
                      <strong>MS11-076</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225915">
                      <strong>MS11-077</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227486">
                      <strong>MS11-080</strong>
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
                  </td><td>Ei mitään</td></tr>
                <tr><td>Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</td><td>Vain Windows 7 for 32-bit Systems:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2">Microsoft .NET Framework 3.5.1</a><br />(KB2572076)<br />(Kriittinen)<br /><br />Vain Windows 7 for 32-bit Systems Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618">Microsoft .NET Framework 3.5.1</a><br />(KB2572077)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4de175be-bbb7-4912-ba4e-d6fe96606c9e">Internet Explorer 8</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b49876c7-7c65-4b6d-be9a-9f18be23037b">Internet Explorer 9</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=02d28e59-b38f-433a-a568-e86f9d43dd42">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(KB2564958)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76fcf0ec-9062-4090-acb2-401355341a2b">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br xmlns="http://www.w3.org/1999/xhtml" />(KB2579686)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e40bc26-f77f-4b57-9b3d-9d053c19ac56">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</td><td>Vain Windows 7 for x64-based Systems:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2">Microsoft .NET Framework 3.5.1</a><br />(KB2572076)<br />(Kriittinen)<br /><br />Vain Windows 7 for x64-based Systems Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618">Microsoft .NET Framework 3.5.1</a><br />(KB2572077)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16fd238e-6f65-4d38-88ae-2689817588e1">Internet Explorer 8</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cc0773f2-6099-4d55-9971-ee6546369c7f">Internet Explorer 9</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=904dec69-e8b9-4b23-a5ea-d3e7e9b9df07">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2564958)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78c099b7-4bcb-4da7-8967-512c6541c541">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2579686)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=219554e6-eb5a-42d0-90c0-42b4d0772cfd">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227075">
                      <strong>MS11-078</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=226382">
                      <strong>MS11-081</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221538">
                      <strong>MS11-075</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227073">
                      <strong>MS11-076</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225915">
                      <strong>MS11-077</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227486">
                      <strong>MS11-080</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>Vain Windows Server 2008 R2 for x64-based Systems:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2">Microsoft .NET Framework 3.5.1</a>*<br />(KB2572076)<br />(Kriittinen) <br /><br />Vain Windows Server 2008 R2 for x64-based Systems:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 R2 for x64-based Systems Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618">Microsoft .NET Framework 3.5.1</a>*<br />(KB2572077)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 R2 for x64-based Systems Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>*[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8435781e-0f77-41d0-abb9-9b70f5b02d33">Internet Explorer 8</a>**<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=646a9a56-c343-45cb-a255-303602aa5a64">Internet Explorer 9</a>**<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7bd50b7-03f1-4ea4-ad71-d428822c62f8">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(KB2564958)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39bd4cfb-fe61-41b8-a5a2-73a9e720fc72">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>Vain Windows Server 2008 R2 for Itanium-based Systems:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2">Microsoft .NET Framework 3.5.1</a><br />(KB2572076)<br />(Kriittinen)<br /><br />Vain Windows Server 2008 R2 for Itanium-based Systems Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618">Microsoft .NET Framework 3.5.1</a><br />(KB2572077)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a">Microsoft .NET Framework 4</a>[1]<br />(KB2572078)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2676597e-c1d4-4397-8dc4-515ce3d0c5fd">Internet Explorer 8</a>
                    <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa816682-9652-433c-b1b4-5d0bc17b6a87">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(KB2564958)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d35c6d0-6d2d-42bf-a97f-4c5e01b1937e">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              </table>


**Huomautukse** **t** **Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 - tai Windows Server 2008 R2 -versioita, jos se asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Huomautus: MS11-0** **78**

\[1\] **Koskee .NET Framework 4:ää ja .NET Framework 4 Client Profilea.** .NET Framework version 4 jakelutiedostopaketeista on kaksi versiota: .NET Framework 4 and .NET Framework 4 Client Profile. .NET Framework 4 Client Profile on .NET Framework 4:n osajoukko. Haavoittuvuus, jonka tämä tietoturvapäivitys korjaa, koskee sekä .NET Framework 4:ää että .NET Framework 4 Client Profilea. Lisätietoja on MSDN-artikkelissa, jossa käsitellään [.NET Frameworkin asentamista](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

**Huomautus: MS11-076**

\[1\]Windows Media Center TV Pack for Windows Vista on valinnainen lisäosa, joka on saatavilla vain alkuperäisen laitevalmistajien (OEM) järjestelmiin ja Windows Vista Home Premium- ja Windows Vista Ultimate -versioihin. Asiakkaiden, joiden x64-pohjaisiin järjestelmiin on asennettu tämä valinnainen lisäosa, kannattaa asentaa molemmat saatavilla olevat päivitykset. Parhaiden käytäntöjen mukaisesti Microsoft suosittelee käyttöjärjestelmäpäivityksen (KB2579686) asentamista ennen Windows Media Center TV Pack -päivityksen (KB2579692) asentamista. Asiakkaiden, joiden 32-bittisiin järjestelmiin on asennettu Media Center TV Pack, tarvitsee asentaa vain päivitys KB2579692.

#### Microsoft Server -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Host Integration Server</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=228596">
                      <strong>MS11-082</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Host Integration Server 2004</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7536139-63ea-482a-8d1c-0faad1fcfaa4">Microsoft Host Integration Server 2004 Service Pack 1 (palvelin)</a>
                    <br />(KB2578757)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Host Integration Server 2006</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3bc0c89c-56b2-4463-b671-2a58bed9667b">Microsoft Host Integration Server 2006 Service Pack 1 (palvelin)</a>
                    <br />(KB2579597)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Host Integration Server 2009</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28716ed4-f215-4c69-b6b8-63fbeecefc5b">Microsoft Host Integration Server 2009</a>
                    <br />(KB2579598)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Host Integration Server 2010</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbbd67d8-68aa-424d-8eaf-a273a71624d1">Microsoft Host Integration Server 2010</a>
                    <br />(KB2579599)<br />(Tärkeä)</td></tr>
              </table>


#### Microsoft-kehitystyökalut ja ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Silverlight</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227075">
                      <strong>MS11-078</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Silverlight 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8bde4992-bdf7-4345-835a-4e1fbfcd8c5f">Microsoft Silverlight 4</a> asennettuna Macintosh-järjestelmään<br />(KB2617986)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8bde4992-bdf7-4345-835a-4e1fbfcd8c5f">Microsoft Silverlight 4</a> asennettuna tuettuihin Microsoft Windows -asiakkaaseen<br />(KB2617986)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8bde4992-bdf7-4345-835a-4e1fbfcd8c5f">Microsoft Silverlight 4</a> asennettuna Microsoft Windows -palvelimeen**<br />(KB2617986)</td></tr>
              </table>


**Huomautukset** **:** **MS11-07** **8**

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 - tai Windows Server 2008 R2 -versioita, jos se asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

#### Microsoft Remote Access -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Forefront Unified Access Gateway</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217472">
                      <strong>MS11-079</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Forefront Unified Access Gateway</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=770ad8ba-4d9a-404e-9515-6ed1e41682df">Microsoft Forefront Unified Access Gateway 2010</a>
                    [1]
                    <br />(KB2522482)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0de8d20-9c25-41c0-9c02-d263b9ed22fa">Microsoft Forefront Unified Access Gateway 2010 Update 1</a>[1]<br />(KB2522483)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=166bdfcb-5088-4471-9d51-a3071ac13b73">Microsoft Forefront Unified Access Gateway 2010 Update 2</a>[1]<br />(KB2522484)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b6ad2ae-e168-45d9-bd3f-5590e0cbd2b5">Microsoft Forefront Unified Access Gateway 2010 Service Pack 1</a>[1]<br />(KB2522485)<br />(Tärkeä)</td></tr>
              </table>


**Huomautus** **: MS11-07** **9**

\[1\] Päivitys on saatavana vain Microsoft Download Centeristä.

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

  - [Mila Parkour](http://contagiodump.com) (yhteistyössä [Adobe Systems, Inc.:n Anshul Kotharin ja Nishant Kaushikin kanssa)](http://www.adobe.com)ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-075
  - Andrei Lutas ([BitDefender](http://www.bitdefender.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-077
  - Tarjei Mandt ([Norman](http://www.norman.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-077
  - Maik Wellmann ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-077
  - David Warren ([CERT/CC](http://www.cert.org/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-077
  - Tuntematon henkilö (yhteistyössä [Beyond Securityn SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) -ohjelman kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-078
  - [Tenable Network Security](http://www.tenable.com/) ilmoitti kolmesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS11-079
  - Elisabeth Demeter ([SEC Consult Unternehmensberatung GmbH](http://www.sec-consult.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-079
  - Bo Zhou ([National University of Defense Technology](http://www.nudt.edu.cn/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-080
  - Vishwas Sharma (McAfee Labs) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-081
  - David Bloom ([Greplin](https://www.greplin.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-081
  - Ivan Fratric ([TippingPoint's](http://www.tippingpoint.com)[Zero Day Initiative](http://www.zerodayinitiative.com)) ilmoitti kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS11-081
  - [GWSlabs](http://www.gwslabs.com) (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-081
  - Sebastian Apelt (yhteistyössä [TippingPointin](http://www.tippingpoint.com)[Zero Day Initiative](http://www.zerodayinitiative.com)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-081
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com)[Zero Day Initiative](http://www.zerodayinitiative.com)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-081
  - Eduardo Vela Nava ([Google Inc.](http://www.google.com)) David Bloom ([Greplin](https://www.greplin.com)) tekivät yhteistyötä kanssamme kehittääkseen tietoturvaa koskevia muutoksia liittyen haavoittuvuuteen, joka on kuvattu tietoturvatiedotteessa MS11-081
  - [Soroush Dalili](http://www.secproject.com) teki yhteistyötä kanssamme kehittääkseen tietoturvaa koskevia muutoksia liittyen haavoittuvuuteen, joka on kuvattu tietoturvatiedotteessa MS11-081
  - Billy Rios ([Google Inc.](http://www.google.com)) teki yhteistyötä kanssamme kehittääkseen tietoturvaa koskevia muutoksia liittyen haavoittuvuuteen, joka on kuvattu tietoturvatiedotteessa MS11-081

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [tietoturvapalvelu](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia. Lisätietoja saatavissa olevista tukivaihtoehdoista on [Microsoftin Ohjeessa ja tuessa](http://support.microsoft.com/).
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - Versio 1.0 (11.10.2011): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (26. lokakuuta 2011): Tietoturvatiedote MS11-078:ssa korjattiin Server Core -asennuksen sovellettavuus .NET Framework 4:lle Windows Server 2008 R2 for x64 -pohjaisissa järjestelmissä.

*Built at 2014-04-18T01:50:00Z-07:00*

