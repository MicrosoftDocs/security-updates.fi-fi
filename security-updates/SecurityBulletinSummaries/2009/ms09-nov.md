---
title: Microsoftin turvatiedotteiden yhteenveto, marraskuu 2009
TOCTitle: MS09-NOV
ms:assetid: ms09-nov
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms09-nov(v=Security.10)
ms:contentKeyID: 61225639
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, marraskuu 2009

Julkaistu: 10. marraskuuta 2009 | Päivitetty: 25. marraskuuta 2009

**Versio:** 1.1

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo marraskuussa 2009 julkaistuista tietoturvatiedotteista.

Marraskuun 2009 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 5. marraskuuta 2009. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 11. marraskuuta 2009, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt marraskuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407490&culture=en-us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

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
<th>Edellyttää uudelleenkäynnistystä</th>
<th>Ohjelmistot, joita haavoittuvuus koskee</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=163840">MS09-063</a></td>
<td><strong>WSDAPI-haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (973565)</strong><br />
<br />
Tietoturvapäivitys korjaa yksityishenkilön ilmoittamaan WSDAPI (Web Services on Devices Application Programming Interface) -haavoittuvuuteen Windows-käyttöjärjestelmässä. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos Windows-järjestelmä, jota haavoittuvuus koskee, vastaanottaa tietyllä tavalla muodostetun paketin. Vain paikallista aliverkkoa käyttävät hyökkääjät voivat hyödyntää tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=163841">MS09-064</a></td>
<td><strong>Sisäänkirjautumisen lisenssipalvelimen haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (974783)</strong><br />
<br />
Tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windows 2000:n haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä lähettää tietyllä tavalla muodostetun verkkoviestin tietokoneeseen, jossa sisäänkirjautumisen lisenssipalvelinta käytetään. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada järjestelmän kokonaan hallintaansa. Palomuurikäytännöistä ja palomuurin vakiomäärityksistä annetut toimintaohjeet suojaavat verkkoa hyökkäyksiltä, joiden lähde on yritysverkon ulkopuolella.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=162428">MS09-065</a></td>
<td><strong>Windowsin ydintilan ohjaimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityk</strong> <strong>sellä (969947)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa useita yksityishenkilön ilmoittamia Windowsin ytimen haavoittuvuuksia. Vakavin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä on tarkastellut sisältöä, joka on hahmotettu tietyllä tavalla muodostetulla EOT-fontilla. Verkkohyökkäyksessä hyökkääjän on isännöitävä sivustoa, jossa on tämän haavoittuvuuden hyödyntämistä yrittämään suunniteltuja upotettuja fontteja. Lisäksi sivustot, jotka ovat vaarantuneet ja jotka hyväksyvät tai isännöivät käyttäjien toimittamaa materiaalia, voivat sisältää tätä haavoittuvuutta hyödyntävää, tietyllä tavalla muodostettua sisältöä. Hyökkääjä ei pysty pakottamaan käyttäjää avaamaan tietyllä tavalla muodostettua sivustoa. Hyökkääjä voi kuitenkin onnistua saamaan käyttäjän avaaman sivuston. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä olevaa linkkiä tai pikaviestinviestiä, joka avaa hyökkääjän sivuston.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157862">MS09-066</a></td>
<td><strong>Active Directoryn haavoittuvuus voi aiheuttaa palveluneston (973309)</strong><br />
<br />
Tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Active Directory -hakemistopalvelun, ADAM:n (Active Directory Application Mode) ja AD LDS:n (Active Directory Lightweight Directory Service) haavoittuvuuden. Haavoittuvuus saattaa sallia palveluneston, jos pinotila loppuu tietyntyyppisten LDAP- tai LDAPS-pyyntöjen suorittamisen aikana. Haavoittuvuus koskee ainoastaan toimialueen ohjauskoneita ja järjestelmiä, jotka on määritetty suorittamaan ADAM tai AD LDS.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Palvelunesto</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td><strong>Microsoft Office Excelin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välit</strong> <strong>yksellä (972652)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa useita yksityishenkilön ilmoittamia Microsoft Office Excelin haavoittuvuuksia. Haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Excel-tiedoston. Jotakin näistä haavoittuvuuksista onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin paikallinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165890">MS09-068</a></td>
<td><strong>Microsoft Office Wordin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (976307)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden, joka saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Word-tiedoston. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
</tbody>
</table>


## Hyödyntämisindeksi

Seuraavassa taulukossa on kunkin tässä kuussa käsitellyn haavoittuvuuden hyödyntämisluokitus. Haavoittuvuudet on järjestetty tiedotteen tunnuksen ja CVE-tunnuksen mukaan.

**Miten taulukkoa käytetään?**

Tämän taulukon avulla saat selville, kuinka todennäköistä on sellaisen hyväksikäyttökoodin julkaiseminen 30 päivän kuluessa tietoturvatiedotteen julkaisemisesta, joka koskee tietoturvapäivitystä, joka sinun on ehkä asennettava. Tutustu järjestelmän määritysten perusteella kuhunkin arviointiin. Tällä tavoin voit ottaa päivitykset käyttöön tärkeysjärjestyksessä. Lisätietoja näistä luokituksista ja niiden määrittämisestä on [Microsoftin hyödyntämisindeksissä](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table>
<thead>
<tr class="header">
<th>Tiedotteen tunnus</th>
<th>Haavoittuvuuden otsikko</th>
<th>CVE-tunnus</th>
<th>Hyödyntämisindeksin arvio</th>
<th>Tärkeät huomautukset</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=163840">MS09-063</a></td>
<td>Muistia vioittava WSDAPI-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2512">CVE-2009-2512</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Skenaarion mukaan rajoitettu palvelunestohyökkäys on mahdollinen.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=163841">MS09-064</a></td>
<td>Sisäänkirjautumisen lisenssipalvelimen keon ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2523">CVE-2009-2523</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>Hyökkäys luottaa kilpailutilanteeseen, jota on vaikea hyödyntää. Muiden kuin palvelunestohyökkäyksien odotetaan olevan epäluotettavia.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=162428">MS09-065</a></td>
<td>Win32k:n NULL-osoittimen viittauksen poistamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1127">CVE-2009-1127</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=162428">MS09-065</a></td>
<td>Win32k:n riittämättömän tietojen tarkistamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2513">CVE-2009-2513</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=162428">MS09-065</a></td>
<td>Win32k:n EOT-jäsennyksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2514">CVE-2009-2514</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157862">MS09-066</a></td>
<td>LSASS:n rekursiivinen pinon ylivuodon haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1928">CVE-2009-1928</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Palvelunestoon on mahdollisuus.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td>Excel-välimuistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3127">CVE-2009-3127</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td>Excel-SxView'n muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3128">CVE-2009-3128</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td>Excelin Featheader-tallennuksen muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3129">CVE-2009-3129</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td>Excel-tiedoston jäsentämisen keon ylivuodon haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3130">CVE-2009-3130</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td>Excel-kaavan jäsentämisen muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3131">CVE-2009-3131</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td>Excel-indeksin jäsentämisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3132">CVE-2009-3132</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td>Excel-tiedoston jäsentämisen muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3133">CVE-2009-3133</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td>Excel-kentän siivoamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3134">CVE-2009-3134</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=165890">MS09-068</a></td>
<td>Microsoft Office Word -tiedostotietojen muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3135">CVE-2009-3135</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
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
                <tr><th colspan="5">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=163840">
                      <strong>MS09-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=163841">
                      <strong>MS09-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=162428">
                      <strong>MS09-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=157862">
                      <strong>MS09-066</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
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
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=365a8dff-2383-42f6-b567-e545461fd135">Microsoft Windows 2000 Server Service Pack 4</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45db8bb1-c81b-4d3f-a658-74f5fa445f81">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=297158cf-374c-45d9-b213-978e1f54d244">Microsoft Windows 2000 Server Service Pack 4:n Active Directory</a>
                    <br />(KB973037)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="5">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=163840">
                      <strong>MS09-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=163841">
                      <strong>MS09-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=162428">
                      <strong>MS09-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=157862">
                      <strong>MS09-066</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 ja Windows XP Service Pack 3</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=916abdad-44b7-4f9d-986a-0c3558fb8e06">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cbe09780-f288-457a-b254-58c9c8744055">Active Directory Application Mode (ADAM)</a>
                    <br />(KB973039)<br />(Tärkeä)</td></tr>
                <tr><td>Windows XP Professional x64 Edition Service Pack 2</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d0464c6-5ed8-4064-887e-618a2db09236">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b65ddf36-a02d-4aa2-9b4f-7416dbf59e2a">Active Directory Application Mode (ADAM)</a>
                    <br />(KB973039)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="5">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=163840">
                      <strong>MS09-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=163841">
                      <strong>MS09-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=162428">
                      <strong>MS09-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=157862">
                      <strong>MS09-066</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5cd62750-e269-44ae-8c7c-c335e8545b9a">Windows Server 2003 Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28f1c494-4e16-43b6-93d2-49e15f142ac9">Active Directory</a>
                    <br />(KB973037)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44cb9029-4b19-4bad-8fc9-3efe285adb0e">Active Directory Application Mode (ADAM)</a><br />(KB973039)<br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04a7f817-f330-4003-8b25-d3e744905b12">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=509aeec0-112b-44ab-8686-43f381b61940">Active Directory</a>
                    <br />(KB973037)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87f2109e-5129-467c-930f-70af31ebf5de">Active Directory Application Mode (ADAM)</a><br />(KB973039)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b95daac0-4c99-47a4-b0ca-9429997ea3d9">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=040e691b-1ef0-4b73-bef7-a1d77b84b0ca">Active Directory</a>
                    <br />(KB973037)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="5">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=163840">
                      <strong>MS09-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=163841">
                      <strong>MS09-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=162428">
                      <strong>MS09-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=157862">
                      <strong>MS09-066</strong>
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
                <tr><td>Windows Vista, Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebf0c294-cd99-445a-a741-78253e47189f">Windows Vista, Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54562103-1d99-42d7-8f7f-c0cbcdce90db">Windows Vista, Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9645fc9-f524-43f1-8b8c-94b3b4312158">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fcb87cc8-6fd7-4f16-93d6-552999462fb1">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="5">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=163840">
                      <strong>MS09-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=163841">
                      <strong>MS09-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=162428">
                      <strong>MS09-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=157862">
                      <strong>MS09-066</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6a60883-b103-459a-a91b-cd6ed946cefe">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b97d48de-0f6d-4bca-b990-acf543fdb8b7">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=701abf15-7f93-41de-8d09-13404fd79a7e">Active Directory ja AD LDS (Active Directory Lightweight Directory Service)</a>*<br />(KB973037)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3dde1587-42d3-438f-8344-696a5657b9b1">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0e2b8607-10fa-406a-96a5-18290f479c48">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17f5f9e0-5869-41da-9b3b-6e67540af1f0">Active Directory ja AD LDS (Active Directory Lightweight Directory Service)</a>*<br />(KB973037)<br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=841a027f-22fa-42de-93b3-57a3fe92a1d3">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Kriittinen)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28eba3f3-99a5-424c-bc8d-a718c716699e">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              </table>


**Huomautus: Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on MSDN-artikkeleissa, [Server Coressa](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) ja [Server Core for Windows Server 2008 R2:ssa](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=165431">
                      <strong>MS09-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=165890">
                      <strong>MS09-068</strong>
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
                  </td></tr>
                <tr><td>Microsoft Office XP</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5672c8fc-8509-4962-ad86-ebc0f2575043">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB973471)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0369fae5-958b-4eba-83a4-9c07e701c273">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB973444)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a6a0f5d-17dc-4a34-b9a0-0774aa287ba5">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB973475)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b77bc62-bcbb-4b9a-97d1-a49ca0582e54">Microsoft Office Word 2003 Service Pack 3</a>
                    <br />(KB973443)<br />(Tärkeä)</td></tr>
                <tr><td>2007 Microsoft Office System</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=322b24ca-aff6-4ca0-acf1-440cae0f9693">Microsoft Office Excel 2007 Service Pack 1 ja Microsoft Office Excel 2007 Service Pack 2</a>
                    [1]
                    <br />(KB973593)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="3">Microsoft Office for Mac</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=165431">
                      <strong>MS09-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=165890">
                      <strong>MS09-068</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärk</strong>
                      <strong>eä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2004 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e">Microsoft Office 2004 for Mac</a>
                    <br />(KB976830)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e">Microsoft Office 2004 for Mac</a>
                    <br />(KB976830)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Office 2008 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b84fe57d-ddda-451e-9ead-69e10aee7928">Microsoft Office 2008 for Mac</a>
                    <br />(KB976828)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b84fe57d-ddda-451e-9ead-69e10aee7928">Microsoft Office 2008 for Mac</a>
                    <br />(KB976828)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Open XML File Format Converter for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6">Open XML File Format Converter for Mac</a>
                    <br />(KB976831)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6">Open XML File Format Converter for Mac</a>
                    <br />(KB976831)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="3">Muu Microsoft Office -ohjelmisto</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=165431">
                      <strong>MS09-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=165890">
                      <strong>MS09-068</strong>
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
                  </td></tr>
                <tr><td>Microsoft Office Excel Viewer 2003</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19151e22-5642-456c-bd39-298574369cdb">Microsoft Office Excel Viewer 2003 Service Pack 3</a>
                    <br />(KB973484)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fb36df5e-ebef-46bf-9edd-67f2c76dbdb3">Microsoft Office Excel Viewer Service Pack 1 ja Microsoft Office Excel Viewer Service Pack 2</a>
                    <br />(KB973707)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office Word Viewer 2003</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1">Microsoft Office Word Viewer 2003 Service Pack 3</a>
                    <br />(KB973866)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Word Viewer</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1">Microsoft Office Word Viewer</a>
                    <br />(KB973866)<br />(Tärkeä)</td></tr>
                <tr><td>Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4c92d2e-e87d-446f-8d3e-8f4be10c70aa">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1 ja Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2</a>
                    <br />(KB973704)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              </table>


**Huomautus: MS09-067**

\[1\]Jos käyttäjällä on Microsoft Office Excel 2007 Service Pack 1 ja Microsoft Office Excel 2007 Service Pack 2, hänen on asennettava sekä tietoturvapäivitys KB973593 että Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen [Microsoft Office -yhteensopivuuspaketin Service Pack 1:n ja Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2:n](http://www.microsoft.com/downloads/details.aspx?familyid=c4c92d2e-e87d-446f-8d3e-8f4be10c70aa)(KB973704) tietoturvapäivitys, jolla suojaudutaan tässä tiedotteessa kuvatuilta haavoittuvuuksilta.

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)- ja [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) -sivustoista. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Huomautus** Microsoft lopetti Office Updaten ja Office Update Inventory -työkalun tuen 1.8.2009. Saat jatkossa Microsoft Office -tuotteiden päivitykset [Microsoft Updaten](http://go.microsoft.com/fwlink/?linkid=40747) kautta. Lisätietoja on kohdassa [Tietoja Microsoft Office Updatesta: usein kysytyt kysymykset](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut ohjeita tietoturvapäivitysten tunnistamiseen ja käyttöönottamiseen. Ohjeisiin sisältyy suosituksia ja tietoja, joiden avulla IT-ammattilaiset oppivat tunnistamaan ja ottamaan käyttöön tietoturvapäivityksiä erilaisilla työkaluilla. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso myös [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) -sivustossa. SMS 2.0 -käyttäjät voivat ottaa tietoturvapäivitykset käyttöön myös SUIT (Security Update Inventory Tool) -työkalulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää Microsoft Baseline Security Analyzer -työkalua tietoturvapäivityksien kattavaan tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

**Update Compatibility Evaluator ja sovellusten yhteensopivuusty** **ökalu**

Päivitykset usein kirjoittavat samoihin tiedostoihin ja rekisteriasetuksiin, joita tarvitaan sovelluksia käytettäessä. Tämä voi aiheuttaa yhteensopivuusongelmia ja pidentää aikaa, joka kuluu tietoturvapäivitysten käyttöönottamiseen. Voit tehostaa Windows-päivitysten testaamista ja tarkistamista asennetuissa sovelluksissa käyttämällä [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) -osia, jotka sisältyvät [Application Compatibility Toolkitiin](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Sovellusten yhteensopivuustyökalu sisältää työkalut ja ohjeistuksen, joilla voi arvioida ja lieventää sovellusten yhteensopivuusongelmia ennen Microsoft Windows Vistan, Windowsin päivityksen, Microsoftin tietoturvapäivitysten tai Windows Internet Explorerin uuden versioon käyttöönottoa ympäristössäsi.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tietoja Windows Update- ja Microsoft Update -sivustoissa julkaistavista päivityksistä, jotka eivät ole tietoturvapäivityksiä:

  - [Microsoft Knowledge Base -artikkeli 894199](http://support.microsoft.com/kb/894199): Kuvaus Software Update Services- ja Windows Server Update Services -sisällön muutoksista. Sisältää kaiken Windows-sisällön.
  - [Windows Server Update Services -palvelun aiemmin toimittamat päivitykset](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (englanninkielinen). Näyttää kaikki uudet, muokatut ja uudelleenulkaistut Microsoft-tuotteiden päivitykset Microsoft Windowsia lukuun ottamatta.

#### Microsoft Active Protections Program (MAPP)

Microsoft haluaa parantaa asiakkaittensa tietoturvasuojauksia tarjoamalla haavoittuvuustietoja suurille tietoturvaohjelmistojen valmistajille ennen joka kuukausi julkaistavan tietoturvapäivityksen julkaisemista. Tietoturvaohjelmistojen valmistajat voivat sitten päivittää näiden haavoittuvuustietojen perusteella asiakkailleen tarjoamiaan tietoturvaohjelmistoja tai laitteita. Tällaisia ovat esimerkiksi viruksentorjunta, verkkopohjaiset tunkeutumisen havaintojärjestelmät ja isäntäpohjaiset tunkeutumisenestojärjestelmät. Voit selvittää, mitä aktiivisia suojauksia tietoturvaohjelmistojen toimittajilla on tarjolla, tutustumalla ohjelman kumppanien ylläpitämiin aktiivisen suojauksen sivustoihin. Nämä kumppanit ovat [MAPP (Microsoft Active Protections Program) -kumppaneita](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

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

  - Neel Mehta ([Google Inc.](http://www.google.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-063
  - Cody Pierce ([TippingPoint DVLabs](http://dvlabs.tippingpoint.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-064
  - Agin Sun ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-065
  - Tavis Ormandy ([Google Inc.](http://www.google.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-065
  - Bing Liu ([Fortinetin FortiGuard Labs](http://www.fortiguard.com/)) ilmoitti kolmesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS09-067
  - [TippingPoint](http://www.tippingpoint.com/) ja [Zero Day Initiative](http://www.zerodayinitiative.com/) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-067
  - Sean Larsson ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-067
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-067
  - Nicolas Joly ([VUPEN Security](http://www.vupen.com/)) ilmoitti neljästä haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS09-067
  - Jun Mao ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-068

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [tietoturvapalvelu](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia. Lisätietoja saatavissa olevista tukivaihtoehdoista on [Microsoftin Ohjeessa ja tuessa](http://support.microsoft.com/).
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (10. marraskuuta 2009): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (25. marraskuuta 2009): Lisättiin tärkeä huomautus hyödyntämisindeksiin kohteessa CVE-2009-2523.

*Built at 2014-04-18T01:50:00Z-07:00*

