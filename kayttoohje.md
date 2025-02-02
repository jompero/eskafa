### Lukuvinkkikirjaston käyttö

Ohjelma sisältää seuraavia toimintoja: 

#### 1. Lukuvinkkien listaaminen

Sovellukseen lisättyjä lukuvinkkejä pääsee selailemaan valitsemalla komennon  

`1 --- List all recommendations`,

joka palauttaa listan kaikista tietokantaan lisätyistä lukuvinkeistä.

#### 2. Kirjavinkin lisääminen

Uuden kirjavinkin lisääminen onnistuu valitsemalla vaihtoehdon

`2 --- Add a new book`
 
Tämän jälkeen ohjelma kysyy lisättävän kirjan tiedot ja tallentaa ne tietokantaan.  

#### 3. Lukuvinkin poistaminen

Lukuvinkin poistaminen onnistuu komennolla 

`3 --- Remove a recommendation from the list`

Ohjelma kysyy, poistetaanko kirja- (*book*) vai linkkivinkki (*link*). Seuraavaksi   
ohjelma etsii teoksen/linkin nimen perusteella ja poistaa sen tiedot lukuvinkkien listalta. 

#### 4. Linkkien listaaminen

Komento 

`4 --- List all links`

mahdollistaa linkkien avaamisen komentoriviltä. Tällöin ohjelma listaa tietokantaan tallennettuja
linkkejä yksi kerrallaan antaen käyttäjän valita, avataanko kyseinen nettisivu selaimessa. 

#### 5. Linkin lisääminen

Uuden linkkivinkin lisääminen onnistuu valitsemalla vaihtoehdon

`5 --- Add a new link`

Tämän jälkeen ohjelma kysyy lisättävän linkin tiedot ja tallentaa ne tietokantaan. Ohjelma hakee
automaattisesti lisättävän sivun metatiedot.  

#### 6. Lista lisätyistä tageista

Komento

`6 --- List tags`

palauttaa listan kaikista ohjelmaan lisätyistä tageista.

#### 7. Haku tagin perusteella

Komennon

`7 --- Search by tag`

avulla käyttäjä voi hakea lukuvinkkejä ohjelmaan lisättyjen tagien perusteella. Komento palauttaa 
listan lisätyistä tageista, joista käyttäjä voi valita yhden hakusanaksi.  

#### 8. Ohjelman sulkeminen

Ohjelman voi sulkea komennolla 

`q --- quit`