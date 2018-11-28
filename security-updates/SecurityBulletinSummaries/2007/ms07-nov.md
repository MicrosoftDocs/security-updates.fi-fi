---
title: Microsoftin turvatiedotteiden yhteenveto, marraskuu 2007
TOCTitle: MS07-NOV
ms:assetid: ms07-nov
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms07-nov(v=Security.10)
ms:contentKeyID: 61225590
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, marraskuu 2007

Julkaistu: 13. marraskuuta 2007

**Versio:** 1.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo marraskuussa 2007 julkaistuista tietoturvatiedotteista.

Marraskuun 2007 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 8. marraskuuta 2007. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 14. marraskuuta 2007, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt marraskuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344694&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (1)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-061</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=103190"><strong>Windowsin URI-tunnuksen käsittelyn haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (943460)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä päivitys korjaa julkisesti raportoidun haavoittuvuuden. Windows-käyttöliittymän tapaan käsitellä siihen välitettyjä tietyllä tavalla muodostettuja URI-tunnuksia sisältyy koodin suorittaminen verkon välityksellä -tyyppinen haavoittuvuus. Jos Windows-käyttöliittymän URI-tunnusten tarkistus ei ole riittävä, hyökkääjä voi hyödyntää tätä haavoittuvuutta ja suorittaa haluamaansa koodia. Microsoft on tunnistanut ainoastaan tavat, jolla tätä haavoittuvuutta voidaan hyödyntää Internet Explorer 7:ää käyttävissä järjestelmissä. Haavoittuvuus kuitenkin sisältyy Windows-tiedostoon Shell32.dll, joka sisältyy kaikkiin Windows XP:n ja Windows Server 2003:n tuettuihin versioihin.</td>
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
<td><strong>Tunn</strong> <strong>istus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (1)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-062</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=99391"><strong>DNS:n haavoittuvuus saattaa sallia tietojen väärentämisen (941672)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Tämä Windows DNS -palvelimissa olevan tietojen väärentämisen mahdollistavan haavoittuvuuden takia hyökkääjä saattaa pystyä lähettämään tietyllä tavalla muodostettuja vastauksia DNS-pyyntöihin ja väärentää tai uudelleenohjata näin internet-tietoliikennettä luotettavista sijainneista.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Tietojen väärentäminen</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tämä päivitys edellyttää järjestelmän käynnistämistä uudelleen, paitsi tietyissä tilanteissa.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
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
  </tr>
            <tr><td>
                <strong>Tiedotteen numero</strong>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=103190">
                  <strong>MS07-061</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=99391">
                  <strong>MS07-062</strong>
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
              </td></tr>
          
            <tr><th colspan="3">Windows-käyttöjärjestelmä</th></tr>
          
            <tr><td>Microsoft Windows 2000 Server Service Pack 4</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c80fcd9b-d0f8-44db-96fc-bf2ead054ff4">Tärkeä</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ba1c2f9-1bde-4e97-b327-21259c5e5104">Kriittinen</a>
              </td><td>
                 
              </td></tr>
            <tr><td>Windows XP Professional x64 Edition</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f">Kriittinen</a>
              </td><td>
                <strong> </strong>
              </td></tr>
            <tr><td>Windows Server 2003 Service Pack 1</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b">Kriittinen</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d">Tärkeä</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b">Kriittinen</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d">Tärkeä</a>
              </td></tr>
            <tr><td>Server 2003 x64 Edition</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326">Kriittinen</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e">Tärkeä</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326">Kriittinen</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e">Tärkeä</a>
              </td></tr>
            <tr><td>Windows Server 2003 with SP1 for Itanium-based Systems</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5">Kriittinen</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6">Tärkeä</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5">Kriittinen</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6">Tärkeä</a>
              </td></tr>
          </table>


## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin ja laajennettu Inventory-työkalu (ESUIT). Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Huomautus** MBSA 1.2.1:n käyttämää MSSecure.XML-tiedostoa ei päivitetä 9.10.2007 jälkeen. Tämän päivämäärän jälkeen uusia tietoturvapäivityksiä ei lisätä MBSA 1.2.1:n käyttämän MSSecure.XML-tiedostoon eikä Enterprise Scan Tool -tarkistustyökalusta julkaista enää uusia versioita. Tämä ei koske SMS 2.0.n ja SMS 2003:n tietoturvapäivityksen Inventory-työkalua (SUIT) tai laajennettua tietoturvapäivityksen Inventory-työkalua (ESUIT). Lisätietoja on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update** **Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939)-sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU- ja SUS-sivustoissa:

Tässä kuussa:

  - Microsoft on julkaissut kolme tärkeää päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**, MU (Microsoft Update)- ja WSUS (Windows Server Update Services) -sivustoissa.
  - Microsoft ei ole julkistanut yhtään tärkeää Windows-päivitystä, joka **ei kuitenkaan ole tietoturvapäivitys**, WU (Windows Update) -sivustossa.

Huomaa, että nämä tiedot koskevat **vain** sellaisia tärkeitä päivityksiä, **jotka eivät ole tietoturvapäivityksiä** ja jotka julkaistaan saman päivänä kuin tietoturvatiedotteiden yhteenveto Microsoft Update-, Windows Update- ja Windows Server Update Services -sivustoissa. Tietoja **ei** julkaista muina päivinä julkaistavista päivityksistä, **jotka eivät ole tietoturvapäivityksiä**.

#### Tietoturvastrategiat ja yhteisö

**Korjaustiedostojen hallintamenetelmät**

[Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivitysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT** **Pro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - Jesper Johansson teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS07-061
  - Carsten H. Eiram ([Secunia](http://corporate.secunia.com/)) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS07-061
  - Aviv Raff ([Finjan](http://www.finjan.com/)) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS07-061
  - Petko Petkov ([GNUCITIZEN](http://www.gnucitizen.org/)) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS07-061
  - Alla Berzroutchko ([Scanit](http://www.scanit.be/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-062.
  - Amit Klein ([Trusteer](http://www.trusteer.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS07-062.

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Lisätietoa ja yhteystiedot Microsoftin tuotetukeen on [Tuotetuki](http://support.microsoft.com/) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (13. marraskuuta 2007): Tietoturvatiedotteen yhteenveto julkaistu.

*Built at 2014-04-18T01:50:00Z-07:00*

