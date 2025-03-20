# PROVA2
Daniela Erba e Laura Venturini
2111039 
2101061

PROVA PRATICA 1 MTSS

DESCRIZIONE DEL PROGETTO: 
Un negozio di elettronica ha deciso di utilizzare un sistema di versionamento per organizzare il
proprio inventario.
Ha deciso di creare:
• Un file di inventario (inventario.md) contenente la lista dei prodotti venduti
• Un file per ogni categoria di prodotti (popolate i file con un paio di righe di prodotti anche
inventati)

PRIMA VERSIONE
La prima versione dell’inventario sarà composta dai seguenti elementi:
• Inventario (file inventario.md): l’inventario dei prodotti (il file che conterrà l’elenco dei prodotti
gestiti)
• Processori (file processori.md): file che identifica i vari processori in vendita
• Schede Madri (file schede_madri.md): file che identifica le varie schede madri in vendita
Seconda versione
La seconda versione dell’inventario dovrà gestire anche le periferiche.
Per questo è necessario:
• Spostare i componenti (processori.md e schede_madri.md) sotto la cartella componenti (e
aggiornare il file di inventario)
• Creare una cartella periferiche
• Inserire i file per le seguenti periferiche nella cartella periferiche (e aggiornare il file di
inventario):
◦ Tastiere (tastiere.md)
◦ Mouse (mouse.md)

SVOLGIMENTO 

ISSUE TRACKING SYSTEM
Gestire il progetto nel issue tracking system di github, ad ogni attività numerata deve
corrispondere una issue:
• Le attività dovranno essere suddivise tra sviluppatore 1 e sviluppatore 2 (i due componenti del
gruppo)
• Registrare le due versioni (vedi laboratorio ITS - Milestone)
• Creare la project board (vedi laboratorio ITS - Project Board)
• Creare e svolgere le seguenti attività per la prima versione:
◦ (1) Prima versione Inventario: creare il file inventario.md vuoto [sviluppatore 1]
◦ (2) Processori: creare il file processori.md e aggiornare il file inventario.md aggiungendo il
riferimento al nuovo componente [sviluppatore 1]
◦ (3) Schede madri: creare il file schede_madri.md e aggiornare il file inventario.md
aggiungendo il riferimento al nuovo componente [sviluppatore 2]
• Creare e svolgere le seguenti attività per la seconda versione:
◦ (4) Sezione Componenti: aggiungere al file inventario.md un sottotitolo componenti e
spostare i file dei componenti sotto una nuova cartella componenti [sviluppatore 2]
◦ (5) Sezione Periferiche: aggiungere al file inventario.md un sottotitolo periferiche e creare la
cartella periferiche [sviluppatore 1] (su git non si può fare il push di una cartella vuota, per
farlo quindi è necessario creare un file vuoto all’interno della cartella)
◦ (6) Tastiere: creare un file tastiere.md nella cartella periferiche [sviluppatore 2]
◦ (7) Mouse: creare un file mouse.md nella cartella periferiche [sviluppatore 1]

DVCS
Sviluppare il progetto utilizzando git e il workflow gitflow andando a creare:
• Feature branch per ogni attività con il "Gitflow feature" (vedi: https://danielkummer.github.io/
git-flow-cheatsheet/#features)
• Aggiornare le Issue tramite gli automatismi del comando commit (vedi laboratorio GIT)
• Aggiornare lo stato delle Issue tramite merge (vedi comando git flow release …)
• Svolgere le attività "Processori" (2) e "Schede Madri" (3) in parallelo (creare i feature branch a
partire dallo stesso commit) ogni componente del gruppo lavora a una delle due attività
• Uno dei due sviluppatori dovrà rilasciare la versione 1 svolgendo nella fase di release (ramo di
release) la seguente attività (commit):
◦ Aggiungere una riga al termine del file inventario.md contenente: Elettronica Padovana
• Completare le attività per la versione 2 (che possono partire in parallelo con il rilascio della
versione 1)
• Attivare il ramo di rilascio per la versione 2 ma senza completare il rilascio (senza effettuare il
comando "git flow release finish RELEASE")
Di seguito viene riportato un esempio di svolgimento dell’esercizio dall’attività 1 all’attività 4
Note per la consegna
• In ogni file inserire come prime due righe i numeri di matricola dei componenti del
gruppo (fin dal primo commit del file)
• I nomi dei file devono essere gli stessi riportati nelle istruzioni (tutto minuscolo con '_' come
separatore)
• Condividere nel repository remoto tutti i rami di feature creati (vedere comando git flow
feature finish -k git flow feature finish)
• Condividere nel repository i rami di develop, master/main e i tag creati per il rilascio della
prima versione e il ramo di rilascio della seconda versione.
• Al termine dell’esercizio completare i dati richiesti dall’apposito questionario presente nel sito
del corso.
• La prova pratica deve essere completata e consegnata entro il 21/03/2025 alle ore 18:00.
• Ogni consegna successiva a tale data non sarà valutata (fa fede la data della consegna del
questionario).