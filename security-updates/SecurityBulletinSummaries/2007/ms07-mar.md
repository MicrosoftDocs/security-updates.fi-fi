---
title: Microsoftin turvatiedotteiden yhteenveto, maaliskuu 2007
TOCTitle: MS07-MAR
ms:assetid: ms07-mar
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms07-mar(v=Security.10)
ms:contentKeyID: 61225588
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, maaliskuu 2007

Julkaistu: 13. maaliskuuta 2007

**Versio:** 1.0

*Microsoft ei julkaissut tietoturvatiedotteita 13. maaliskuuta 2007.*

**Tietoturva:** Seuraavilla sivustoilla on Microsoftin julkaisemia tietokoneen suojaamista käsitteleviä tietoja:

  - Kotikäyttäjät voivat tutustua näihin tietoihin [Kodin tietoturva](http://www.microsoft.com/finland/athome/security/update/default.mspx) -sivustolla.
  - IT-asiantuntijat saavat lisätietoja englanninkielisestä [TechNet Security Centeristä](http://go.microsoft.com/fwlink/?linkid=21171).

**Korjaustiedostojen hallintamenetelmät:** [Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**IT Pro Security Zone -yhteisö:** Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

**Microsoft Security Notification Service -palvelu:** Saat automaattisen ilmoituksen sähköpostitse aina Microsoftin julkaistessa uuden tietoturvatiedotteen, kun tilaat [Microsoft Technical Security Notification](http://go.microsoft.com/fwlink/?linkid=21163) -palvelun.

#### Tietoturvapäivitykset

*Microsoft ei julkaissut yhtään tietoturvatiedotetta 13. maaliskuuta* *2007.*

## Käyttöönotto

**Software Update Services:**

Microsoft Software Update Services (SUS) -palvelun avulla järjestelmänvalvojat voivat ottaa käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset nopeasti ja luotettavasti Windows 2000- ja Windows Server 2003 -pohjaisissa palvelimissa sekä työasemissa, joissa on Windows 2000 Professional- tai Windows XP Professional -käyttöjärjestelmä.

Lisätietoja tämän tietoturvapäivityksen ottamisesta käyttöön Software Update Services -palvelun avulla on [Software Update Services](http://go.microsoft.com/fwlink/?linkid=21133) -sivustossa.

**Windows Server Update Services:**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server:**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939)-sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää Microsoft Baseline Security Analyzer -työkalua ja Microsoft Office Inventory Tool -työkalua laajan tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseksi. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

**Mic** **rosoft Baseline Security Analyzer:**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Tunnistus- ja käyttöönotto-ohjeet:**

Microsoft on laatinut lisäohjeita tietoturvapäivitysten tunnistamiseen ja käyttöönottamiseen. Näiden ohjeiden avulla myös IT-asiantuntijat osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin, laajennettu Inventory-työkalu ja Enterprise Update Scan (EST) -työkalu. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/default.aspx?scid=kb;en-us;910723).

#### Muita tietoja:

**Windowsin haittaohjelmien poistotyökalu:**

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa: [Windows Update](http://www.microsoft.com/technet/security/bulletin/update.microsoft.com/windowsupdate/), [Microsoft Update](http://update.microsoft.com/microsoftupdate), [Windows Server Update Services](http://www.microsoft.com/windowsserversystem/updateservices/) ja [Download Center](http://www.microsoft.com/downloads/).

Huomaa, että tätä työkalua **ei** jaeta Software Update Services (SUS) -palvelun kautta.

**Tärkeät, muut kuin tietoturvapäivitykset MU-, WU-, WSUS- ja SUS-sivustoissa:**

  - Microsoft on julkaissut on kaksi tärkeää päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**, MU (Microsoft Update)- ja WSUS (Windows Server Update Services) -sivustoissa.
  - Microsoft on julkaissut on neljä tärkeää Windows-päivitystä, **jotka eivät kuitenkaan ole** **tietoturvapäivityksiä**, WU (Windows Update)- ja SUS (Software Update Services) -sivustoissa.

Huomaa, että nämä tiedot koskevat **vain** sellaisia tärkeitä päivityksiä, **jotka eivät ole tietoturvapäivityksiä** ja jotka julkaistaan saman päivänä kuin tietoturvatiedotteiden yhteenveto Microsoft Update-, Windows Update-, Windows Server Update Services- ja Software Update Services -sivustoissa. Tietoja **ei** julkaista muina päivinä julkaistavista päivityksistä, **jotka eivät ole tietoturvapäivityksiä**.

**Muiden tietoturvapäivi** **tysten hankkiminen:**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan security\_patch avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.

**Tuki:**

  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

**Tietoturvaresurssit:**

  - [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21132) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista.
  - [Microsoft Software Update Services](http://go.microsoft.com/fwlink/?linkid=21133)
  - [Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)
  - [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (MBSA)
  - [Microsoft Update](http://update.microsoft.com/microsoftupdate)
  - [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)
  - Windows Update Catalog: Lisätietoja Windows Update Catalogista on [Microsoft Knowledge Base -artikkelissa 323166](http://support.microsoft.com/default.aspx?scid=kb;en-us;323166).
  - [Office Update](http://go.microsoft.com/fwlink/?linkid=21135)

**Vastuuvapauslauseke:**

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

**Versiot:**

  - V1.0 (13. maaliskuuta 2007): Tietoturvatiedotteen yhteenveto julkaistu.

*Built at 2014-04-18T01:50:00Z-07:00*

