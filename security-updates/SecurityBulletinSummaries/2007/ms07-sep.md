---
title: Microsoftin turvatiedotteiden yhteenveto, syyskuu 2007
TOCTitle: MS07-SEP
ms:assetid: ms07-sep
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms07-sep(v=Security.10)
ms:contentKeyID: 61225592
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, syyskuu 2007

Julkaistu: 11. syyskuuta 2007 | Päivitetty: 12. syyskuuta 2007

**Versio:** 1.1

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo syyskuussa 2007 julkaistuista tietoturvatiedotteista.

Syyskuun 2007 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 6. elokuuta 2007. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi web-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Web-lähetyksen ajankohta on 12. syyskuuta 2007, kello 21.00 Suomen aikaa (kello 11.00 Tyynenmeren aikaa). [Rekisteröidy nyt syyskuun tietoturvatiedotteen web-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344690&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen web-lähetyksestä voi katsoa tallenteen, Lisätietoja on [Microsoftin tietoturvatiedotteista ja web-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa sivustolla.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät, muut kuin tietoturvapäivitykset, jotka julkaistaan samana päivänä kuin kuukausittain julkaistavat tietoturvapäivitykset. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (1)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-051</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94667"><strong>Microsoft Agentin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (938827)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Microsoft Agent -komponentissa on havaittu haavoittuvuus, joka antaa vihamieliselle hyökkääjälle mahdollisuuden suorittaa ohjelman koodia verkon välityksellä. Se aiheutuu tavasta, jolla ohjelma käsittelee erityisesti muodostettuja URL-osoitteita. Haavoittuvuus saattaa antaa hyökkääjän suorittaa haavoittuvuuden sisältävässä järjestelmässä koodia verkon välityksellä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (3)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-052</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=98460"><strong>Visual Studion Crystal Reportsin heikkous saattaa sallia koodin suorittamisen verkon välityksellä (941522)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa julkistetun haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun RPT-tiedoston. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer ja Enterprise Update Scan Tool havaitsevat, tarvitseeko tietokone tämän päivityksen. Tietokone on ehkä käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Visual Studio.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-053</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94467"><strong>Windows Services for UNIXin haavoittuvuus saattaa sallia käyttöoikeuksien laajentamisen (939778)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa julkistetun haavoittuvuuden. Windows Services for UNIX 3.0:ssa, Windows Services for UNIX 3.5:ssä ja UNIX-pohjaisten sovellusten alijärjestelmässä on haavoittuvuus, jossa joidenkin setuid-binaaritiedostojen suorittaminen saattaa sallia hyökkääjän käyttöoikeuksien laajentamisen.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Käyttöoikeuksien korottaminen</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer ja Enterprise Update Scan Tool havaitsevat, tarvitseeko tietokone tämän päivityksen. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows Services for UNIX, UNIX-pohjaisten sovellusten alijärjestelmä.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-054</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=99364"><strong>MSN Messengerin ja Windows Live Messengerin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (942099)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tietoturvapäivitys korjaa julkistetun MSN Messengerin ja Windows Live Messengerin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, kun käyttäjä hyväksyy hyökkääjän lähettämän videokeskustelukutsun. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa järjestelmän, jota ongelma koskee. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Näihin tuotteisiin sisältyy päivitysten automaattinen tunnistaminen ja käyttöönotto. Tämä päivitys ei edellytä järjestelmän käynnistämistä uudelleen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>MSN Messenger, Windows Live Messenger.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

**Miten taulukkoa käytetään?**

Tämän taulukon avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja edellyttääkö se tietoturvapäivityksen asentamista. Kunkin mainitun ohjelman tai osan yhteydessä näkyy haavoittuvuuden vaikutus ja linkki saatavana oleviin ohjelmistopäivityksiin.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää useiden tietoturvapäivitysten asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

**Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
    <th>Tiedot        </th>
  </tr>
            <tr><td>
                <strong>Tiedotteen numero</strong>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=94667">
                  <strong>MS07-051</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=98460">
                  <strong>MS07-052</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=94467">
                  <strong>MS07-053</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=99364">
                  <strong>MS07-054</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td>
                <strong>Luokitus</strong>
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
              </td></tr>
          
            <tr><th colspan="5">Windows-käyttöjärjestelmä</th></tr>
          
            <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7cd248ed-d154-4dce-89ef-ceefd2700965">Kriittinen</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Windows Server 2003 Service Pack 1</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Server 2003 x64 Edition</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Windows Vista</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
          
            <tr><th colspan="5">Windows-käyttöjärjestelmien osat</th></tr>
          
            <tr><td>Windows Services for UNIX 3.0, kun käyttöjärjestelmä on Windows 2000 Service Pack 4 </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Services for UNIX 3.5, kun käyttöjärjestelmä on Windows 2000 Service Pack 4 </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663">Tärkeä</a>
              </td><td /></tr>
            <tr><td>Windows Services for UNIX 3.0, kun käyttöjärjestelmä on Windows 2000 Service Pack 2 </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Services for UNIX 3.5, kun käyttöjärjestelmä on Windows 2000 Service Pack 2 </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663">Tärkeä</a>
              </td><td /></tr>
            <tr><td>Windows Services for UNIX 3.5, kun käyttöjärjestelmä on Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2 </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Services for UNIX 3.5, kun käyttöjärjestelmä on Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2 </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663">Tärkeä</a>
              </td><td /></tr>
            <tr><td>UNIX-pohjaisten sovellusten alijärjestelmä, kun käyttöjärjestelmä on Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2 </td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ab5cc43-0b9c-45eb-aa51-47568ab6ce3f">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>UNIX-pohjaisten sovellusten alijärjestelmä, kun käyttöjärjestelmä on Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d21e3e8-b5f6-4044-9db6-054af836492b">Tärkeä</a>
              </td><td /></tr>
            <tr><td>UNIX-pohjaisten sovellusten alijärjestelmä, kun käyttöjärjestelmä on Windows Vista</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d52e4f4-2888-42df-8163-85c648e65b29">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>UNIX-pohjaisten sovellusten alijärjestelmä, kun käyttöjärjestelmä on Windows Vista x64 Edition</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4be667cc-c239-480b-a9a0-939bcd27f0de">Tärkeä</a>
              </td><td /></tr>
          
            <tr><th colspan="5">Kehitystyökalut ja käyttöympäristöt</th></tr>
          
            <tr><td>Visual Studio .NET 2002 Service Pack 1<br />(KB937057)</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2608c83b-e1b2-4449-9a0e-1e566aac3d76">Tärkeä</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Visual Studio .NET 2003<br />(KB937058)</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d612ad41-5a0d-4e13-99ea-d6a5589786d6">Tärkeä</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr><td>Visual Studio .NET 2003 Service Pack 1 <br />(KB937059)</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b10b04b-932c-4bff-9cbc-b3eeb15064b1">Tärkeä</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Visual Studio 2005<br />(KB937060)</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=21073cc2-919c-40df-8ebb-aa3db06050d2">Tärkeä</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr><td>Visual Studio 2005 Service Pack 1<br />(KB937061)</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=967d43c8-efba-4221-beb0-981e7deef33a">Tärkeä</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
          
            <tr><th colspan="5">Muut ohjelmistot, joita haavoittuvuus koskee</th></tr>
          
            <tr class="alternateRow"><td>MSN Messenger 6.2</td><td /><td /><td /><td>
                <strong>[3]</strong>
              </td></tr>
            <tr><td>MSN Messenger 7.0</td><td /><td /><td /><td>
                <strong>[3]</strong>
              </td></tr>
            <tr class="alternateRow"><td>MSN Messenger 7.5</td><td /><td /><td /><td>
                <strong>[3]</strong>
              </td></tr>
            <tr><td>MSN Messenger 8.0</td><td /><td /><td /><td>
                <strong>[3]</strong>
              </td></tr>
          </table>


**Huomautuksia**

**\[1\]** Tähän käyttöjärjestelmään on saatavana tietoturvapäivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa. 

**\[2\]** Haavoittuvuus ei koske kaikki tämän Visual Studion version versioita. Tarkista asiaa koskevasta tietoturvatiedotteesta, mitä versioita haavoittuvuus koskee. 

**\[3\]** Tälle ohjelmistolle on saatavana päivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa. 

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustolla (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustolla Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security\_patch" avulla. Tietoturvapäivitykset voidaan ladata lisäksi Windows Update Catalog -palvelusta. Lisätietoja Windows Update Catalogista on [Microsoft Knowledge Base -artikkelissa 323166](http://support.microsoft.com/kb/323166).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla myös IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin, laajennettu Inventory-työkalu ja Enterprise Update Scan (EST) -työkalu. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer jaEnterprise Update Scan Tool**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustolla.

Kun MBSA 1.2.1 ei tue tietyn tietoturvapäivityksen tunnistamista, Microsoft julkaisee kyseistä tietoturvapäivitystä varten EST (Enterprise Update Scan Tool) -version. Lisätietoja EST-tarkistustyökalusta on sivustolla [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193).

**Huomautus** MBSA 1.2.1:n käyttämää MSSecure.XML-tiedostoa ei päivitetä 9.10.2007 jälkeen. Tämän päivämäärän jälkeen uusia tietoturvapäivityksiä ei lisätä MBSA 1.2.1:n käyttämän MSSecure.XML-tiedostoon eikä Enterprise Scan Tool -tarkistustyökalusta julkaista enää uusia versioita. Lisätietoja on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustolla.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustolla.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939)-sivustolla. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustolla.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustolla. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tässä kuussa:

  - Microsoft on julkaissut yhden tärkeän päivityksen, joka **ei kuitenkaan ole tietoturvapäivitys**, MU (Microsoft Update)- ja WSUS (Windows Software Update Services) -sivustoissa.
  - Microsoft ei ole julkistanut yhtään tärkeää Windows-päivitystä, joka **ei kuitenkaan ole tietoturvapäivitys**, WU (Windows Update) -sivustolla.

Huomaa, että nämä tiedot koskevat **vain** sellaisia tärkeitä päivityksiä, **jotka eivät ole tietoturvapäivityksiä** ja jotka julkaistaan saman päivänä kuin tietoturvatiedotteiden yhteenveto Microsoft Update-, Windows Update- ja Windows Server Update Services -sivustoissa. Tietoja **ei** julkaista muina päivinä julkaistavista päivityksistä, **jotka eivät ole tietoturvapäivityksiä**.

#### Tietoturvastrategiat ja yhteisö

**Korjaustiedostojen hallintamenetelmät**

[Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustolla on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivitysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavilta sivustoilta:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security\_patch" avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustolta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustolla.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - [Assurent Secure Technologiesin](http://www.assurent.com/) haavoittuvuuksien etsintätiimi ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667)
  - Yamata Li ([Palo Alto Networks](http://www.paloaltonetworks.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667)
  - Tuntematon tutkija (yhteistyössä [iDefense VCP:n](http://labs.idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667).
  - Brian A. Reiter (WolfeReiter) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, josta kerrottiin tietoturvatiedotteessa [MS07-053](http://go.microsoft.com/fwlink/?linkid=94467)
  - Woo Shi ([team 509](http://www.team509.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-054](http://go.microsoft.com/fwlink/?linkid=99364)

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustolla.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustolla.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (11. syyskuuta 2007): Tietoturvatiedotteen yhteenveto julkaistu.

*Built at 2014-04-18T01:50:00Z-07:00*

