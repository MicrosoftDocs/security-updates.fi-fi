---
title: Microsoftin turvatiedotteiden yhteenveto, joulukuu 2010
TOCTitle: MS10-DEC
ms:assetid: ms10-dec
ms:mtpsurl: https://technet.microsoft.com/fi-FI/library/ms10-dec(v=Security.10)
ms:contentKeyID: 61225699
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Microsoftin turvatiedotteiden yhteenveto, joulukuu 2010

Julkaistu: 14. joulukuuta 2010 | Päivitetty: 15. joulukuuta 2010

**Versio:** 1.1

Tässä tietoturvatiedotteiden yhteenvedossa on luettelo joulukuussa 2010 julkaistuista tietoturvatiedotteista.

Joulukuun 2010 tietoturvatiedotteiden julkaisun yhteydessä tämä tietoturvatiedotteiden yhteenveto korvaa tietoturvatiedotteiden ennakkoilmoituksen, joka julkaistiin 9. joulukuuta 2010. Lisätietoja tietoturvatiedotteiden ennakkoilmoituspalvelusta on [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance) -sivulla (englanninkielinen).

Katso lisätietoja, kuinka voit saada automaattisen ilmoituksen, kun Microsoftin tietoturvatiedote julkaistaan: [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) (englanninkielinen).

Microsoft isännöi webcast-lähetystä, jossa käsitellään asiakkaiden esittämiä näihin tiedotteisiin liittyviä kysymyksiä. Webcast-lähetyksen ajankohta on 15. joulukuuta 2010, kello 21 Suomen aikaa (kello 11.00 Tyynenmeren aikaa, USA ja Kanada). [Rekisteröidy nyt joulukuun tietoturvatiedotteen webcast-lähetykseen](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454444&eventcategory=4&culture=en-us&countrycode=us). Tämän päivämäärän jälkeen webcast-lähetyksestä voi katsoa tallenteen, lisätietoja on [Microsoftin tietoturvatiedotteista ja webcast-lähetyksistä](http://technet.microsoft.com/security/bulletin/summary) kertovassa englanninkielisessä sivustossa.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td><strong>Internet Explorerin kumulatiivinen tietoturvapäivitys (2416400)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa neljä yksityishenkilön ilmoittamaa ja kolme yleisessä tiedossa olevaa Internet Explorerin haavoittuvuutta. Vakavimmat haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tietyllä tavalla muodostetun sivun Internet Explorerissa. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td><strong>OTF (OpenType Font) -</strong> <strong>ohjaimen haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (2296199)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa useita yksityishenkilön ilmoittamia Windowsin OTF (Open Type Font) -haavoittuvuuksia, jotka saattavat sallia koodin suorittamisen verkon välityksellä. Hyökkääjä voi sijoittaa tietyllä tavalla muodostetun OpenType-fontin jaettuun verkkoresurssiin. Ohjauspolku, jota haavoittuvuus koskee, käynnistyy, kun käyttäjä siirtyy jakamaan resurssia Windowsin Resurssienhallinnassa, jolloin tietyllä tavalla muodostettu fontti voi ottaa hallintaansa koko järjestelmän, jota haavoittuvuus koskee. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kriittinen</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203463">MS10-092</a></td>
<td><strong>Tehtävien ajoituksen haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (2305420)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Windowsin Tehtävien ajoituksen haavoittuvuuden. Haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen, jos hyökkääjä on kirjautunut järjestelmään, jota haavoittuvuus koskee, ja suorittanut tietyllä tavalla muodostetun sovelluksen. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja pystyttävä kirjautumaan paikallisesti, jotta hän pystyy hyödyntämään tätä haavoittuvuutta. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206698">MS10-093</a></td>
<td><strong>Windows Movie Makerin</strong> <strong>haavoittuvuus saattaa sallia ko</strong> <strong>odin suorittamisen verkon välityksellä (2424434)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Windows Movie Makerin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä onnistuu saamaan käyttäjän avaamaan oikean Windows Movie Maker -tiedoston siinä verkkokansiossa, jossa myös tietyllä tavalla muodostettu kirjastotiedosto on. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja avattava tiedosto tästä sijainnista. Lisäksi sovelluksen, jota haavoittuvuus koskee, on ladattava kyseinen tiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206699">MS10-094</a></td>
<td><strong>Windows Media Encoderin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2447961)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Windows Media Encoderin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos hyökkääjä onnistuu saamaan käyttäjän avaamaan oikean Windows Media Profile (.prx) -tiedoston siinä verkkokansiossa, jossa myös tietyllä tavalla muodostettu kirjastotiedosto on. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja avattava tiedosto tästä sijainnista. Lisäksi sovelluksen, jota haavoittuvuus koskee, on ladattava kyseinen tiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206683">MS10-095</a></td>
<td><strong>Microsoft</strong> <strong>Windowsin</strong> <strong>haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2385678)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa tiedoston, joka on tyypiltään esimerkiksi .eml ja .rss (Windows Live Mail) tai .wpost (Microsoft Live Writer), siinä verkkokansiossa, jossa myös tietyllä tavalla muodostettu kirjastotiedosto on. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja avattava tiedosto tästä sijainnista. Lisäksi sovelluksen, jota haavoittuvuus koskee, on ladattava kyseinen tiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206738">MS10-096</a></td>
<td><strong>Windowsin osoitteiston haavoittuvuus saattaa sallia koodin suorittamis</strong> <strong>en verkon välityksellä (2423089)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Windowsin osoitteiston haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa Windowsin osoitteistotiedoston siinä verkkokansiossa, jossa myös tietyllä tavalla muodostettu kirjastotiedosto on. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja avattava tiedosto tästä sijainnista. Lisäksi sovelluksen, jota haavoittuvuus koskee, on ladattava kyseinen tiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206689">MS10-097</a></td>
<td><strong>Suojaamattoman</strong> <strong>kirjaston lataaminen ohjatussa internet-yhteyden kirjautumisessa saattaa sallia koodin suorittamisen verkon välityksellä (2443105)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yleisessä tiedossa olevan Microsoft Windowsin ohjatun internet-yhteyden kirjautumisen haavoittuvuuden. Tämä tietoturvatiedote on luokiteltu tärkeäksi kaikissa tuetuissa Windows XP- ja Windows Server 2003 -versioissa. Haavoittuvuus ei koske tuettuja Windows Vista-, Windows Server 2008-, Windows 7- ja Windows Server 2008 R2 -versioita.<br />
<br />
Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa .ins- tai .isp-tiedoston siinä verkkokansiossa, jossa myös tietyllä tavalla muodostettu kirjastotiedosto on. Jotta hyökkäys onnistuisi, käyttäjän on vierailtava ei-luetetussa etätiedostojärjestelmässä tai jaetussa WebDAV-resurssissa ja avattava tiedosto tästä sijainnista. Lisäksi sovelluksen, jota haavoittuvuus koskee, on ladattava kyseinen tiedosto.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td><strong>Windows-ytimen ohjaimien haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (2436673)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yhden yleisessä tiedossa olevan haavoittuvuuden ja useita yksityishenkilön ilmoittamia Microsoft Windowsin haavoittuvuuksia. Haavoittuvuudet saattavat sallia käyttöoikeuksien korottamisen, jos hyökkääjä on kirjautunut paikallisesti ja suorittaa tietyllä tavalla muodostetun sovelluksen. Hyökkääjällä on oltava voimassaolevat kirjautumistiedot ja hyökkääjän on pystyttävä kirjautumaan paikallisesti, jotta haavoittuvuutta voi hyödyntää. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään näitä haavoittuvuuksia.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206365">MS10-099</a></td>
<td><strong>Reitityksen ja etäkäytön haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (2440591)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Windowsin NDProxy-osan reitityksen ja etäkäytön haavoittuvuuden. Tämä tietoturvatiedote on luokiteltu tärkeäksi kaikissa tuetuissa Windows XP- ja Windows Server 2003 -versioissa. Haavoittuvuus ei koske tuettuja Windows Vista-, Windows Server 2008-, Windows 7- ja Windows Server 2008 R2 -versioita.<br />
<br />
Haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen, jos hyökkääjä kirjautuu järjestelmään, jota haavoittuvuus koskee, ja suorittaa tietyllä tavalla muodostetun sovelluksen. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja pystyttävä kirjautumaan paikallisesti, jotta hän pystyy hyödyntämään tätä haavoittuvuutta. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204906">MS10-100</a></td>
<td><strong>Käyttäjän hyväksynnän ilmaisevan liittymän</strong> <strong>haavoittuvuus saattaa sallia käyttöoikeuksien korottamisen (2442962)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman käyttäjän hyväksynnän ilmaisevan liittymän haavoittuvuuden. Haavoittuvuudet saattavat sallia käyttöoikeuksien korottamisen, jos hyökkääjä suorittaa tietyllä tavalla muodostetun sovelluksen järjestelmässä, jota haavoittuvuus koskee. Hyökkääjällä on oltava kelvolliset kirjautumiskäyttöoikeudet ja SeImpersonatePrivilege ja hänen on pystyttävä kirjautumaan paikallisesti, jotta hän voisi hyödyntää tätä haavoittuvuutta. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Käyttöoikeuksien korottaminen</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=201319">MS10-101</a></td>
<td><strong>Windowsin verkkokirjauspalvelun haavoittuvuus saattaa sallia palveluneston (2207559)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman verkkokirjautumisen etäproseduurikutsupalvelun haavoittuvuuden, joka koskee niitä Windows Serverin versioita, jotka on määritetty toimimaan toimialueen ohjauskoneina. Haavoittuvuus saattaa sallia palveluneston, jos hyökkääjä lähettää tietyllä tavalla muodostetun etäproseduurikutsupaketin verkkokirjautumisen etäproseduurikutsupalvelun liittymään järjestelmässä, jota haavoittuvuus koskee. Jotta hyökkääjä voisi hyödyntää tätä haavoittuvuutta, hänellä on oltava järjestelmänvalvojan oikeudet sellaiseen koneeseen, joka on liitetty samaan toimialueeseen kuin se toimialueen ohjauskone, jota haavoittuvuus koskee.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Palvelunesto</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=205309">MS10-102</a></td>
<td><strong>Hyper-V:n haavoittuvuus saattaa sallia palveluneston (2345316)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Windows Server 2008 Hyper-V:n ja Windows Server 2008 R2 Hyper-V:n haavoittuvuuden. Haavoittuvuus saattaa sallia palveluneston, jos todennettu käyttäjä lähettää tietyllä tavalla muodostetun paketin VMBus-väylään, joka on yhdessä Hyper-V-palvelimessa olevassa vieras-virtuaalikoneessa. Jotta hyökkääjä pystyisi hyödyntämään tätä haavoittuvuutta, hänellä on oltava kelvolliset kirjautumisoikeudet ja hänen on pystyttävä lähettämään tietyllä tavalla muodostettu paketti vieras-virtuaalikoneesta. Anonyymit käyttäjät tai etäkäyttäjät eivät pysty hyödyntämään tätä haavoittuvuutta.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Palvelunesto</td>
<td>Edellyttää uudelleenkäynnistystä</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td><strong>Microsoft Publisherin haavoittuvuudet saat</strong> <strong>tavat sallia koodin suorittamisen verkon välityksellä (2292970)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa viisi yksityishenkilön ilmoittamaa Microsoft Publisherin haavoittuvuutta, jotka saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä avaa erityisesti muodostetun Publisher-tiedoston. Hyödyntämällä jotakin näistä haavoittuvuuksista onnistuneesti hyökkääjä voi saada kokonaan hallintaansa haavoittuvuuden sisältävän järjestelmän. Tällöin hyökkääjä voi asentaa ohjelmia tai tarkastella, muuttaa ja poistaa tietoja tai luoda käyttäjätilejä kaikilla valtuuksilla. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206469">MS10-104</a></td>
<td><strong>Microsoft SharePointin haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä (2455005)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft SharePointin haavoittuvuuden. Haavoittuvuus saattaa sallia koodin suorittamisen verkon välityksellä suojatun Vieras-tilin yhteydessä, jos hyökkääjä lähettää tietyllä tavalla muodostetun SOAP-pyynnön tiedostojen muuntamisen käynnistyspalveluun sellaisessa SharePoint-palvelinympäristössä, jossa käytetään tiedostojen muuntamisen kuormituksen tasauspalvelua. Oletusarvoisesti tiedostojen muuntamisen kuormituksen tasauspalvelua ja tiedostojen muuntamisen käynnistyspalvelua ei ole otettu käyttöön Microsoft Office SharePoint Server 2007:ssä.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft SharePoint</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td><strong>Microsoft Officen grafiikkasuodattimien haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä (968095)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa seitsemän yksityishenkilön ilmoittamaa Microsoft Officen haavoittuvuutta. Haavoittuvuudet saattavat sallia koodin suorittamisen verkon välityksellä, jos käyttäjä tarkastelee tietyllä tavalla muodostettua kuvatiedostoa Microsoft Officella. Jotakin näistä haavoittuvuuksista onnistuneesti hyödyntävä hyökkääjä saattaa saada samat käyttöoikeudet kuin paikallinen käyttäjä. Käyttäjät, joiden tilit on määritetty niin, että heillä on järjestelmään vain rajoitetut käyttöoikeudet, eivät ole niin alttiina tälle hyökkäykselle kuin järjestelmänvalvojan käyttöoikeuksin toimivat käyttäjät.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Tärkeä</a><br />
Koodin suorittaminen verkon välityksellä</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204624">MS10-106</a></td>
<td><strong>Microsoft Exchange Serverin haavoittuvuus</strong> <strong>saattaa sallia palveluneston (2407132)</strong><br />
<br />
Tämä tietoturvapäivitys korjaa yksityishenkilön ilmoittaman Microsoft Exchange Serverin haavoittuvuuden. Haavoittuvuus saattaa sallia palveluneston, jos todennettu hyökkääjä lähettää tietyllä tavalla muotoillun verkkoviestin tietokoneeseen, jossa on käynnissä Exchange-palvelu. Palomuurikäytännöistä ja palomuurin vakiomäärityksistä annetut toimintaohjeet suojaavat verkkoa hyökkäyksiltä, joiden lähde on yritysverkon ulkopuolella. Hyvän käytännön mukaisesti internetiin yhteydessä olevissa järjestelmissä pitäisi olla mahdollisimman vähän portteja alttiina uhille.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Keskitaso</a><br />
Palvelunesto</td>
<td>Tietokone on ehkä käynnistettävä uudelleen</td>
<td>Microsoft Exchange</td>
</tr>
</tbody>
</table>


## Hyödyntämisindeksi

Seuraavassa taulukossa on kunkin tässä kuussa käsitellyn haavoittuvuuden hyödyntämisluokitus. Haavoittuvuudet on lueteltu laskevassa järjestyksessä ensin hyödyntämisasteen ja sitten CVE-tunnuksen mukaan. Taulukossa on vain haavoittuvuudet, jotka on luokiteltu tiedotteissa kriittisiksi tai tärkeiksi.

**Kuinka taulukkoa käytetään?**

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td>pubconv.dll-haavoittuvuus (kokoarvon keon vioittuminen)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2569">CVE-2010-2569</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td>pubconv.dll-haavoittuvuus (keon ylivuoto)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2570">CVE-2010-2570</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206689">MS10-097</a></td>
<td>Suojaamattoman kirjastoon lataamisen haavoittuvuus ohjatussa internet-yhteyden kirjautumisessa</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3144">CVE-2010-3144</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><strong>Tämä haavoittuvuus on ollut yleisessä tiedossa</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206738">MS10-096</a></td>
<td>Suojaamattoman kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3147">CVE-2010-3147</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><strong>Tämä</strong> <strong>haavoittuvuus on ollut yleisessä tiedossa</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203463">MS10-092</a></td>
<td>Tehtävien ajoituksen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3338">CVE-2010-3338</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><strong>Tätä haavoittuvuutta hyödynnetään internet-ekosysteemissä</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td>HTML-objektin muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3340">CVE-2010-3340</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td>HTML-objektin muistin vioittumisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3343">CVE-2010-3343</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td>Haavoittuvuus HTML-elementin muistin käytössä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3345">CVE-2010-3345</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td>Haavoittuvuus HTML-elementin muistin käytössä</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3346">CVE-2010-3346</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>Win32k:n puskurin ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3939">CVE-2010-3939</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><strong>Tämä haavoittuvuus on ollut yleisessä tiedossa</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>Win32k PFE:n osoittimen double free -haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3940">CVE-2010-3940</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>Win32k:n osoittimen linkityshaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3943">CVE-2010-3943</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>Win32k:n muistin vioittumisenhaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3944">CVE-2010-3944</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>FlashPix-kuvamuuntimen puskurin ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3951">CVE-2010-3951</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td>OpenType-fontin double free -haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3957">CVE-2010-3957</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td>OpenTypen CMAP-taulukon haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3959">CVE-2010-3959</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204906">MS10-100</a></td>
<td>Käyttäjän hyväksyntää ilmaisevan liittymän käyttäjäksi tekeytymisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3961">CVE-2010-3961</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td>Alustamattoman muistin vioittumishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3962">CVE-2010-3962</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><strong>Tätä haavoittuvuutta hyödynnetään nyt internet-ekosysteemissä</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206365">MS10-099</a></td>
<td>Ytimen NDProxyn puskurin ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3963">CVE-2010-3963</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206469">MS10-104</a></td>
<td>Väärinmuodostetun pyyntökoodin suorittamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3964">CVE-2010-3964</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206699">MS10-094</a></td>
<td>Suojaamattoman kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3965">CVE-2010-3965</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><strong>Tämä haavoittuvuus on ollut yleisessä tiedossa</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206683">MS10-095</a></td>
<td>Suojaamattoman BranchCache-kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3966">CVE-2010-3966</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206698">MS10-093</a></td>
<td>Suojaamattoman kirjastoon lataamisen haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3967">CVE-2010-3967</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Yhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td><strong>Tämä haavoittuvuus on ollut yleisessä tiedossa</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td>Pubconv.dll-haavoittuvuus (muistin vioittuminen virheellisen taulukoinnin vuoksi)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2571">CVE-2010-2571</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>Win32k:n double free -haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3941">CVE-2010-3941</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>Win32k:n WriteAV-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3942">CVE-2010-3942</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>CGM-kuvamuuntimen puskurin ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3945">CVE-2010-3945</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>PICT-kuvamuuntimen kokonaisluvun ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3946">CVE-2010-3946</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>TIFF-kuvamuuntimen keon ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3947">CVE-2010-3947</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>TIFF-kuvamuuntimen puskurin ylivuotohaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3949">CVE-2010-3949</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>TIFF-kuvamuuntimen muistin vioittumishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3950">CVE-2010-3950</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>FlashPix-kuvamuuntimen keon vioittumishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3952">CVE-2010-3952</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td>Taulukkoindeksoinnin muistin vioittumishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3955">CVE-2010-3955</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td>OpenType-fontin indeksointihaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3956">CVE-2010-3956</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Epäyhtenäinen hyväksikäyttökoodi todennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=201319">MS10-101</a></td>
<td>Verkkokirjautumisen etäproseduurikutsun Null-viittauksen poistamisen DOS-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2742">CVE-2010-2742</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Haavoittuvuus aiheuttaa ainoastaan palveluneston</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204624">MS10-106</a></td>
<td>Exchange Serverin päättymätön silmukka -haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3937">CVE-2010-3937</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Haavoittuvuus aiheuttaa ainoastaan palveluneston</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td>Microsoft Publisherin muistin vioittumishaavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3954">CVE-2010-3954</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>(Ei mitään)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=205309">MS10-102</a></td>
<td>Hyper-V:n VMBus-haavoittuvuus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3960">CVE-2010-3960</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Toimiva hyväksikäyttökoodi epätodennäköinen</td>
<td>Haavoittuvuus aiheuttaa ainoastaan palveluneston</td>
</tr>
</tbody>
</table>


## Ohjelmistot, joita haavoittuvuus koskee, ja lataussivustot

Seuraavissa taulukoissa tiedotteet on järjestetty pääohjelmistoluokkien ja vakavuuden mukaan.

**Taulukoiden käyttö**

Näiden taulukoiden avulla voit selvittää, mitä tietoturvapäivityksiä järjestelmääsi on asennettava. Katso, sisältääkö taulukko käyttämäsi ohjelman tai osan ja koskeeko jokin tietoturvapäivitys niiden asennusta. Jos ohjelma tai osa on luettelossa, saatavana olevaan ohjelmistopäivitykseen on linkki. Myös ohjelmistopäivityksen luokitus mainitaan.

**Huomautus** Yksittäinen haavoittuvuus saattaa edellyttää usean tietoturvapäivityksen asentamista. Voit tarkistaa järjestelmääsi asennettujen ohjelmien tai osien tarvitsemat päivitykset tutustumalla tarkemmin kuhunkin yksittäiseen tietoturvatiedotteeseen.

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
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="14">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen </strong>
                    <strong>numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-</strong>
                      <strong>090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-</strong>
                      <strong>092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-</strong>
                      <strong>093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-</strong>
                      <strong>094</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-</strong>
                      <strong>095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10</strong>
                      <strong>-096</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-</strong>
                      <strong>100</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-</strong>
                      <strong>101</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-</strong>
                      <strong>102</strong>
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
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>Ei mitään</td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6031d98a-cd0f-4dd8-80b6-70a7167e9e55">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=922a0835-7f69-4e37-a9f7-c64e976e3513">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a55b8029-9499-4219-99b7-65c30b0b864a">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cdef3358-ad3e-40a6-9ba5-3be220a56a65">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1">Windows Media Encoder 9 x86</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46baa431-126c-4fa5-9a7b-525008e2817d">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa9a1aac-b9c5-4d4e-9083-a080ad4ccc6f">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb9d1657-5beb-4372-b74c-a612a6fff5a8">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d0ae558-a4f2-4048-b5fd-ba072ca35e48">Windows XP Service Pack 3</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d3a5678-77f8-4ebc-8775-aedd25ef0eb8">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7c826b0-4aac-41ce-b297-6b6e11105c14">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5207bf5-7e58-4001-aa8f-f9a4b2c037d8">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=070fef8e-ba09-40f4-abaa-9cebf08983c3">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d">Windows Media Encoder 9 x86</a>
                    <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75">Windows Media Encoder 9 x64</a><br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9ce9d62-2eaa-48d8-bb6d-ea137e63d077">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6dabc306-c858-46b1-815c-cd8d011ff62e">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f277ae4-4f85-4c8a-bfc5-dcdc8afed133">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=238bb885-eae6-464a-bb3d-679025f1cb50">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="14">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f1f41fb-368a-42e6-8d17-fca83b64f57b">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a3b57d26-5551-4785-86cf-41b532d78979">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f5a3677-0990-4702-bf08-af64cf12cb6c">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b70334c-490d-446c-988a-a88a75595fd4">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1">Windows Media Encoder 9 x86</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0b2837c-019b-419b-954d-5bdc71a3a332">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8fa2cfa4-a01d-4910-b69f-736aeb585bab">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aa39f59-2177-459f-9b8a-9543330d48ec">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c87af292-a068-4089-aab8-115c18b4b024">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad843b97-2f6e-4406-a17a-627b7db8a926">Windows Server 2003 Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a9f56a0-230a-4dde-94da-f051ebf51f47">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b0d2a3a-7fed-4d48-9ec5-8558000e51bb">Internet Explorer 7</a><br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e134e5d-84fb-432b-99b1-593b1be5d5a4">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08328e82-b012-4ea5-bf89-becb4881084f">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d">Windows Media Encoder 9 x86</a>
                    <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75">Windows Media Encoder 9 x64</a><br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c5cb600-9a39-40a0-be42-1593b1e0b97d">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17b0b340-73b2-42a7-9d86-1297c63dcc2b">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bca61d61-d5cf-49a4-ab99-b61e50e8f619">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e17b8878-d065-49cc-bdba-0f24cdf35ea3">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b0a06e7-0ae5-41f4-9ff5-d524fc0afbfa">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Server 2003 with SP2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c1cf126-604c-4f70-bbe8-aa4d145eb68f">Internet Explorer 6</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96884bfa-00c8-4263-9936-d7c054919dd3">Internet Explorer 7</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=15588d6a-f576-4e3d-95e8-d422af8a94de">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9abc8270-f3ac-474d-9ebc-410aaa6262cc">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04a178cc-1afd-4e47-8cab-05e402e5a568">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4fce129d-2b4e-4a66-af27-bbbde1e65ba1">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad896d80-167f-4e8f-a448-cac93516f4d0">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c0c2850-e81d-4347-aeb3-47036caa7c1b">Windows Server 2003 with SP2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="14">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=897351de-9697-4954-aa7e-169e980b932c">Internet Explorer 7</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bebf0df0-5ebe-44b4-9ace-b3085a993e58">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ddb8a06-c9cc-4d33-b6d1-22dbda2d871f">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48f10251-34d8-4149-b4b2-bf3ec28f5846">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55141a02-3ad3-4691-98b9-80dd8ecb14c5">Movie Maker 2.6</a>
                    [1]
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8a57950-43cd-486f-bd97-70b0ad360a0b">Windows Media Encoder 9 x86</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1c7f1b5-e054-4cd6-857d-2ab0a2fe9f62">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b824d3b9-2ce1-4abc-ae06-68aef1250be9">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85265a23-5094-4007-8d33-f402cabd1664">Windows Vista Service Pack 1 ja Windows Vista Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=171c02f9-f7d2-42f2-ba31-4c819a43784a">Internet Explorer 7</a>
                    <br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=837b6056-af04-4aed-8afe-cc392770a590">Internet Explorer 8</a><br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a245f3c-ffb6-4ccd-956c-e7d1231fca30">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=099ccc5f-b92f-4d06-bcb5-92e35c49f613">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b078136-a492-4a2e-939d-82799f774d82">Movie Maker 2.6</a>
                    [1]
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f98c3b96-acb5-49f1-be42-3dd44d316408">Windows Media Encoder 9 x86</a>
                    <br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1054088-f484-4f44-ba0e-5cbd21773c0c">Windows Media Encoder 9 x64</a><br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73624b68-a69d-4517-b971-f0b7d2ccc9d6">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4c42cfe-b7f2-4436-919e-4bd305a3439a">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63c7257a-16bf-4108-80b9-9dfe53528348">Windows Vista x64 Edition Service Pack 1 ja Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="14">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-</strong>
                      <strong>101</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
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
                  </td><td>Ei mitään</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3785f3b-64c6-46a4-8e3a-9b9448124a8f">Internet Explorer 7</a>**<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98183a76-5642-4e19-b488-029eb7ed3942">Internet Explorer 8</a>**<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87149ec2-74a8-4dea-b7e3-873558e0103e">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bdc9564a-4091-4cde-963a-239513db6c17">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a4ea028f-edfc-4237-8325-7ece11fcf437">Windows Media Encoder 9 x86</a>**<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=118f528f-bd05-49c2-a4a4-78314cd00992">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>**<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e2f572a-4169-47f2-a872-5466997122ed">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14e079a8-01a4-47c9-bd47-f5c9a6ca070a">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>**<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6793f75b-cdf4-42ef-a53e-a1acb5b662d1">Windows Server 2008 for 32-bit Systems ja Windows Server 2008 for 32-bit Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr><td>Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b81aae5-6034-4c83-b5d2-e7e472435284">Internet Explorer 7</a>**<br />(Kriittinen)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d47b457d-e995-4a7e-9bfa-eebab9b3a729">Internet Explorer 8</a>**<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=523a47d3-771d-471a-889b-16311c276a00">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dff39bfe-0799-4912-ae22-392562178ae6">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f468d2b5-f02c-4691-9fb5-a7f69752f126">Windows Media Encoder 9 x86</a>**<br />(Tärkeä)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=533d91d8-0291-421e-9701-3bd86d18bc45">Windows Media Encoder 9 x64</a>**<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77e288fb-b51f-4f57-baac-1443d8fbd37b">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>**<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09a4b646-989d-43ef-a3e8-64af8b380a14">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6baf92b7-a336-45f2-a1ba-c00c34dfb76f">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>**<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85add876-ca5a-4a92-984e-188a72e349fc">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c06bbc-6e84-4cf1-89f0-c0d34cfffaed">Windows Server 2008 for x64-based Systems ja Windows Server 2008 for x64-based Systems Service Pack 2</a>*<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ddafaaf-84a0-4325-b06f-4aac7cd61274">Internet Explorer 7</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=959146ee-0e70-4e56-9012-72ed59aeb24b">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf341a35-32ea-4ff7-aca9-1a4683c100ee">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82f71194-6f1f-4f43-8752-4bf5e5f94a93">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46522323-837e-4a74-9cf0-45f69343e776">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a4b23d4-f68e-4d5b-8814-d9247145f164">Windows Server 2008 for Itanium-based Systems ja Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="14">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-</strong>
                      <strong>102</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokitu</strong>
                    <strong>skooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriitt</strong>
                      <strong>inen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kriitt</strong>
                      <strong>inen</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärk</strong>
                      <strong>eä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärk</strong>
                      <strong>eä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärk</strong>
                      <strong>eä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärk</strong>
                      <strong>eä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärk</strong>
                      <strong>eä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>Ei mitään</td></tr>
                <tr><td>Windows 7 for 32-bit Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c288fe87-b113-4615-9b02-5e388bcb5241">Internet Explorer 8</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ff590db8-4264-42ba-9e07-88d100e1c4f5">Windows 7 for 32-bit Systems</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf85cdb6-58c7-4144-82f6-f01a6a4f9c3a">Windows 7 for 32-bit Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75591d37-2cb8-4cdf-acbb-89cd0d1a9290">Windows 7 for 32-bit Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e8ad5cd-af27-4f00-9378-ad778b8ee7b3">Windows 7 for 32-bit Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa7de2e4-ba48-4d58-b034-05349f0eb920">Windows 7 for 32-bit Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7c7d57a-d031-46a3-9613-eae2b9cb6401">Windows 7 for 32-bit Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2cf4ac70-88b4-4840-9895-2bcf119312a7">Internet Explorer 8</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ea4e339-9db2-4b99-b567-80ee55ecdf92">Windows 7 for x64-based Systems</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0597018d-39f5-4ca9-b437-63d9e68f264d">Windows 7 for x64-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a0c4dd0-98b4-4e7a-99ed-22b9d9f76cd1">Windows 7 for x64-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35a3e821-b463-411c-858b-d01eb5aed42b">Windows 7 for x64-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b21db627-91c2-4ebf-b7c0-38ac58ae5b6c">Windows 7 for x64-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e52c36f5-637b-4928-83d0-27514c6cc384">Windows 7 for x64-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="14">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                  </td><td>Ei mitään</td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td><td>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99a91ba7-035b-4717-ada5-c1ad6645db64">Internet Explorer 8</a>**<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e52f7869-474a-44c8-a102-e766c576fc01">Windows Server 2008 R2 for x64-based Systems</a>*<br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28c832fb-4937-4652-8799-eab6c76d05fb">Windows Server 2008 R2 for x64-based Systems</a>*<br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f58a765f-cea9-456d-b0ab-bfc70b109cbf">Windows Server 2008 R2 for x64-based Systems</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e2c95f6-9381-4484-b11b-814ab9138118">Windows Server 2008 R2 for x64-based Systems</a>**<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d417ebce-7841-4bbb-8abc-b15ef5f4b733">Windows Server 2008 R2 for x64-based Systems</a>*<br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b823a7aa-0eb9-42dd-bf56-8907d94b314a">Windows Server 2008 R2 for x64-based Systems</a>**<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d7307afd-84a0-434e-9658-bf9f8ae4b938">Windows Server 2008 R2 for x64-based Systems</a>*<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39b7abc7-65a4-4dfd-92ba-c638e3de1118">Windows Server 2008 R2 for x64-based Systems</a>*<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c26de145-94b8-404a-b946-744988fab83b">Internet Explorer 8</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a21d061a-794a-4012-b3cd-c67445c074f5">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Kriittinen)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ad64d5c-2d81-4ac8-934e-8917b2fcf961">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13a9f838-ac07-43dc-9aee-a77207998e1e">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb4211f3-1082-4245-8f03-7cbac90e9a31">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7eeac1bb-9f86-4ea5-b30f-980d52be5044">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66b2506d-80e0-4e32-86e6-0908ef56ae90">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Tärkeä)</td><td>Ei käytössä</td><td>Ei käytössä</td></tr>
              </table>


**Huomautukset: Windows Server 2008 ja Windows Server 2008 R2**

**\*Haavoittuvuus koskee Server Core -asennusta.** Tämä päivitys koskee mainittuja tuettuja Windows Server 2008- tai Windows Server 2008 R2 -versioita samalla luokituksella siitä riippumatta, onko asennuksessa käytetty Server Core -asennusta vai ei. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Haavoittuvuus ei koske Server Core -asennuksia.** Haavoittuvuudet, jotka tämä päivitys korjaa, eivät koske mainittuja tuettuja Windows Server 2008 -versioita, jos Windows Server 2008 asennettiin Server Core -asennuksella. Lisätietoja tästä asennusvaihtoehdosta on TechNet-artikkeleissa [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) ja [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Huomaa, että Server Core -asennusvaihtoeheto ei koske tiettyjä Windows Server 2008- ja Windows Server 2008 R2 -versioita. Lisätietoja on [Server Core -asennusvaihtoehtojen vertailussa](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Huomautus: MS10-093**

\[1\]Windows Movie Maker 2.6 on valinnainen ladattava tiedosto, joka voidaan asentaa ilmoitettuihin käyttöjärjestelmiin.

#### Microsoft Office -ohjelmistopaketit ja -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Microsoft Office -ohjelmistopaketit ja -osat</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=198156">
                      <strong>MS10-103</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=147425">
                      <strong>MS10-105</strong>
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
                <tr><td>Microsoft Office XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f540692c-e404-4383-8937-4d6a36475da5">Microsoft Publisher 2002 Service Pack 3</a>
                    <br />(KB2284692)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=724d0ad6-ba5f-4dbf-b280-3fb36335d33b">Microsoft Office XP Service Pack 3</a>
                    [1]
                    <br />(KB2289162)<br />(Tärkeä)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e600de65-3e9d-4e37-8906-8b7091ff523e">Microsoft Publisher 2003 Service Pack 3</a>
                    <br />(KB2284695)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=976857e9-77fc-4667-88ca-7637e57536cd">Microsoft Office 2003 Service Pack 3</a>
                    [1]
                    <br />(KB2289163)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Office 2007 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79275011-bdc1-446a-8ea6-56fc31bd9c35">Microsoft Publisher 2007 Service Pack 2</a>
                    <br />(KB2284697)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=676eeed6-f2b7-4265-afc7-a82ffdbeb290">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2288931)<br />(Ei luokitusta[2])</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2010 (32-bit edition)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99e18990-75e9-497e-9b4f-5d7ef8656ab2">Microsoft Publisher 2010 (32-bittiset versiot)</a>
                    <br />(KB2409055)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6d644494-b530-4b37-bc37-8a8a7edefe53">Microsoft Office 2010 (32-bittiset versiot)</a>
                    <br />(KB2289078)<br />(Ei luokitusta[2])</td></tr>
                <tr><td>Microsoft Office 2010 (64-bit edition)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b27ee11-e563-4152-9691-25eec1ee9966">Microsoft Publisher 2010 (64-bittiset versiot)</a>
                    <br />(KB2409055)<br />(Tärkeä)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58e54779-aa8f-41b3-9993-8cec12c49082">Microsoft Office 2010 (64-bittiset versiot)</a>
                    <br />(KB2289078)<br />(Ei luokitusta[2])</td></tr>
              
                <tr><th colspan="3">Muu Office-ohjelmisto</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=198156">
                      <strong>MS10-103</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=147425">
                      <strong>MS10-105</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Converter Pack</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dcded2ee-0673-4afe-abe6-04941a2ad306">Microsoft Office Converter Pack</a>
                    <br />(KB2456849)<br />(Tärkeä)</td></tr>
                <tr><td>Microsoft Works 9</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=10f6f330-05d8-4b60-9ebb-822a7321ac0f">Microsoft Works 9</a>
                    <br />(KB2431831)<br />(Tärkeä)</td></tr>
              </table>


**Huomautukset: MS10-105**

\[1\]Ilmoitettuja ohjelmistoja käyttävien asiakkaiden on myös asennettava tietoturvatiedotteen MS10-087 Microsoft Office -päivitys, jotta he voisivat suojautua tietoturvatiedotteessa MS10-105 kuvatuilta haavoittuvuuksilta.

\[2\]Tällä päivityksellä ei ole luokitusta, koska tiedotteessa kuvatut haavoittuvuudet eivät koske tätä ohjelmistoa. Microsoft kuitenkin suosittelee, että käyttäjät asentavat tämän tietoturvapäivityksen, jotta järjestelmä on suojattu myös mahdollisilta myöhemmin havaittavilta uusilta hyökkäystavoilta.

#### Microsoft Server -ohjelmisto

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Microsoft SharePoint Server</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206469">
                      <strong>MS10-104</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204624">
                      <strong>MS10-106</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Tärkeä</strong>
                    </a>
                  </td><td>Ei mitään</td></tr>
                <tr><td>Microsoft Office SharePoint Server 2007 Service Pack 2 (32-bittiset versiot)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c8fb9f9-7920-43ea-b618-e26dc3360c60">Microsoft Office SharePoint Server 2007 Service Pack 2 (32-bittiset versiot)</a>
                    <br />(KB2433089)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
                <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007 Service Pack 2 (64-bittiset versiot)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db09280-24bd-42e0-9ae3-02c9bf3e8ee3">Microsoft Office SharePoint Server 2007 Service Pack 2 (64-bittiset versiot)</a>
                    <br />(KB2433089)<br />(Tärkeä)</td><td>Ei käytössä</td></tr>
              
                <tr><th colspan="3">Microsoft Exchange Server</th></tr>
              
                <tr><td>
                    <strong>Tiedotteen numero</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=206469">
                      <strong>MS10-104</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204624">
                      <strong>MS10-106</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Luokituskooste</strong>
                  </td><td>Ei mitään</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Keskitaso</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Exchange Server 2007 Service Pack 2 for x64-based Systems</td><td>Ei käytössä</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b983156-9e9f-4d29-9e9b-2369747e3b62">Microsoft Exchange Server 2007 Service Pack 2 for x64-based Systems</a>
                    <br />(KB2407132)<br />(Keskitaso)</td></tr>
              </table>


## Tunnistus- ja käyttöönottotyökalut ja ohjeet

**Tietoturvakeskus**

Voit hallita ohjelmistoa ja tietoturvapäivityksiä, joita tarvitset organisaatiosi palvelimien, työaseman ja kannettavien tietokoneiden käyttöönottamiseen. Lisätietoja on [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) -sivustossa (joka voi olla englanninkielinen). [TechNet Security Centerissä](http://go.microsoft.com/fwlink/?linkid=21171) on lisätietoja Microsoft-tuotteiden suojausominaisuuksista. Kotikäyttäjät voivat tutustua näihin tietoihin valitsemalla [Kodin tietoturva](http://go.microsoft.com/fwlink/?linkid=85102) -sivustossa Tietoturvapäivitykset.

Tietoturvapäivitykset ovat saatavana [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)- ja [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) -sivustoista. Tietoturvapäivityksiä voi ladata myös [Microsoft Download Centeristä](http://go.microsoft.com/fwlink/?linkid=21129). Päivitysten etsiminen on helpointa hakusanahaun ja hakusanan "security update" avulla.

Microsoft Office for Mac -käyttäjät: Microsoft AutoUpdate for Mac helpottaa Microsoft-ohjelmiston pitämistä ajan tasalla. Lisätietoja Microsoft AutoUpdate for Macin käyttämisestä on [ohjelmistopäivitysten automaattista tarkistamista](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) käsittelevällä sivulla.

Tietoturvapäivitykset voidaan ladata lisäksi [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155) -palvelusta. Microsoft Update Catalog -palvelu sisältää hakemiston Windows Updaten ja Microsoft Updaten kautta tarjottavasta sisällöstä, kuten tietoturvapäivityksistä, ohjaimista ja Service Packeista. Tästä hakemistosta voidaan myös tehdä hakuja. Kun teet hakuja tieturvatiedotteen numeron mukaan (kuten MS07-036), voit lisätä kaikki haun tuloksena saatavat päivitykset ostoskoriisi (mukaan lukien kaikki päivityksen kieliversiot) ja ladata sitten koko paketin valitsemaasi kansioon. Lisätietoja Microsoft Update Catalogista on [Microsoft Update Catalogin usein kysytyissä kysymyksissä](http://go.microsoft.com/fwlink/?linkid=97900).

**Tunnistus- ja käyttöönotto-ohjeet**

Microsoft on laatinut ohjeita tietoturvapäivitysten tunnistamiseen ja käyttöönottamiseen. Ohjeisiin sisältyy suosituksia ja tietoja, joiden avulla IT-ammattilaiset oppivat tunnistamaan ja ottamaan käyttöön tietoturvapäivityksiä erilaisilla työkaluilla. Lisätietoja on [Microsoft Knowledge Base -artikkelissa 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) -työkalulla järjestelmänvalvojat voivat tarkistaa sekä paikallisista järjestelmistä että etäjärjestelmistä, puuttuuko niistä tietoturvapäivityksiä ja onko niissä muita yleisiä tietoturvapuutteita. Lisätietoja MBSA-työkalusta on [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) -sivustossa.

**Windows Server Update Services**

Käyttämällä WSUS (Windows Server Update Services) -palvelua järjestelmänvalvojat voivat ottaa nopeasti ja luotettavasti käyttöön uusimmat kriittiset päivitykset ja tietoturvapäivitykset seuraavissa järjestelmissä: Microsoft Windows 2000 ja sitä uudemmat, Office XP ja sitä uudemmat, Exchange Server 2003, SQL Server 2000 (Microsoft Windows 2000 ja sitä uudemmat käyttöjärjestelmät).

Lisätietoja tämän tietoturvapäivityksen käyttöönottamisesta WSUS-palvelun avulla on [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) -sivustossa.

**SystemCenter Configuration Manager 2007**

Configuration Manager 2007:n ohjelmistopäivitysten hallinta yksinkertaistaa päivitysten toimittamista yrityksen eri IT-järjestelmiin sekä niiden hallintaa. Configuration Manager 2007 auttaa järjestelmänvalvojia toimittamaan Microsoft-tuotteiden päivitykset niin työasemiin, kannettaviin, palvelimiin kuin mobiililaitteisiinkin.

Configuration Manager 2007:n automatisoitu haavoittuvuuksien arviointi havaitsee päivitystarpeet ja tekee raportin suositeltavista toimista. Configuration Manager 2007:n ohjelmistopäivitysten hallinta perustuu Microsoftin WSUS (Windows Software Update Services) -palveluihin, ja eri puolilla maailmaa toimivat järjestelmänvalvojat tuntevat tämän aikatestatun päivitysinfrastruktuurin. Lisätietoja tavoista, joilla järjestelmänvalvojat voivat ottaa päivityksiä käyttöön Configuration Manager 2007:n avulla, on [ohjelmistopäivitysten hallintaa](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) käsittelevässä sivustossa. Lisätietoja Configuration Managerissa on sivustossa [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) tarjoaa monipuolisesti määritettävän yritysratkaisun päivitysten hallintaan. SMS:n avulla järjestelmänvalvojat voivat tunnistaa tietoturvapäivityksiä tarvitsevat Windows-järjestelmät ja suorittaa hallitun päivitysten asennuksen koko yrityksessä niin, että käyttäjien työt keskeytyvät mahdollisimman vähän.

**Huomautu** **s** System Management Server 2003:n yleinen tuki päättyi 12.1.2010. Lisätietoja tuotteiden elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle) -sivustossa. SMS:n seuraava versio eli System Center Configuration Manager 2007 on nyt saatavana. Katso edellä oleva kohta **SystemCenter Configuration Manager 2007**.

Lisätietoja tavoista, joilla järjestelmänvalvojat voivat ottaa päivityksiä käyttöön SMS 2003:n avulla, on artikkelissa [Microsoft Systems Management Server 2003:n skenaarioita ja menetelmiä: ohjelmistojen jakaminen ja korjauspäivitysten hallinta](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (englanninkielinen). Lisätietoja SMS:stä on [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx) -sivustossa.

**Huomautus** SMS tukee tietoturvapäivitysten kattavaa tunnistamista ja käyttöönottoa Microsoft Baseline Security Analyzer -työkalulla. Nämä työkalut eivät ehkä tunnista joitakin päivityksiä. Järjestelmänvalvojat voivat käyttää SMS:n analysointiominaisuuksia päivitysten kohdentamiseen tiettyihin järjestelmiin. Lisätietoja tämän tekemisestä on [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) -sivustossa. Jotkin tietoturvapäivitykset saattavat edellyttää järjestelmänvalvojan oikeuksia, kun järjestelmä on käynnistetty uudelleen. Järjestelmänvalvojat voivat asentaa nämä päivitykset käyttämällä Elevated Rights Deployment Tool -työkalua (sisältyy [SMS 2003 Administration Feature Packiin](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

**Update Compatibility Evaluator ja Application Compatibility Toolkit**

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

  - Aniway ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-090
  - Nicolas Joly ([VUPEN Vulnerability Research Team](http://www.vupen.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-090
  - Stephen Fewer (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-090
  - [Peter Vreugdenhil](http://vreugdenhilresearch.nl/) (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-090
  - Masatoshi Sato ([AZIA CO., LTD.](http://www.azia.jp)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-090
  - [Yosuke Hasegawa](http://utf-8.jp/) teki yhteistyötä kanssamme selvittääkseen haavoittuvuuden, joka on kuvattu tietoturvatiedotteessa MS10-090
  - Jose Antonio Vazquez Gonzalez ([VeriSign iDefense Labs](http://labs.idefense.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-090
  - Marc Schoenefeld ([Red Hat Security Response Team](https://www.redhat.com/security/team/) yhteistyössä [Opera Security Teamin](http://www.opera.com/security/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-091
  - Marc Schoenefeld ([Red Hat Security Response Team](https://www.redhat.com/security/team/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-091
  - Paul-Kenji Cahier Furuya ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-091
  - Sergei Golovanov, Aleksander Gostev, Maksim Golovkin ja Aleksei Monastirski ([Kaspersky Lab](http://usa.kaspersky.com/)) sekä Vitali Kiktenko ja Aleksander Saprikin ([Design and Test Lab](http://www.dnt-lab.com/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-092
  - Liam O Murchu ([Symantec](http://www.symantec.com/index.jsp)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-092
  - Alexandr Matrosov, Eugene Rodionov, Juraj Malcho ja David Harley ([ESET](http://www.eset.com/)) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-092
  - Haifei Li ([Fortinetin FortiGuard Labs](http://www.fortiguard.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-095
  - Simon Raner ([ACROS Security](http://www.acrossecurity.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-096
  - HD Moore ([Rapid7](http://www.rapid7.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-096
  - Muhaimin Dzulfakar ([NGS Software](http://www.ngssoftware.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-096
  - Muhaimin Dzulfakar ([NGS Software](http://www.ngssoftware.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-097
  - Tarjei Mandt ([Norman](http://www.norman.com/)) ilmoitti neljästä haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS10-098
  - Stéfan Le Berre ([Sysdream](http://www.sysdream.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-098
  - Honggang Ren ([Fortinetin FortiGuard Labs](http://www.fortiguard.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-099
  - Cesar Cerrudo ([Argeniss](http://www.argeniss.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-100
  - Matthias Dieter Wallnöfer ja Andrew Bartlett (Samba Team) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-101
  - [HP](http://www.hp.com/) ja [techit](http://www.techit.de/) ilmoittivat haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-102
  - Chaouki Bekrar ([VUPEN Vulnerability Research Team](http://www.vupen.com/)) ilmoitti viidestä haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS10-103
  - Oleksandr Mirosh (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-104
  - Yamata Li ([Palo Alto Networks](http://www.paloaltonetworks.com/)) ilmoitti kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS10-105
  - Alin Rad Pop ([Secunia Research](http://secunia.com/)) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-105
  - Carsten Eiram ([Secunia Research](http://secunia.com/)) ilmoitti kolmesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS10-105
  - Dyon Balding ([Secunia Research](http://secunia.com/)) ilmoitti kahdesta haavoittuvuudesta, jotka on kuvattu tietoturvatiedotteessa MS10-105
  - Oleksandr Mirosh (yhteistyössä [TippingPointin](http://www.tippingpoint.com/)[Zero Day Initiativen](http://www.zerodayinitiative.com/) kanssa) ilmoitti haavoittuvuudesta, joka on kuvattu tietoturvatiedotteessa MS10-106

#### Tuki

  - Mainitut ohjelmistoversiot on testattu sen selvittämiseksi, koskeeko ongelma niitä. Muiden versioiden tuen elinkaari on päättynyt. Lisätietoja tuote- ja versiotuen elinkaaresta on [Microsoftin Tuotetuen elinkaari](http://go.microsoft.com/fwlink/?linkid=21742) -sivustossa.
  - Tuotetukea Yhdysvalloissa ja Kanadassa tarjoaa [tietoturvapalvelu](http://go.microsoft.com/fwlink/?linkid=21131), jonka puhelinnumero on 1-866-PCSAFETY. Tietoturvapäivityksiin liittyvät tukipuhelut ovat maksuttomia. Lisätietoja saatavissa olevista tukivaihtoehdoista on [Microsoftin Ohjeessa ja tuessa](http://support.microsoft.com/).
  - Muissa maissa asiakkaat saavat tukea paikallisista Microsoftin tytäryhtiöistä. Tietoturvapäivityksiin liittyvä tuki on maksutonta. Lisätietoja yhteyden ottamisesta Microsoft-tukeen on [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155) -sivustossa.

#### Vastuuvapauslauseke

Microsoft Knowledge Base -tietokannan sisältämät tiedot toimitetaan "sellaisenaan" ilman minkäänlaista takuuta. Microsoft kiistää kaikki nimenomaiset ilmaistut tai epäsuorat takuut, mukaan lukien takuut tuotteen soveltuvuudesta kaupankäynnin kohteeksi ja sopivuudesta tiettyyn tarkoitukseen. Microsoft Corporation tai sen toimittajat eivät missään tapauksessa ole vastuussa vahingoista mukaan lukien suorat, satunnaiset, epäsuorat ja välilliset vahingot, liikevoiton menetys sekä erityiset vahingot, vaikka Microsoft Corporationille tai sen toimittajille olisi ilmoitettu vahinkojen mahdollisuudesta. Koska jotkin valtiot eivät salli välillisten tai satunnaisten vahinkojen vahingonkorvausvastuun poissulkemista tai rajoittamista, edellä mainittu rajoitus ei koske kaikkia asiakkaita.

#### Versiot

  - V1.0 (14. joulukuuta 2010): Tietoturvatiedotteen yhteenveto julkaistu.
  - V1.1 (15. joulukuuta 2010): Tarkennettiin, että Microsoft Office XP- ja Microsoft Office 2003 -asiakkaiden on asennettava tietoturvatiedotteen MS10-087 päivitys, jotta he voisivat suojautua tietoturvatiedotteessa MS10-105 kuvatuilta haavoittuvuuksilta.

*Built at 2014-04-18T01:50:00Z-07:00*

