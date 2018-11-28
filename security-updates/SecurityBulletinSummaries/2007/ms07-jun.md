---
title: Microsoftin turvatiedotteiden yhteenveto, kesäkuu 2007
TOCTitle: MS07-JUN
ms:assetid: ms07-jun
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms07-jun(v=Security.10)
ms:contentKeyID: 61225587
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, kesäkuu 2007

Julkaistu: 12. kesäkuuta 2007

**Versio:** 1.0

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo kesäkuussa 2007 julkaistuista tietoturvatiedotteista.

Kesäkuun 2007 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka jukaistiin 7. kesäkuuta 2007. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Saat automaattisen ilmoituksen aina Microsoftin julkaistessa uuden tietoturvatiedotteen, kun tilaat [Microsoft Technical Security Notification](http://go.microsoft.com/fwlink/?linkid=21163) -palvelun.

Microsoft isännöi web-lähetystä, jossa käsitellään asiakkaiden esittämiä, näihin tiedotteisiin liittyviä kysymyksiä. Web-lähetyksen ajankohta on keskiviikko kesäkuun 13. 2007, kello 21:00 Suomen aikaa (11:00 Pacific Time). [Rekisteröidy nyt kesäkuun tietoturvatiedotteen web-lähetykseen.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032327013&eventcategory=4&culture=en-us&countrycode=us) Lähetyspäivän jälkeen web-lähetyksen voi ladata katsottavaksi. Lisätietoja on [Microsoftin tietoturvatiedotteista ja web-lähetyksistä kertovassa sivustossa](http://technet.microsoft.com/security/bulletin/summary).

Microsoft antaa myös tietoja, joiden avulla asiakkaat voivat priorisoida kerran kuukaudessa julkaistavat tietoturvapäivitykset ja tärkeät, muut kuin tietoturvapäivitykset, jotka julkaistaan samana päivänä kuin kuukausittaiset tietoturvapäivitykset. Lisätietoja kohdassa **Muita tietoja**.

### Tietoturvatiedot

#### Yhteenveto

Kesäkuun tietoturvatiedotteet luokittelujärjestyksessä:

## Kriittinen (4)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-031</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=91396"><strong>Windowsin suojatun kanavan suojauspaketin haavoittuvuus saattaa sallia koodin suorittamisen verkon kautta (935840)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa yksityishenkilön raportoiman Windowsin suojatun kanavan suojauspaketin haavoittuvuuden. Suojatun kanavan suojauspaketti käyttää tavallisia Internetin SSL (Secure Sockets Layer)- ja TLS (Transport Layer Security) -todennusyhteyskäytäntöjä. Tämä haavoittuvuus saattaa sallia koodin suorittamisen verkon kautta, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet-selaimella tai käyttää sovellusta, jossa käytetään SSL- tai TLS-käytäntöjä. Tämän haavoittuvuuden hyödyntäminen johtaisi kuitenkin todennäköisimmin Internet-selaimen tai sovelluksen sulkeutumiseen. Järjestelmä ei voisi muodostaa yhteyttä web-sivustoihin tai resursseihin SSL- tai TLS-käytännön avulla, ennen kuin järjestelmä on käynnistetty uudelleen.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden</strong> <strong>vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on ehkä käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-033</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=83835"><strong>I</strong> <strong>nternet Explorerin kumulatiivinen tietoturvapäivitys (933566)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa viisi yksityishenkilön ilmoittamia haavoittuvuuksia ja yhden yleisessä tiedossa olleen haavoittuvuuden. Yhtä lukuun ottamatta nämä haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet Explorerilla. Yksi haavoittuvuus saattaa sallia tietojen väärentämisen, ja siihen liittyy myös tietyllä tavalla muodostettu web-sivu. Kaikissa tapauksissa, joissa kyseessä on koodin suorittaminen etäyhteyden avulla, käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Tietojen väärentämistapauksessa haavoittuvuuden hyödyntäminen edellyttää käyttäjän toimia.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on ehkä käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows, In</strong> <strong>ternet Explorer</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-034</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=88627"><strong>Outlook Expressin ja Windows Mailin kumulatiivinen tietoturvapäivitys (929123)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa kaksi yksityishenkilön ilmoittamaa ja kaksi yleisessä tiedossa ollutta haavoittuvuutta. Yksi näistä haavoittuvuuksista saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua sähköpostiviestiä Windows Vistan Windows Mailissa. Muut haavoittuvuudet saattavat sallia tietojen paljastumisen muille käyttäjille, jos käyttäjä tarkastelee tietyllä tavalla muodostettua web-sivua Internet Explorerilla, eikä sitä voi hyödyntää suoraan Outlook Expressissä. Jos kyseessä on haavoittuvuus, joka sallii tietojen paljastumisen muille käyttäjille, käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
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
<td>Microsoft Baseline Security Analyzer ja Enterprise Scan Tool havaitsevat, tarvitseeko tietokone tämän päivityksen. Tietokone on ehkä käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows, Outlook Express, Windows Mail</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-035</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=91397"><strong>Win32 API -liittymä saattaa sallia koodin suorittamisen etäyhteyden välityksellä avulla (935839)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä kriittinen tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Win32 API -liittymän haavoittuvuuden. Tämä haavoittuvuus saattaa sallia koodin suorittamisen etäyhteyden välityksellä ja käyttöoikeuksien laajentamisen, jos API-liittymää, jota haavoittuvuus koskee, käytetään paikallisesti erityisesti muodostetulla sovelluksella. Tätä Win32 API -komponenttia käyttäviä sovelluksia voi siis olla mahdollista käyttää haavoittuvuutta hyödyntävänä hyökkäystapana. Esimerkiksi Internet Explorer käyttää tätä Win32 API -toimintoa jäsentäessä erityisesti muodostettuja web-sivuja.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden</strong> <strong>vaikutus</strong></td>
<td>Koodin suorittaminen verkon välityksellä</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on ehkä käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Tärkeä (1)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-030</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=76089"><strong>Microsoft Vision haavoittuvuudet saattavat sallia koodin suorittamisen etäyhteyden välityksellä (927051)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä tärkeä tietoturvapäivitys korjaa kaksi yksityishenkilön havaitsemaan ja ilmoittamaa haavoittuvuutta sekä muita tietoturvaongelmia, jotka havaittiin tutkinnan aikana. Nämä yksityishenkilön raportoimat haavoittuvuudet saattavat sallia koodin suorittamisen etäyhteyden välityksellä, jos käyttäjä avaa erityisesti muodostetun Visio-tiedoston. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät. Näiden haavoittuvuuksien hyödyntäminen edellyttää käyttäjän suorittamia toimia.</td>
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
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on ehkä käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Office, Visio</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
</tr>
</tbody>
</table>


## Keskitaso (1)

<table>
<thead>
<tr class="header">
<th>Tiedotteen numero</th>
<th>Microsoftin tietoturvatiedote MS07-032</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Tiedotteen otsikko</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=84693"><strong>Windows Vistan haavoittuvuus saattaa s</strong> <strong>allia tietojen paljastumisen muille käyttäjille (931213)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Yhteenveto</strong></td>
<td>Tämä keskitasoinen tietoturvapäivitys korjaa yksityishenkilön ilmoittaman haavoittuvuuden. Tämä haavoittuvuuden vuoksi luvattomat käyttäjät voivat päästä käyttämään paikallisen käyttäjän tietojen tietosäilöjä, kuten rekisterissä ja paikallisessa tiedostojärjestelmässä olevat järjestelmänvalvojan salasanat.</td>
</tr>
<tr class="odd">
<td><strong>Luokitus</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Keskitaso</a></td>
</tr>
<tr class="even">
<td><strong>Haavoittuvuuden vaikutus</strong></td>
<td>Tietojen paljastuminen muille käyttäjille</td>
</tr>
<tr class="odd">
<td><strong>Tunnistus</strong></td>
<td>Microsoft Baseline Security Analyzer tunnistaa, tarvitseeko tietokone tätä päivitystä. Tietokone on ehkä käynnistettävä uudelleen päivityksen jälkeen.</td>
</tr>
<tr class="even">
<td><strong>Ohjelmistot, joita haavoittuvuus koskee</strong></td>
<td><strong>Windows</strong>. Lisätietoja on tämän tietoturvatiedotteen kohdassa Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot</td>
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
    <th>Tiedot        </th>
    <th>Tiedot        </th>
  </tr>
            <tr><td>
                <strong>Tiedotteen numero</strong>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=76089">
                  <strong>MS07-030</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=91396">
                  <strong>MS07-031</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=84693">
                  <strong>MS07-032</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=83835">
                  <strong>MS07-033</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=88627">
                  <strong>MS07-034</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=91397">
                  <strong>MS07-035</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td>
                <strong>Luokitus</strong>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Tärkeä</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Kriittinen</strong>
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
                  <strong>Kriittinen</strong>
                </a>
              </td><td>
                <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Kriittinen</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="7">Windows-käyttöjärjestelmät, joita haavoittuvuus koskee</th></tr>
          
            <tr><td>Microsoft Windows 2000 Service Pack 4</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b8e728c-cb9f-4176-93a0-bf42d6387f93">Keskitaso</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3918ac76-ebb6-4886-9a9e-808eafb96b1b">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8615e6f3-415b-4c23-ba52-7eef70a11d77">Kriittinen</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27c7f1b9-2d1d-40cb-ad7e-bfedb6156a9c">Kriittinen</a>
              </td></tr>
            <tr><td>Windows XP Professional x64 Edition</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a">Kriittinen</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a">Kriittinen</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2">Kriittinen</a>
              </td></tr>
            <tr><td>Windows Server 2003 Service Pack 1</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f">Tärkeä</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f">Tärkeä</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610">Kriittinen</a>
              </td></tr>
            <tr><td>Server 2003 x64 Edition</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da424772-079c-4351-9759-8886e0f1ba79">Tärkeä</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da424772-079c-4351-9759-8886e0f1ba79">Tärkeä</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182">Kriittinen</a>
              </td></tr>
            <tr><td>Windows Server 2003 with SP1 for Itanium-based Systems</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4">Tärkeä</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99">Kriittinen</a>
              </td></tr>
            <tr class="alternateRow"><td>Itanium-järjestelmien Windows Server 2003 ja SP2</td><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4">Tärkeä</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99">Kriittinen</a>
              </td></tr>
            <tr><td>Windows Vista</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cdf79d00-6f34-404b-8ad5-a2801ff35443">Keskitaso</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89dde3f4-4123-4c97-86d8-00a83462c34b">Keskitaso</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
          
            <tr><th colspan="7">Windows-käyttöjärjestelmien osat, joita haavoittuvuus koskee</th></tr>
          
            <tr><td>Internet Explorer 5.01 Service Pack 4 ja Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b49f1ed-abe3-4dbd-a91d-973415658f6b">Kriittinen</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6 Service Pack 1 ja Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c958650-28d2-4dd0-96a8-dbfe79ce3f68">Kriittinen</a>
              </td><td /><td /></tr>
            <tr><td>Windows XP Service Pack 2:n Internet Explorer 6</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60fb294e-a8e1-405e-a289-2d2723edf7ee">Kriittinen</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Editionin Internet Explorer 6 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=086d6d6e-4703-4c6c-a7af-b6dafeeede5d">Kriittinen</a>
              </td><td /><td /></tr>
            <tr><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Internet Explorer 6</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ed19127-5c2d-48e4-a8d1-090dc69fd68b">Kriittinen</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Internet Explorer 6</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1449eb5d-6e4c-4332-8cb6-ab9ee59c9a95">Kriittinen</a>
              </td><td /><td /></tr>
            <tr><td>Internet Explorer 6 Itanium-järjestelmissä, kun käyttöjärjestelmänä on Windows Server 2003 SP1, ja Itanium-järjestelmien Windows Server 2003 SP2:</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b628a3cc-a70c-478a-a10c-eee254ee34ab">Kriittinen</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2:n Internet Explorer 7</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2191703-8cbd-4959-9f84-e13f21173926">Kriittinen</a>
              </td><td /><td /></tr>
            <tr><td>Windows XP Professional x64 Editionin Internet Explorer 7 ja Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=69c526b8-8b07-42bc-9bed-e18deae21c8e">Kriittinen</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1:n ja Windows Server 2003 Service Pack 2:n Internet Explorer 7</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a074d9c0-1fed-4753-845e-073cfce99f45">Keskitaso</a>
              </td><td /><td /></tr>
            <tr><td>Windows Server 2003 x64 Editionin ja Windows Server 2003 x64 Edition Service Pack 2:n Internet Explorer 7</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=744acb43-64da-48cc-ae69-9386b597eabc">Keskitaso</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 Itanium-järjestelmissä, kun käyttöjärjestelmänä on Windows Server 2003 SP1, ja Itanium-järjestelmien Windows Server 2003 SP2:</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=069c1560-b5e5-4dfe-a18d-e0507d406028">Keskitaso</a>
              </td><td /><td /></tr>
            <tr><td>Windows Vistan Internet Explorer 7</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77287386-48eb-4aa9-9537-626a3093aaf7">Kriittinen</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Editionin Internet Explorer 7</td><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77287386-48eb-4aa9-9537-626a3093aaf7">Kriittinen</a>
              </td><td /><td /></tr>
            <tr><td>Outlook Express 6 ja Windows XP Service Pack 2</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27cca556-0872-4803-b610-4c895ceb99aa">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 ja Windows XP Professional x64 Edition</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7">Tärkeä</a>
              </td><td /></tr>
            <tr><td>Windows XP Professional x64 Edition Service Pack 2:n Outlook Express 6</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7">Tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 ja Windows Server 2003 Service Pack 1</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93808a74-035c-4ab7-9283-c693d7bd82be">Ei tärkeä</a>
              </td><td /></tr>
            <tr><td>Outlook Express 6 ja Windows Server 2003 Service Pack 2</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93808a74-035c-4ab7-9283-c693d7bd82be">Ei tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 ja Windows Server 2003 x64 Edition</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f63323a9-e285-45e5-84bd-71ae9da126e3">Keskitaso</a>
              </td><td /></tr>
            <tr><td>Windows Server 2003 x64 Edition Service Pack 2:n Outlook Express 6</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f63323a9-e285-45e5-84bd-71ae9da126e3">Keskitaso</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 ja Itanium-järjestelmien Windows Server 2003 SP1</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025">Ei tärkeä</a>
              </td><td /></tr>
            <tr><td>Outlook Express 6 ja Itanium-järjestelmien Windows Server 2003 SP2</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025">Ei tärkeä</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vistan Windows Mail</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee57de19-44ea-48f2-ae28-e76fd2018633">Kriittinen</a>
              </td><td /></tr>
            <tr><td>Windows Vista x64 Editionin Windows Mail</td><td /><td /><td /><td /><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=343db20f-7794-4423-b11d-885329fbdf78">Kriittinen</a>
              </td><td /></tr>
          
            <tr><th colspan="7">Office-ohjelmistot, joita haavoittuvuus koskee</th></tr>
          
            <tr class="alternateRow"><td>Visio 2002 Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc1d0483-27e8-4541-b81d-4a47973bea30">Tärkeä</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td>Visio 2003 Service Pack 2</td><td>
                <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c47f432e-8538-42fd-92c9-7e0f1d643e8e">Tärkeä</a>
              </td><td /><td /><td /><td /><td /></tr>
          </table>


**Huomautuksia**

**\[1\]** Tähän käyttöjärjestelmään on saatavana tietoturvapäivitys. Tarkista taulukosta, mikä tietoturvatiedote käsittelee haavoittuvuuden sisältävää ohjelmistoa tai osaa.

## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)-, [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)- ja [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) -sivustoissa. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security\_patch" avulla. Tietoturvapäivitykset voidaan ladata lisäksi Windows Update Catalog -palvelusta. Lisätietoja Windows Update Catalogista on [Microsoft Knowledge Base -artikkelissa 323166](http://support.microsoft.com/kb/323166).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut tunnistus- ja käyttöönotto-ohjeet tässä kuussa julkaistuille tietoturvapäivityksille. Näiden ohjeiden avulla myös IT-alan ammattilaiset osaavat käyttää erilaisia työkaluja tietoturvapäivitysten käyttöönottamiseen. Näitä työkaluja ovat esimerkiksi Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office-tunnistustyökalu, MSM (Microsoft Systems Management) -palvelin, laajennettu Inventory-työkalu ja Enterprise Update Scan (EST) -työkalu. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer jaEnterprise Update Scan Tool**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

Kun MBSA 1.2.1 ei tue tietyn tietoturvapäivityksen tunnistamista, Microsoft julkaisee kyseistä tietoturvapäivitystä varten EST (Enterprise Update Scan Tool) -version. Lisätietoja EST-tarkistustyökalusta on sivustossa [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193).

**Huomautus** MBSA 1.2.1:n käyttämää MSSecure.XML-tiedostoa ei päivitetä 9.10.2007 jälkeen. Tämän päivämäärän jälkeen uusia tietoturvapäivityksiä ei lisätä MBSA 1.2.1:n käyttämän MSSecure.XML-tiedostoon eikä Enterprise Scan Tool -tarkistustyökalusta julkaista enää uusia versioita. Lisätietoja on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Software Update Services**

Microsoft Software Update Services (SUS) -palvelun avulla järjestelmänvalvojat voivat ottaa käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset nopeasti ja luotettavasti Windows 2000- ja Windows Server 2003 -pohjaisissa palvelimissa sekä työasemissa, joissa on Windows 2000 Professional- tai Windows XP Professional -käyttöjärjestelmä.

Lisätietoja tämän tietoturvapäivityksen ottamisesta käyttöön Software Update Services -palvelun avulla on [Software Update Services](http://go.microsoft.com/fwlink/?linkid=21133) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**Systems Management Server**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän. Lisätietoja siitä, kuinka järjestelmänvalvojat voivat käyttää SMS 2003:a tietoturvapäivitysten asentamiseen, on [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939)-sivustossa. SMS 2.0:n käyttäjät voivat asentaa tietoturvapäivityksiä myös [Software Updates Services Feature Packin](http://go.microsoft.com/fwlink/?linkid=33340) avulla. Lisätietoja SMS:stä on [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) -sivustossa.

**Huomautus** SMS hyödyntää laaja-alaisesti Microsoft Baseline Security Analyzer- ja Microsoft Office Detection Tool -työkalua tietoturvapäivityksien tunnistamiseen ja asennukseen liittyvän tuen tarjoamiseen. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat käyttää Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=33387) ja [SMS 2.0 Administration Feature Packiin](http://go.microsoft.com/fwlink/?linkid=21161)) päivitysten asentamisessa.

### Muita tietoja:

#### Windowsin haittaohjelmien poistotyökalu

Microsoft on julkaissut päivitetyn version Microsoft Windowsin haittaohjelmien poistotyökalusta seuraavissa sivustoissa:  Windows Update, Microsoft Update, Windows Server Update Services ja Download Center.

Huomaa, että tätä työkalua **ei** jaeta Software Update Services (SUS) -palvelun kautta.

#### Tärkeät, muut kuin tietoturvapäivitykset MU-, WU-, WSUS- ja SUS-sivustoissa

Tässä kuussa:

  - Microsoft on julkaissut seitsemän tärkeää päivitystä, **jotka eivät kuitenkaan ole tietoturvapäivityksiä**, MU (Microsoft Update)- ja WSUS (Windows Server Update Services) -sivustoissa.
  - Microsoft ei ole julkaissut yhtään Windows-päivitystä, **joka ei kuitenkaan ole tietoturvapäivitys**, WU (Windows Update)- ja SUS (Software Update Services) -sivustoissa.

Huomaa, että nämä tiedot koskevat **vain** sellaisia tärkeitä päivityksiä, **jotka eivät ole tietoturvapäivityksiä** ja jotka julkaistaan saman päivänä kuin tietoturvatiedotteiden yhteenveto Microsoft Update-, Windows Update-, Windows Server Update Services- ja Software Update Services -sivustoissa. Tietoja **ei** julkaista muina päivinä julkaistavista päivityksistä, **jotka eivät ole tietoturvapäivityksiä**.

#### Tietoturvastrategiat ja yhteisö

**Korjaustiedostojen hallintamenetelmät**

[Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) -sivustossa on lisätietoja Microsoftin suosittelemista tietoturvapäivitysten käyttötavoista.

**Muiden tietoturvapäivitysten hankkiminen**

Muita tietoturvapäivityksiä on saatavilla seuraavista sivustoista:

  - Tietoturvapäivityksiä voi ladata [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan security\_patch avulla.
  - Kotikäyttäjille suunnattujen ympäristöjen päivityksiä voi ladata [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) -sivustosta.
  - Voit hankkia tämän kuun Windows Update -tietoturvapäivitykset Security and Critical Releases ISO Image -vedostiedostona Download Centeristä. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Zone Community**

Opi uusia tietoturvatekniikoita IT-infrastruktuurisi turvallisuuden parantamiseksi ja keskustele tietoturvaan liittyvistä aiheista muiden IT-alan ammattilaisten kanssa [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) -sivustossa.

#### Kiitokset

Microsoft [kiittää](http://go.microsoft.com/fwlink/?linkid=21127) yhteistyöstä seuraavia tahoja, joiden ansiosta asiakkaiden turvallisuutta on parannettu:

  - Tuntematon tutkija (yhteistyössä [iDefense VCP:n](http://idefense.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Tom Cross ([ISS](http://www.iss.net/)) teki yhteistyötä Microsoftin kanssa selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Tuntematon tutkija (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja [Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Sam Thomas (yhteistyössä [TippingPointin](http://www.tippingpoint.com/) ja[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Will Dorman ([CERT/CC](http://www.cert.org/certcc.html)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - cocoruder ([Fortinet Security Research](http://www.fortinet.com/)) teki yhteistyötä Microsoftin kanssa selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Billy Rios ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-035](http://go.microsoft.com/fwlink/?linkid=91397).
  - Thomas Lim ([COSEINC](http://www.coseinc.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-031](http://go.microsoft.com/fwlink/?linkid=91396).
  - [SANS ISC](http://isc.sans.org/) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa [MS07-034](http://go.microsoft.com/fwlink/?linkid=88627).
  - Yosuke Hasegawa ([WebAppSec.JP](https://www.webappsec.jp/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-034](http://go.microsoft.com/fwlink/?linkid=88627).
  - Robbie Sohlman ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa [MS07-032](http://go.microsoft.com/fwlink/?linkid=84693).

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [Microsoftin tuotetukipalvelut](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia.
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (kesäkuun 12. 2007): Tietoturvatiedotteen yhteenveto julkaistu.

*Built at 2014-04-18T01:50:00Z-07:00*

