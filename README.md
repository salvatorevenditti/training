Definire una classe Java Studenti, composta dai seguenti campi :

int eta;
String nome;
String cognome;
String materiaPreferita;
boolean tassePagate;

All'avvio del programma, nel sistema sono presenti 5 studenti : 

Studente 1 {
	eta = 11;
	nome = "Gennaro"
	cognome = "Malachite"
	classe = "Arte"
	tassePagate = true
}

Studente 2 {
	eta = 14;
	nome = "Fabio"
	cognome = "Onice"
	classe = "Matematica"
	tassePagate = true
}

Studente 3 {
	eta = 13;
	nome = "Giovanni"
	cognome = "Rubino"
	classe = "Arte"
	tassePagate = false
}

Studente 4 {
	eta = 12;
	nome = "Giuseppe"
	cognome = "Zaffiro"
	classe = "Storia"
	tassePagate = true
}

Studente 5 {
	eta = 13;
	nome = "Giulia"
	cognome = "Smeraldo"
	classe = "Storia"
	tassePagate = true
}

Creare metodi per : 

- Inserire nuovo studente (se lo studente è duplicato, non deve essere inserito)
- Eliminare studente esistente (se lo studente esiste e ha le tasse scadute, lo elimino)
- Aggiornare la situazione tasse dello studente

- Restituzione di tutti gli studenti che abbiano le tasse in regola
- Restituzione di tutti gli studenti che abbiano le tasse NON in regola

- Restituzione di tutti gli studenti che frequentano la classe "Storia"
- Restituzione di tutti gli studenti che frequentano la classe "Matematica"

- Restituzione di tutti gli studenti che frequentano la classe "Storia" e hanno almeno 13 anni
- Restituzione di tutti gli studenti che frequentano la classe "Arte" e hanno almeno 12 

- Restituzione di tutti gli studenti, in ordine Nome - Cognome
- Restituzione di tutti gli studenti, in ordine di età (a parità di età occorre ordinare per Nome - Cognome)
