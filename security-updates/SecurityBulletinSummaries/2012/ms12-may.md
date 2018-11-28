---
title: Microsoftin turvatiedotteiden yhteenveto, toukokuu 2012
TOCTitle: MS12-MAY
ms:assetid: ms12-may
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms12-may(v=Security.10)
ms:contentKeyID: 61225746
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, toukokuu 2012

Julkaistu: 8. toukokuuta 2012 | Päivitetty: 22. toukokuuta 2012

**Versio:** 2.1

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo toukokuussa 2012 julkaistuista tietoturvatiedotteista.

Tämä tietoturvatiedotteiden yhteenveto korvaa toukokuun 2012 tietoturvatiedotteiden julkaisun yhteydessä tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 3. toukokuuta 2012. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 9. toukokuuta 2012, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt toukokuun tietoturvatiedotteen webcast-lähetykseen](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499667). Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://go.microsoft.com/fwlink/?linkid=217214) kertovassa englanninkielisessä sivustossa.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=248419"><strong>MS12-029</strong></a></td>
<td><strong>Microsoft Wordin haavoittuvuus saattaa sallia koodin suorittamisen etäyhteyden välityksellä (2680352)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Officen haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun RTF-tiedoston. Tätä haavoittuvuutta onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin nykyinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td><strong>Microsoft Officen, Windowsin, .NET Frameworkin ja Silverlightin yhdistetty tietoturvapäivitys (2681578)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kolme yleisessä tiedossa olevaa ja seitsemän yksityishenkilön ilmoittamaa Microsoft Officen, Microsoft Windowsin, Microsoft .NET Frameworkin ja Microsoft Silverlightin haavoittuvuutta. Vakavimmat haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun tai siirtyy haitalliseen sivustoon, joka käyttää upotettuja TrueType-fonttitiedostoja. Hyökkääjä ei pysty pakottamaan käyttäjää avaamaan haitallista Web-sivustoa. Hyökkääjä voi kuitenkin onnistua saamaan käyttäjän avaaman sivuston. Tämä tapahtuu yleensä napsauttamalla sähköpostiviestissä olevaa linkkiä tai pikaviestinviestiä, joka avaa hyökkääjän sivuston.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows, Microsoft .NET Framework, Microsoft Silverlight,<br />
Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246970"><strong>MS12-035</strong></a></td>
<td><strong>.NET Frameworkin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (2693777)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa .NET Frameworkin haavoittuvuutta. Haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä asiakasjärjestelmässä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua verkkosivua selaimella, jossa voidaan suorittaa XAML-selainsovelluksia (XBAP). Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td><strong>Microsoft</strong> <strong>Officen</strong> <strong>haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (2663830)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yhden yleisessä tiedossa olevan ja viisi yksityishenkilön ilmoittamaa Microsoft Officen haavoittuvuutta. Haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Office-tiedoston. Näitä haavoittuvuuksia onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin järjestelmään kirjautunut käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=248385"><strong>MS12-031</strong></a></td>
<td><strong>Microsoft Visio Viewer 2010:n haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2597981)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Officen haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Visio-tiedoston. Tätä haavoittuvuutta onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin nykyinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246964"><strong>MS12-032</strong></a></td>
<td><strong>TCP/IP:n haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen (2688338)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yhden yksityishenkilön ilmoittaman ja yhden yleisesti tiedossa olevan Microsoft Windowsin haavoittuvuuden. Vakavin näistä haavoittuvuuksista saattaa sallia käyttöoikeuksien laajentamisen, jos hyökkääjä kirjautuu järjestelmään ja suorittaa tietyllä tavalla muodostetun sovelluksen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=247902"><strong>MS12-033</strong></a></td>
<td><strong>Windowsin osioinninhallinnan haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen (2690533)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen, jos hyökkääjä kirjautuu järjestelmään ja suorittaa tietyllä tavalla muodostetun sovelluksen. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja pystyttävä kirjautumaan paikallisesti, jotta hän pystyy hyödyntämään tätä haavoittuvuutta.</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=248419"><strong>MS12-029</strong></a></td>
<td>RTF-vastaavuuden haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0183">CVE-2012-0183</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td>Excel-tiedostomuodon muistin vioittumishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0141">CVE-2012-0141</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td>Excel-tiedostomuodon muistin vioittumishaavoittuvuus OBJECTLINK-tietueessa</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0142">CVE-2012-0142</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td>Excel-muistin käytön haavoittuvuus käytettäessä useita muokattuja bittejä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0143">CVE-2012-0143</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>Haavoittuvuus koskee vain Microsoft Office 2003 -versiota.<br />
<br />
Tämä haavoittuvuus on ollut yleisessä tiedossa</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td>Excelin SXLI-tietueen muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0184">CVE-2012-0184</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td>Excelin solujen yhdistämisen keon ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0185">CVE-2012-0185</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Hyväksikäyttökoodia on vaikea laatia</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Hyväksikäyttökoodia on vaikea laatia</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td>Excel-tietueen jäsennystyypin vastaavuuden haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1847">CVE-2012-1847</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=248385"><strong>MS12-031</strong></a></td>
<td>VSD-tiedostomuodon muistin vioittumishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0018">CVE-2012-0018</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei koske</td>
<td>Ei käytössä</td>
<td>Koskee Visio Viewer 2010- ja Visio Viewer 2010 Service Pack 1 -versioita (Visio-katseluohjelman tuetut versiot).</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246964"><strong>MS12-032</strong></a></td>
<td>Windowsin palomuurin ohittamishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0174">CVE-2012-0174</a></td>
<td>Ei käytössä</td>
<td>Ei käytössä</td>
<td>Ei käytössä</td>
<td>Tämä on tietoturvatoiminnon ohittamishaavoittuvuus.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246964"><strong>MS12-032</strong></a></td>
<td>TCP/IP:n kaksinkertaisen muistinvapautuksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0179">CVE-2012-0179</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei koske</td>
<td>Pysyvä</td>
<td>Tämä haavoittuvuus on ollut yleisessä tiedossa</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=247902"><strong>MS12-033</strong></a></td>
<td>Plug and Play Configuration Managerin haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0178">CVE-2012-0178</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Väliaikainen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td>Haavoittuvuus TrueType-fontin jäsennyksessä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402">CVE-2011-3402</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>Tämä haavoittuvuus on ollut yleisessä tiedossa</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td>Haavoittuvuus TrueType-fontin jäsennyksessä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0159">CVE-2012-0159</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td>.NET Frameworkin puskurin varaamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0162">CVE-2012-0162</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei koske</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td>GDI+-tietuetyypin haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0165">CVE-2012-0165</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Hyväksikäyttökoodia on vaikea laatia</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td>GDI+-keon ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0167">CVE-2012-0167</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td>Silverlightin kaksinkertaisen muistinvapautuksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0176">CVE-2012-0176</a></td>
<td>Ei koske</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td>Windowsin viestien haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0180">CVE-2012-0180</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td>Näppäimistön asettelutiedoston haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0181">CVE-2012-0181</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Hyväksikäyttökoodi epätodennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>Tämä haavoittuvuus on ollut yleisessä tiedossa</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td>Siirtymispalkin laskennan haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1848">CVE-2012-1848</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Pysyvä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246970"><strong>MS12-035</strong></a></td>
<td>.NET Frameworkin sarjoituksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0160">CVE-2012-0160</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Hyväksikäyttökoodi todennäköinen</td>
<td>Ei käytössä</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246970"><strong>MS12-035</strong></a></td>
<td>.NET Frameworkin sarjoituksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0161">CVE-2012-0161</a></td>
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
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246970">
                      <strong>MS12-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246964">
                      <strong>MS12-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=247902">
                      <strong>MS12-033</strong>
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
                  </td><td>Ei mitään</td><td>Ei mitään</td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b2ea7a8d-a537-441c-8e80-2ba4ac37e320">Windows XP Service Pack 3</a>
                    <br />(KB2660649)<br />(vain Tablet PC Edition 2005 Service Pack 3) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a4db1b4-15b2-4fae-83c4-a86331425c9e">Windows XP Service Pack 3</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8d341077-8fcd-4666-a27e-2141a04a321e">Windows XP Service Pack 3</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=954e8ae9-9247-496a-bbde-76981c49e3b3">Windows XP Service Pack 3</a><br />(KB2686509)<br />(Tärkeä) <br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2656407) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0803633-7fda-4862-a908-3450180cdaaa">Microsoft .NET Framework 1.0 Service Pack 3</a>
                    <br />(KB2604042) <br />(vain Media Center Edition 2005 Service Pack 3 ja Tablet PC Edition 2005 Service Pack 3) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846">Microsoft .NET Framework 1.1 Service Pack 1</a><br />(KB2656353) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2604092) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2604110) <br />(Kriittinen) <br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2604111) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ebaccbc-512b-4f2f-bf2a-8958f012e13f">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0357165-4400-40a6-a7a4-7b762a1793ba">Windows XP Professional x64 Edition Service Pack 2</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3b1568f-d7ad-4e6e-b45b-53b16b303d9d">Windows XP Professional x64 Edition Service Pack 2</a><br />(KB2686509) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2656407) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2604092) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2604110) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2604111) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="5">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246970">
                      <strong>MS12-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246964">
                      <strong>MS12-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=247902">
                      <strong>MS12-033</strong>
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
                  </td><td>Ei mitään</td><td>Ei mitään</td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc7bfb79-8eaf-4c22-b1c9-e774c55eb06d">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6287b994-041f-45b7-a230-d689bf1901a8">Windows Server 2003 Service Pack 2</a><br />(KB2676562)<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=167e8c49-f9f6-488b-86ad-4056d3d20213">Windows Server 2003 Service Pack 2</a><br />(KB2686509)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2656407) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0df42a4-7444-4da6-a9b2-35a56bdc64a4">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2604078) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2604092) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2604110) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2604111) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf7c9aea-dc18-499f-b456-2c29e9a74a15">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f9f49cd0-24db-4438-afde-aa7113ec2035">Windows Server 2003 x64 Edition Service Pack 2</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4614161c-ae05-43ad-8dd3-85975ec2bc4c">Windows Server 2003 x64 Edition Service Pack 2</a><br />(KB2686509)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2656407) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2604092) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2604110) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2604111) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6414b607-6fb1-4527-b218-c3cb5adfd4d1">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2563425d-4f6e-4f33-b775-a8d421b0e254">Windows Server 2003 with SP2 for Itanium-based Systems</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67f659ee-0d28-40f3-ae2f-f8fceeac8bff">Windows Server 2003 with SP2 for Itanium-based Systems</a><br />(KB2686509) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2604092) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2604111) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="5">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246970">
                      <strong>MS12-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246964">
                      <strong>MS12-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=247902">
                      <strong>MS12-033</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e11d8738-379a-4dfe-b21c-495041d9523a">Windows Vista Service Pack 2</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8068e95-ac4d-45e8-84b7-b12d633c70b5">Windows Vista Service Pack 2</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=02c857c6-5dfa-46fb-adef-35eac2bf5f41">Windows Vista Service Pack 2</a><br />(KB2660649) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=292d1f3b-a065-4d7d-9046-f35ab7f0591b">Windows Vista Service Pack 2</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2656409) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2604094) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2604105) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2604111) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1dc6e10-34eb-45ea-92b3-9983c00f6cb5">Windows Vista Service Pack 2</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9d5e290-dc57-4587-b31d-706b541924ec">Windows Vista Service Pack 2</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=838f588b-2a0d-4dae-b54d-782e6985fd83">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3bde7f59-163c-4491-abc9-a822daa8142f">Windows Vista x64 Edition Service Pack 2</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f97c5a4-62ee-4e4f-8811-a43545d76327">Windows Vista x64 Edition Service Pack 2</a><br />(KB2660649) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f90c09c-a2cb-4adb-ace7-a8bc38d78ba6">Windows Vista x64 Edition Service Pack 2</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2656409) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2604094) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2604105) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2604111) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d65565d4-d865-438a-bfb7-d71af9dd884e">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=827b9f15-b67d-4dd4-a39b-7c148bae5041">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="5">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246970">
                      <strong>MS12-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246964">
                      <strong>MS12-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=247902">
                      <strong>MS12-033</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=360adbed-a451-44ed-8675-ca5624ef1cf3">Windows Server 2008 for 32-bit Systems Service Pack 2</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47a0df29-f42e-463b-9c15-a93385ff8705">Windows Server 2008 for 32-bit Systems Service Pack 2</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=278c378b-6ee4-4f80-b9c3-ede885f4bbda">Windows Server 2008 for 32-bit Systems Service Pack 2</a>[3]<br />(KB2660649) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=728a84b9-c1b8-46e2-8365-1b542963508a">Windows Server 2008 for 32-bit Systems Service Pack 2</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2656409) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2604094) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2604105) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2604111) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ef72aab-7fd2-4330-bb6a-0c77c3943345">Windows Server 2008 for 32-bit Systems Service Pack 2</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46e6e960-b700-4154-b91d-aca74ea9e5df">Windows Server 2008 for 32-bit Systems Service Pack 2</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5a6d617-8ef6-42fa-a325-c15fa7ece7aa">Windows Server 2008 for x64-based Systems Service Pack 2</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e6d29e1-17fc-4670-9e69-988c040f06e2">Windows Server 2008 for x64-based Systems Service Pack 2</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98c4ac87-eec2-4e02-b0e1-00626bcb0ffd">Windows Server 2008 for x64-based Systems Service Pack 2</a>[3]<br />(KB2660649) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab897da8-a927-42eb-87da-1e5cd820f4c0">Windows Server 2008 for x64-based Systems Service Pack 2</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2656409) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2604094) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb">Microsoft .NET Framework 3.0 Service Pack 2</a><br />(KB2604105) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2604111) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9569d980-766d-4825-bd1c-f30c93d4b035">Windows Server 2008 for x64-based Systems Service Pack 2</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e4ab05ae-3a1c-4d6b-8c84-1165ed741356">Windows Server 2008 for x64-based Systems Service Pack 2</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c65df271-8b7d-46d3-81b3-87c0ad05e8d0">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11da5031-1733-43ea-9204-294eb483c858">Windows Server 2008 for Itanium-based Systems Service Pack 2</a><br />(KB2676562) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656353) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2604094) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2604111) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c5f7ee25-2fc1-44c7-b3e6-e2c969ecf1bc">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c081b058-b95e-4467-a2fc-fb1a68345c8f">Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="5">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246970">
                      <strong>MS12-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246964">
                      <strong>MS12-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=247902">
                      <strong>MS12-033</strong>
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
                  </td></tr>
                <tr><td>Windows 7 for 32-bit Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4d52649-4afc-4c01-b275-93818152f6b7">Windows 7 for 32-bit Systems</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31607fd8-fae8-47a0-971e-0e68be67fb5a">Windows 7 for 32-bit Systems</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35443cfc-0f51-412a-a9d9-91bfb19d805e">Windows 7 for 32-bit Systems</a><br />(KB2660649) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=572af8d4-effb-41a6-8448-7576b03f18fd">Windows 7 for 32-bit Systems</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a">Microsoft .NET Framework 3.5.1</a><br />(KB2656410) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2604114) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46b8749e-3d8f-472f-a1ea-419f44c6bc00">Windows 7 for 32-bit Systems</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a4433e4-7f3f-4083-b3e1-eff2d18483af">Windows 7 for 32-bit Systems</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for 32-bit Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4d52649-4afc-4c01-b275-93818152f6b7">Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31607fd8-fae8-47a0-971e-0e68be67fb5a">Windows 7 for 32-bit Systems Service Pack 1</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35443cfc-0f51-412a-a9d9-91bfb19d805e">Windows 7 for 32-bit Systems Service Pack 1</a><br />(KB2660649) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=572af8d4-effb-41a6-8448-7576b03f18fd">Windows 7 for 32-bit Systems Service Pack 1</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944">Microsoft .NET Framework 3.5.1</a><br />(KB2656411) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2604115) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46b8749e-3d8f-472f-a1ea-419f44c6bc00">Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a4433e4-7f3f-4083-b3e1-eff2d18483af">Windows 7 for 32-bit Systems Service Pack 1</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr><td>Windows 7 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7aa0b61b-b42c-4d60-8a7f-c61cbd25d6d9">Windows 7 for x64-based Systems</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa38b001-eef8-4153-b077-ea524e8a1e18">Windows 7 for x64-based Systems</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e551e0f-3f02-49ee-a5a1-8a7480722a6b">Windows 7 for x64-based Systems</a><br />(KB2660649) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c09cbb73-7814-4946-8c0a-323d304dd633">Windows 7 for x64-based Systems</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a">Microsoft .NET Framework 3.5.1</a><br />(KB2656410) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2604114) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e89fb3f1-44cb-4fc0-bbc2-8e94d6933322">Windows 7 for x64-based Systems</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dfa13df5-9e4e-4cf6-b56d-af7db0a0f5ea">Windows 7 for x64-based Systems</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7aa0b61b-b42c-4d60-8a7f-c61cbd25d6d9">Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa38b001-eef8-4153-b077-ea524e8a1e18">Windows 7 for x64-based Systems Service Pack 1</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e551e0f-3f02-49ee-a5a1-8a7480722a6b">Windows 7 for x64-based Systems Service Pack 1</a><br />(KB2660649) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c09cbb73-7814-4946-8c0a-323d304dd633">Windows 7 for x64-based Systems Service Pack 1</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944">Microsoft .NET Framework 3.5.1</a><br />(KB2656411) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2604115) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e89fb3f1-44cb-4fc0-bbc2-8e94d6933322">Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dfa13df5-9e4e-4cf6-b56d-af7db0a0f5ea">Windows 7 for x64-based Systems Service Pack 1</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="5">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246970">
                      <strong>MS12-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246964">
                      <strong>MS12-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=247902">
                      <strong>MS12-033</strong>
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
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f815b10-c60d-4e9b-8283-494036985e93">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a">Windows Server 2008 R2 for x64-based Systems</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6dab7283-81ba-4362-adb1-0db25e1f055e">Windows Server 2008 R2 for x64-based Systems</a>[4]<br />(KB2660649) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd">Windows Server 2008 R2 for x64-based Systems</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a">Microsoft .NET Framework 3.5.1</a><br />(KB2656410) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2604114) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f815b10-c60d-4e9b-8283-494036985e93">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6dab7283-81ba-4362-adb1-0db25e1f055e">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>[4]<br />(KB2660649) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a><br />(KB2676562) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944">Microsoft .NET Framework 3.5.1</a><br />(KB2656411) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a>[1]<br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2604115) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2008 R2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9172218-8a3f-4b0f-a14d-64db3778f4cc">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9abec73-150e-40cf-a108-1d8ee89aac92">Windows Server 2008 R2 for Itanium-based Systems</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e075c03e-91db-4974-a6ea-8edeba583293">Windows Server 2008 R2 for Itanium-based Systems</a><br />(KB2676562) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2604114) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34643abe-2905-4ac1-a5f3-3f6ea8724b7a">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b66a74a-7022-49ac-89da-8c9ab8105812">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9172218-8a3f-4b0f-a14d-64db3778f4cc">Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(KB2658846) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9abec73-150e-40cf-a108-1d8ee89aac92">Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a><br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e075c03e-91db-4974-a6ea-8edeba583293">Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a><br />(KB2676562) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2604115) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34643abe-2905-4ac1-a5f3-3f6ea8724b7a">Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b66a74a-7022-49ac-89da-8c9ab8105812">Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
              
                <tr><th colspan="5">Server Core -asennusvalinta</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246970">
                      <strong>MS12-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246964">
                      <strong>MS12-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=247902">
                      <strong>MS12-033</strong>
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
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47a0df29-f42e-463b-9c15-a93385ff8705">Windows Server 2008 for 32-bit Systems Service Pack 2</a>
                    <br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=728a84b9-c1b8-46e2-8365-1b542963508a">Windows Server 2008 for 32-bit Systems Service Pack 2</a><br />(KB2676562) <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ef72aab-7fd2-4330-bb6a-0c77c3943345">Windows Server 2008 for 32-bit Systems Service Pack 2</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46e6e960-b700-4154-b91d-aca74ea9e5df">Windows Server 2008 for 32-bit Systems Service Pack 2</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e6d29e1-17fc-4670-9e69-988c040f06e2">Windows Server 2008 for x64-based Systems Service Pack 2</a>
                    <br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab897da8-a927-42eb-87da-1e5cd820f4c0">Windows Server 2008 for x64-based Systems Service Pack 2</a><br />(KB2676562) <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9569d980-766d-4825-bd1c-f30c93d4b035">Windows Server 2008 for x64-based Systems Service Pack 2</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e4ab05ae-3a1c-4d6b-8c84-1165ed741356">Windows Server 2008 for x64-based Systems Service Pack 2</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd">Windows Server 2008 R2 for x64-based Systems</a><br />(KB2676562) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a">Microsoft .NET Framework 3.5.1</a><br />(KB2656410) <br />(Ei luokitusta[2])</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2604114) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850">Windows Server 2008 R2 for x64-based Systems</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for x64-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2659262) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a><br />(KB2676562) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944">Microsoft .NET Framework 3.5.1</a><br />(KB2656411) <br />(Ei luokitusta[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648">Microsoft .NET Framework 4</a><br />(KB2656405) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2604115) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8">Microsoft .NET Framework 4</a>[1]<br />(KB2604121) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2688338) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850">Windows Server 2008 R2 for x64-based Systems Service Pack 1</a>
                    <br />(KB2690533) <br />(Tärkeä)</td></tr>
              </table>


**Huomautukset** **:** **MS12-034**

\[1\] **Koskee .NET Framework 4:ää ja .NET Framework 4 Client Profilea.** .NET Framework version 4 jakelutiedostopaketeista on kaksi versiota: .NET Framework 4 and .NET Framework 4 Client Profile. .NET Framework 4 Client Profile on .NET Framework 4:n osajoukko. Haavoittuvuus, jonka tämä tietoturvapäivitys korjaa, koskee sekä .NET Framework 4:ää että .NET Framework 4 Client Profilea. Lisätietoja on MSDN-artikkelissa, jossa käsitellään [.NET Frameworkin asentamista](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

\[2\]Tällä päivityksellä ei ole luokitusta, koska tällä hetkellä ei tunneta yhtään hyökkäystapaa, jolla hyökkääjä voisi hyödyntää tiedotteessa kuvattua haavoittuvuutta. Microsoft kuitenkin suosittelee, että ohjelmiston käyttäjät asentavat tämän tietoturvapäivityksen.

\[3\]Tämä päivitys koskee vain Windows Server 2008 -järjestelmiä, joissa on asennettuna ja käytössä valinnainen Työpöytäympäristö-toiminto. Lisätietoja on päivityksen MS12-034 usein kysytyissä kysymyksissä.

\[4\]Tämä päivitys koskee vain Windows Server 2008 R2 -järjestelmiä, joissa on asennettuna ja käytössä valinnaisen käsinkirjoitustoiminnon Ink Support -komponentti. Lisätietoja on päivityksen MS12-034 usein kysytyissä kysymyksissä.

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

**Huomautus** **:** **MS12-0** **35**

\[1\] **Koskee .NET Framework 4:ää ja .NET Framework 4 Client Profilea.** .NET Framework version 4 jakelutiedostopaketeista on kaksi versiota: .NET Framework 4 and .NET Framework 4 Client Profile. .NET Framework 4 Client Profile on .NET Framework 4:n osajoukko. Haavoittuvuus, jonka tämä tietoturvapäivitys korjaa, koskee sekä .NET Framework 4:ää että .NET Framework 4 Client Profilea. Lisätietoja on MSDN-artikkelissa, jossa käsitellään [.NET Frameworkin asentamista](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Office -ohjelmistopaketit ja -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="5">Microsoft Office -ohjelmistopaketit ja -osat</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=248419">
                      <strong>MS12-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238499">
                      <strong>MS12-030</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=248385">
                      <strong>MS12-031</strong>
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
                  </td><td>Ei mitään</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9819899d-7f7f-4ddd-9fc8-816a57d2979e">Microsoft Word 2003 Service Pack 3</a>
                    <br />(KB2598332) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0abbf09c-8828-4524-8b38-e34faefa2ae4">Microsoft Office 2003 Service Pack 3</a>
                    <br />(KB2598253) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=162901b1-4c1d-476f-99e9-218780897f92">Microsoft Excel 2003 Service Pack 3</a>
                    <br />(KB2597086) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2007 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c6f79d01-8735-4b0f-a50b-90cde3fba4ee">Microsoft Word 2007 Service Pack 2</a>
                    [1]
                    <br />(KB2596917) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9a27671-883a-4ab7-b86f-99730a9af729">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2596672) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa054591-b202-47f2-9610-f3cd288d34c0">Microsoft Office 2007 Service Pack 2</a><br />(KB2596792) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22b9b3a6-ad09-4397-892c-2190a86baf3e">Microsoft Excel 2007 Service Pack 2</a>
                    [1]
                    <br />(KB2597161) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ff6650c-eaf4-4c7d-986c-c4d9e5324dac">Microsoft Office 2007 Service Pack 2</a><br />(KB2597969)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office 2007 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c6f79d01-8735-4b0f-a50b-90cde3fba4ee">Microsoft Word 2007 Service Pack 3</a>
                    [1]
                    <br />(KB2596917) <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9a27671-883a-4ab7-b86f-99730a9af729">Microsoft Office 2007 Service Pack 3</a>
                    <br />(KB2596672) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa054591-b202-47f2-9610-f3cd288d34c0">Microsoft Office 2007 Service Pack 3</a><br />(KB2596792) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22b9b3a6-ad09-4397-892c-2190a86baf3e">Microsoft Excel 2007 Service Pack 3</a>
                    [1]
                    <br />(KB2597161) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ff6650c-eaf4-4c7d-986c-c4d9e5324dac">Microsoft Office 2007 Service Pack 3</a><br />(KB2597969) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2010 (32-bit edition)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c355d598-ff4d-4cac-afa9-2de3236a7d71">Microsoft Office 2010 (32-bit edition)</a>
                    <br />(KB2589337) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f537f6d0-be63-42af-8b39-fa6f38715f84">Microsoft Excel 2010 (32-bittiset versiot)</a>
                    <br />(KB2597166) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e1060fa-c43d-42df-be5f-f536d9b39ba4">Microsoft Office 2010 (32-bit edition)</a><br />(KB2553371) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office 2010 Service Pack 1 (32-bittiset versiot)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c355d598-ff4d-4cac-afa9-2de3236a7d71">Microsoft Office 2010 Service Pack 1 (32-bittiset versiot)</a>
                    <br />(KB2589337) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f537f6d0-be63-42af-8b39-fa6f38715f84">Microsoft Excel 2010 Service Pack 1 (32-bittiset versiot)</a>
                    <br />(KB2597166) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e1060fa-c43d-42df-be5f-f536d9b39ba4">Microsoft Office 2010 Service Pack 1 (32-bittiset versiot)</a><br />(KB2553371) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2010 (64-bit edition)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91619bcc-9d5d-4011-a185-c405758782be">Microsoft Office 2010 (64-bit edition)</a>
                    <br />(KB2589337) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=123b96d9-de3f-4aab-bcf8-bf9089fef400">Microsoft Excel 2010 (64-bittiset versiot)</a>
                    <br />(KB2597166) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec4371f6-644d-430d-880f-12425f1b36d4">Microsoft Office 2010 (64-bit edition)</a><br />(KB2553371) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office 2010 Service Pack 1 (64-bittiset versiot)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91619bcc-9d5d-4011-a185-c405758782be">Microsoft Office 2010 Service Pack 1 (64-bittiset versiot)</a>
                    <br />(KB2589337) <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=123b96d9-de3f-4aab-bcf8-bf9089fef400">Microsoft Excel 2010 Service Pack 1 (64-bittiset versiot)</a>
                    <br />(KB2597166) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec4371f6-644d-430d-880f-12425f1b36d4">Microsoft Office 2010 Service Pack 1 (64-bittiset versiot)</a><br />(KB2553371) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="5">Microsoft Office for Mac</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=248419">
                      <strong>MS12-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238499">
                      <strong>MS12-030</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=248385">
                      <strong>MS12-031</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f85fc23-480e-4835-9ce5-0aa56702ef59">Microsoft Office 2008 for Mac</a>
                    <br />(KB2665346) <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f85fc23-480e-4835-9ce5-0aa56702ef59">Microsoft Office 2008 for Mac</a>
                    <br />(KB2665346) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Office for Mac 2011</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d88d3d4-89bd-44c3-9e5a-657998223e2f">Microsoft Office for Mac 2011</a>
                    <br />(KB2665351) <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d88d3d4-89bd-44c3-9e5a-657998223e2f">Microsoft Office for Mac 2011</a>
                    <br />(KB2665351) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="5">Muu Microsoft Office -ohjelmisto</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=248419">
                      <strong>MS12-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238499">
                      <strong>MS12-030</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=248385">
                      <strong>MS12-031</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
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
                <tr class="alternateRow"><td>Microsoft Excel Viewer</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9dedfb18-a651-49f7-b1fc-78f7b6cb234a">Microsoft Excel Viewer</a>
                    [2]
                    <br />(KB2596842) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Visio Viewer 2010</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d21d110-c787-49b6-8384-6eaf9da5a38f">Microsoft Visio Viewer 2010 (32-bittinen versio)</a>
                    <br />(KB2597981) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d21d110-c787-49b6-8384-6eaf9da5a38f">Microsoft Visio Viewer 2010 Service Pack 1 (32-bittinen versio)</a><br />(KB2597981) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=331d8247-559c-4040-bdea-84cb6fd5dee2">Microsoft Visio Viewer 2010 (64-bittinen versio)</a><br />(KB2597981) <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=331d8247-559c-4040-bdea-84cb6fd5dee2">Microsoft Visio Viewer 2010 Service Pack 1 (64-bittinen versio)</a><br />(KB2597981) <br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Officen yhteensopivuuspaketti Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80d5a86a-33b0-4464-af76-0fe13bd07a5c">Microsoft Officen yhteensopivuuspaketti Service Pack 2</a>
                    <br />(KB2596880) <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8386ad9-635f-45a7-b33e-ac9a3ca55f82">Microsoft Officen yhteensopivuuspaketti Service Pack 2</a>
                    <br />(KB2597162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Microsoft Officen yhteensopivuuspaketti Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80d5a86a-33b0-4464-af76-0fe13bd07a5c">Microsoft Officen yhteensopivuuspaketti Service Pack 3</a>
                    <br />(KB2596880) <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8386ad9-635f-45a7-b33e-ac9a3ca55f82">Microsoft Officen yhteensopivuuspaketti Service Pack 3</a>
                    <br />(KB2597162) <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              </table>


**Huomautus: MS12-0** **29**

\[1\]Microsoft Word 2007: tietoturvapaketin KB2596917 lisäksi asiakkaiden on asennettava Microsoft Office Compatibility Packin tietoturvapäivitys (KB2596880), jolla suojaudutaan tässä tiedotteessa kuvatulta haavoittuvuudelta.

**Huomautukset:** **MS12-0** **30**

\[1\]Microsoft Excel 2007: tietoturvapaketin KB2597161 lisäksi asiakkaiden on asennettava Microsoft Office Compatibility Packin tietoturvapäivitys (KB2597162), jolla suojaudutaan tässä tiedotteessa kuvatuilta haavoittuvuuksilta.

\[ 2 \]Microsoft Excel Viewer on päivitettävä tuetulle Service Pack -päivitystasolle (Excel Viewer 2007 Service Pack 2 tai Excel Viewer 2007 Service Pack 3) ennen tämän päivityksen asentamista. Lisätietoja tuetuista Office-katseluohjelmista on [Microsoft Knowledge Base -artikkelissa 979860](http://support.microsoft.com/kb/979860).

**Huomautus** **:** **MS12-0** **3** **4**

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

#### Microsoft-kehitystyökalut ja ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Silverlight 4</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Silverlight 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b">Microsoft Silverlight 4</a> asennettuna Macintosh-järjestelmään<br />(KB2690729) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b">Microsoft Silverlight 4</a> asennettuna tuettuihin Microsoft Windows -asiakkaaseen<br />(KB2690729) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b">Microsoft Silverlight 4</a> asennettuna Microsoft Windows -palvelimeen<br />(KB2690729) <br />(Kriittinen)</td></tr>
              
                <tr><th colspan="2">Microsoft Silverlight 5</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251038">
                      <strong>MS12-034</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Silverlight 5</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63">Microsoft Silverlight 5</a> asennettuna Macintosh-järjestelmään<br />(KB2636927) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63">Microsoft Silverlight 5</a> asennettuna tuettuun Microsoft Windows -työpöytäversioon<br />(KB2636927) <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63">Microsoft Silverlight 5</a> asennettuna tuettuun Microsoft Windows -palvelimeen<br />(KB2636927) <br />(Kriittinen)</td></tr>
              </table>


**Huomautus** **:** **MS12-0** **3** **4**

Lisää saman tietoturvatiedotteen päivitystiedostoja on **Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot** -kohdan muiden ohjelmistojen kohdalla. Tietoturvatiedote kattaa useita ohjelmistoluokkia.

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

  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-029
  - [Omair](http://krash.in/) ilmoitti kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS12-030
  - Omair (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-030
  - Sean Larsson ja Jun Mao (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoittivat kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS12-030
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/)n kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-030
  - Luigi Auriemma (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-031
  - Bojan Zdrnja ([INFIGO IS](http://www.infigo.hr/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-032
  - Anatoli Glagolev ([Genesys Telecommunications](http://www.genesyslab.com/)) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS12-032
  - Alin Rad Pop (yhteistyössä [Tipping Pointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-034
  - Vitali Toropov (yhteistyössä [Tipping Pointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-034
  - [Omair](http://krash.in/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-034.
  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-034
  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-034
  - Alex Plaskett ([MWR InfoSecurity](http://www.mwrinfosecurity.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-034
  - Tarjei Mandt ([Azimuth Security](http://www.azimuthsecurity.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-034
  - Nicolas Economou ([Core Security Technologies](http://www.coresecurity.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-034
  - Geoff McDonald (Symantec) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-034
  - h4ckmp ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS12-034.
  - James Forshaw ([Context Information Security](http://www.contextis.co.uk/)) ilmoitti kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS12-035.

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - IT-ammattilaisten tietoturvaratkaisut: [TechNetin ongelmanratkaisu- ja tukisivusto](http://technet.microsoft.com/security/bb980617,aspx)
  - Suojaa Windows-käyttöjärjestelmäsi viruksilta ja haittaohjelmilta: [Virusten ja tietoturvan ratkaisukeskus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
  - Maakohtaiset tukipalvelut: [Kansainvälinen tukipalvelu](http://support.microsoft.com/common/international.aspx)

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - Versio 1.0 (8.5.2012): Tietoturvatiedotteen yhteenveto julkaistu.
  - Versio 1.1 (9.5.2012): Päivitettiin tiedote CVE-2012-1847 **Hyödyntämisindeksissä**.
  - Versio 2.0 (11.5.2012): Tietoturvatiedotteessa MS12-035 korjattiin tietoturvapäivityksen numeroksi KB2656353 kaikissa tuetuissa järjestelmissä, joissa on käytössä Microsoft .NET Framework 1.1 Service Pack 1, lukuun ottamatta Windows Server 2003 Service Pack 2 -asennuksia. Tietoturvapäivityksen tiedostoja ei muutettu. Asiakkaiden, jotka ovat päivittäneet järjestelmänsä, ei tarvitse tehdä mitään.
  - Versio 2.1 (22.5.2012): Tietoturvatiedotteeseen MS12-034 lisättiin tietoturvapäivitystä KB2660649 koskevat alaviitteet Windows Server 2008- ja Windows Server 2008 R2 -järjestelmiä varten. Tietoturvapäivityksen tiedostoja ei muutettu. Asiakkaiden, jotka ovat päivittäneet järjestelmänsä, ei tarvitse tehdä mitään.

*Built at 2014-04-18T01:50:00Z-07:00*

