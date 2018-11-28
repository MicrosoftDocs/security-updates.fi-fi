---
title: Microsoftin turvatiedotteiden yhteenveto, tammikuu 2012
TOCTitle: MS12-JAN
ms:assetid: ms12-jan
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms12-jan(v=Security.10)
ms:contentKeyID: 61225743
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, tammikuu 2012

Julkaistu: 10. tammikuuta 2012 | Päivitetty: 27. tammikuuta 2012

**Versio:** 2.1

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo tammikuussa 2012 julkaistuista tietoturvatiedotteista.

Tämä tietoturvatiedotteiden yhteenveto korvaa tammikuun 2012 tietoturvatiedotteiden julkaisun yhteydessä tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 5. tammikuuta 2012. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 11. tammikuuta 2012, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt tammikuun tietoturvatiedotteen webcast-lähetykseen.](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499498) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://go.microsoft.com/fwlink/?linkid=217214) kertovassa englanninkielisessä sivustossa.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=227487">MS12-004</a></td>
<td><strong>Windows Median haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (2636391)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa Microsoft Windowsin haavoittuvuutta. Haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun mediatiedoston. Näitä haavoittuvuuksia onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin paikallinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235999">MS12-001</a></td>
<td><strong>Windows-ytimen haavoittuvuus voi sallia tietoturvatoiminnon kiertämisen (2644615)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Tämä haavoittuvuus saattaa antaa hyökkääjän ohittaa ohjelmistosovelluksen SafeSEH-tietoturvatoiminnon. Tämän jälkeen hyökkääjä voi hyödyntää muita haavoittuvuuksia ja suorittaa haluamansa koodin rakenteisen poikkeuskäsittelyn avulla. Tätä haavoittuvuutta voidaan hyödyntää vain ohjelmistosovelluksissa, jotka käyttävät Microsoft Visual C++ .NET 2003:a.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Tietoturvaominaisuuden ohittamishaavoittuvuus</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229637">MS12-002</a></td>
<td><strong>Windows Object Packagerin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2603381)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä avaa upotetun pakatun objektin sisältävän kelvollisen tiedoston verkkokansiossa, jossa on myös tietyllä tavalla muodostettu suoritustiedosto. Tätä haavoittuvuutta onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin sisäänkirjautunut käyttäjä. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235400">MS12-003</a></td>
<td><strong>Windows-asiakkaan ja CRSSS-järjestelmän haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (2646524)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Tämä tietoturvatiedote on luokiteltu tärkeäksi kaikissa tuetuissa Windows XP-, Windows Server 2003-, Windows Vista- ja Windows Server 2008 -versioissa. Haavoittuvuus ei koske tuettuja Windows 7- ja Windows Server 2008 R2 -versioita.<br />
<br />
Haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen, jos hyökkääjä kirjautuu järjestelmään, jota haavoittuvuus koskee, ja suorittaa tietyllä tavalla muodostetun sovelluksen. Hyökkääjä saattaa tämän jälkeen saada haavoittuvuuden sisältävän järjestelmän täysin hallintaansa ja asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Tätä haavoittuvuutta voi hyödyntää vain käyttöjärjestelmän kiinalaisissa, japanilaisissa tai korealaisissa versioissa.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=230777">MS12-005</a></td>
<td><strong>Microsoft Windowsin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2584146)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Microsoft Office -tiedoston, joka sisältää upotetun ClickOnce-haittaohjelman. Tätä haavoittuvuutta onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin paikallinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232510">MS12-006</a></td>
<td><strong>SSL-/TLS-haavoittuvuus saattaa sallia tietojen paljastumisen (2643584)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan SSL 3.0- ja TLS 1.0.-haavoittuvuuden. Haavoittuvuus vaikuttaa protokollaan eikä liity Windows-käyttöjärjestelmään. Haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille, jos hyökkääjä voi tarkastella salattua Web-tietoliikennettä haavoittuvuuden sisältävässä järjestelmässä. Haavoittuvuus ei koske ohjelmistoja, jotka eivät käytä CBC-muotoa, kuten TLS 1.1 ja TLS 1.2.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Tietojen paljastuminen muille käyttäjille</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227561">MS12-007</a></td>
<td><strong>AntiXSS</strong> Libraryn <strong>haavoittuvuus</strong> <strong>saattaa johtaa tietojen paljastumiseen muille käyttäjille (2607664)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Anti-Cross Site Scripting (AntiXSS) Libraryn haavoittuvuuden. Haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille, jos hyökkääjä lähettää haitallisen komentosarjan AntiXSS Library -siivoamistoimintoa käyttävään web-sivustoon. Tietojen paljastumisen haitallisuus riippuu paljastettujen tietojen luonteesta. Huomaa, että tämä haavoittuvuus ei anna hyökkääjien suorittaa koodia tai suoraan nostaa käyttöoikeuksiensa tasoa. Sen avulla voidaan kuitenkin hankkia tietoja, jotka voivat vaarantaa entisestään haavoittuvuuden sisältävää järjestelmää. Tätä haavoittuvuutta voi hyödyntää vain järjestelmissä, jossa käytetään AntiXSS Library -siivoamismoduulia.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Tietojen paljastuminen muille käyttäjille</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft-kehitystyökalut ja ohjelmisto</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=235999">MS12-001</a></td>
<td>Windows-ytimen SafeSEH-toiminnon ohittamishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0001">CVE-2012-0001</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä on tietoturvatoiminnon ohittamishaavoittuvuus.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229637">MS12-002</a></td>
<td>Object Packagerin suojaamattoman käynnistämisen salliva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0009">CVE-2012-0009</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235400">MS12-003</a></td>
<td>CSRSS-käyttöoikeuksien korottamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0005">CVE-2012-0005</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227487">MS12-004</a></td>
<td>MIDI-koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0003">CVE-2012-0003</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227487">MS12-004</a></td>
<td>DirectShow-koodin etäsuorittamisen salliva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0004">CVE-2012-0004</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=230777">MS12-005</a></td>
<td>Prosessin suorittamisen salliva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0013">CVE-2012-0013</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232510">MS12-006</a></td>
<td>SSL- ja TLS-protokollien haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3389">CVE-2011-3389</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä on yleisessä tiedossa oleva tietojen paljastumisen muille käyttäjille aiheuttava haavoittuvuus. Haavoittuvuuden tietoja on rajoitettu.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227561">MS12-007</a></td>
<td>AntiXSS Libraryn ohittamishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0007">CVE-2012-0007</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>Tämä on tietojen paljastumisen muille käyttäjille aiheuttava haavoittuvuus.</td>
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
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
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
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a142f7ba-4268-4453-a8eb-470213c028ac">Windows Multimedia Library</a>
                    <br />(KB2598479)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89b23d72-410f-4133-9c14-24eb01e5a732">Windows Multimedia Library</a><br />(KB2628259)<br />(vain Windows XP Media Center Edition 2005 Service Pack 3)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b168ee8-eb15-4c2c-afb0-e63d62b4a6dc">DirectShow</a><br />(KB2631813)<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feaeda8c-84ee-47be-8c68-736f0e5b1fc7">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cfc38dc2-c4c7-4a44-8e5a-b98bb9bc0396">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1bcb1d1e-9261-4a36-9256-90d3df9bd4fb">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fb0360b1-254c-4ecb-a36a-807cabfec1ab">Windows XP Service Pack 3</a>
                    <br />(KB2585542)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0928d720-ae88-40d6-b76f-636d67da8526">Windows Multimedia Library</a>
                    <br />(KB2598479)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13d74cc6-8d8e-45ea-8cdc-c15782f6626b">DirectShow</a><br />(KB2631813)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46386269-6e37-4710-bfef-cedfe60d881c">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=211827f2-fe6a-4e16-a90c-0cc3b60a722d">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3956db98-88d9-49fc-be51-247b40bfc272">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c687796-4c41-4d17-b738-511d2fbfc126">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afe6b34d-21b1-4dfa-afa6-2c5c2a678e9e">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2585542)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=986f1156-0190-48c2-9f39-29cacb91f0f9">Windows XP Professional x64 Edition Service Pack 2</a><br />(KB2638806)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen  </strong>
                    <strong>numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
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
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c266dfb-630d-4f32-b2ca-63955279b6a9">Windows Multimedia Library</a>
                    <br />(KB2598479)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89ae6ed0-537f-421c-b755-ef28691abd88">DirectShow</a><br />(KB2631813)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9cdfc0fe-8f43-4e13-8a1f-2b48ff9ff472">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8e46267-7988-4fbe-ae94-68b6fdb2e7d9">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39f5f8fb-ee4d-4b7a-9cd7-3d1e9c8abd8c">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c39be84-1eab-4794-b3ed-e529643aca21">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2c503a5-3f15-4a77-9a05-9ea0fbaf4503">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2585542)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c23e7604-d489-4836-8b54-3b2b3d6a365c">Windows Server 2003 Service Pack 2</a><br />(KB2638806)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8dd1c882-4ed1-4e47-a017-7d162bd94194">Windows Multimedia Library</a>
                    <br />(KB2598479)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08be569c-e9d1-4fc5-8670-ebe9da0a2072">DirectShow</a><br />(KB2631813)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e5783aa-6847-404c-9b75-621fa14ebbb8">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5975b01e-139b-4b9d-a0d5-a87a279bfea1">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e27d85f8-a285-4e95-85a0-0868286cc2b9">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3cf29dfd-239e-4707-92e6-952133c1c1c2">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ad34496-40af-40cb-9f85-5d3c31543211">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2585542)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f36e991-4e1a-4b8c-8cfb-e7f20d97cf0b">Windows Server 2003 x64 Edition Service Pack 2</a><br />(KB2638806)<br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a9b09d6-7060-47ab-9f76-c3c5acb024e6">Windows Multimedia Library</a>
                    <br />(KB2598479)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3401ac20-3701-471f-9757-097a9402d761">DirectShow</a><br />(KB2631813)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cdf8208c-d55b-428f-bdd3-26e291dfb08d">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26079c35-4b96-42fc-ad47-138be25a6bf0">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b69bd01d-9925-4ff1-bfeb-b4473631578c">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=623c1c7d-6902-4876-9614-1b6e1ef80831">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=56deb935-9226-49f8-b705-edb3d662d8aa">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(KB2585542)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2d72cf5a-cca7-4341-b862-017e3f34a3c9">Windows Server 2003 with SP2 for Itanium-based Systems</a><br />(KB2638806)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
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
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99d9b9fc-ed37-4a32-a20d-6604a1b9c4ca">Windows Multimedia Library</a>
                    <br />(KB2598479)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f345e093-336d-4464-b7f8-a14398b62ebf">Windows Media Center TV Pack for Windows Vista (32-bittiset versiot</a>)[1]<br />(KB2628642)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4818059a-52ad-4c2e-9605-4e0f5d9da5ba">DirectShow</a><br />(KB2631813)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44eeb0a2-ae17-4971-8a7e-e25b260c582c">Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73682d4b-3179-4488-8ba9-94ed68c4896b">Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=038970b6-aeec-4e18-8dfe-887b260a7c87">Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f9269bd6-8c4f-476e-8481-fc0de52a22e6">Windows Vista Service Pack 2</a>
                    <br />(KB2585542)<br />(Tärkeä)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44aa8d91-2b30-4191-8965-8aee2b860d50">Windows Multimedia Library</a>
                    <br />(KB2598479)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=559d028f-9810-4c50-b65d-f567cbb15427">Windows Media Center TV Pack for Windows Vista (64-bittiset versiot</a>)[1]<br />(KB2628642)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13cc2519-860d-4c64-b7f8-8f9c0bdaefcf">DirectShow</a><br />(KB2631813)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79ceba86-59a1-4138-a5de-8df20ad81b02">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b5c33025-13d9-43d2-a415-a8a4d683a821">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23abeb12-f2fe-43fd-9c4a-4d3d244832f8">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0403c753-d4fa-4e3d-a61b-7f816f5c352b">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2585542)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
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
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=787e6285-3ba5-4aae-9d8d-e3c1eca3b35d">Windows Multimedia Library</a>*<br />(KB2598479)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92df13c1-fdf6-4602-acb2-e634a1bcd9da">DirectShow</a>**<br />(KB2631813)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ab87c6c-5802-4454-bce4-12501e5b816d">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fbf119cf-a8ed-4266-a673-442149992f7c">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d089d9cb-382c-4e64-94c5-69b9864010b1">Windows Server 2008 for 32-bit Systems Service Pack 2</a>**<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fe2f398-433f-4338-a273-813185b43ea8">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(KB2585542)<br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9eff12b2-70a4-452b-b6bc-0d83f2edcf6c">Windows Multimedia Library</a>*<br />(KB2598479)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ff10d7f-26a6-403a-a4b7-7aff55e2fa16">DirectShow</a>**<br />(KB2631813)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=726ff17e-ac90-4832-91e7-46f71ad2f868">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8e68f89-27f4-4142-94ca-58f086a98157">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ac8a368-4298-4c1d-9cfd-924d6df563af">Windows Server 2008 for x64-based Systems Service Pack 2</a>**<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f54ac30d-8e41-4df9-bd43-db6742a24d4c">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(KB2585542)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e2edb23-7f4e-4fe4-848c-1d744e0dce9f">Windows Multimedia Library</a>
                    <br />(KB2598479)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e0394c9-3de4-46f6-ae7f-18d5a555532e">DirectShow</a><br />(KB2631813)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba2c3d57-1bdd-44f2-9233-86c7ea6f0ddb">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc6491e8-6c3e-43a1-bc56-16c9a2fd2749">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e08b242-2516-4cf6-b38e-35ec2b8b788d">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3979db3b-4961-4df8-84a4-1f26672b127c">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(KB2585542)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
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
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d736daf8-db6d-485f-b0cb-7f2d8c86f9a2">DirectShow</a>
                    <br />(KB2631813)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ee22036-b7f4-40f5-8f40-a77e8faf48b2">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7422605b-7a02-4161-b7f8-92b3ccffef64">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f433f2c-c61d-461d-af9c-0145af4b72ab">Windows 7 for 32-bit Systems ja Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(KB2585542)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=21b37775-3e7b-462d-8234-7c47d52daef9">DirectShow</a>
                    <br />(KB2631813)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7444e20c-9821-4c91-9779-2728c537dd6a">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ba46bc7-af7a-445a-84f2-b0c13674409b">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0839fec0-b6a7-4e47-9da3-2caef44a7df4">Windows 7 for x64-based Systems ja Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2585542)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
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
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=355c980d-ec2e-4b2d-a7d4-2e3dbd3a0dde">DirectShow</a>**<br />(KB2631813)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c73a16d-e9fa-48de-9dca-a6360ce3d029">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=db3a4814-a409-4def-944d-4eaa540b83b0">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>**<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34542a5a-88df-4a07-b1ed-d4c845502cd8">Windows Server 2008 R2 for x64-based Systems ja Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(KB2585542)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4b2389e-fd9f-47c7-9afd-4077f5632c21">DirectShow</a>
                    <br />(KB2631813)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1cc14ee8-f035-4bfc-bf38-33c6b9a2e776">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2101663a-ed3d-4850-b79a-16960ab56b45">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe661936-06e1-45d3-89f6-1093504496a7">Windows Server 2008 R2 for Itanium-based Systems ja Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(KB2585542)<br />(Tärkeä)</td></tr>
              </table>


**Huomautukset Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 - tai Windows Server 2008 R2 -versioita, jos se asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Huomautus: MS1** **2** **-0** **04**

\[1\]Windows Media Center TV Pack for Windows Vista on valinnainen lisäosa, joka on saatavilla vain alkuperäisen laitevalmistajien (OEM) järjestelmiin ja Windows Vista Home Premium- ja Windows Vista Ultimate -versioihin. Asiakkaiden, joiden järjestelmiin on asennettu tämä valinnainen lisäosa, kannattaa asentaa kaikki saatavana olevat Windows Vista -järjestelmän päivitykset. Parhaiden käytäntöjen mukaisesti Microsoft suosittelee käyttöjärjestelmäpäivityksien (KB2598479 ja KB2631813) asentamista ennen Windows Media Center TV Pack -päivityksen (KB2628642) asentamista.

#### Microsoft-kehitystyökalut ja ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Anti-Cross Site Scripting Library</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227561">
                      <strong>MS12-007</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Anti-Cross Site Scripting Library 3.x ja Microsoft Anti-Cross Site Scripting Library 4.0</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3ef05ce-70fe-4f25-9aee-cb7a42a53d11">Microsoft Anti-Cross Site Scripting Library 3.x ja Microsoft Anti-Cross Site Scripting Library 4.0</a>
                    [1][2]
                  </td></tr>
              </table>


**Huomautus: MS1** **2** **-** **0** **07**

\[1\]Tämä ladattava ohjelmisto päivittää Microsoft Anti-Cross Site Scripting (AntiXSS) Libraryn uudempaan versioon, joka korjaa tässä tietoturvatiedotteessa kuvatun haavoittuvuuden.

\[2\] Päivitys on saatavana vain Microsoft Download Centeristä.

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

  - Joshua J. Drake ([Accuvant LABS](http://www.accuvant.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-001
  - Parvez Anwar (yhteistyössä [Secunia Researchin](http://secunia.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-002
  - Kang Wu ([Shenzhen Jowto Research Dep](http://www.jowto.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-003
  - Shane Garrett ([IBM Security System's X-Force Research](http://xforce.iss.net/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-004
  - Neel Mehta ([Google Inc.](http://www.google.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-004
  - Tuntematon henkilö (yhteistyössä [Beyond Securityn SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) -ohjelman kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-005
  - Adi Cohen ([IBM Rational Application Security](http://blog.watchfire.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-007

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [tietoturvapalvelu](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY (1-866-727-2338). Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia. Lisätietoja saatavissa olevista tukivaihtoehdoista on [Microsoftin Ohjeessa ja tuessa](http://support.microsoft.com/).
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - Versio 1.0 (10.1.2012): Tietoturvatiedotteen yhteenveto julkaistu.
  - Versio 2.0 (11.1.2012): Tietoturvatiedotteessa MS12-003 korjattiin uusimman ohjelmistoversion hyödyntämisaste haavoittuvuuden CVE-2012-0005 **Hyödyntämisindeksi**-taulukossa. Tietoturvatiedote MS12-007 julkaistiin uudelleen. Lisätietoja on tietoturvatiedotteessa MS12-007.
  - Versio 2.1 (27.1.2012): Tietoturvatiedotteessa MS12-004 korjattiin luokituskooste päivityksessä KB2631813, joka koskee kaikkia tuettuja Windows XP-, Windows Server 2003-, Windows Vista- ja Windows Server 2008 -versioita. Lisätietoja on tietoturvatiedotteessa MS12-004.

*Built at 2014-04-18T01:50:00Z-07:00*

