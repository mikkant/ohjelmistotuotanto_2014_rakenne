## Käyttöliittymä

* listaa käyttöliittymän näkymät
* niiden keskinäiset suhteet
* kuvaile mitä näkymässä tapahtuu / tehdään

## Näkymät   
	
    Sisäänkirjautuminen: Koostuu käyttäjätunnus- ja salasanakentästä. Toimii tuubitunnuksilla ja oikeilla tunnuksilla ohjaa etusivulle.
    Etusivu: Etusivu koostuu pohjapiirroksesta ja valintapainikkeista. Valintapainikkeilla saadaan esille haettavat kohteet.
    Hakukenttä: Vapaa haku, esim nimen perusteella. 3 valintapainiketta: Opettajat, Henkilökunta, oppilaat. Painikkeita painamalla listaa kaikki mahdolliset hakukohteet Liittyen valintaan.
    Chat-näkymä: Erillinen näkymä johon pääsee sivupyyhkäisyllä. Sisältää hakupalkin jossa nimen perusteella haetaan chat-paria.
    Haun tulokset: Kohdennettu näkymä kartasta, joka antaa kohteen tarkan sijainnin koululla.

##Esim 1. 
    Oppilas on uusinut tentin kaksi viikkoa sitten, muttei ole saanut arvosanaa uusintatentistä. 
	Hän haluaa kysyä opettajalta miksei arvosanaa ole kirjattu Winha-järjestelmään.
	-> Käynnistää sovelluksen ja kirjoittaa hakukenttään opettajan nimen.
	-> Sovellus näyttää opettajan sijainnin ja statuksen (käytettävissä/varattu) ja
	statuksen jatkuvuuden (esim. käytettävissä klo 14:00 saakka/varattu klo 14:00 saakka).
	-> Oppilas lähettää opettajalle tapaamispyynnön, jonka opettaja saa välittömästi ja sovellus kysyy
	hyväksyykö opettaja tapaamisen ja tapaamispaikan (oletuksena opettajan sijainti). Jos opettaja hylkää
	tapaamisen, voi hän asettaa syyn hylkäykselle sekä mahdollisen tapaamisajan.
##Esim 2. 
    Uusi oppilas on eksynyt eikä löydä luokkaa jossa hänellä on tunti. 
	-> Käynnistää sovelluksen ja kirjoittaa hakukenttään hakemansa luokan.
	-> Sovellus hakee luokan koordinaatit ja näyttää karttanäkymässä luokan sijainnin sekä samalla luokan
	tapahtumat.
##Esim 3. 
    Oppilas ei tiedä pidetäänkö tuntia. Hän haluaa kysyä joltakin siitä. 
	-> Käynnistää sovelluksen, avaa chat-ikkunan ja kysyy yleisestä keskusteluhuoneesta onko joku tietoinen asiasta.

	
## Liikkuminen näkymien välillä

	Sisäänkirjautumisnäkymästä pääsee oikeilla tuubi-tunnuksilla etusivulle.
	Etusivu-näkymä sisältää hakukentät ja haun tulokset avautuvat etusivunäkymään.
	Chat-näkymä avautuu etusivun alalaidassa olevalla pyyhkäisypalkilla.

