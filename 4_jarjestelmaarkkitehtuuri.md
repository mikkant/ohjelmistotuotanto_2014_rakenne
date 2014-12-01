##  Järjestelmäarkkitehtuuri

* Pyri kuvailemaan tässä luvussa järjestelmäarkkitehtuuri yleisellä tasolla
* Mitä komponentteja järjestelmään tarvitaan jotta se pystyy palvelemaan määritettyjä käyttötapauksia?

Sovellus koostuu 2 päänäkymästä: sisäänkirjautumisnäkymä sekä etusivunäkymä. Sisäänkirjautumisnäkymä avautuu sovelluksen
käynnistyessä. Jos käyttäjä antaa oikeat tunnukset siirtyy hän etusivunäkymään joka sisältää kartan, hakupalkin, kerrosvalikon,
hakutuloskentän sekä liukupainikkeen Chat toiminnon avaamiseen.
Chat toiminto avautuu vetämällä ruudun alareunassa olevasta liukupainikkeesta. tämä avaa etusivulle erillisen
chat näkymän. Näkymästä löytyy taivoitettavissa olevat henkilöt, vapaa haku kenttä sekä suurempi kirjoituskenttä
tekstejä/keskustelua varten.

Tärkeimmät komponentit ovat:
Kosketusnäyttö: Kaikki valinnat tehdään kosketusnäytön avulla.
Bluetooth- ja Wi-Fi tekniikat: Sisätilapaikannus käyttää näitä tekniikoita paikannustarkkuuden määrittämiseen. Sekä
Chat tarvitsee toimiakseen internet-yhteyden.


