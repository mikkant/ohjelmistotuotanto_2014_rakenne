## Käyttötapaukset

* Määritä tänne järjestelmän loppukäyttäjät
* Käyttötapauskaavio, jossa järjestelmän keskeiset käyttötapaukset
* Kuvaile tärkeimmät käyttötapauksista käyttötapausskenaarioina mallipohjaan perustuen
  * mallipohja: määritä alkutila (initial state), normaali kulku (normal flow), lopputila (end state)
  * kerro myös kuinka normaali kulku voi mennä pieleen sekä
  * mahdolliset vaihtoehtoiset kulut (alternate flow)
  
  Järjestelmän loppukäyttäjät koostuvat oppilaista, opettajista, henkilökunnasta ja vierailijoista.
  


## 1. Mitkä ovat järjestelmän keskeiset käyttötapaukset? Mille käyttäjäryhmälle? ##
- Opettajat/henkilökunta voivat etsiä kiiretilanteessa toisensa.
- Oppilaat voivat löytää tarvitsemansa henkilökohtaisen avun nopeasti.
- Tarvittaessa löydetään nopeasti joku hädänhetkellä.
- Vierailijat voivat etsiä tietyn opettajan/luennoitsijan tullessaan ensi kertaa taloon.


### Skenaario 1:

Talonmies on saanut useita valituksia puhelimitse ja kasvotusten. Valituksen aiheena on auto, joka on valunut osittain koulun parkkipaikan ajoväylälle ja näin estää kulun ajoväylällä.
Talonmies käy kurkkaamassa tilanteen vakavuuden ja katsoo onko mitään tehtävissä. Tämän jälkeen talonmies selvittää koulun järjestelmään rekisteröidyn rekisterinumeron perusteella kenelle
ajoneuvo kuuluu. Selvittelyn jälkeen käy ilmi, että ajoneuvo kuuluu eräälle koulun henkilökuntaan kuuluvalle opettajalle. 
Talonmies selvittää ensiksi koulun oman järjestelmän kautta opettajan puhelinnumeron ja sijainnin. Tämän jälkeen talonmies soittaa ensiksi puhelimitse opettajalle. Kukaan ei kuitenkaan vastaa, 
joten talonmies päättää käydä katsomassa vielä toimistosta varmistuakseen, ettei opettaja ole paikalla. 
Talonmies on saanut tarpeekseen etsiskelystä ja haluaa saada asian hoidetuksi, joten hän käynnistää mCon sovelluksen ja hakee opettajan sijaintia. Opettajan sijanniksi selviää välittömästi 
koulun ruokala ja talonmies lähtee ilmoittamaan tilanteesta opettajalle. Talonmies löytää opettajan ruokalasta ja pyytää tätä siirtämään ajoneuvon välittömästi ruokailun jälkeen, 
jotta ajoväylä saadaan jälleen käyttöön. 
Talonmies lähtee jatkamaan omia töitänsä ja opettaja viimeistelee annoksensa. Tämän jälkeen opettaja lähtee samoin siirtämään ajoneuvoa, jonka jälkeen ajoväylä onkin jo taas käytössä. 


## 2. Listaa jokaiseen käyttötapaukseen liittyen mitä ruudulla näkyy. Kuvaile em. käyttötapauksiin liittyen mitä käyttäjälle näytetään sovelluksen ruudulla, lisää ja tallenna ##
- 1. kohta: Opettajan auto on valunut ajoväylälle. Talonmies näkee ruudulta nopeasti, että opettaja on ruokalassa.
- 2. kohta: Oppilaan palautus on 15min päässä ja opettajaa ei löydy huoneestaan.
			Oppilas näkee ruudulta opettajan olevan kirjastossa.
- 3. kohta: Opettajan lapsi on hädässä ja opettajaa ei saada kiinni muutoin. Talonmies näkee ruudulta
			opettajan olevan kokoustilassa.
- 4. kohta: Vierailija näkee ruudulta missä luennoitsija sijaitsee. Löytää luentosalin hetkessä.

![kayttotapaus 1.](http://users.metropolia.fi/~mikarul/ohjelmistotuotanto/projekti/kayttis1.png)