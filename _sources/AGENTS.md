# Regole persistenti per le lezioni

## Ambito e memoria
- Queste istruzioni valgono per la cartella lezioni e le sue sottocartelle.
- All'inizio di ogni attivita leggere REGISTRO_LAVORO.md e verificare lo stato Git. Il registro contiene il contesto persistente, da confrontare con i file attuali.
- Aggiornare il registro dopo ogni passaggio significativo: decisioni didattiche, modifiche, verifiche, problemi e attivita ancora da completare. Evitare la cronaca dei singoli comandi.
- Scrivere fatti verificati; distinguere lavoro completato, ipotesi e lavoro previsto. Non dichiarare letture o test mai effettuati.

## Obiettivo didattico
- Il materiale insegna Python, in particolare NumPy, a studenti principianti. Comunicare in italiano e mantenere lo stile della lezione.
- Prima di modificare un notebook, leggere tutte le celle di codice e Markdown in ordine, considerando le dipendenze tra celle e gli output pertinenti.
- Preferire esempi piccoli, nomi chiari e passaggi espliciti. Spiegare scopo, sintassi nuova e risultato atteso senza introdurre complessita superflua.
- Per NumPy chiarire, quando pertinente: differenze tra liste e array, shape, ndim, dtype, indicizzazione da zero, slicing, axis e broadcasting.
- Distinguere operazioni elemento per elemento da prodotti matriciali; spiegare copie e viste quando influiscono sull'esempio.
- Preservare la progressione didattica e gli esercizi; non inserire soluzioni non richieste.

## Modifiche e verifiche
- Lavorare sui sorgenti, ad esempio my_ipynb/1_basics_python.ipynb. La cartella _build contiene artefatti generati: non correggerli manualmente; rigenerarli solo quando necessario al compito.
- Conservare le modifiche preesistenti dell'utente. Evitare riscritture massive del JSON, dei metadati e degli output dei notebook.
- Dopo modifiche al codice, eseguire verifiche proporzionate. Quando possibile verificare il notebook con kernel pulito e celle in ordine, controllando prima eventuali effetti esterni.
- Per modifiche solo documentali controllare contenuto e diff; non sono necessari test del codice.
- Registrare quali controlli sono stati davvero eseguiti, il loro esito e gli eventuali limiti. Non considerare gli output salvati prova di una nuova esecuzione.

## Git e comunicazione
- Prima di un commit verificare il diff e includere soltanto i file pertinenti al lavoro autorizzato, evitando git add indiscriminati.
- Eseguire commit e push quando richiesti o autorizzati dall'utente; una domanda sulle credenziali non equivale a una richiesta di pubblicazione.
- Usare la configurazione Git esistente. Non salvare password o token nei file o nel registro e non chiederli in chat; usare il normale flusso di autenticazione se necessario.
- Concludere con un riepilogo breve di modifiche, verifiche e lavoro ancora aperto.
