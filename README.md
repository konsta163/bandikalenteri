# 🎸 Bändikalenteri — Electric Marmalade

Yhteinen kalenteri bändin treenien, keikkojen ja poissaolojen hallintaan.

## Ominaisuudet

- Treenien ja keikkojen lisääminen kellonaikoineen
- Vapaamuotoiset lisätiedot tapahtumalle (äänimies, aikataulu, load-in jne.)
- Poissaolojen merkitseminen päivä- tai aikavälikohtaisesti jäsenelle (Jani, Jarkko, Konsta, Rane, Sami)
- Settilistan liittäminen tapahtumaan Google Drive tai Dropbox -linkin kautta
- Tapahtumien muokkaus jälkikäteen — päivämäärä, tyyppi, kuvaus, kellonaika, lisätiedot ja settilista samassa näkymässä
- Reaaliaikainen synkronointi — kaikki näkevät saman kalenterin Firebase-tietokannan kautta
- Kalenteriboksit pysyvät siisteinä — pitkät tekstit katkeavat automaattisesti
- Klikkaamalla päivää näet sen tapahtumat sekä kaikki tulevat tapahtumat alla
- Tapahtumien poisto vahvistusdialogin kera
- Lataa tulevat treenit ja keikaat Outlookiin .ics-tiedostona
- Electric Marmalade -logo kalenterin otsikossa
- Toimii pikakuvakkeena iPhonen kotinäytöllä (Safari → Jaa → Lisää Koti-valikkoon)
- Ei kirjautumista, ei asennuksia — toimii suoraan selaimessa

## Käyttö

Avaa yllä oleva linkki selaimessa ja jaa se bändiläisille. Siinä kaikki.

Settilistan lisääminen tai muokkaaminen:
1. Lataa PDF Google Driveen tai Dropboxiin
2. Kopioi tiedoston julkinen jakolinkki
3. Liitä linkki tapahtumaa lisätessä tai muokatessa (✏️-nappi)

## Tekniset tiedot

- Frontend: HTML/CSS/JavaScript, ei frameworkeja
- Tietokanta: Firebase Realtime Database (synkronointi 20 sekunnin välein)
- Hosting: GitHub Pages
