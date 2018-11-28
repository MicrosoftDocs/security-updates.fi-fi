---
title: Microsoftin turvatiedotteiden yhteenveto, tammikuu 2008
TOCTitle: MS08-JAN
ms:assetid: ms08-jan
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms08-jan(v=Security.10)
ms:contentKeyID: 61225610
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, tammikuu 2008

Julkaistu: 8. tammikuuta 2008 | Päivitetty: 25. tammikuuta 2008

**Versio:** 1.2

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo tammikuussa 2008 julkaistuista tietoturvatiedotteista.

Tammikuun 2008 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 3. tammikuuta 2008. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Lisätietoja Microsoftin tietoturvatiedotteita koskevasta automaattisesta ilmoituksesta on osoitteessa [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 9. tammikuuta 2008, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt tammikuun tietoturvatiedotteen webcast-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357213&eventcategory=4&culture=en-us&countrycode=us) Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat luokitella kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät muut tietoturvapäivitykset, jotka julkaistaan samana päivänä. Lisätietoja on kohdassa **Muita tietoja**.

### Tietoturvatiedotteet

#### Yhteenveto

Tässä julkaistavat tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (1)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-001</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104919"><strong>Windows TCP/IP:n haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (941644)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa kaksi suoraan Microsoftille ilmoitettua haavoittuvuutta TCP/IP (Transmission Control Protocol/Internet Protocol) -käsittelyssä. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda järjestelmänvalvojan oikeuksilla varustettuja käyttäjätilejä.</td>
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
<td><strong>Windows.</strong> Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (1)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS08-002</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104921"><strong>LSASS:n haavoittuvuus saattaa sallia paikallisen käyttöoikeuksien korottamisen (943485)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa suoraan Microsoftille ilmoitetun Microsoft Windows LSASS:n (Local Security Authority Subsystem Service) haavoittuvuuden. Haavoittuvuus saattaa antaa hyökkääjän suorittaa haluamaansa koodia laajennetuilla käyttöoikeuksilla. Hyödyntämällä tätä haavoittuvuutta onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda järjestelmänvalvojan oikeuksilla varustettuja käyttäjätilejä.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Paikallinen käyttöoikeuksien korottaminen</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows. </strong>Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
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
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=104919">
                  <strong>MS08-001</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=104921">
                  <strong>MS08-002</strong>
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
          
            <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=980f5457-c7b5-421c-8643-0e57429ec156">Keskitaso</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7956632e-17d9-4876-8340-84fe3e43e5cc">Tärkeä</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a766242-2342-4fa0-9b66-8953c54a2211">Kriittinen</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a4cf182-8e36-490e-aefe-edb7b3a0df9c">Tärkeä</a>
              </td></tr>
            <tr><td>Windows XP Professional x64 Edition ja Windows XP Professional x64 Edition Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e8bc7d5-fe81-4ed5-9efa-360738d160ee">Kriittinen</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51fc657b-2b4a-4725-a744-d279e027c4a5">Tärkeä</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 ja Windows Server 2003 Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fda060a5-9a1e-4036-9899-13eb61fdd8be">Tärkeä</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12397b47-b18f-4d4d-b8d7-adec8ff310d5">Tärkeä</a>
              </td></tr>
            <tr><td>Windows Server 2003 x64 Edition ja Windows Server 2003 x64 Edition Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19d993f9-06dd-4dc4-b0cc-c59e822eb8fa">Tärkeä</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f19fd790-a4e6-4a8a-8077-d1bbfe37ecca">Tärkeä</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 with SP1 for Itanium-based Systems ja Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c2264f7-ebbb-40ab-9dbf-9b4e313665a7">Tärkeä</a>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0382a195-aa3d-409b-8a79-9fe61588d8a9">Tärkeä</a>
              </td></tr>
            <tr><td>Windows Small Business Server 2003 Service Pack 1, Windows Small Business Server 2003 R2, Windows Small Business Server 2003 R2 Service Pack 2 ja Windows Home Server</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fda060a5-9a1e-4036-9899-13eb61fdd8be">Kriittinen</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vista</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23c0e03a-db66-4618-bce0-af55e5c1b067">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Windows Vista x64 Edition</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f6a37b1-c604-47c9-932f-485db2eda133">Kriittinen</a>
              </td><td /></tr>
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

**Windows Ser** **ver Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso myös [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) -sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU- ja WSUS-sivustoissa:

Tässä kuussa:

  - Microsoft on julkaissut MU (Microsoft Update) -sivustolla ja WSUS (Windows Server Update Services) -palvelussa viisi tärkeää päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**.
  - Microsoft on julkaissut WU (Windows Update) -sivustolla ja WSUS (Windows Server Update Services) -palvelussa kaksi tärkeää Windows-päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**.

Huomaa, että nämä tiedot koskevat **vain** sellaisia tärkeitä päivityksiä, **jotka eivät ole tietoturvapäivityksiä** ja jotka julkaistaan samana päivänä kuin tietoturvatiedotteiden yhteenveto Microsoft Update-, Windows Update- ja Windows Server Update Services -sivustoissa. Tietoja **ei** julkaista muina päivinä julkaistavista päivityksistä, **jotka eivät ole tietoturvapäivityksiä**.

#### Tietoturvastrategiat ja yhteisö

**Korjaustiedostojen hallintamenetelmät**

[Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäiv** **itysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - [IBM Internet Security Systems X-Force](http://www.iss.net/) (Alex Wheeler ja Ryan Smith) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS08-001](http://go.microsoft.com/fwlink/?linkid=104919)
  - Thomas Garnier ([SkyRecon](http://www.skyrecon.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS08-002](http://go.microsoft.com/fwlink/?linkid=104921)

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (8.1.2008): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (23.1.2008): Windows Small Business Server 2003 Service Pack 2 on lisätty tietoturvatiedotteen yhteenvetoon ohjelmistona, jota tietoturvatiedote MS08-001 koskee.
  - V1.2 (25.1.2008): Windows Small Business Server 2003 Service Pack 1, Windows Small Business Server 2003 R2, Windows Small Business Server 2003 R2 Service Pack 2 ja Windows Home Server on lisätty tietoturvatiedotteen yhteenvetoon ohjelmistoina, jota tietoturvatiedote MS08-001 koskee.

*Built at 2014-04-18T01:50:00Z-07:00*

