# Gestione Titoli

Registro personale delle operazioni in titoli (azioni, ETF, obbligazioni…), pensato per chi opera con **Fineco**.
Calcola da solo commissioni, Tobin Tax, tasse (26% / 12,5%), prezzo medio di carico, prezzo alla pari, minusvalenze da
recuperare e il riepilogo mensile e annuale.

Disponibile per **Windows** e per **Android**: le due versioni possono usare lo stesso archivio (un file `.db`), ad
esempio tenuto su Google Drive, così trovi gli stessi dati sul PC e sul telefono.

> Versione **beta**: il programma è in sviluppo e viene aggiornato spesso.
> Le novità di ogni versione sono nel programma, in **Aiuto → Novità delle versioni**.

---

## ⬇️ Scarica

| | File | Link |
|---|---|---|
| **Windows** 10 / 11 | `GestioneTitoli.exe` | [Scarica per Windows](https://github.com/jjjohn7000/gestione-titoli/releases/latest/download/GestioneTitoli.exe) |
| **Android** 8.0 o successivo | `GestioneTitoli.apk` | [Scarica per Android](https://github.com/jjjohn7000/gestione-titoli/releases/latest/download/GestioneTitoli.apk) |

I link portano sempre all'**ultima versione**. Le versioni precedenti e le note di ogni versione sono nella pagina
[Releases](https://github.com/jjjohn7000/gestione-titoli/releases).

---

## 💻 Installare su Windows

1. Scarica **GestioneTitoli.exe** e mettilo dove preferisci (ad esempio sul Desktop). Non serve installarlo: si avvia
   con un doppio clic.
2. Il browser potrebbe avvisare che il file «non viene scaricato di solito»: scegli **Mantieni** (in Edge: **…** →
   **Mantieni**).
3. Al primo avvio Windows può mostrare **«Windows ha protetto il PC»**: clicca **Ulteriori informazioni** e poi
   **Esegui comunque**. Succede con tutti i programmi che non hanno una firma digitale a pagamento.
4. Al primo avvio scegli dove tenere l'archivio (un file `.db`) e imposta il primo **utente**: da lì puoi inserire
   le tue posizioni.

Per aggiornare: scarica il nuovo `GestioneTitoli.exe`, chiudi il programma e sostituisci quello vecchio. L'archivio
non si tocca. Dalla beta 0.34.0 il programma avvisa da solo all'avvio quando esce una versione nuova, con il link per
scaricarla (anche da **Aiuto → Cerca aggiornamenti…**).

## 📱 Installare su Android

1. Dal telefono apri il link **Scarica per Android** e scarica **GestioneTitoli.apk**.
2. Apri il file scaricato (dalla notifica o da **File / Download**).
3. Android chiede di consentire l'installazione di app da questa fonte: tocca **Impostazioni**, attiva
   **Consenti da questa fonte** e torna indietro, poi **Installa**.
4. Se compare un avviso di Play Protect, scegli **Installa comunque**.
5. Al primo avvio scegli un archivio esistente (ad esempio quello del PC su Google Drive) oppure creane uno nuovo.

Per aggiornare: scarica e installa il nuovo `.apk` sopra quello vecchio. I dati restano.

---

## ✨ Cosa fa

- **Posizioni aperte**: acquisti e vendite parziali di ogni titolo, con prezzo medio di carico, investito, netto
  potenziale e prezzo alla pari.
- **Se vendo a…**: quanto incasseresti, al netto di commissioni e tasse, vendendo a un certo prezzo, con una tabella di
  prezzi vicini a quello di carico.
- **Test**: posizioni di prova per fare simulazioni senza toccare quelle vere.
- **Posizioni chiuse**: tutte le operazioni concluse, filtrabili per anno, mese e titolo.
- **Riepilogo**: guadagni e perdite per mese e per anno, guadagno medio mensile, grafico.
- **Più utenti** nello stesso archivio, ognuno con il suo colore.
- **Esporta in Excel**, **Annulla / Ripeti**, **Copia e incolla** tra le schede, **Guida completa** consultabile
  senza internet (tasto **F1** su Windows).

## 🔒 I tuoi dati

Il programma non invia nulla su internet: i dati restano nel file `.db` che scegli tu, sul tuo PC, sul telefono o
nella cartella cloud che usi. Su Windows, alla chiusura viene fatta una copia di sicurezza dell'archivio.
L'unico accesso a internet è il controllo degli aggiornamenti: il programma legge in questa pagina qual è l'ultima
versione pubblicata (si può spegnere da Aiuto → Controlla gli aggiornamenti all'avvio).

## ⚠️ Avvertenze

Gestione Titoli è uno strumento personale di registrazione e calcolo, distribuito gratuitamente e **senza alcuna
garanzia**. I calcoli di tasse e commissioni sono indicativi: per dichiarazioni e verifiche fanno fede i documenti
della banca e del tuo consulente fiscale. Non è collegato né approvato da Fineco o da altre banche.
