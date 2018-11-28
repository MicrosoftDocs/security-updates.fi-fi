---
title: Microsoftin turvatiedotteiden yhteenveto, huhtikuu 2012
TOCTitle: MS12-APR
ms:assetid: ms12-apr
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms12-apr(v=Security.10)
ms:contentKeyID: 61225741
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, huhtikuu 2012

Julkaistu: 10. huhtikuuta 2012 | Päivitetty: 26. huhtikuuta 2012

**Versio:** 2.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo huhtikuussa 2012 julkaistuista tietoturvatiedotteista.

Tämä tietoturvatiedotteiden yhteenveto korvaa huhtikuun 2012 tietoturvatiedotteiden julkaisun yhteydessä tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 5. huhtikuuta 2012. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 11. huhtikuuta 2012, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt huhtikuun tietoturvatiedotteen webcast-lähetykseen](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499650). Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://go.microsoft.com/fwlink/?linkid=217214) kertovassa englanninkielisessä sivustossa.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (2675157)</strong><br />
<br />
Tämä tietoturvatiedote korjaa viisi yksityishenkilön ilmoittamaa Internet Explorerin haavoittuvuutta. Vakavimmat haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun sivun Internet Explorerissa. Jotakin näistä haavoittuvuuksista onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin nykyinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238623">MS12-024</a></td>
<td><strong>Windows-käyttöjärjestelmän haavoittuvuus saattaa sallia koodin suorittamisen etäyhteyden välityksellä (2653956)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tai sovellus suorittaa tai asentaa tietyllä tavalla muodostetun allekirjoitetun PE-tiedoston (portable executable) haavoittuvuuden sisältävässä järjestelmässä..</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242032">MS12-025</a></td>
<td><strong>.NET Frameworkin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2671605)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows .NET Frameworkin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä asiakasjärjestelmässä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua selaimella, jossa voidaan suorittaa XAML-selainsovelluksia (XBAP) Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä myös palvelinjärjestelmissä, joissa on käynnissä IIS, jos palvelin sallii ASP.NET-sivujen käsittelemisen ja jos hyökkääjä pystyy lataamaan tietyllä tavalla muodostetun ASP.NET-sivun kyseiseen palvelimeen ja suorittamaan sen. Tämä voi olla mahdollista esimerkiksi Web-palvelujen yhteydessä. Myös Windows .NET -sovellukset voivat käyttää tätä haavoittuvuutta koodin käyttöoikeusrajoitusten ohittamiseen. Verkkohyökkäyksessä hyökkääjä saattaa isännöidä sivustoa, jossa on tämän haavoittuvuuden hyödyntämistä varten suunniteltu sivusto. Lisäksi sivustot, jotka ovat vaarantuneet ja jotka hyväksyvät tai isännöivät käyttäjien toimittamaa materiaalia, voivat sisältää tätä haavoittuvuutta hyödyntävää, tietyllä tavalla muodostettua sisältöä. Joka tapauksessa hyökkääjä ei voisi millään tavoin pakottaa käyttäjiä siirtymään näille verkkosivuille. Hyökkääjä voi kuitenkin onnistua saamaan käyttäjän avaaman sivuston. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä olevaa linkkiä tai pikaviestinviestiä, joka avaa hyökkääjän sivuston.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246275">MS12-027</a></td>
<td><strong>Windowsin yleisen Control-kirjaston haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2664258)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windowsin yleisen Control-kirjaston haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä siirtyy tämän haavoittuvuuden hyödyntämistä varten luotuun sivustoon. Hyökkääjä ei kuitenkaan pysty missään tapauksessa pakottamaan käyttäjää avaamaan tällaista sivustoa. Hyökkääjä voi kuitenkin onnistua saamaan käyttäjän avaaman sivuston. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä olevaa linkkiä tai pikaviestinviestiä, joka avaa hyökkääjän sivuston. Haitallinen tiedosto voidaan lähettää myös sähköpostiviestin liitetiedostona, mutta haavoittuvuuden hyödyntämiseksi hyökkääjän on saatava käyttäjä avaamaan liitetiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office,<br />
Microsoft SQL Server,<br />
Microsoft Server -ohjelmisto,<br />
Microsoft Developer Tools</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238519">MS12-026</a></td>
<td><strong>Forefront Unified Access Gatewayn (UAG) haavoittuvuudet saattavat sallia tietojen paljastumisen (2663860)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa Microsoft Forefront Unified Access Gateway (UAG) -haavoittuvuutta. Vakavin näistä haavoittuvuuksista saattaa sallia tietojen paljastumisen muille käyttäjille, jos hyökkääjä lähettää tietyllä tavalla muodostetun kyselyn haavoittuvuuden sisältävään UAG-palvelimeen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Tietojen paljastuminen muille käyttäjille</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Forefront United Access Gateway</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232498">MS12-028</a></td>
<td><strong>Microsoft Officen haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2639185)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Officen ja Microsoft Worksin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Works-tiedoston. Tätä haavoittuvuutta onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin nykyinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td>JScript9-koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0169">CVE-2012-0169</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei koske</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td>OnReadyStateChange-käsittelijän koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0170">CVE-2012-0170</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td>SelectAll-käsittelijän koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0171">CVE-2012-0171</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td>VML Style -käsittelijän koodin suorittamiseen verkon välityksellä liittyvä haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0172">CVE-2012-0172</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238623">MS12-024</a></td>
<td>WinVerifyTrustin allekirjoituksen tarkistuksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0151">CVE-2012-0151</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242032">MS12-025</a></td>
<td>.NET Frameworkin parametrien tarkistuksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0163">CVE-2012-0163</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238519">MS12-026</a></td>
<td>UAG-oletussivuston suodattamattoman käytön salliva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0147">CVE-2012-0147</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei koske</td>
<td>Ei käytössä</td>
<td>Tämä on tietojen paljastumisen muille käyttäjille aiheuttava haavoittuvuus.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246275">MS12-027</a></td>
<td>MSCOMCTL.OCX:n koodin suorittamisen salliva haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0158">CVE-2012-0158</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Microsoft on saanut ilmoituksia rajoitetuista, kohdistetuista hyökkäyksistä, jotka yrittävät hyödyntää tätä haavoittuvuutta.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232498">MS12-028</a></td>
<td>Office WPS Converter -keon ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0177">CVE-2012-0177</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Haavoittuvuus ei koske Microsoft Office 2007 Service Pack 3 -versiota eikä tuettuja Microsoft Office 2010 -versioita.</td>
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
                <tr><th colspan="4">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
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
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a490c62-16c4-402a-b2d9-3e8cfb5bcebd">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81b28dd9-87aa-46cc-94c6-2da39d0298db">Internet Explorer 7</a><br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=74ce0e29-046b-4ac3-89a1-b292a177972f">Internet Explorer 8</a><br />(KB2675157)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=575afd20-cee4-4fa9-b781-9f8dfdd41ebe">Windows XP Service Pack 3</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1cfeae57-d4e9-4fff-8956-523e7b71453c">Microsoft .NET Framework 1.0 Service Pack 3</a>
                    <br />(KB2656378)<br />(vain Media Center Edition 2005 ja Tablet PC Edition 2005) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a><br />(KB2656370) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1b7be43-a32e-456b-8df0-c26cdf187682">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29ec7b06-c7aa-4149-bb2c-25af7d38a6a9">Internet Explorer 7</a><br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=646c6352-4d99-413a-a75b-71289b5d2b25">Internet Explorer 8</a><br />(KB2675157)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=adc31695-1be6-4976-869c-007df8ac8508">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="4">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokitus </strong>
                    <strong>kooste</strong>
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
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=020e0d68-dd1c-4297-b565-fcc6dcf5f280">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17b0c139-2709-424d-9d17-827af468e858">Internet Explorer 7</a><br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3289a80a-d1b1-4494-bede-03d0be579acf">Internet Explorer 8</a><br />(KB2675157)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f79c8940-ca31-4ff7-924e-847f5eef7864">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffd26218-e149-44ea-a0b9-f2a1315fce9e">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656376) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=295292d3-01a3-4574-b994-8cdbcf5a0d2e">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04656a93-e958-4764-afe8-27c476855506">Internet Explorer 7</a><br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dff4fb63-b319-49ed-8a9d-6b15e43d5bfd">Internet Explorer 8</a><br />(KB2675157)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03ebf111-1e7b-4dc2-b84f-a26c6b5f0d58">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09011393-c7d5-4225-9b8e-5a234d4dbcd1">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a5ef0147-595e-43b5-819f-73780fcef10d">Internet Explorer 7</a><br />(KB2675157)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=734ff97a-7d72-4bfe-9557-7fac91902f8e">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="4">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
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
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f598cad1-4d1a-40ce-a016-bb58778d5dc0">Internet Explorer 7</a>
                    <br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44284277-06a7-405d-9187-8f50a042604d">Internet Explorer 8</a><br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51088164-13b7-4216-90f1-20c92c8b8ca9">Internet Explorer 9</a><br />(KB2675157)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7683919-6d46-4b3e-aa98-1bef20141835">Windows Vista Service Pack 2</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2717a997-2066-4a83-ae9b-4611a0851101">Internet Explorer 7</a>
                    <br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19684033-ddeb-464f-9a22-f580a9c19f8e">Internet Explorer 8</a><br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbb99aee-aadd-4ec7-9e27-91cb8d90803e">Internet Explorer 9</a><br />(KB2675157)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d9f8a6e-17bd-4ed3-8bc7-d5e3b11ca12a">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="4">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e361edd-234b-4053-aa49-278b9fde4d5c">Internet Explorer 7</a>**<br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6eb6781e-7b38-4679-afbc-4e3bb5747fd8">Internet Explorer 8</a>**<br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d34d7981-ed63-460d-95e4-e6da1ac41d2f">Internet Explorer 9</a>**<br />(KB2675157)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c36c20f7-a742-4151-b8f2-85ef80479d06">Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60b76a3c-4530-4101-931f-45df621e1eed">Internet Explorer 7</a>**<br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd657467-a45c-4354-b947-3a3cceb9b690">Internet Explorer 8</a>**<br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9d773e9-6a2e-45db-8f30-7da0082d909c">Internet Explorer 9</a>**<br />(KB2675157)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=330cea47-221d-439e-b106-58a146fc28ee">Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3235216f-497f-4934-81b8-1eb9929e98c9">Internet Explorer 7</a>
                    <br />(KB2675157)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ec74522-ec1e-4b3c-bfeb-6a505cc4f11a">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="4">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
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
                  </td></tr>
                <tr><td>Windows 7 for 32-bit Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a58ca0b-fad7-418e-80ae-ca478168f887">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6724be3-ff4b-4dea-95f3-0b13998b6758">Internet Explorer 9</a><br />(KB2675157)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac183b66-0247-4ae5-bda0-e8d0070917c8">Windows 7 for 32-bit Systems</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656372) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a58ca0b-fad7-418e-80ae-ca478168f887">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6724be3-ff4b-4dea-95f3-0b13998b6758">Internet Explorer 9</a><br />(KB2675157)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac183b66-0247-4ae5-bda0-e8d0070917c8">Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656373) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr><td>Windows 7 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7215f707-c536-4d81-ad66-e7bff592e400">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ff822d0-074a-409c-9174-8100618c6171">Internet Explorer 9</a><br />(KB2675157)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27226e64-266f-499e-8c57-866593fc3430">Windows 7 for x64-based Systems</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656372) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7215f707-c536-4d81-ad66-e7bff592e400">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ff822d0-074a-409c-9174-8100618c6171">Internet Explorer 9</a><br />(KB2675157)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27226e64-266f-499e-8c57-866593fc3430">Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656373) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="4">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
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
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=237d94e6-b9b9-4177-81fa-a67df2806b0e">Internet Explorer 8</a>**<br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d002bfe4-10e9-46d3-a460-06d112201ca5">Internet Explorer 9</a>**<br />(KB2675157)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54db1495-31bb-4435-a442-74e484630b8a">Windows Server 2008 R2 for x64-based Systems</a>*<br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>*<br />(KB2656372) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=237d94e6-b9b9-4177-81fa-a67df2806b0e">Internet Explorer 8</a>**<br />(KB2675157)<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d002bfe4-10e9-46d3-a460-06d112201ca5">Internet Explorer 9</a>**<br />(KB2675157)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54db1495-31bb-4435-a442-74e484630b8a">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>*<br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>*<br />(KB2656373) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>*[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr><td>Windows Server 2008 R2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7bdba902-0a6e-451e-a29b-6d0a03ff5664">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a4115bf-028b-4dcc-8995-d3341fdf42f2">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656372) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7bdba902-0a6e-451e-a29b-6d0a03ff5664">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a4115bf-028b-4dcc-8995-d3341fdf42f2">Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(KB2653956)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656373) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kriittinen)</td></tr>
              </table>


**Huomautukset Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 - tai Windows Server 2008 R2 -versioita, jos se asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoehto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Huomautus** **:** **MS12-02** **5**

\[1\] **Koskee .NET Framework 4:ää ja .NET Framework 4 Client Profilea.** .NET Framework version 4 jakelutiedostopaketeista on kaksi versiota: .NET Framework 4 and .NET Framework 4 Client Profile. .NET Framework 4 Client Profile on .NET Framework 4:n osajoukko. Haavoittuvuus, jonka tämä tietoturvapäivitys korjaa, koskee sekä .NET Framework 4:ää että .NET Framework 4 Client Profilea. Lisätietoja on MSDN-artikkelissa, jossa käsitellään [.NET Frameworkin asentamista](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Office -ohjelmistopaketit ja -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="3">Microsoft Office -ohjelmistopaketit ja -osat</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232498">
                      <strong>MS12-028</strong>
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
                  </td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft Office 2003 Service Pack 3</a>
                    <br />(Windows Common Controls -kirjasto)<br />(KB2597112) <br />(Kriittinen)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2007 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft Office 2007 Service Pack 2</a>
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fbf24cc6-89e1-48dd-bb83-23eed30195e1">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2596871)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Office 2007 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft Office 2007 Service Pack 3</a>
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2010 (32-bit edition)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23c9d7bf-c9e0-4e01-8b66-da542332a28b">Microsoft Office 2010 (32-bit edition)</a>
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598039) <br />(Kriittinen)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office 2010 Service Pack 1 (32-bittiset versiot)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23c9d7bf-c9e0-4e01-8b66-da542332a28b">Microsoft Office 2010 Service Pack 1 (32-bittiset versiot)</a>
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598039) <br />(Kriittinen)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="3">Microsoft Office Web Components</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232498">
                      <strong>MS12-028</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Web Components Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft Office 2003 Web Components Service Pack 3</a>
                    <br />(Windows Common Controls -kirjasto)<br />(KB2597112) <br />(Kriittinen)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="3">Muu Microsoft Office -ohjelmisto</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232498">
                      <strong>MS12-028</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Works 9</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94e17a66-cf09-4314-89ec-53deadabfa66">Microsoft Works 9</a>
                    <br />(KB2680317) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Works 6–9 File Converter</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4605f684-6314-4758-adeb-2a8810dfc8d1">Microsoft Works 6–9 File Converter</a>
                    <br />(KB2680326) <br />(Tärkeä)</td></tr>
              </table>


**Huomautus: MS12-027**

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

#### Microsoft Server -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft SQL Server</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft SQL Server 2000 Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=198f1819-818b-4b2e-a424-4a45729746eb">Microsoft SQL Server 2000 Analysis Services Service Pack 4</a>
                    <br />(KB983807) <br />(Kriittinen)<br /><br />GDR-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a9d97e8-79e0-4997-88fe-1224707e1b37">Microsoft SQL Server 2000 Service Pack 4</a><br />(KB983808) <br />(Kriittinen)<br /><br />QFE-päivitys:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8d0cac2f-f227-4e00-9454-4df62be86407">Microsoft SQL Server 2000 Service Pack 4</a><br />(KB983809) <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="2">Microsoft SQL Server Components</th></tr>
              
                <tr class="alternateRow"><td>Microsoft SQL Server 2005 for 32-bit Systems Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 for 32-bit Systems Service Pack 4</a>
                    [1]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2597112) <br />(Kriittinen)</td></tr>
                <tr><td>Microsoft SQL Server 2005 for Itanium-based Systems Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 for Itanium-based Systems Service Pack 4</a>
                    [1]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2597112) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2005 for x64-based Systems Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 for x64-based Systems Service Pack 4</a>
                    [1]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2597112) <br />(Kriittinen)</td></tr>
                <tr><td>Microsoft SQL Server 2005 Express Edition with Advanced Services Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 Express Edition with Advanced Services Service Pack 4</a>
                    [1]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2597112) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for 32-bit Systems Service Pack 2</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr><td>Microsoft SQL Server 2008 for 32-bit Systems Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for 32-bit Systems Service Pack 3</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for x64-based Systems Service Pack 2</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr><td>Microsoft SQL Server 2008 for x64-based Systems Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for x64-based Systems Service Pack 3</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 2</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr><td>Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 3</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 R2 for 32-bit Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 for 32-bit Systems</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr><td>Microsoft SQL Server 2008 R2 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 for 32-bit Systems Service Pack 1</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 R2 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 for x64-based Systems</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr><td>Microsoft SQL Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 R2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 for Itanium-based Systems</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
                <tr><td>Microsoft SQL Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    [2]
                    <br />(Windows Common Controls -kirjasto)<br />(KB2598041) <br />(Kriittinen)</td></tr>
              </table>


**Huomautukset** **:** **MS12-02** **7**

\[1\]Tämä päivitys on sama kuin Microsoft Office 2003:n päivitys KB2597112

\[2\]Tämä päivitys on sama kuin Microsoft Office 2007:n päivitys KB2598041

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft BizTalk Server</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft BizTalk Server 2002 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d90b78d2-551b-499b-9bd2-85b40646dbc7">Microsoft BizTalk Server 2002 Service Pack 1</a>
                    <br />(KB2645025) <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="2">Microsoft Commerce Server</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Commerce Server 2002 Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35de8833-50ae-482d-aa07-497bf68fb38e">Microsoft Commerce Server 2002 Service Pack 4</a>
                    <br />(KB2658674) <br />(Kriittinen)</td></tr>
                <tr><td>Microsoft Commerce Server 2007 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f04fb90-8f11-4392-a4bc-800903091f04">Microsoft Commerce Server 2007 Service Pack 2</a>
                    <br />(KB2658677) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft Commerce Server 2009</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8998b6b-e9a4-457e-a34f-0458dda81f2f">Microsoft Commerce Server 2009</a>
                    <br />(KB2655547) <br />(Kriittinen)</td></tr>
                <tr><td>Microsoft Commerce Server 2009 R2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9221811-8913-412b-ae04-21a55ce7c4c5">Microsoft Commerce Server 2009 R2</a>
                    <br />(KB2658676) <br />(Kriittinen)</td></tr>
              </table>


**Huomautus: MS12-027**

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

#### Microsoft-kehitystyökalut ja ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Visual FoxPro</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visual FoxPro 8.0 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a7ff474-f1e0-4c86-9555-64e8e7357890">Microsoft Visual FoxPro 8.0 Service Pack 1</a>
                    <br />(KB2647488) <br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual FoxPro 9.0 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=53c0132e-7724-4e94-abe9-e79b76ce35d7">Microsoft Visual FoxPro 9.0 Service Pack 2</a>
                    <br />(KB2647490) <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="2">Visual Basic</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Visual Basic 6.0 Runtime</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0afe933a-1e62-45c4-910c-ea94b203df5a">Visual Basic 6.0 Runtime</a>
                    <br />(KB2641426) <br />(Kriittinen)</td></tr>
              </table>


**Huomautus: MS12-027**

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

#### Microsoft Remote Access -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Forefront Unified Access Gateway</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238519">
                      <strong>MS12-026</strong>
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
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4b4ecc4-8bc6-43d0-b872-93673e0d9a6f">Microsoft Forefront Unified Access Gateway 2010 Service Pack 1</a>
                    [1]
                    <br />(KB2649261)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0f9acab-bfb8-4758-b60d-64e68a84fba0">Microsoft Forefront Unified Access Gateway 2010 Service Pack 1 Update 1</a>[1]<br />(KB2649262)<br />(Tärkeä)</td></tr>
              </table>


**Huomautus** **:** **MS12-026**

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

  - linx2008 ([AISec](http://www.aisec.cn/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-023
  - Roel Spilker ([TOPdesk](http://www.topdesk.com)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-023
  - Jose Antonio Vazquez Gonzalez (yhteistyössä [VeriSign iDefense Labs](http://labs.idefense.com)in kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-023
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com)[Zero Day Initiative](http://www.zerodayinitiative.com)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-023
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com)[Zero Day Initiative](http://www.zerodayinitiative.com)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-023
  - Masato Kinugawa teki yhteistyötä kanssamme kehittääkseen tietoturvaa koskevia muutoksia liittyen haavoittuvuuteen, joka on kuvattu tietoturvatiedotteessa MS12-023
  - Robert Zacek ja Igor Glucksmann ([Avast Software](http://www.avast.com/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-024
  - Vitali Toropov (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-025
  - Shaun Colley ([IOActive Software](http://ioactive.co.uk/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-028

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - IT-ammattilaisten tietoturvaratkaisut: [TechNetin ongelmanratkaisu- ja tukisivusto](http://technet.microsoft.com/security/bb980617,aspx)
  - Suojaa Windows-käyttöjärjestelmäsi viruksilta ja haittaohjelmilta: [Virusten ja tietoturvan ratkaisukeskus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
  - Maakohtaiset tukipalvelut: [Kansainvälinen tukipalvelu](http://support.microsoft.com/common/international.aspx)

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - Versio 1.0 (10.4.2012): Tietoturvatiedotteen yhteenveto julkaistu.
  - Versio 2.0 (26.4.2012): Lisättiin tietoturvatiedotteeseen MS12-027 SQL Server 2008 R2 Service Pack 1 -versiot taulukkoon "Ohjelmistot, joita haavoittuvuus koskee" ja tarkennettiin, että päivitys koskee kaikkia Microsoft SQL Server 2000 Analysis Services Service Pack 4 -asennuksia, koska QFE:n ja GDR:n ero ei koske tätä tuotetta. Muutokset on tarkoitettu vain tiedonannoiksi. Tietoturvapäivityksen tiedostoja tai tunnistustietoja ei muutettu. Tarvittavat päivitykset ovat olleet saatavana alkuperäisen tuotteen julkaisusta lähtien, joten asiakkaiden, jotka ovat päivittäneet järjestelmänsä, ei tarvitse tehdä mitään.

*Built at 2014-04-18T01:50:00Z-07:00*

