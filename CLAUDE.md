# type-approval-app – file di sincronizzazione

Repository **pubblico** che contiene **solo** la pagina web (GitHub Pages) per usare dal telefono
il sistema del repository **privato** `ingegnererecca-web/type-approval`.

- Link: https://ingegnererecca-web.github.io/type-approval-app/
- Qui NON vanno mai dati: niente foto, risultati, token o documenti. Solo `index.html`.
- La pagina carica la foto nel repo privato (API GitHub), avvia il workflow "Cerca certificato",
  elenca i risultati temporanei (artifact, scadenza 1 giorno) e li cancella.
- Il token lo inserisce l'utente nella pagina e resta solo nel suo browser (localStorage).
- `index.html` è una copia di quella del repo privato: modificarle insieme.
- Documentazione completa del progetto: `CLAUDE.md` del repo privato.
