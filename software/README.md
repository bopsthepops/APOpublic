# Utilizzo e installazione software
Questa è una guida per utilizzo e installazione del software necessario allo svolgimento dei laboratori. Seguire le istruzioni nell'ordine indicato per evitare problemi.

## Usare il terminale
Su MAC e Linux è presente l'applicativo Terminal (o simili) che lancia un terminale. Su Windows l'applicativo da usare è PowerShell. Il terminale ha impostato il percorso alla vostra cartella home. Per avviarlo in una specifica cartella fare come segue:

- Per MAC da finder fare tasto destro su una cartella, andare su *Servizi* e poi su *Nuovo terminale alla cartella*.

- Per Windows dal file explorer premere shift in contemporanea al tasto destro di modo da far comparire la voce *Apri finestra PowerShell qui*

Per provare, lanciare i segueni comandi:
``` bash
 ls # mostra contenuto cartella
 cd nome_cartella # si sposta nella cartella
 cd .. # si sposta nella cartella padre
 ```

## Python
Scaricare python dal sequente [link](https://www.python.org/downloads/release/python-3910/). Al fondo della pagina trovate i link al download per i diversi sistemi operativi.

Selezionare le versioni 64 bit, a meno che il vostro sistema non sia a 32 bit. Una volta scaricato avviare l'installer.

**IMPORTATE**: mettere la spunta su *"add python to PATH"* (Windows)

Una volta eseguita l'installazione aprire un terminale e digitare il comando:
``` bash
 python --version # mosta versione python
 python # lancia l'interprete di python, digitare exit() per uscire
 ```

 ## Git
 Per installare Git seguire le istruzioni al seguente [link](https://git-scm.com/downloads), selezionando il proprio sistema operativo.
 
 Per Windows durante il processo di installazione, lasciare tutte le opzioni a quelle di default.

 Aprire un terminale e digitare:
``` bash
git -- version # mostra versione git
git --help # mostra tutti i possibili comandi
 ```

Successivamente configurare git eseguendo i seguenti due comandi:
```bash
git config --global user.email "you@example.com" # mettere email (se vi create un account github usate quella)
git config --global user.name "Your Name" # inserire vostro nome/nickname
```

## PyCharm
Dal [sito web](https://www.jetbrains.com/pycharm/download/) di PyCharm, seguire le istruzioni di installazione per il vostro sistema operativo. 

La *Community Edition* basta e avanza (questo corso potreste farlo, e lo consiglio, usando terminale e Notepad++).

Altrimenti JetBrains permette di [richiedere](https://www.jetbrains.com/community/education/#students) licenze gratuite per studenti.

Creare un progetto e testare un semplice programma per verificare che Python venga trovato da PyCharm.

## Github
Questo è (per ora) facoltativo, ma fortemente consigliato per diversi motivi:
- Vi insegna ad usare git, che è al giorno d'oggi è fondamentale
- Ci rende più semplice rispondere a domande da casa su problemi specifici del vostro codice

Andate su [github](https://github.com/) e create un account. 

Create un respository (possibilmente pubblico) dove andrete a caricare, laboratorio per laboratorio, le vostre soluzioni. Questa parte verrà spiegata con maggiore chiarezza durante i laboratori.








