---
title: Microsoftin tietoturvatiedotteiden yhteenveto, marraskuu 2011
TOCTitle: MS11-NOV
ms:assetid: ms11-nov
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms11-nov(v=Security.10)
ms:contentKeyID: 61225730
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin tietoturvatiedotteiden yhteenveto, marraskuu 2011

Julkaistu: 8. marraskuuta 2011

**Versio:** 1.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo marraskuussa 2011 julkaistuista tietoturvatiedotteista.

Marraskuun 2011 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 3. marraskuuta 2011. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 9. marraskuuta 2011, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt marraskuun tietoturvatiedotteen webcast-lähetykseen](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487958). Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://go.microsoft.com/fwlink/?linkid=217214) kertovassa englanninkielisessä sivustossa.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=229071">MS11-083</a></td>
<td><strong>TCP/IP:n haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2588516)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus voi sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä lähettää jatkuvana virtana erityisesti muotoiltuja UDP-paketteja kohdejärjestelmän suljettuun porttiin.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217214">MS11-085</a></td>
<td><strong>Windows Meeting Spacen ja Windows Mailin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2620704)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa laillisen tiedoston (kuten .eml- tai .wcinv-tiedoston), joka sijaitsee samassa verkkokansiossa kuin tietyllä tavalla muodostettu kirjastotiedosto. Avattaessa oikeaa tiedostoa Windows Mail tai Windows Meeting Space saattaa yrittää ladata DLL-tiedoston ja suorittaa siinä olevan koodin. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja laillinen tiedosto (kuten .eml- tai .wcinv-tiedoston) tästä sijainnista. Lisäksi sovelluksen, jota haavoittuvuus koskee, on ladattava kyseinen tiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229253">MS11-086</a></td>
<td><strong>Active Directoryn haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen (2630837)</strong><br />
<br />
Tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Active Directoryn, ADAM:n (Active Directory Application Mode) ja AD LDS:n (Active Directory Lightweight Directory Service) haavoittuvuuden. Haavoittuvuus voi sallia käyttöoikeuksien laajentumisen, jos Active Directory on määritetty käyttämään LDAPia SSL:n kautta (LDAPS) ja hyökkääjä hankkii hylätyn varmenteen, joka liittyy kelvolliseen toimialueeseen ja käyttää sitten kyseistä varmennetta Active Directory -toimialueen todentamiseen. Oletusarvoisesti Active Directorya ei ole määritetty käyttämään LDAPia SSL:n kautta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229245">MS11-084</a></td>
<td><strong>Haavoittuvuus Windows-ytimen ohjaimissa saattaa sallia palveluneston (2617657)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus voi sallia palveluneston, jos käyttäjä avaa erityisesti muotoillun sähköpostiviestin liitteenä tulleen TrueType-fonttitiedoston tai siirtyy jaettuun verkkoresurssiin tai WebDAV-sijaintiin, jossa on erityisesti muotoiltu TrueType-fonttitiedosto. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja avattava tietyllä tavalla muodostettu TrueType-fonttitiedosto tai avattava sähköpostin liitteenä ollut tiedosto. Joka tapauksessa hyökkääjä ei voisi millään tavoin pakottaa käyttäjiä näihin toimenpiteisiin. Hyökkääjä voi kuitenkin onnistua saamaan käyttäjän tekemään näin. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä tai pikaviestissä olevaa linkkiä.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Keskitaso</a><br />
Palvelunesto</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=229071">MS11-083</a></td>
<td>Viitemäärän ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2013">CVE-2011-2013</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217214">MS11-085</a></td>
<td>Windows Mailin suojaamattoman kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2016">CVE-2011-2016</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229253">MS11-086</a></td>
<td>LDAPS-todennuksen ohittamishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2014">CVE-2011-2014</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
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
  <tr class="thead">
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
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217214">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td colspan="2">Ei mitään</td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>Ei käytössä</td><td>Ei käytössä</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8c7c21c5-677d-4a5d-8f2b-8ca7691b6b00">Active Directory Application Mode (ADAM)</a>
                    <br />(KB2616310) <br />(Tärkeä)</td><td colspan="2">Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>Ei käytössä</td><td>Ei käytössä</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=989cca2d-cce1-4f52-b50e-43152693f240">Active Directory Application Mode (ADAM)</a>
                    <br />(KB2616310) <br />(Tärkeä)</td><td colspan="2">Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217214">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td colspan="2">Ei mitään</td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>Ei käytössä</td><td>Ei käytössä</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08b27ce7-c32e-41e4-ad04-481c5eab17a7">Active Directory</a>
                    <br />(KB2601626) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f116824e-ea48-422d-b284-c9ffa7604bf5">Active Directory Application Mode (ADAM)</a><br />(KB2616310) <br />(Tärkeä)</td><td colspan="2">Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>Ei käytössä</td><td>Ei käytössä</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=de5a74f2-2cc8-4677-b495-3a40fe3d6b9e">Active Directory</a>
                    <br />(KB2601626) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1af1b734-62c7-4e08-91c8-90b6d026da84">Active Directory Application Mode (ADAM)</a><br />(KB2616310) <br />(Tärkeä)</td><td colspan="2">Ei käytössä</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>Ei käytössä</td><td>Ei käytössä</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6168bc67-3d59-450f-bd8a-02d61dabe16b">Active Directory</a>
                    <br />(KB2601626) <br />(Tärkeä)</td><td colspan="2">Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217214">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
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
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td colspan="2">Ei mitään</td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc3fe87c-2493-431d-a904-dec9310f6042">Windows Vista Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e08266d8-fffa-40bf-b8f6-10a65ee27524">Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bd602cf-ae0d-4790-a5d0-6133fd7d01a0">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2601626) <br />(Tärkeä)</td><td colspan="2">Ei käytössä</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=042c1a8f-834d-4eed-8a59-9e030ccc6d39">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f2365ed-d50e-44d9-b859-1ec54d3b4d38">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=783521ad-5c50-4194-a582-4e5a1c9999e7">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2601626) <br />(Tärkeä)</td><td colspan="2">Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217214">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
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
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td colspan="2">Ei mitään</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79382bf2-d2cb-42ea-92dc-64f949353521">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f82dc413-668c-4ca8-a8c8-db74f05346bc">Windows Server 2008 for 32-bit Systems Service Pack 2</a>**<br />(Keskitaso)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b5688923-3914-4f6c-8bc9-036fb4870cc6">Active Directory ja Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB2601626) <br />(Tärkeä)</td><td colspan="2">Ei käytössä</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71ff3a89-d7ad-4dda-9e59-fab54b21bd5d">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06ad5637-56a1-4478-aaa0-063e877503c9">Windows Server 2008 for x64-based Systems Service Pack 2</a>**<br />(Keskitaso)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51f47181-08f6-4de1-80e5-253355675965">Active Directory ja Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB2601626) <br />(Tärkeä)</td><td colspan="2">Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1c0cb05-c284-49b1-ae4f-92813fdf520f">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2de5de74-e643-4045-9c22-ff95b0dbcafc">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Keskitaso)</td><td colspan="2">Ei käytössä</td><td colspan="2">Ei käytössä</td></tr>
              
                <tr><th colspan="7">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217214">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
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
                      <strong>Ei tärkeä</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ddb4c2a-bada-49b0-ad78-e07e7e11ced7">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2307fa93-8e45-4841-a5a9-7e89960712f9">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Ei tärkeä)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b06f9f55-e3b2-4705-83d0-1b9f5de9d378">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2601626) <br />(Tärkeä)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=156c1bd9-55bc-482c-874b-61998d1ef153">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Keskitaso)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05eef5d7-acf6-46e4-abfc-dc83f0a7cae5">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62603d18-1b21-400c-8eba-202193182960">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Ei tärkeä)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=790f1d99-96a5-438d-b433-895b692912ce">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2601626) <br />(Tärkeä)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c7db930-5495-43f0-928c-d586ac9e80d0">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Keskitaso)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217214">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
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
                      <strong>Ei tärkeä</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f9f74a6-e984-4aab-837c-ef7286e7305f">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9cf6a22-f9ab-427a-9b16-33c60baaabb5">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>**<br />(Ei tärkeä)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cc1e99af-fc67-400b-a82c-171f8c4d1ac9">Active Directory ja Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB2601626) <br />(Tärkeä)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d810dae-5c52-4155-b5c2-163d27be6e78">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>***<br />(Keskitaso)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b20bfcbd-a515-4074-b56e-b82539fe5bad">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=012777f5-51f2-4944-91af-a9c79b8081a1">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Ei tärkeä)</td><td colspan="2">Ei käytössä</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=395819e2-1028-44b7-ace4-ca754b1a7543">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Keskitaso)</td></tr>
              </table>


**Huomautukse** **t** **Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 - tai Windows Server 2008 R2 -versioita, jos se asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, ei koske mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita, jos on käytetty Server Core -asennusta, vaikka järjestelmässä olisi tiedostoja, joita tämä haavoittuvuus koskee. Käyttäjille, joilla on haavoittuvia tiedostoja, kuitenkin tarjotaan tämä päivitys, koska päivitystiedostot ovat uudempia (niiden versionumero on suurempi) kuin järjestelmässä olevat tiedostot. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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

  - David Warren ([CERT/CC](http://www.cert.org/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-084
  - Ivan Sanchez (EvilCode) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-085
  - Xavier Lassoie Sébastien Godard (Autosécurité) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS11-086

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [tietoturvapalvelu](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY (1-866-727-2338). Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia. Lisätietoja saatavissa olevista tukivaihtoehdoista on [Microsoftin Ohjeessa ja tuessa](http://support.microsoft.com/).
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - Versio 1.0 (8.11.2011): Tietoturvatiedotteen yhteenveto julkaistu.

*Built at 2014-04-18T01:50:00Z-07:00*

