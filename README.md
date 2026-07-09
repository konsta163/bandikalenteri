# 🎸 Bändikalenteri

Yhteinen kalenteri bändin treenien, keikkojen ja poissaolojen hallintaan.

🔗 **[Avaa kalenteri](https://konsta163.github.io/bandikalenteri/kalenteri.html)**

## Ominaisuudet

- Treenien ja keikkojen lisääminen kellonaikoineen
- Poissaolojen merkitseminen päivä- tai aikavälikohtaisesti määritetyille jäsenille
- Settilistan liittäminen tapahtumaan Google Drive tai Dropbox -linkin kautta
- Reaaliaikainen synkronointi — kaikki näkevät saman kalenterin Firebase-tietokannan kautta
- Kalenteriboksit pysyvät siisteinä — pitkät tekstit katkeavat automaattisesti
- Klikkaamalla päivää näet sen tapahtumat sekä kaikki tulevat tapahtumat alla
- Tapahtumien poisto vahvistusdialogin kera
- Lataa tulevat treenit ja keikaat Outlookiin .ics-tiedostona
- Ei kirjautumista, ei asennuksia — toimii suoraan selaimessa
- 
## Käyttö

Avaa yllä oleva linkki selaimessa ja jaa se bändiläisille. Siinä kaikki.

Settilistan lisääminen tapahtumaan:
1. Lataa PDF Google Driveen tai Dropboxiin
2. Kopioi tiedoston julkinen jakolinkki
3. Liitä linkki tapahtumaa lisätessä "Settilista-linkki" -kenttään

## Tekniset tiedot

- Frontend: HTML/CSS/JavaScript, ei frameworkeja
- Tietokanta: Firebase Realtime Database (synkronointi 20 sekunnin välein)
- Hosting: GitHub Pages
