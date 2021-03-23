# Gestore Corsi

Realizzare un programma `JavaFX` che gestisca un elenco di corsi universitari.

Il programma si basa sul database **iscritticorsi**, diponibile nella cartella **db** di questo progetto. Nella stessa cartella è presente il [diagramma entità-relazioni](db/iscritticorsi/diagrammaER.PNG).

Il programma deve permettere all'utente di:

**Analizzare i corsi sulla base del periodo didattico:**
- Elencare tutti i corsi di un determinato periodo didattico. Se l'utente digita "1", il programma dovrà stampare tutti i corsi del primo semestre, se l'utente digita "2", il programma dovrà stampare tutti i corsi del secondo semestre.
- Stampare il numero di iscritti ai corsi di un determinato periodo didattico.
	
**Analizzare un singolo corso:**
- Elencare tutti gli studenti di un determinato corso. L'utente inserisce il codice di un corso, e il programma stampa tutti gli studenti iscritti.
- Dato il codice di un corso, stampare la divisione degli studenti iscritti tra i vari Corsi di Studio (CDS).