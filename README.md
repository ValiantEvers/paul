# paul

Personlig side for Paul Evers. Live på **[evers.no/paul](https://www.evers.no/paul/)**.

En enkel, selvstendig HTML-side uten rammeverk og uten bygg-steg. Hele siden ligger i `index.html`.

## Slik redigerer du siden (enkleste vei)

Du trenger ikke installere noe. Alt kan gjøres rett i nettleseren på GitHub:

1. Gå til dette repoet på github.com.
2. Klikk på filen `index.html`.
3. Klikk blyant-ikonet (✏️) oppe til høyre.
4. Endre teksten. Alt som er ment å endres er merket med `ENDRE ...` i filen, og hjelpenotatene står mellom `<!--` og `-->` (de vises aldri på siden).
5. Klikk den grønne **Commit changes**-knappen nederst.

Etter omtrent ett minutt er endringen synlig på evers.no/paul.

## Vanlige endringer

- **Tekst og navn:** stå i `index.html` og se etter `ENDRE ...`-kommentarene.
- **Farger:** øverst i `<style>` ligger en blokk med fargevariabler (`--accent`, `--bg` osv.). Bytt verdien ett sted, så endres hele siden.
- **Nytt profilbilde:** last opp en bildefil i repoet (f.eks. `meg.jpg`) og følg instruksjonen i `.avatar`-blokken i `index.html`.
- **Ny seksjon:** kopier en hel `<section> ... </section>`-blokk og bytt ut overskrift og tekst.

## Hvordan det publiseres

Siden ligger på GitHub Pages. Hver endring som lagres (commits) på `main`-grenen publiseres automatisk. Det finnes ikke noe bygg-steg.

## Viktig

Ikke legg til en fil som heter `CNAME` i dette repoet. Adressen `evers.no/paul` fungerer nettopp fordi repoet *ikke* har et eget domene, og dermed arver `www.evers.no` fra hovedsiden. En `CNAME`-fil her vil ødelegge adressen.

---

Adressen `evers.no/paul` sender videre til `www.evers.no/paul/`.
