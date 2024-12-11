
# Questo è il mio primo progetto con Git in IntelliJ!
# test per rollback
# rollback completed

Esercizio: Gestire un Progetto con Git in IntelliJ IDEA
Obiettivo

Imparare a utilizzare Git in IntelliJ IDEA per creare un repository, effettuare commit, visualizzare le modifiche e il log dei commit.
Prerequisiti

    IntelliJ IDEA installato.
    Git installato e configurato nel sistema (verifica con il comando git --version nel terminale).
    Conoscenza di base di IntelliJ IDEA.

Parte 1: Creare un Nuovo Progetto con Git √

    Aprire IntelliJ IDEA e creare un nuovo progetto:
        Vai su File > New > Project.
        Scegli un progetto Java o un semplice progetto vuoto.
        Dai un nome al progetto, ad esempio: MioProgettoGit.

    Abilitare il Version Control (Git):
        Dopo aver creato il progetto, vai su VCS > Enable Version Control Integration.
        Seleziona Git dall'elenco e premi OK.
        IntelliJ inizializzerà un repository Git nella cartella del progetto.

Parte 2: Aggiungere un File e Fare un Commit √

    Crea un nuovo file:
        Clicca con il tasto destro sul progetto nella finestra Project e seleziona New > File.
        Dai un nome al file, ad esempio: README.md.
        Aggiungi del contenuto, ad esempio:

        # Questo è il mio primo progetto con Git in IntelliJ!

    Aggiungere il file al repository:
        IntelliJ mostrerà il file in rosso (non tracciato).
        Fai clic destro sul file e seleziona Git > Add oppure usa la scorciatoia Ctrl+Alt+A.
        Il file diventerà verde (tracciato e in area di staging).

    Fare un commit:
        Vai su VCS > Git > Commit o premi Ctrl+K.
        Nella finestra che appare:
            Aggiungi un messaggio di commit, ad esempio: "Aggiunto il file README.md".
            Premi Commit per salvare le modifiche nel repository.

Parte 3: Modificare un File e Fare un Nuovo Commit

    Modifica il file README.md:
        Aggiungi un'altra riga, ad esempio:

        Sto imparando Git con IntelliJ IDEA.

    Controllare le modifiche:
        IntelliJ mostrerà il file in blu (modificato).
        Per vedere i dettagli delle modifiche, vai su VCS > Git > Show Diff o fai clic destro sul file e seleziona Git > Show Diff.

    Aggiungere e committare le modifiche:
        Premi di nuovo Ctrl+K.
        Aggiungi un nuovo messaggio di commit, ad esempio: "Aggiornato il file README.md".
        Premi Commit.

Parte 4: Visualizzare la Cronologia

    Vedere lo storico dei commit:
        Vai su VCS > Git > Log.
        Si aprirà una finestra con l'elenco di tutti i commit, i loro messaggi, gli autori e le date.

Parte 5: Bonus - Ripristino di una Modifica

    Annullare le modifiche non committate:
        Modifica nuovamente il file README.md, ma questa volta non fare commit.
        Vai su VCS > Git > Rollback per annullare le modifiche non committate.

    Ripristinare una versione precedente:
        Nella finestra Git Log, fai clic destro su un commit precedente e seleziona Checkout Revision per tornare a quella versione.

Conclusione

Con questo esercizio hai imparato a utilizzare Git attraverso IntelliJ IDEA, includendo:

    L'inizializzazione di un repository.
    L'aggiunta e il commit di file.
    La gestione delle modifiche.
    La visualizzazione del log.