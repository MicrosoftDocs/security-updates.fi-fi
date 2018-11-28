---
title: Microsoftin turvatiedotteiden yhteenveto, maaliskuu 2012
TOCTitle: MS12-MAR
ms:assetid: ms12-mar
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms12-mar(v=Security.10)
ms:contentKeyID: 61225745
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, maaliskuu 2012

Julkaistu: 13. maaliskuuta 2012

**Versio:** 1.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo maaliskuussa 2012 julkaistuista tietoturvatiedotteista.

Tämä tietoturvatiedotteiden yhteenveto korvaa maaliskuun 2012 tietoturvatiedotteiden julkaisun yhteydessä tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 8. maaliskuuta 2012. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 14. maaliskuuta 2012, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt maaliskuun tietoturvatiedotteen webcast-lähetykseen](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499508). Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://go.microsoft.com/fwlink/?linkid=217214) kertovassa englanninkielisessä sivustossa.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td><strong>Etätyöpöytäyhteyden haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (2671387)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan RDP-etäkäyttöprotokollan haavoittuvuuden. Vakavampi näistä haavoittuvuuksista saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä lähettää sarjan tietyllä tavalla muodostettuja RDP-paketteja haavoittuvuuden sisältävään järjestelmään. RDP-etäkäyttöprotokollaa ei ole oletusarvoisesti otettu käyttöön missään käyttöjärjestelmässä. Haavoittuvuus ei koske järjestelmiä, joissa ei käytetä RDP-protokollaa.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235401">MS12-017</a></td>
<td><strong>DNS-palvelimen haavoittuvuus saattaa sallia palveluneston (2647170)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia palveluneston, jos todentamaton etähyökkääjä lähettää tietyllä tavalla muodostetun DNS-kyselyn haavoittuvuuden sisältävään DNS-palvelimeen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Palvelunesto</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235364">MS12-018</a></td>
<td><strong>Windows-ytimen ohjaimien haavoittuvuudet saattavat sallia käyttöoikeuksien korottamisen (2641653)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen, jos hyökkääjä kirjautuu järjestelmään ja suorittaa tietyllä tavalla muodostetun sovelluksen. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja pystyttävä kirjautumaan paikallisesti, jotta hän pystyy hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235362">MS12-021</a></td>
<td><strong>Visual Studion haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (2651019)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Visual Studion haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen, jos hyökkääjä sijoittaa tietyllä tavalla muodostetun apuohjelman Visual Studion käyttämään hakemistopolkuun ja Visual Studion käynnistää käyttäjä, jolla on laajemmat käyttöoikeudet. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja pystyttävä kirjautumaan paikallisesti, jotta hän pystyy hyödyntämään tätä haavoittuvuutta. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Visual Studio</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235361">MS12-022</a></td>
<td><strong>Expression Designin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2651018)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Expression Designin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa laillisen tiedoston (kuten .xpr- tai .DESIGN-tiedoston), joka sijaitsee samassa verkkokansiossa kuin tietyllä tavalla muodostettu kirjastotiedosto. Avattaessa oikeaa tiedostoa Microsoft Expression Design saattaa yrittää ladata DLL-tiedoston ja suorittaa siinä olevan koodin. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja laillinen tiedosto (kuten .xpr- tai .DESIGN-tiedoston) tästä sijainnista. Lisäksi sovelluksen, jota haavoittuvuus koskee, on ladattava kyseinen tiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Expression Design</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=239573">MS12-019</a></td>
<td><strong>DirectWriten</strong> <strong>haavoittuvuudet</strong> <strong>voivat aiheuttaa palveluneston (2665364)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Windows DirectWriten haavoittuvuuden. Instant Messager -hyökkäyksessä haavoittuvuus saattaa aiheuttaa palveluneston, jos hyökkääjä lähettää tietyllä tavalla muodostetun sarjan Unicode-merkkejä suoraan Instant Messenger -asiakkaaseen. Hyökkäyksen kohteena oleva sovellus ei ehkä enää vastaa, kun DirectWrite hahmontaa tietyllä tavalla muodostettuja Unicode-merkkejä.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Keskitaso</a><br />
Palvelunesto</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=235401">MS12-017</a></td>
<td>DNS-palveluneston aiheuttava haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0006">CVE-2012-0006</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Pysyvä</td>
<td>Tämä on palveluneston aiheuttava haavoittuvuus.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235364">MS12-018</a></td>
<td>PostMessage-toiminnon haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0157">CVE-2012-0157</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Hyväksikäyttökoodia on vaikea laatia</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Hyväksikäyttökoodia on vaikea laatia</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td>RDP-etäkäyttöprotokollan haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0002">CVE-2012-0002</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>Tämä on todentamaton koodin suorittamisen verkon välityksellä salliva haavoittuvuus.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td>Päätepalvelimen palveluneston salliva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0152">CVE-2012-0152</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei koske</td>
<td>Väliaikainen</td>
<td>Tämä on palveluneston aiheuttava haavoittuvuus.<br />
<br />
Palveluneston salliva haavoittuvuus koskee vain uusinta versiota.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235362">MS12-021</a></td>
<td>Visual Studion apuohjelman haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0008">CVE-2012-0008</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235361">MS12-022</a></td>
<td>Expression Designin suojaamattoman kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0016">CVE-2012-0016</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
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
                <tr><th colspan="5">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232664">
                      <strong>MS12-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235401">
                      <strong>MS12-017</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235364">
                      <strong>MS12-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=239573">
                      <strong>MS12-019</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18a1fe48-1318-4b93-afad-206950bb1ae5">Windows XP Service Pack 3</a>
                    <br />(KB2621440)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2922411c-9755-461b-9904-f6940322af19">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eccf865d-399a-4862-b26f-f35580419875">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2621440)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e72b6b1f-68f5-4e1a-878e-290a5f03ca30">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="5">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232664">
                      <strong>MS12-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235401">
                      <strong>MS12-017</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235364">
                      <strong>MS12-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=239573">
                      <strong>MS12-019</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b69b4b9b-c0a1-4c1e-b081-8529eaf1536a">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2621440)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b04da098-666f-4760-90da-d2a17e78bf47">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=599e5db1-3bf1-4d44-bc7c-81bc545c58ec">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8081e67f-288c-4714-bff8-e0ff9777692f">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2621440)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=647eaf09-3959-439e-8418-fd25221eb6b9">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=482c2890-8d4c-4e13-820f-d5ff256b6a3a">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=521baa02-5d7a-4cba-8a1a-2af1b6e4cbe4">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(KB2621440)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92f3af60-9a9b-4419-9e95-55f5cb54cf00">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ccd0f116-73c2-4471-a6d9-e07d1dbdd406">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="5">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232664">
                      <strong>MS12-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235401">
                      <strong>MS12-017</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235364">
                      <strong>MS12-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=239573">
                      <strong>MS12-019</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39abdf7b-ea9d-4b95-a28d-4140374d531d">Windows Vista Service Pack 2</a>
                    <br />(KB2621440)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4e73a92-583b-4352-b19d-7a8e3ef162b7">Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7da5b341-6a6f-46de-8d01-448da38e9908">Windows Vista Service Pack 2</a>
                    <br />(Keskitaso)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5970daf-4440-42fa-8efc-e6190c6a22aa">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2621440)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ead9d29b-becf-448e-bff4-d5bb12d02c64">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ba25d9c-0fef-471f-8e30-045fe9586a9c">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Keskitaso)</td></tr>
              
                <tr><th colspan="5">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232664">
                      <strong>MS12-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235401">
                      <strong>MS12-017</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235364">
                      <strong>MS12-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=239573">
                      <strong>MS12-019</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef2c1d7-2004-43d7-aa49-673c6f374670">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(KB2621440)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=233c62b7-f2b1-49ce-9a7f-e51435be0d26">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd547364-f6bb-453c-9e4d-6b80dfc47fbb">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45a4784e-5051-4628-9a19-d53f30c1fdf3">Windows Server 2008 for 32-bit Systems Service Pack 2</a>**<br />(Keskitaso)</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ffae13f-3432-4849-a2da-a76f96d7ceb3">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(KB2621440)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=56eae770-5990-4e1b-8b48-3d0602fcc72b">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ff65fc2-5969-4d7e-9c72-9a2096dafdcf">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=503cb9c0-d6db-4deb-a555-67af0b25739b">Windows Server 2008 for x64-based Systems Service Pack 2</a>**<br />(Keskitaso)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67581250-50fd-4f4c-a3cc-45ce2662b0c3">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(KB2621440)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eeb5385c-fb81-4d33-af2a-986e6cf14ee2">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="5">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232664">
                      <strong>MS12-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235401">
                      <strong>MS12-017</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235364">
                      <strong>MS12-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=239573">
                      <strong>MS12-019</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16b0195c-84d3-4c08-8b98-ff2c80d144e1">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(KB2621440)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a6c7fdf-105a-4886-ad52-c892f37e32d1">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a><br />(KB2667402)<br />(Keskitaso)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75fd93ff-5be5-42b5-ab00-3378e545c271">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3a14012-38ae-490e-a48e-7c851f82a7e6">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Keskitaso)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b62d08-d2a2-4900-b01c-46fc761973d0">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2621440)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1bbe7cda-4bee-4d65-8127-3c13624a1168">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a><br />(KB2667402)<br />(Keskitaso)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71ffba4c-d816-45a9-abef-131915885bc8">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=760b5aa4-4e65-4ff1-9ae2-771234803bf0">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Keskitaso)</td></tr>
              
                <tr><th colspan="5">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232664">
                      <strong>MS12-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235401">
                      <strong>MS12-017</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235364">
                      <strong>MS12-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=239573">
                      <strong>MS12-019</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c1774cc-e00c-47f3-97a2-bc90de857793">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(KB2621440)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ec21f41-1673-4592-b45c-6438ad57e08c">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(KB2667402)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19a4f3d1-24d2-41af-a41a-e5cc2c6232e8">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22d6a234-6447-4854-8119-4fddd3c6e1bb">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=86095b20-5869-4b55-8777-ee0af82aaf37">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>**<br />(Keskitaso)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a07f99c-8ab4-4e44-8d48-6ac787dd2b51">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(KB2621440)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=469aa1f6-ed89-4649-8736-eaa5e2ad44ee">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a><br />(KB2667402)<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb5ac981-e8e5-4df7-84bb-7a2a916d0ce9">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc5c336f-329c-4a56-8b24-555e3c8afd50">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Keskitaso)</td></tr>
              </table>


**Huomautukset Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 - tai Windows Server 2008 R2 -versioita, jos se asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft-kehitystyökalut ja ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="3">Microsoft Visual Studio</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235362">
                      <strong>MS12-021</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235361">
                      <strong>MS12-022</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr><td>Microsoft Visual Studio 2008 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99d7c39a-14f1-4e7e-8a4f-2466b16821eb">Microsoft Visual Studio 2008 Service Pack 1</a>
                    <br />(KB2669970)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio 2010</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f80235ae-da15-4527-93b3-c2f31ec2f387">Microsoft Visual Studio 2010</a>
                    <br />(KB2644980)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Visual Studio 2010 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2aaec35-b2c0-48f0-8a51-34e44f6d12fb">Microsoft Visual Studio 2010 Service Pack 1</a>
                    <br />(KB2645410)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="3">Microsoft Expression Design</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235362">
                      <strong>MS12-021</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235361">
                      <strong>MS12-022</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Expression Design</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49e12f3a-718d-4d54-82be-b78efb372d07">Microsoft Expression Design</a>
                    <br />(KB2675064) <br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Expression Design Service Pack 1</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=899c6860-6081-429b-971a-4d689444920f">Microsoft Expression Design Service Pack 1</a>
                    <br />(KB2667724) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Expression Design 2</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ca4fb5a-3ab4-410b-b42b-075eb1d70410">Microsoft Expression Design 2</a>
                    <br />(KB2667725) <br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Expression Design 3</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73b44e97-6dda-4e24-9758-e86a1de4c0c8">Microsoft Expression Design 3</a>
                    <br />(KB2667727) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Expression Design 4</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=be56221e-4271-42dc-a6e4-ebf0290e4ad8">Microsoft Expression Design 4</a>
                    <br />(KB2667730) <br />(Tärkeä)</td></tr>
              </table>


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

Sovellusten yhteensopivuustyökalu sisältää työkalut ja ohjeistuksen, joilla voi arvioida ja lieventää sovellusten yhteensopivuusongelmia ennen Windows Vistan, Windowsin päivityksen, Microsoftin tietoturvapäivitysten tai Windows Internet Explorerin uuden versioon käyttöönottoa ympäristössäsi.

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

  - Nikolaos Bougalis ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-018
  - Khaled M. Salameh ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-019
  - Luigi Auriemma (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-020
  - [Laplinker](http://www.laplinker.com) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-021.
  - [Laplinker](http://www.laplinker.com) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-022.

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [tietoturvapalvelu](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY (1-866-727-2338). Lisätietoja saatavissa olevista tukivaihtoehdoista on [Microsoftin Ohjeessa ja tuessa](http://support.microsoft.com/).
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - Versio 1.0 (13.3.2012): Tietoturvatiedotteen yhteenveto julkaistu.

*Built at 2014-04-18T01:50:00Z-07:00*

