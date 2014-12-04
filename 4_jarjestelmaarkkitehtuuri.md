##  Järjestelmäarkkitehtuuri

* Pyri kuvailemaan tässä luvussa järjestelmäarkkitehtuuri yleisellä tasolla
* Mitä komponentteja järjestelmään tarvitaan jotta se pystyy palvelemaan määritettyjä käyttötapauksia?

Sovelluksen järjestelmäarkkitehtuuri asteittain

* Käyttäjätiedot
	* Sisältää käyttäjien tuubi-tunnuksien tiedot, eli säköpostiosoitteen, käyttäjänimet ja salasanat.
		* Käytetään sisäänkirjautumiseen

* Vierailija-profiili
	* Avaa sovelluksen rajoitetuilla ominaisuuksilla. Sisältää vain opettajien/luennoitsijen nimihaun.
		* Käytetään palvelemaan myös harvoin talossa vierailevia
		
* Paikannustiedot
	* Sisältää käyttäjien ja luokkahuoneiden koordinaatit, jotka tunnistetaan WLAN- ja Bluetooth-signaaleja hyväksikäyttäen
		* Käytetään kohteen paikantamiseen

* Chat-näkymä
	* Mahdollistaa reaaliaikaisen vuorovaikuttamisen muiden käyttäjien kesken.
	
* Ylläpito
	* Ylläpidolla on mahdollisuus poistaa epäasiallisesti Chatissa käyttäytyvän tai koulutuksensa keskeyttäneen opiskelijan tunnus.
		* Käytetään pitämään sovellus selkeänä ja asiallisena


