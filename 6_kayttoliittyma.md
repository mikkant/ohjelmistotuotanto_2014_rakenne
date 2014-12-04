## Käyttöliittymä

* listaa käyttöliittymän näkymät
* niiden keskinäiset suhteet
* kuvaile mitä näkymässä tapahtuu / tehdään

## Näkymät   
	
* Sisäänkirjautuminen: 
Koostuu käyttäjätunnus- ja salasanakentästä. Toimii tuubitunnuksilla. 
Käyttäjä syöttää tekstikenttiin tunnuksensa ja oikeilla tunnuksilla sovellus ohjaa käyttäjän etusivulle.
![Sisäänkirjautuminen](http://users.metropolia.fi/~nikij/mCon/Kirjautuminen%20%281%29.png)	
* Etusivu:
 Etusivu koostuu pohjapiirroksesta ja valintapainikkeista. Valintapainikkeilla saadaan esille haettavat kohteet. Näkyviä kohteita ovat hakukenttä, profiilikuvake,
kerros(1,2,3), käyttäjäryhmä(oppilas, henkilökunta, opettaja)
![Etusivu](http://users.metropolia.fi/~nikij/mCon/Etusivu,_Avatar_painettu%20%283%29.png)	
* Hakukenttä:
Vapaa haku, esim nimen perusteella. Haun suorittamalla listaa kaikki mahdolliset hakukohteet liittyen valintaan.
![hakukenttä](http://users.metropolia.fi/~nikij/mCon/Etusivu%20%282%29_haku.png)
* Chat-näkymä: 
Erillinen näkymä johon pääsee alalaidassa olevalla pyyhkaisypalkilla. Sisältää hakupalkin jossa nimen perusteella haetaan chat-paria ja kirjoituskentän johon syötetään/
vastaanotetaan tekstiä
![chat] (http://users.metropolia.fi/~nikij/mCon/Chat-n%C3%A4kym%C3%A4%20%284%29.png)
* Haun tulokset: 
Sisältää suoritetun haun tulokset ja antaa kohteen koordinaatit kartalla ja kirjallisesti.
![haun tulokset] (http://users.metropolia.fi/~nikij/mCon/Etusivu%20%282%29_hauntulokset.png)

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


