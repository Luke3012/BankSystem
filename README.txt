@readme progetto banksystem DI PALMA MATTIA, PALLADINO SIMONE, TARTAGLIA LUCA

CONFIGURAZIONI PER LA CORRETTA ESECUZIONE:

1)Utilizzare l'ultima versione di tomcat (10.1.5) per poter compilare ed eseguire il progetto
2)Copiare il database SQLite fornito (banksystem.sqlite) nel seguente path:
		directory_di_tomcat/bin/banksystem.sqlite

NOTE DI SVILUPPO:

1)Per accedere alla sezione ADMIN per eseguire le varie operazioni utilizzare le credenziali salvate all'interno
della tabella ADMIN di banksystem ovvero: USERNAME = luke , PASSWORD = pippo
	(oppure aggiungere un altra voce)

2) La password iniziale per un nuovo correntista sarà uguale al CF inserito nel form compilato dall'admin.
Al primo accesso del correntista, la password potrà essere modificata.
(N.B. LE PASSWORD ALL'INTERNO DEL DATABASE SONO CRIPTATE QUINDI NON CONSULTABILI FACILMENTE)