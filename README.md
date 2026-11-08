# Tascabestie

Un piccolo gioco di cattura mostri in stile retro, da giocare sul telefono in verticale come su una vecchia console portatile. Funziona nel browser: niente installazione, niente account.

![Anteprima del gioco](screenshots/anteprima.png)

## Come si gioca

Apri `index.html` nel browser, oppure visita la pagina pubblicata con GitHub Pages. Sul telefono il gioco occupa lo schermo come una console tascabile.

| Tasto | Su telefono | Su computer |
|---|---|---|
| Croce direzionale | croce sullo schermo | frecce o W A S D |
| A (parla, conferma) | tasto A | Z o J |
| B (annulla, corri) | tasto B | X o K |
| Start (menu) | tasto Start | Invio |
| Select (Bestiario) | tasto Select | Maiusc |

Su iPhone conviene aprire il gioco in Safari e scegliere "Aggiungi a schermata Home": così parte a schermo intero. La partita si salva nel browser che usi per giocare.

## Cosa c'è dentro

- 56 Tascabestie da catturare e far evolvere, con 12 tipi diversi
- Lotte a turni con fino a 4 mosse per Tascabestia, esperienza condivisa e mosse che si imparano salendo di livello
- Un'avventura completa: città, pineta, stazione, torrente, borgo in collina, una palestra e una rivale
- Zaino con Pozioni e Tascaball, un supermercato, un computer per il box e un Bestiario da completare
- Salvataggio automatico e manuale
- Grafica e suoni originali, generati interamente dal codice

## Struttura

Il gioco è un unico file, `index.html`, con HTML, CSS e JavaScript. Non usa librerie esterne né file di grafica: sprite, mappe ed effetti sonori sono disegnati e generati dal codice. L'unica risorsa esterna è il font della cornice, caricato da Google Fonts.

## Pubblicarlo con GitHub Pages

1. Carica i file del repository su GitHub.
2. Vai su **Settings → Pages**.
3. In **Build and deployment**, scegli **Deploy from a branch**, poi il branch `main` e la cartella `/ (root)`.
4. Dopo un minuto il gioco sarà disponibile all'indirizzo `https://<tuo-utente>.github.io/<nome-repository>/`.

## Nota

Tascabestie è un progetto amatoriale e non ha legami con Nintendo, Game Freak, The Pokémon Company o altri marchi di videogiochi. Nomi, creature, grafica e suoni sono originali.

## Licenza

Distribuito con licenza MIT: vedi il file [LICENSE](LICENSE).
