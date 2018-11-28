---
title: Microsoftin turvatiedotteiden yhteenveto, toukokuu 2009
TOCTitle: MS09-MAY
ms:assetid: ms09-may
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms09-may(v=Security.10)
ms:contentKeyID: 61225638
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, toukokuu 2009

Julkaistu: 12. toukokuuta 2009 | Päivitetty: 9. kesäkuuta 2009

**Versio:** 2.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo toukokuussa 2009 julkaistuista tietoturvatiedotteista.

Toukokuun 2009 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 7. toukokuuta 2009. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 13. toukokuuta 2009, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt toukokuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032395223) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td><strong>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Microsoft Office PowerPointin haavoittuvuuden sekä useita yksityishenkilöiden ilmoittamia haavoittuvuuksia. Nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun PowerPoint-tiedoston. Hyödyntämällä jotakin näistä haavoittuvuuksista onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
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
<th>Tiedotteen otsikko</th>
<th>CVE-tunnus</th>
<th>Hyödyntämisindeksin arvio</th>
<th>Tärkeät huomautukset</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0220">CVE-2009-0220</a></td>
<td>Office-versiot, jotka on käännetty ilman /GS:ää:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>/GS-suojaus, joka on muodostettu Office 2003 Service Pack 3:n ja sitä uudempia Office-versioita käännettäessä, lieventää tätä haavoittuvuutta ja pienentää kyseisten järjestelmien riskin luokitukseen <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0221">CVE-2009-0221</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0222">CVE-2009-0222</a></td>
<td>Office-versiot, jotka on käännetty ilman /GS:ää:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>/GS-suojaus, joka on muodostettu Office 2003 Service Pack 3:n ja sitä uudempia Office-versioita käännettäessä, lieventää tätä haavoittuvuutta ja pienentää kyseisten järjestelmien riskin luokitukseen <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0223">CVE-2009-0223</a></td>
<td>Office-versiot, jotka on käännetty ilman /GS:ää:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>/GS-suojaus, joka on muodostettu Office 2003 Service Pack 3:n ja sitä uudempia Office-versioita käännettäessä, lieventää tätä haavoittuvuutta ja pienentää kyseisten järjestelmien riskin luokitukseen <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0224">CVE-2009-0224</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0225">CVE-2009-0225</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0226">CVE-2009-0226</a></td>
<td>Office-versiot, jotka on käännetty ilman /GS:ää:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>/GS-suojaus, joka on muodostettu Office 2003 Service Pack 3:n ja sitä uudempia Office-versioita käännettäessä, lieventää tätä haavoittuvuutta ja pienentää kyseisten järjestelmien riskin luokitukseen <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0227">CVE-2009-0227</a></td>
<td>Office-versiot, jotka on käännetty ilman /GS:ää:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>/GS-suojaus, joka on muodostettu Office 2003 Service Pack 3:n ja sitä uudempia Office-versioita käännettäessä, lieventää tätä haavoittuvuutta ja pienentää kyseisten järjestelmien riskin luokitukseen <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0556">CVE-2009-0556</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><strong>Tätä haavoittuvuutta hyödynnetään nyt Internet-ekosysteemissä.</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1128">CVE-2009-1128</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1129">CVE-2009-1129</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1130">CVE-2009-1130</a></td>
<td>Office-versiot, jotka on käännetty ilman /GS:ää:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>/GS-suojaus, joka on muodostettu Office 2003 Service Pack 3:n ja sitä uudempia Office-versioita käännettäessä, lieventää tätä haavoittuvuutta ja pienentää kyseisten järjestelmien riskin luokitukseen <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1131">CVE-2009-1131</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td>Microsoft Office PowerPointin haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (967340)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1137">CVE-2009-1137</a></td>
<td>Office-versiot, jotka on käännetty ilman /GS:ää:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>/GS-suojaus, joka on muodostettu Office 2003 Service Pack 3:n ja sitä uudempia Office-versioita käännettäessä, lieventää tätä haavoittuvuutta ja pienentää kyseisten järjestelmien riskin luokitukseen <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen.</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

Seuraavissa taulukoissa tiedotteet on järjestetty pääohjelmistoluokkien ja vakavuuden mukaan.

**Taulukoiden käyttö**

Näiden taulukoiden avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja koskeeko jokin tietoturvapäivitys niiden asennusta. Jos ohjelma tai osa on luettelossa, saatavana olevaan ohjelmistopäivitykseen on linkki. Myös ohjelmistopäivityksen luokitus mainitaan.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää useiden tietoturvapäivitysten asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

#### Microsoft Office -ohjelmistopaketit ja -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Office -ohjelmistopaketit, -järjestelmät ja -osat</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=141704">
                      <strong>MS09-017</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriittinen</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2000 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f443312a-ac74-4ebc-a4ac-7a756aa67894">Microsoft Office PowerPoint 2000 Service Pack 3</a>
                    <br />(KB957790)<br />(Kriittinen)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a24ec7ab-c1c7-4ddb-8b6e-107f1af67f49">Microsoft Office PowerPoint 2002 Service Pack 3</a>
                    <br />(KB957781)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ccfa978b-3340-40db-a45d-c880ba36b106">Microsoft Office PowerPoint 2003 Service Pack 3</a>
                    <br />(KB957784)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>2007 Microsoft Office System Service Pack 1 ja 2007 Microsoft Office System Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11f8380f-ffb6-4c22-a89c-3dc55d0f9834">Microsoft Office PowerPoint 2007 Service Pack 1 ja Microsoft Office PowerPoint 2007 Service Pack 2</a>
                    <br />(KB957789)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="2">Microsoft Office for Mac</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=141704">
                      <strong>MS09-017</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2004 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550">Microsoft Office 2004 for Mac</a>
                    <br />(KB969661)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58">Microsoft Office 2008 for Mac</a>
                    <br />(KB971822)<br />(Tärkeä)</td></tr>
                <tr><td>Open XML File Format Converter for Mac</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6">Open XML File Format Converter for Mac</a>
                    <br />(KB971824)<br />(Tärkeä)</td></tr>
              
                <tr><th colspan="2">Muu Office-ohjelmisto</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=141704">
                      <strong>MS09-017</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>PowerPoint Viewer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a57e6ed-bd24-406f-87bb-117391e083e0">PowerPoint Viewer 2003</a>
                    <br />(KB969615)<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=141b8338-5c52-4326-a9e4-d2f2d8940d9c">PowerPoint Viewer 2007 Service Pack 1 ja PowerPoint Viewer 2007 Service Pack 2</a><br />(KB970059)<br />(Tärkeä)</td></tr>
                <tr><td>Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketti</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1d3a4c3-538a-4f98-8d60-250803a80e2a">Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 1 ja Word-, Excel- ja PowerPoint 2007 -tiedostomuotojen Microsoft Office -yhteensopivuuspaketin Service Pack 2</a>
                    <br />(KB969618)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Works 8.5</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=628280fe-e035-4274-85f2-393d9bad543c">Microsoft Works 8.5</a>
                    <br />(KB967043)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Works 9</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6fa110e-45c6-450f-ae47-c89a06e3f762">Microsoft Works 9</a>
                    <br />(KB967044)<br />(Tärkeä)</td></tr>
              </table>


**Huomautus: MS09-017**

Microsoft julkaisee uudelleen tietoturvatiedotteen MS09-017, jossa on Microsoft Office 2004 for Macin, Microsoft Office 2008 for Macin, Open XML File Format Converter for Macin, Microsoft Works 8.5:n ja Microsoft Works 9:n tietoturvapäivityspaketteja. Jos asiakkaalla on näitä ohjelmistoja, hänen on asennettava päivitys heti.

Kun MS09-017 julkaistiin ensimmäisen kerran, näitä tietoturvapäivityspaketteja kehitettiin vielä. Microsoft julkaisi tietoturvatiedotteen MS09-17 tuolloin, koska koko tuoteryhmää koskevia päivityspaketteja oli valmiina tiedotteiden säännöllisen julkaisun aikaan. Tämä päivitys korjasi suurinta osaa käyttäjistä koskevan riskin. Tämä nyt julkaistava tietoturvatiedote MS09-017 täydentää päivitykset, jotka koskevat tässä tiedotteessa käsiteltyjä haavoittuvuuksia.

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

**Update Compatibility Evaluator ja sovellusten yhteensopivuustyökalu**

Päivitykset usein kirjoittavat samoihin tiedostoihin ja rekisteriasetuksiin, joita tarvitaan sovelluksia käytettäessä. Tämä voi aiheuttaa yhteensopivuusongelmia ja pidentää aikaa, joka kuluu tietoturvapäivitysten käyttöönottamiseen. Voit tehostaa Windows-päivitysten testaamista ja tarkistamista asennetuissa sovelluksissa käyttämällä [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) -osia, jotka sisältyvät [Application Compatibility Toolkit 5.0:aan](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

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

  - Tuntematon tutkija (yhteistyössä [VeriSign iDefense Labsin](http://labs.idefense.com/) kanssa) ilmoitti kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS09-017
  - Sean Larsson ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoitti kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS09-017
  - Nicolas Joly ([VUPEN Security](http://www.vupen.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-017
  - Marsu Pilami ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoitti useista haavoittuvuuksista, jotka on kuvattu tietoturvatiedotteessa MS09-017
  - Nicolas Joly ([VUPEN Security](http://www.vupen.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-017
  - Marsu Pilami (yhteistyössä [Zero Day Initiative](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-017
  - Ling ja Wushi ([team509](http://www.team509.com/)) yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa sekä Sean Larsson ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-017
  - Carsten H. Eiram ([Secunia](http://secunia.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS09-017

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [tietoturvapalvelu](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia. Lisätietoja saatavissa olevista tukivaihtoehdoista on [Microsoftin Ohjeessa ja tuessa](http://support.microsoft.com/).
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (12. toukokuuta 2009): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (13. toukokuuta 2009): Tietoturvatiedotteen MS09-017 virheellisen huomautuksen poisto. Huomautus koski tuettujen Microsoft Office PowerPoint 2007 -versioiden tietoturvapäivityksiä KB969618 ja KB957789.
  - V2.0 (9. kesäkuuta 2009): Korjattu tietoturvatiedotteen MS09-017 uudelleenjulkaisua varten. Uudelleenjulkaistavassa tietoturvatiedotteessa MS09-017 on Microsoft Office 2004 for Macin, Microsoft Office 2008 for Macin, Open XML File Format Converter for Macin, Microsoft Works 8.5:n ja Microsoft Works 9.0:n tietoturvapäivityspaketteja. Jos asiakkaalla on näitä ohjelmistoja, hänen on asennettava päivitys heti.

*Built at 2014-04-18T01:50:00Z-07:00*

