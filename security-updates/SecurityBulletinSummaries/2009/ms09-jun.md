---
title: Microsoftin turvatiedotteiden yhteenveto, kesäkuu 2009
TOCTitle: MS09-JUN
ms:assetid: ms09-jun
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms09-jun(v=Security.10)
ms:contentKeyID: 61225636
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, kesäkuu 2009

Julkaistu: 9. kesäkuuta 2009

**Versio:** 1.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo kesäkuussa 2009 julkaistuista tietoturvatiedotteista.

Kesäkuun 2009 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 5. kesäkuuta 2009. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 10. kesäkuuta 2009, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt kesäkuun tietoturvatiedotteen web-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032395225) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=151361">MS09-018</a></td>
<td><strong>Active Directoryn haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (971055)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa Microsoft Windows 2000 Server- tai Windows Server 2003 -käyttöjärjestelmään asennetun Active Directoryn sekä Windows XP Professional- tai Windows Server 2003 -käyttöjärjestelmään asennetun ADAM:n (Active Directory Application Mode) haavoittuvuuden. Vakavin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän verkon välityksellä. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Palomuurikäytännöistä ja palomuurin vakiomäärityksistä annetut toimintaohjeet suojaavat verkkoa hyökkäyksiltä, joiden lähde on yritysverkon ulkopuolella. Parhaissa käytännöissä suositellaan, että Internetiin yhteydessä olevissa järjestelmissä on avoinna mahdollisimman vähän portteja.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141786">MS09-022</a></td>
<td><strong>Windowsin taustatulostuksen haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (961501)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kolme yksityishenkilön ilmoittamaa Windowsin taustatulostuksen haavoittuvuutta. Vakavin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos palvelin, jota haavoittuvuus koskee, vastaanottaa tietyllä tavalla muodostetun RPC-pyynnön. Palomuurikäytännöistä ja palomuurin vakiomäärityksistä annetut toimintaohjeet suojaavat verkkoa hyökkäyksiltä, joiden lähde on yritysverkon ulkopuolella. Parhaissa käytännöissä suositellaan, että Internetiin yhteydessä olevissa järjestelmissä on avoinna mahdollisimman vähän portteja.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td><strong>Internet Explorerin kumulatiivi</strong> <strong>nen tietoturvapäivitys (969897)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa seitsemän yksityishenkilön ilmoittamaa Internet Explorerin haavoittuvuutta ja yhden yleisessä tiedossa olevan haavoittuvuuden. Vakavin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun sivun Internet Explorerissa. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147416">MS09-027</a></td>
<td><strong>Microsoft Office Wordin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (969514)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa haavoittuvuutta, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Word-tiedoston. Hyödyntämällä jompaakumpaa haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td><strong>Microsoft Office Excelin haavoittuv</strong> <strong>uudet saattavat sallia koodin suorittamisen verkon välityksellä (969462)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa useita yksityishenkilön ilmoittamia haavoittuvuuksia, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Excel-tiedoston. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128104">MS09-024</a></td>
<td><strong>Microsoft Works -muuntajien haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (957632)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Officen haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun Works-tiedoston. Tätä haavoittuvuutta onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin paikallinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150174">MS09-026</a></td>
<td><strong>Etäproseduurikutsun haavoittuvuus sa</strong> <strong>attaa sallia käyttöoikeuksien korottamisen (970238)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Windowsin RPC-toiminnon haavoittuvuuden, jossa RPC-järjestelymoduuli ei päivitä sisäistä tilaansa asianmukaisesti. Haavoittuvuus saattaa antaa hyökkääjän suorittaa haluamaansa koodia ja ottaa haavoittuvuuden sisältävän järjestelmän kokonaan hallintaansa. Microsoft Windowsin tuettujen versioiden mukana ei toimiteta sellaisia RPC-palvelimia tai -asiakkaita, joissa on tätä haavoittuvuutta voi hyödyntää. Jos käyttäjä käyttää oletuskokoonpanoa, hyökkääjä ei voi hyödyntää tätä haavoittuvuutta. Tämä haavoittuvuus kuitenkin esiintyy Microsoft Windowsin RPC-palvelussa ja se voi vaikuttaa muiden valmistajien RPC-sovelluksiin.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td><strong>Windows-ytimen haavoittuvuus voi sallia käyttöoikeuksien korott</strong> <strong>amisen (968537)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa kaksi yleisessä tiedossa ollutta ja kaksi yksityishenkilön ilmoittamaa Windows-ytimen haavoittuvuutta, jotka voivat sallia käyttöoikeuksien korottamisen. Hyödyntämällä jotakin näistä haavoittuvuuksista onnistuneesti hyökkääjä voi suorittaa haluamaansa koodia ja saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Hyökkääjällä on oltava voimassaolevat kirjautumistiedot ja hyökkääjän on pystyttävä kirjautumaan paikallisesti, jotta haavoittuvuutta voi hyödyntää. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään näitä haavoittuvuuksia.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150568">MS09-020</a></td>
<td><strong>Internet Information Servicesin (IIS:n) haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (970483)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yhden yleisessä tiedossa olevan ja yhden yksityishenkilön ilmoittaman Internet Information Servicesin (IIS:n) haavoittuvuuden. Haavoittuvuudet saattavat sallia käyttöoikeuksien korottamisen, jos hyökkääjä lähettää tietyllä tavalla muotoillun HTTP-pyynnön sivustoon, jossa on käytössä todennus. Tietyllä tavalla muotoiltu HTTP-pyyntö voi ohittaa IIS-määritykset, jotka määrittävät sallitut todennukset, mutta ei järjestelmänkohtaista käyttöoikeusluettelotarkistusta, joka varmistaa, voiko ilmoitettu käyttäjä käyttää tiedostoa. Näiden haavoittuvuuksien onnistunut hyödyntäminen rajoittaisi hyökkääjän tiedostojärjestelmän käyttöoikeusluettelotasoilla vain anonyymeille käyttäjätileille myönnettyihin käyttöoikeuksiin.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=143550">MS09-023</a></td>
<td><strong>Windows Searchin haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille (963093)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Searchin haavoittuvuuden. Haavoittuvuus saattaa sallia tietojen paljastumisen muille käyttäjille, jos käyttäjän suorittaman haun ensimmäisenä tuloksena on tietyllä tavalla muodostettu tiedosto tai jos käyttäjä esikatselee hakutuloksissa tietyllä tavalla muodostetun tiedoston. Windows Search -osaa ei ole oletusarvoisesti asennettu Microsoft Windows XP:hen ja Windows Server 2003:een, vaan se on ladattava lisäosa. Haavoittuvuus ei koske tuettuihin Windows Vista- ja Windows Server 2008 -versioihin asennettua Windows Searchia.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Keskitaso</a><br />
Tietojen paljastuminen muille käyttäjille</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
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
<th>Tiedotteen otsikko</th>
<th>CVE-tunnus</th>
<th>Hyödyntämisindeksin arvio</th>
<th>Tärkeät huomautukset</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=xxx">MS09-xxx</a></td>
<td></td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-xxxx">CVE-2009-xxxx</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><strong>Tätä haavoittuvuutta hyödynnetään nyt Internet-ekosysteemissä.</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=xxx">MS09-xxx</a></td>
<td></td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-xxxx">CVE-2009-xxxx</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=xxx">MS09-xxx</a></td>
<td></td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-xxxx">CVE-2009-xxxx</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td></td>
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
    <th></th>
  </tr>
                <tr><th colspan="8">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
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
                  </td><td>Ei mitään</td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bba6e20a-0345-46ae-a6f1-fd27fdee7c21">Microsoft Windows 2000 Server Service Pack 4:n Active Directory</a>
                    <br />(KB969805)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=86378753-db24-44c2-a27d-cc0239f40ab8">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d645ad82-13c3-4030-808b-834e86ed3298">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe8b3796-a407-4f41-89eb-35b4bcc24ff6">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=155a79c1-e5e4-4f62-b4b0-53aca59f20ac">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79b0481d-a3d7-477b-928a-a98cc79374af">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8515a294-4f25-4dc5-860a-e7ad9b6c1c01">Microsoft Internet Information Services 5.0</a>
                    <br />(Tärkeä)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="8">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 ja Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb2c9b76-0c65-4754-9941-d45a7c74a29a">Active Directory Application Mode (ADAM) Windows XP Professional Service Pack 2:ssa ja Windows XP Professional Service Pack 3:ssa</a>
                    <br />(KB970437)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f2119aca-a98e-4810-be52-f38241443baf">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d7f63ee-d7c3-48a5-902e-60625405e97d">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=827b735c-660b-4723-b688-3297e107153a">Windows Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9e27ce1-4e7c-437f-9477-e7805a33da08">Windows Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f033fa78-c451-44f8-aa6c-a49622c37f40">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6349e046-a3f8-4ae5-b8c3-c9879cc99e8f">Windows XP Service Pack 2 ja Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=97da589f-4534-42f6-9f29-967b5a33c542">Microsoft Internet Information Services 5.1</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=759f22cb-ea7f-49dd-a200-19cb83fffd8d">Windows Search 4.0</a>
                    <br />(Keskitaso)</td></tr>
                <tr><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ef3aaf0-a2a9-4c17-99ab-a0dc3d3f7e86">Active Directory Application Mode (ADAM)</a>
                    <br />(KB970437)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22699d09-1e68-456a-8733-bfad6667ebf5">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=088f70eb-c5c5-426a-880a-18ed386d0b56">Microsoft Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5d2c81e-ffab-4e3b-a59a-a55000597213">Windows Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a24aedf0-7a31-4ee8-a9a6-998f1160c700">Windows Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=20734b70-37f1-47dd-bc09-d56f93577a55">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3769800e-af93-4a44-8a1e-b30cc54b226f">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8982e6d2-e1f7-4208-88e3-80b159a8e21a">Microsoft Internet Information Services 6.0</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50c56dd6-c34d-4632-a779-8bcf8fdb341b">Windows Search 4.0</a>
                    <br />(Keskitaso)</td></tr>
              
                <tr><th colspan="8">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-</strong>
                      <strong>023</strong>
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
                      <strong>Keskitaso</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
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
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d814ce65-a193-4027-a6cd-106d388830a6">Active Directory</a> <br />(KB969805)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6f99957-f74f-4446-8734-a468283eebae">Active Directory Application Mode (ADAM)</a> <br />(KB970437)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=865414f8-3f77-4fee-acc6-6684a3dc0aa4">Windows Server 2003 Service Pack 2</a>
                    <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72a23752-86fb-4cc9-ab8e-63ffdfae5bec">Microsoft Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a980b867-c67f-4c61-b6db-e55c2ca68dc0">Windows Internet Explorer 7</a><br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=?...?">Windows Internet Explorer 8</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62bb9e22-4f4b-4ffc-ba76-f626e94c79d5">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9356404c-d89a-4de0-b9b4-f6e1bdadf745">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bd4e410-dbd8-431a-b316-e1e2f1825c3a">Microsoft Internet Information Services 6.0</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e72ef31f-5161-4fe6-8ed3-6206e02cef31">Windows Search 4.0</a>
                    <br />(Keskitaso)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d1f23c8-06eb-4996-92eb-0eb635fd6a42">Active Directory</a>
                    <br />(KB969805)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a2badc7-c0a5-4032-a009-73ebe9d76313">Active Directory Application Mode (ADAM)</a><br />(KB970437)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=197a6cc7-4ba3-4d2e-b621-0ef3da645ef2">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a03d3c4-e39d-43a3-8d42-216e9551be96">Microsoft Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a03d3c4-e39d-43a3-8d42-216e9551be96">Windows Internet Explorer 7</a><br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4a5401d7-ca97-4734-a0e9-d7ffe0777e34">Windows Internet Explorer 8</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=888b8dd8-d76c-42f5-a377-1f1750d3cf56">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a3123af-173d-49eb-9997-14e82e764aee">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ea363223-535d-4142-9aba-3890960c6259">Microsoft Internet Information Services 6.0</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ffc3680-f9bf-423b-96a7-102f4cc9c240">Windows Search 4.0</a>
                    <br />(Keskitaso)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92e7808b-92ff-449d-bb73-ee8638e9ccd1">Active Directory</a>
                    <br />(KB969805)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=719efd62-fb33-447d-b6dd-2aaafbbad881">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58efde2c-e0b8-4259-b19e-80564b834882">Microsoft Internet Explorer 6</a>
                    <br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a2d2907e-67ae-44a4-a805-8670e659ea57">Windows Internet Explorer 7</a><br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3084f46e-02b9-4d99-a7a1-033817f9bd9f">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13b50993-410f-4e7a-a33a-6d9b48dbb4d1">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6b806eb-e2c4-4436-8964-720db593055d">Microsoft Internet Information Services 6.0</a>
                    <br />(Tärkeä)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="8">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td></tr>
                <tr><td>Windows Vista, Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ad8f037-2434-4dea-bfc3-9d3b4008b828">Windows Vista, Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e60215c3-b8b9-4e45-9d9f-b3fb0b47cce1">Windows Internet Explorer 7</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f2730e9-b4fc-4f20-96cf-73f1be63f374">Windows Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ca227c0-f2dd-429c-a542-e08e93527214">Windows Vista, Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c31b36f8-330c-4a0c-9a3d-7cbe9a1ab8c8">Windows Vista, Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85c317cd-2a14-4747-9f50-3af3ddd3ae1b">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88185088-8c2c-4bc6-89b2-87f4d4849cf7">Windows Internet Explorer 7</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f2730e9-b4fc-4f20-96cf-73f1be63f374">Windows Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=188adafe-1feb-46ad-b237-a88d35104dcd">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d70a65f-07ce-4992-8bec-28fefd7587bc">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td></tr>
              
                <tr><th colspan="8">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
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
                      <strong>Keskitaso</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td></tr>
                <tr><td>Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f18356d-9f09-4d24-8361-970c0d1ccac4">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0e3f975-57da-43fa-ac12-3d14fd6ce939">Windows Internet Explorer 7</a>**<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aaad301c-d232-4733-a0df-8e5d41bbfde8">Windows Internet Explorer 8</a>**<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eaa26c6c-5bf7-4099-bb21-1e03de3a25ca">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98ba52b2-da1a-4939-a10e-d43b3a7e7ed4">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d0a6e8d-a31d-4f3d-a7d7-e61215bfebed">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=758edce7-2a82-4b2e-bd71-5b7075cc4b17">Windows Internet Explorer 7</a>**<br />(Keskitaso)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faac92d4-4a2b-4bb5-8bd1-1519a9fa8147">Windows Internet Explorer 8</a>**<br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=447aaa4f-946b-4f23-b151-dcf46ea9f80e">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbaa5a72-c267-4907-a207-525c2803d7b9">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbac3deb-6c93-45aa-832c-02b915ac7f44">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67d4c189-030d-42eb-98b9-7957ccd92592">Windows Internet Explorer 7</a>
                    <br />(Keskitaso)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f33012b9-5d5b-4f72-8d49-a8e1c8bc1337">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0e3ad56-a363-44ba-af4d-b7f551c88afd">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td></tr>
              </table>


**Huomautukset : Windows Server 2** **008**

**\*Windows Server 2008 Server Core -asennus, jota haavoittuvuus koskee.** Tämä päivitys koskee tuettuja Windows Server 2008 -versioita samalla luokituksella siitä riippumatta. onko Windows Server 2008:n asennuksessa käytetty Server Core -asennusta vai ei. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Windows Server 2008 Server Core -asennus, joita haavoittuvuus koskee.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksella. Jos haluat lisätietoja tästä asennusvaihtoehdosta, katso [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office -ohjelmistopaketit ja -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="4">Microsoft Office -ohjelmistopaketit, -järjestelmät ja -osat</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=147416">
                      <strong>MS09-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=147294">
                      <strong>MS09-021</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128104">
                      <strong>MS09-024</strong>
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
                <tr><td>Microsoft Office 2000 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3663e9f2-a952-4238-b902-90b5b09feb38">Microsoft Office Word 2000 Service Pack 3</a>
                    <br />(KB969600)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd16e243-b8e2-4afb-86b6-4d60214598eb">Microsoft Office Excel 2000 Service Pack 3</a>
                    <br />(KB969683)<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4bf95806-3d32-411b-9779-a81aebad45e9">Microsoft Office Word 2000 Service Pack 3</a>
                    <br />(KB957838)<br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1323be1-15f2-491b-abae-c03ba1394398">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB969602)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd80ce95-0aec-4493-b9d1-c3dad95c3415">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB969680)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0ba8c9e-75ee-46bd-9e92-d4e6599309ad">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB957646)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7cbc2587-2c8c-49b4-9f40-e4cdccb61ecd">Microsoft Office Word 2003 Service Pack 3</a>
                    <br />(KB969603)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=10156044-a5a4-4312-98a7-1b1ced625ddb">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB969681)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7ba3ea7-d06a-4c14-9107-9b92ef68fcae">Microsoft Office Word 2003 Service Pack 3 with the Microsoft Works 6–9 File Converter</a>***<br />(KB968326)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>2007 Microsoft Office System Service Pack 1 ja 2007 Microsoft Office System Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e205108-4c28-4cab-a4d0-4ed3fd696473">Microsoft Office Word 2007 Service Pack 1 ja Microsoft Office Word 2007 Service Pack 2</a>
                    <br />(KB969604)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bcd565a-6acb-407d-80da-0398526ddf99">Microsoft Office Excel 2007 Service Pack 1 ja Microsoft Office Excel 2007 Service Pack 2</a>*<br />(KB969682)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd47e1e5-cd2e-4c08-9864-471e97f38ca3">Microsoft Office Word 2007 Service Pack 1</a>
                    <br />(KB969559)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="4">Microsoft Office for Mac</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=147416">
                      <strong>MS09-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=147294">
                      <strong>MS09-021</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128104">
                      <strong>MS09-024</strong>
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
                  </td><td>Ei mitään</td></tr>
                <tr><td>Microsoft Office 2004 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550">Microsoft Office 2004 for Mac</a>
                    <br />(KB969661)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550">Microsoft Office 2004 for Mac</a>
                    <br />(KB969661)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58">Microsoft Office 2008 for Mac</a>
                    <br />(KB971822)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58">Microsoft Office 2008 for Mac</a>
                    <br />(KB971822)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Open XML File Format Converter for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6">Open XML File Format Converter for Mac</a>
                    <br />(KB971824)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6">Open XML File Format Converter for Mac</a>
                    <br />(KB971824)<br />(Tärkeä)</td><td>Ei koske</td></tr>
              
                <tr><th colspan="4">Muu Office-ohjelmisto</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=147416">
                      <strong>MS09-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=147294">
                      <strong>MS09-021</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=128104">
                      <strong>MS09-024</strong>
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
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=20e6933d-85f8-4cec-9534-893789cd053e">Microsoft Office Excel Viewer 2003 Service Pack 3</a>
                    <br />(KB969685)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac0530dc-7f63-4ad0-85c1-784ad28156cf">Microsoft Office Excel Viewer</a><br />(KB969686)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Office Word Viewer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82980a40-f10c-4f02-b06c-3a12d4434a6b">Microsoft Office Word Viewer 2003 Service Pack 3</a>
                    <br />(KB969614)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82980a40-f10c-4f02-b06c-3a12d4434a6b">Microsoft Office Word Viewer</a><br />(KB969614)<br />(Tärkeä)</td><td>Ei koske</td><td>Ei koske</td></tr>
                <tr class="alternateRow"><td>Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63bd8f14-e736-46ce-af66-d30f17461e5a">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1 ja Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2</a>
                    <br />(KB969613)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8be8457-b0b6-455e-907e-d13be883adf2">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1 ja Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2</a>
                    <br />(KB969679)<br />(Tärkeä)</td><td>Ei koske</td></tr>
                <tr><td>Microsoft Works 8.5</td><td>Ei koske</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=628280fe-e035-4274-85f2-393d9bad543c">Microsoft Works 8.5</a>
                    <br />(KB967043)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Works 9.0</td><td>Ei koske</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6fa110e-45c6-450f-ae47-c89a06e3f762">Microsoft Works 9.0</a>
                    <br />(KB967044)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Office SharePoint Server</td><td>Ei koske</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=862e6ad1-8124-4060-93b1-2b882ef5ce3d">Microsoft Office SharePoint Server 2007 Service Pack 1 ja Microsoft Office SharePoint Server 2007 Service Pack 2 (32-bit editionit)</a>**<br />(KB969737)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7b6e611-2c5d-4639-add9-972055789ecd">Microsoft Office SharePoint Server 2007 Service Pack 1 ja Microsoft Office SharePoint Server 2007 Service Pack 2 (32-bit editionit)</a>**<br />(KB969737)<br />(Tärkeä)</td><td>Ei koske</td></tr>
              </table>


**Huomautukset: MS09-021**

\*Jos käyttäjällä on Microsoft Office Excel 2007 Service Pack 1 ja Microsoft Office Excel 2007 Service Pack 2, hänen on asennettava sekä tietoturvapäivitys KB969682 että [Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1:n ja Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2:n](http://www.microsoft.com/downloads/details.aspx?familyid=?...?) (KB969679) tietoturvapäivitys, jolla suojaudutaan tässä tiedotteessa kuvatuilta haavoittuvuuksilta.

\*\*Tämä päivitys koskee palvelimia, joihin on asennettu Excel-palvelut, kuten Microsoft Office SharePoint Server 2007 Enterprise- ja Microsoft Office SharePoint Server 2007 For Internet Sites -palvelinten oletuskokoonpanot. Microsoft Office SharePoint Server 2007 Standard ei sisällä Excel-palveluja.

**Huomautus: MS09-024**

\*\*\*Haavoittuvuus koskee Microsoft Office Word 2003:a, jos Works-muunnin on asennettu. Microsoft Office Word 2003:n Works-muuntimet voi ladata [Microsoft Works 6–9 File Converter](http://www.microsoft.com/downloads/details.aspx?familyid=bf41401e-70fa-465d-ae2e-cf44dbf05297&displaylang=en) -sivustosta.

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin ja laajennettu Inventory-työkalu (ESUIT). Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso myös [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) -sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

**Update Compatibility** **Evaluator ja sovellusten yhteensopivuustyökalu**

Päivitykset usein kirjoittavat samoihin tiedostoihin ja rekisteriasetuksiin, joita tarvitaan sovelluksia käytettäessä. Tämä voi aiheuttaa yhteensopivuusongelmia ja pidentää aikaa, joka kuluu tietoturvapäivitysten käyttöönottamiseen. Voit tehostaa Windows-päivitysten testaamista ja tarkistamista asennetuissa sovelluksissa käyttämällä [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) -osia, jotka sisältyvät [Application Compatibility Toolkit 5.0:aan](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Sovellusten yhteensopivuustyökalu sisältää työkalut ja ohjeistuksen, joilla voi arvioida ja lieventää sovellusten yhteensopivuusongelmia ennen Microsoft Windows Vistan, Windowsin päivityksen, Microsoftin tietoturvapäivitysten tai Windows Internet Explorerin uuden versioon käyttöönottoa ympäristössäsi.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tietoja Windows Update- ja Microsoft Update -sivustoissa julkaistavista päivityksistä, jotka eivät ole tietoturvapäivityksiä:

  - [Microsoft Knowledge Base -artikkeli 894199](http://support.microsoft.com/kb/894199): Kuvaus Software Update Services- ja Windows Server Update Services -sisällön muutoksista. Sisältää kaiken Windows-sisällön.
  - [Muiden Microsoft-tuotteiden kuin Microsoft Windowsin uudet, päivitetyt ja julkaistut päivitykset](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

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

  - Joshua J. Drake ([Verisign iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-018
  - David Bloom ([Google Inc.](http://www.google.com/)) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS09-019
  - Jorge Luis Alvarez Medina ([Core Security Technologies](http://www.coresecurity.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-019
  - Haifei Li ([Fortinet](http://www.fortinet.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-019
  - [Tippingpoint](http://www.tippingpoint.com/) ja [Zero Day Initiative](http://www.zerodayinitiative.com/) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-019
  - Peter Vreugdenhil (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-019
  - Wushi (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS09-019
  - Nils (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-019
  - Wushi ([team509](http://www.team509.com/)) yhteistyössä [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-027
  - Nicolas Joly ([VUPEN Security](http://www.vupen.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-027
  - Bing Liu (Fortinetin [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com)) ilmoitti kolmesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS09-021
  - Carsten H. Eiram ([Secunia](http://secunia.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-021
  - Ehsan Foroughi ([Telus](http://www.telus.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-021
  - Sean Larsson ja Joshua Drake ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-021
  - Carsten H. Eiram ([Secunia](http://secunia.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-021
  - [Tippingpoint](http://www.tippingpoint.com/) ja [Zero Day Initiative](http://www.zerodayinitiative.com/) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-021
  - Jun Mao ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-022
  - [VeriSign iDefense Labs](http://labs.idefense.com/) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-023
  - Thomas Garnier ([SkyRecon](http://www.skyrecon.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-023
  - Shaun Colley ([NGS Software](http://www.ngssoftware.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-024
  - Thomas Garnier ([SkyRecon](http://www.skyrecon.com/)) ilmoitti kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS09-025
  - Yamata Li ([Palo Alto Networks](http://www.paloaltonetworks.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-020
  - Yair Amit ([IBM Rational Application Security](http://www-01.ibm.com/software/rational/offerings/websecurity/webappsecurity.html)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-028

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [tietoturvapalvelu](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia. Lisätietoja saatavissa olevista tukivaihtoehdoista on [Microsoftin Ohjeessa ja tuessa](http://support.microsoft.com/).
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (9. kesäkuuta 2009): Tietoturvatiedotteen yhteenveto julkaistu.

*Built at 2014-04-18T01:50:00Z-07:00*

