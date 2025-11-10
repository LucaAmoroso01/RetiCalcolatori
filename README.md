# Italiano :it:

# Traccia - Università
Scrivere un'applicazione client/server parallelo per gestire gli esami universitari

## Gruppo 1 studente

### Segreteria:

- Inserisce gli esami sul server dell'università (salvare in un file o conservare in memoria il dato)

- Inoltra la richiesta di prenotazione degli studenti al server universitario

- Fornisce allo studente le date degli esami disponibili per l'esame scelto dallo studente

### Studente:

- Chiede alla segreteria se ci siano esami disponibili per un corso

- Invia una richiesta di prenotazione di un esame alla segreteria

### Server universitario:

- Riceve l'aggiunta di nuovi esami

- Riceve la prenotazione di un esame

## Gruppo 2 studenti

Il server universitario ad ogni richiesta di prenotazione invia alla segreteria il numero di prenotazione progressivo assegnato allo studente e la segreteria a sua volta lo inoltra allo studente 

## Gruppo 3 studenti

Se la segreteria non risponde alla richiesta dello studente questo deve ritentare la connessione per 3 volte. Se le richieste continuano a  fallire allora aspetta un tempo random e ritenta.  Simulare un timeout della segreteria in modo da arrivare a testare l'attesa random

# Note di sviluppo

La prova d’esame richiede la progettazione e lo sviluppo della traccia proposta. 

Il progetto deve essere sviluppato secondo le seguenti linee:

- utilizzare un linguaggio di programmazione a scelta (C, Java, Python, etc...)

- utilizzare una piattaforma Unix-like;

- utilizzare le socket;

- inserire sufficienti commenti;

# Consegna progetto

## Documentazione

Lo studente deve presentare la documentazione relativa al progetto. La documentazione deve contenere:

- Descrizione del progetto;

- Descrizione e schema dell'architettura;

- Dettagli implementativi dei client/server;

- Parti rilevanti del codice sviluppato;

- Manuale utente con le istruzioni su compilazione ed esecuzione;

E' possibile redigere la documentazione usando latex o markdown

Per chi usa latex. Si consiglia di utilizzare la piattaforma Overleaf: https://www.overleaf.com/

Per i markdown:

- https://mystmd.org/

- Pagine descrittive usando Jekyll (https://jekyllrb.com/) o Hugo (https://gohugo.io/). Consigliato usare le github pages (https://pages.github.com/)

# English :gb:
# University Assignment

Develop a parallel client/server application to manage university exams

## Group 1 Student

### Administrative Office:

* Adds exams to the university server (save in a file or keep the data in memory)
* Forwards students’ exam reservation requests to the university server
* Provides students with the available exam dates for the selected course

### Student:

* Asks the administrative office if exams are available for a course
* Sends a request to reserve an exam to the administrative office

### University Server:

* Receives new exam additions
* Receives exam reservation requests

## Group 2 Students

The university server, for each reservation request, sends the administrative office the sequential reservation number assigned to the student, and the administrative office forwards it to the student.

## Group 3 Students

If the administrative office does not respond to the student's request, the student must retry the connection 3 times. If the requests continue to fail, the student waits for a random amount of time and retries. Simulate an administrative office timeout to test the random wait mechanism.

# Development Notes

The exam requires the design and development of the proposed assignment.

The project must be developed according to the following guidelines:

* Use a programming language of your choice (C, Java, Python, etc.)
* Use a Unix-like platform
* Use sockets
* Include sufficient comments in the code

# Project Submission

## Documentation

Students must submit documentation related to the project. The documentation must include:

* Project description
* Description and diagram of the architecture
* Implementation details of the clients/servers
* Relevant parts of the developed code
* User manual with instructions for compilation and execution

Documentation can be written using LaTeX or Markdown.

For LaTeX, it is recommended to use the Overleaf platform: [https://www.overleaf.com/](https://www.overleaf.com/)

For Markdown:

* [https://mystmd.org/](https://mystmd.org/)
* Descriptive pages using Jekyll ([https://jekyllrb.com/](https://jekyllrb.com/)) or Hugo ([https://gohugo.io/](https://gohugo.io/)). GitHub Pages are recommended ([https://pages.github.com/](https://pages.github.com/)).


