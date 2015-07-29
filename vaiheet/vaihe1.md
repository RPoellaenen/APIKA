#1. Palvelun kuvaus
##1.1. Palvelun visio

**Liityntäkatalogi**

Palvelu on myös palveluvälyän liityntäkatalogin proof of concept. Sähköisten palveluiden toimintaperiaatteita ja rajapintoja kuvaileva luettelo. Liityntäkatalogin tarkoituksena on auttaa palvelun tuottajia ja toteuttajia kehittämään tehokkaampia sähköisiä palveluita ja tukemaan tietojen uudelleenkäyttöä. Liityntäkatalogiin kuvataan sähköiset palvelut, joissa käsiteltävät tiedot ovat muiden tietojärjestelmien hyödynnettävissä.

Liityntäkatalogi tulee toimimaan yhteisenä komponenttina kansallisen palveluväylän hyödynnettävyyden takaamisessa. Sen kautta löytyy kaikki kansallisen palveluväylän liitynnät teknisine ja hallinnollisine kuvauksineen tuoden esille palveluista esimerkiksi

* perustiedot,
* tekniset toimintamallit,
* palvelulupaukset sekä
* jatkossa myös rajapintojen testaustyökalut.

Kansallisen palveluväylän liityntäkatalogi on palveluväylään liitettyjen palveluiden sekä niiden tietojen hyödyntämisen keskitetty esilletuontipaikka. Liityntäkatalogi on ihmisluettava portaali (www-sivusto), jossa on palvelukatalogin tapaan esitetty palveluväylässä olevat palveluita, mutta myös niiden teknisiä spesifikaatioita, tarkkoja tietosisältöjä sekä palvelunomistajien yhteystiedot. 

Palvelukatalogi ja liityntäkatalogi eroavatkin toisistaan käyttötavoissa - palvelukatalogissa voidaan tarjota esimerkiksi linkki sähköiseen veroilmoitukseen, kun taas liityntäkatalogissa kuvataan miten sähköisen veroilmoituksen voisi esimerkiksi integroida suoraan yrityksen taloushallinnon järjestelmiin. Liityntäkatalogi tarjoaa näyteikkunan palveluväylään liittyneistä palveluista ja sisältää myös teknisen ylläpitovälineen siellä näytettäville tiedoille.

**Hajautettu hallinta**

Liityntäkatalogeja on useita. Jokaisella toimialalla on oma katalogi, jota se hallinnoi, ohjaa ja opastaa sen hyödyntäjiä. Hyödyntäjät ovat rajapintojen tuottajia. Kansallisen tason liityntäkatalogin tietosisältö muodostuu aggregoimalla toimialakohtaisten katalogien tiedot yhteen paikkaan rajapintoja hyödyntämällä. 

**Kehittäjän tietokeskus**

API -hallinta tai katalogi on palvelu, jonka kautta jaetaan tietoa rajapinnoista (API). Palvelun kautta sovelluksien ja palveluiden kehittäjä voi luoda itselleen kehittäjätunnukse, ottaa rajapintoja käyttöön, antaa palautetta rajapinnoista, nähdä eri API:en backlogit, ehdottaa uusia ominaisuuksia. Palvelu tulee olemaan API:en keskus, josta jatkossa pääsee käsiksi esimerkiksi OPH:n rajapintojen tietoihin. 

API- hallinta lienee liian rajaava termi. Enemmän kyse on API-keskuksesta tai developer portaalista. Palvelulla on muitakin käyttäjiä kuin vain "kuluttajat" eli API:en hyödyntäjät. Jostainhan ne rajapinnat sinne ilmestyy eli joku niitä ylläpitää, kehittää ja operoi. Palvelu tarjoaa API:en tuottajille helpon tavan kontrolloida kuka käyttää rajapintaa ja kuinka paljon. Lisäksi palvelussa näkyy API:n tuottamat virhetilanteet, kyselymäärät ja käyttäjämäärät graafeina ja lukuina. 
#2. Projektin sisältö

##2.1. Ajankohta ja kesto
* Projekti toteutetaan 1.10.2015 - 1.12.2015 välisenä aikana.
* Kesto 2 kuukautta. 

##2.2. Lopputulokset

* Proof of Concept API hallinta router/gatekeeper
  * SOAP and JSON/REST  
* Kehittäjille:   
  * hakutoiminto
  * yhtenäistetty dokumentaatio eri rajapinnoille
* API omistajille/tuottajille:
  * swagger tuki 
  * pääsynhallinta
  * statistiikat käytöstä
  * kuormantasaus (cache)
* Eri toimialojen API -tuottajien tarpeita käyttäjätarinoina 


##2.3. Projektin kuvaus ja kohde.

##2.4. Ratkottavat ongelmat

Ei ole olemassa kehittäjäystävällistä palvelua, josta löytyisi kootusti opetussektorin API:en tiedot. 
Tämä puolestaan hidastaa palvelukehitystä huomattavasti. Lisäksi innovaatiot monesti tapahtuvat organisaation 
ulkopuolella ja vain avaamalla rajapinnat, voimme saada julkishallinnon tietovarannot ja toimintarajapinnat 
laajaan hyötykäyttöön.


##2.5. Projektin tuotoksen kuvaus

##2.6. Projektin omistaja.

##2.7. Toteutuksen osapuolet

#3. Toteutus

##3.1. Läpiviennin yleiset periaatteet

##3.2. Aikataulu ja vaiheistus

##3.3. Vaiheet


###3.3.1. Suunnitelman laatiminen
Laaditaan projektisuunnitelma (tämä dokumentti), jota voidaan käyttää kilpailutuksessa kuvauksena siitä mitä halutaan saada aikaiseksi. Suuunitelma kuvaa MVP eli minimi lopputuloksen, joka voidaan ylittää sikäli kuin nyt määritellyt tavoitteet osoittautuvat liian mataliksi. 

Vaiheen tuotokset:
* Projektisuunnitelma
* Kilpailutuksessa tarvittavat dokumentit

Vaiheen kesto:
* 1.7.-1.9.2015

###3.3.2. Kilpailutus
Kilpailutetaan toteutus edellä tuotettujen dokumenttien sisältämää tietoa hyväksykäyttäen. 

Vaiheen tuotokset:
* Kilpailutus asiakirjat
* Vertailudokumentti
* Hankintapäätös
* Hankintasopimus

Vaiheen kesto: 
* 1.9.-1.10.2015
* 
###3.3.3. API -hallinnan pystytys
Pystytetään API -hallinta käyttäen API umbrella pohjana, mutta paremmalla käyttäjäkokemuksella tehdyllä käyttöliittymällä. Apinf.com taustalla oleva ratkaisu on API umbrella pohjainen, mutta frontend on uusittu ja tehty Meteor alustan päälle. Ratkaisu on avointa lähdekoodia kokonaisuudessaan. 

###3.3.4. [Vaihe 2]

###3.3.5. Evaluointi ja jatkotoimista päättäminen
Evaluoidaan tulokset käyttäen yhteisten käytäntöjen määrittämää kehikkoa. Evaluoinnin tekee projektin alussa ja tässä dokumentissa määritetyistä osapuolista koostettu kehitysyhteisö. Osana evaluointia tulee tehdä päätös jatkotoimista eli käytännössä päätös siitä jatketaanko kehitystä vai ei. 

Vaiheen kesto: 
* 15.12.-20.12.2015

Vaiheen tuotokset: 
* Evaluointidokumentti saaduista tuloksista
* Päätös jatkotoimista


#4. Projektin organisointi

##4.1. Projektin hallinnollinen organisointi

##4.2. Ohjausryhmä

##4.3. Roolit, vastuut ja velvollisuudet

##4.4. Viestintä ja tiedonvaihto.

##4.5. Tuotokset

#5. Työmääräarvio ja kustannusarvio. (edited)

#6. Muuta

## Onko se avointa lähdekoodia?

Toteutus tulee olemaan API Umbrella pohjainen. Ratkaisua parannetaan erilaisilla toiminnoilla ja parannukset kontribuoidaan takaisin pääprojektiin aina kun mahdollista.

## Mitä käyttö maksaa? 

Palvelu on ainakin aluksi ilmainen kaikille 5/2016 asti.

## Miten voi osallistua?

Helpoin ja pienimmän kynnyksen tapa osallistua on kertoa mitä ominaisuuksia sinä palvelulta odotat. Kerro tarpeesi niin sanotun käyttäjätarinan muodossa: "Opettaja voi hyväksyä ilmoittautuneen opiskelijan kurssille", "Kehittäjä löytää tarjolla olevat autentikointitavat esimerkkikoodeineen". Käyttäjätarinat kerätään Githubiin, josta tiimi poimii tarinoita toteutukseen.

## Koska palvelu on käytössä?

Ensimmäinen versio palvelusta otetaan käyttöön syksyn 2015 aikana. 
