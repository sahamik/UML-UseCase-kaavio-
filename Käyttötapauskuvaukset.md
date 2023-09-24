
Käyttötapauskuvaukset


Browse votes

- Käyttäjä: Vierailija ja ylläpitäjä
- Laukaisija: Kun kirjaudutaan sovellukseen sisään. Kaksi kirjautumisvaihtoehtoa: Vierailijat sekä Ylläpito.
- Esiehto: Jos kirjautuja on vierailija --> Pystyy selaamaan äänestyksiä, näkee äänestystilanteen sekä pystyy         äänestämään.
           Jos kirjautuja ylläpitäjä --> Pystyy selaamaan äänestyksiä sekä tekemään muutoksia äänestyksiin.
- Käyttötapauksen kulku: 
    Vierailija: 1. Avaa sovelluksen
                2. Kirjautuu sisään vierailijana
                3. Vierailija valitsee Browse votes
                4. Sovellus näyttää listan äänestyksistä

    Ylläpito:   1. Avaa sovelluksen
                2. Kirjautuu sisään ylläpitäjänä
                3. Ylläpitäjä valitsee Browse votes
                4. Sovellus näyttää listan äänestyksistä


Select vote

- Käyttäjä: Vierailija
- Laukaisija: Vierailija valitsee äänestyslistasta äänestyksen
- Esiehto: Vierailija on valinnut äänestyksen
- Jälkiehto: Vierailija näkee äänestyksen
- Käyttötapauksen kulku: 1. Vierailija valitsee äänestyslistalta äänestyksen
                         2. Sovellus näyttää äänestyksen
                         3. Vierailija voi katsoa äänestyksen äänestystilanteen tai äänestää sitä


Vote

- Käyttäjä: Vierailija
- Laukaisija: Vierailija äänestää äänestystä
- Esiehto: Vierailija on valinnut äänestyksen
- Jälkiehto: Vierailija on äänestänyt
- Käyttötapauksen kulku: 1. Vierailija äänestää valitsemaansa äänestystä
- Poikkeuksellinen toiminta: Jos käyttäjä yrittää äänestää samaa äänestystä, jota on jo äänestänyt näytetään virheilmoitus "Olet jo äänestänyt kyseiseen äänestykseen!"


Show voting status

- Käyttäjä: Vierailija
- Laukaisija: Vierailija on valitsee näytä äänestystilanne
- Esiehto: Vierailija on valinnut äänestyksen
- Jälkiehto: vierailija näkee äänestystilanteen
- Käyttötapauksen kulku: 1. Vierailija valitsee äänestyksen
                         2. Vierailija valitsee äänestyksen tilanteen


Create vote

- Käyttäjä: Ylläpitäjä
- Laukaisija: Ylläpitäjä kirjautuu sovellukseen ja valitsee "Create vote"
- Esiehto: Ylläpitäjä on kirjautunut sovellukseen
- Jälkiehto: Uusi äänestys lisätty
- Käyttötapauksen kulku: 1. Ylläpitäjä kirjautuu sovellukseen
                         2. Valitsee "Create vote"
                         3. Syöttää äänestystiedot ja lisää äänestyksen


Delete vote

- Käyttäjä: Ylläpitäjä
- Laukaisija: Ylläpitäjä kirjautuu sovellukseen ja valitsee "Delete vote"
- Esiehto: Ylläpitäjä on kirjautunut sovellukseen
- Jälkiehto: Valittu äänestys poistettu sovelluksesta
- Käyttötapauksen kulku: 1. Ylläpitäjä kirjautuu sovellukseen
                         2. Valitsee "Delete vote"
                         3. Valitsee poistettavan äänestyksen ja poistaa sen
